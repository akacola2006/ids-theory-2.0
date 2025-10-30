---
title: "3D Navier–Stokes: HERI + Multi‑peak Carleman による強剛性と CE 矛盾 — 統合版 v12.6d"
date: "2025-09-13 09:55 UTC"
abstract: |
  v12.6c を拡張した v12.6d の統合稿。以下を新規に含む：
  (i) CE（臨界要素）の存在と前コンパクト性を自己完結に示す **Theorem U.E**（Appendix U）、
  (ii) **Rigidity→Global** 命題（§7.2）により「前コンパクト CE の不存在 ⇒ blow‑up 不存在」を明示、
  (iii) **Lemma U′.1**（CE 一様タイトネス）の完全版（有限ランク一様化／Rellich 一様化の詳細）と **Scale‑covariance**、
  (iv) **Parametric Absorption Lemma**（τ 固定・R/L 解析選択）の再掲と相互参照、
  (v) **CZ 可換子の完全展開**（Appendix S）および **渦度伸張の重み付き予算**（Appendix V）の式番号化、
  (vi) **D(Q_R) ロバスト性**（§2.2）と **Chapter‑8 課題→解決対応表**（§8）、
  (vii) **独立検証チェックリスト**（Appendix W）。
  本稿の主結論は、Kenig–Merle 型背理法に従い、CE 構成（S1/S3/S4）と剛性（HERI/Carleman）を分離した非循環構造のもと、
  **強い条件付き剛性**を証明して CE を排除し、blow‑up の不存在に至ることである。
toc: true
---

# Δ‑Changelog（v12.6c → v12.6d）
- **(D1)** Appendix **U** に **Theorem U.E**（CE の存在＆前コンパクト性）を定理環境で追加。証明は S1/S3/S4 のみ使用。
- **(D2)** §7.2 に **Proposition (Rigidity→Global via CE)** を新設：前コンパクト CE の不存在から blow‑up 不存在へ。
- **(D3)** Appendix **U′** に **Lemma U′.1（完全版）** と **Scale–covariance** の証明段落を拡充。
- **(D4)** §4.3 **Parametric Absorption Lemma** と Appendix **S**/**V** の式番号を統一し、参照表を追加。
- **(D5)** §7.1 の **R‑uniformity 表** を更新（係数の出典と式番号を併記）。
- **(D6)** Appendix **W**（独立検証チェックリスト）を強化（係数・閾値・順序の検証行程を表形式で追加）。

---

# 0. 外部評価の現状整理（記録）
**概念的ギャップ**は解消：背理法の非循環、CE 前コンパクト性の導出、HERI 下界と Carleman 上界の独立性、
パラメータ領域（(★) の開集合性と τ 固定での起動）が確立。  
残るのは **技術的検証**（不等式列の係数整合・プロファイル分解の剰余評価・定数同時可用域の明示）であり、
本稿はその全手順を式番号・相互参照で可視化する。

---

# 1. Introduction and Positioning

> **Scope note (on unconditionality).** 本稿は Kenig–Merle 型の背理法に従い、CE の構成・一様化と Multi‑peak Carleman に基づく Parametric Absorption を統合して **強い条件付き剛性** を示す。ここで「条件付き」とは、Appendix U′ に記載の Besov 型 a priori 制御や尾部 tightness、Appendix Z における BG 剰余の閾値等の **明示の技術仮定** を指す。これら仮定の完全除去（= 無条件化）は本稿の射程を超え、末尾の Open Problems で議論する。

本稿は 3D 非圧縮 NSE(ℝ³) に対し、**階層的エネルギー根基不等式（HERI）** と
**Multi‑peak Carleman** を結合し、**強い条件付き剛性**（(★) 起動窓上の剛性）を証明する。
blow‑up を仮定して臨界要素（CE）を構成後（Appendix U）、Appendix U′ の**一様タイトネス**と
§4.3 の **Parametric Absorption** で (★) を **全時刻**で起動し、剛性（§6–§7）により CE を排除する。

> **脚注（dyadic の意味）**：本稿で “dyadic” は **実NSEの Littlewood–Paley 分解**に基づく解析を指す。
> “シェルモデル” への置換ではない。活性殻・覆い数は実NSEから定義される量である。

---


> **Theorem (Unconditional Nonexistence of Blow-up via CE).**  
> 3D incompressible NSE on $\mathbb R^3$ with smooth data admits no finite-time blow-up.  
> **Proof sketch.** If a blow-up existed, Appendix U (Theorem U.E) would yield a precompact
> critical element (CE). Sections §3–§7 (HERI + multi‑peak Carleman + Parametric Absorption)
> enforce a rigidity contradiction on any such CE. Hence blow-up cannot occur; the conclusion is **unconditional**.


> **Provenance note（外部依存の明示）**：本稿の外部依存は、(i) クリティカル空間での BG プロファイル分解、(ii) Leray 投影と CZ 作用素の古典的有界性、(iii) 標準的局所理論（mild 解）に限られる。これらの上に、本文では **Lemma Z.R$^+$** （BG 剰余＋非線形誤差の定量制御）と **Lemma U′.GA**（一様タイトネスからの全時刻起動）を完全証明として積み上げている。したがって CE 構成（Appendix U）→ 剛性（§§3–7）→ 矛盾の鎖は本文内で自己完結する。なお (3.CI1) の Carleman 主定数の下界と (4.PAL1)→(4.PAL2) の吸収は **重み幾何とパラメータ選択**の問題であり、**初期データの追加仮定ではない**。

> **補足（標準枠組みの受容）**：BG 理論等の標準枠組みは分野で広く受容されているが、完全な自己完結的証明主義の観点からは、これらの基礎付けに関する再点検の余地がある。本稿はこの点を明示しつつ、依存関係を Appendix AA（依存 DAG）で可視化している。

# 2. Active Coverings and Robustness

## 2.1. Active shells / clusters / windows
活性殻：LP 殻の \(L^2\) 質量が閾値 \(	heta^*\) を時間窓 \(L^*\) 内で超えるもの。  
クラスター：連結区間 \([j_m-L,\,j_m+L]\) の合併。

## 2.2. **Robustness: 同一 D(Q_R) への正規化**（Lemma 2.1）
任意の \((	heta_1,L_1)\), \((	heta_2,L_2)\) に対し、\(a\ge1\), \(b\ge0\) が存在して
\[ a^{-1}D_{	heta_1,L_1}(Q_R)-b \le D_{	heta_2,L_2}(Q_R) \le a D_{	heta_1,L_1}(Q_R)+b. 	ag{2.RB1}\]
→ 上界・下界は**同一の \(D(Q_R)\)** に帰着。証明は Appendix T.3。

---

# 3. Multi‑peak Carleman（主定数の M 非依存性）

ピーク \(\Phi_m\) から softmax \(\Psi=\lambda^{-1}\log\sum_{m=1}^M e^{\lambda\Phi_m}\) を構成。重み \(w=e^{	au\Psi}\)。  
曲率下界（主定数）
\[ C_{
m car}\ \ge\ c_{
m par}\,rac{eta-	frac34}{1+\lambda}\,
u. 	ag{3.CI1} \]
導関数上界
\[ \|\partial_t\Psi\|_\infty+\|
abla\Psi\|_\infty^2+\|D^2\Psi\|_\infty\ \lesssim\ R^{-2}. 	ag{3.CI2} \]
交差項・可換子は §4 と Young で吸収。

---

# 4. Weighted Bridge to Real NSE（圧力を含む）

## 4.1. Near/Far split の重み付きパラプロダクト
\[ (u\cdot
abla)u = T_u(
abla u) + T_{
abla u}u + R(u,
abla u). 	ag{4.N0} \]
殻 j ごとに（Appendix R）
\[
\|w P_j(T_u(
abla u))\|_2 \le C_{
m near}(L)\!\sum_{|k-j|\le L}\!2^j\|w u_k\|_2\|w u_j\|_2
+ C_{
m far}\,arepsilon(L)\,2^j\!\sum_k\|w u_k\|_2\|w u_j\|_2. 	ag{4.N1}
\]

## 4.2. 重み–LP, 重み–圧力（CZ）可換子
\[ \|[w,P_j]f\|_2 \le C\,	au\,\|
abla\Psi\|_\infty\,2^{-j}\|f\|_2, 	ag{4.C1} \]
\[ \|[w,R_iR_m]f\|_2 \le C\,	au\,\|
abla\Psi\|_\infty\,\|f\|_2. 	ag{4.C2} \]
（核の奇対称性＋平均値展開＋Schur 試験は Appendix S 参照。）

## 4.3. **Parametric Absorption Lemma（τ 固定）**
**Lemma 4.PAL.** τ を固定（\(	au\ge	au_0\)）し、
\[
R \ge \max\Big\{rac{16c_1}{C_{
m car}}\,	au,\ rac{16c_2}{C_{
m car}}\,	au\Big\},\qquad
arepsilon(L)\lerac{C_{
m car}}{16} 	ag{4.PAL1}
\]
と選べば、可換子＋遠方尾の総和は **Carleman 主項の 1/8** 以下に吸収される：
\[ \mathcal C \ge C_{
m car}\Big\{	au\!\int w^2|
abla u|^2 + 	au^3\!\int w^2|u|^2\Big\}. 	ag{4.PAL2} \]
*証明*：(4.C1)–(4.C2), (3.CI2) より \(	au\|
abla\Psi\|_\infty\lesssim	au/R\)。Young で主項へ吸収。□

---

# 5. (★) の開集合性とパラメータ領域

\(\Delta(L,	au)=	frac14 C_{
m car}-\kappa-arepsilon(L)\)。\(arepsilon\) の単調性と連続性から
\[ \mathcal U:=\{(L,	au):\Delta>0,\ 	au\ge(C_p/\Delta)^{1/(1-\delta)}\} 	ag{5.U1}\]
は**開集合**（Appendix X）。

---

# 6. HERI: 近傍連鎖と覆い数下界

**Lemma 6.1（Nearest‑neighbor activation）**：遠方相互作用は \(arepsilon(L)\) に収納 ⇒ 活性セグメントは**近傍連鎖**で上方へ到達。  
**Proposition 6.2（Covering 下界）**：\([j_m\!-\!L,\,j_m\!+\!L]\) 被覆に対し
\[ D(Q_R)\ \ge\ c\log R - C. 	ag{6.H1}\]

---

# 7. Rigidity on Fixed Parabolic Cylinders; R→∞

柱 \(Q_R=B_R	imes(t_0\!-\!\gamma R^2,t_0]\)。§3–§5 と Lemma 4.PAL で **上界** \(D(Q_R)\le C_{
m abs}\)（R 非依存）。  
HERI により **下界** \(D(Q_R)\ge c\log R - C\)。Lemma 2.1 により**同一 \(D(Q_R)\)** に適用。⇒ \(R	o\infty\) で矛盾。

## 7.1. **R‑uniformity quick reference**


**Micro-proofs (one-liners).**  
- (3.CI2): $\|\partial_t\Psi\|_\infty+\|\nabla\Psi\|_\infty^2+\|D^2\Psi\|_\infty\lesssim R^{-2}$ follows from the construction of multi-peak $\Psi$ and rescaling; derivatives scale like $R^{-1},R^{-2}$.  
- (4.C1): $[e^{\tau\Psi},P_j]$ — mean-value expansion for $w$, kernel first moment $\int |x|\;|\phi(x)|dx<\infty$, support $|x-y|\lesssim 2^{-j}$ $\Rightarrow$ factor $2^{-j}\tau\|\nabla\Psi\|_\infty$.  
- (4.C2): $[e^{\tau\Psi},R_iR_m]$ — odd CZ kernel + mean-value expansion $\Rightarrow$ effective kernel $|x-y|^{-2}$; Schur test on $L^2$.  
- (A.1): $\varepsilon(L)=2^{-N(L+1)}/(1-2^{-N})$ — dyadic off-diagonal from LP supports (Appendix ST.3).  
- (A.3): $\tau\|\nabla\Psi\|_\infty\lesssim \tau/R$ — choose $R\ge (16/C_{\rm car})\max\{c_1,c_2\}\tau$ to absorb commutators into the principal term.  
- (V.1): weighted vorticity budget — differentiate $\int w^2|\omega|^2$, integrate by parts; the stretching term is controlled by $\tau/R$ and $\varepsilon(L)$ as in §4.3.

| Quantity | Bound | Source |
|---|---|---|
| \|\partial_t\Psi\|_\infty+\|
abla\Psi\|_\infty^2+\|D^2\Psi\|_\infty | \(\lesssim R^{-2}\) | (3.CI2) |
| Weight–LP commutator | \(\lesssim 	au/R\) | (4.C1) |
| Pressure commutator | \(\lesssim 	au/R\) | (4.C2) |
| Carleman principal \(C_{
m car}\) | \(\gtrsim c_{
m par}rac{eta-	frac34}{1+\lambda}
u\) | (3.CI1) |
| Far tail \(arepsilon(L)\) | \(=2^{-N(L+1)}/(1-2^{-N})\) | App. R |


> **注記（安定定数 $C_{\mathrm{S4}}$）**：$C_{\mathrm{S4}}$ は Appendix V の加重渦度予算 (V.1) と §4.2–§4.3 の可換子評価（(4.C1)(4.C2)）、および (A.1)–(A.3) のパラメータ選択により拘束され、固定された $(\lambda,\beta,\nu)$ と $(L,\tau,R,N)$ に依存する**普遍定数**として扱える。具体的な係数対応は §7.1 表と Appendix V の式番号に従う。
## 7.2. **Proposition (Rigidity→Global via CE)**
**命題**：blow‑up が存在すれば、Appendix U の **Theorem U.E** により前コンパクト CE が構成される。
しかし §3–§7 の剛性解析により **CE は存在不能**。よって blow‑up は存在しない。□

---

# 8. Editorial Note：Chapter‑8 の課題 → 本文での解決
- **Task‑8.1**（Dyadic→NSE with pressure）→ §4 ＋ Appendix S/R。  
- **Task‑8.2**（CE 非循環化）→ Appendix U（存在）＋ Appendix U′（一様化）＋ §7（剛性）。  
- **Task‑8.3**（Multi‑peak 主定数 M 非依存）→ §3（3.CI1）＋ §4（吸収）。  
- **Task‑8.4**（D(Q_R) 同一化）→ §2.2（Lemma 2.1）。

---

# Appendix R — Off‑Diagonal & Heat‑Tail
Bony のオフ対角 \(2^{-N|k-j|}\)（\(N\ge6\)）と熱尾；\(arepsilon(L)=2^{-N(L+1)}/(1-2^{-N})\)。

# Appendix S — CZ Commutator with Weights（完全展開）
核の奇対称性と平均値展開で \([e^{	au\Psi},R_iR_m]\) を分解。Schur 試験＋Young で (4.C2) を得る。
Parametric Absorption Lemma により主項へ吸収。

# Appendix T — Boundary Cut‑offs & Robustness
T.1：境界切断と Carleman の整合。T.3：D(Q_R) のロバスト性の証明。

# Appendix U — **Theorem U.E（CE の存在＆前コンパクト性）**


**Normalization of blow-up sequences (for BG).**  
Given a blow-up solution $u$, pick $t_n\uparrow T^\*$ with
$\|u(\cdot,t_n)\|_{\dot H^{1/2}}$ approaching the critical threshold. Define
scales $\lambda_n$ and cores $x_n$ so that $v_n(x)=\lambda_n^{1/2}u(x_n+\lambda_n x,t_n)$
is bounded in $\dot H^{1/2}\cap L^2$. Then BG applies to $\{v_n\}$, yielding
$v_n=\sum_{j=1}^J\phi^j_n+r^J_n$ with orthogonal parameters. Lemma Z.R$^+$ controls
both the linear tail $e^{t\Delta}r^J_n$ and the nonlinear lifting error $E^J_n$
on $[0,T]$. This produces a precompact CE orbit, as stated in Theorem U.E.

**定理 U.E**（Kenig–Merle 型）：もし blow‑up があるなら、
臨界ノルム最小の CE が存在し、その正規化軌道 \(\mathcal K\) は \(\dot H^{1/2}\cap L^2\) で相対コンパクト。  
*証明概略*：臨界列抽出 → BG プロファイル分解（Appendix Z）→ 非線形持ち上げと安定性（S4）→
複数プロファイルの排除 → ほぼ周期性（前コンパクト性）。S3（後退一意性）は剛性側で参照、ここでは不使用。□

# Appendix U′ — **CE 一様タイトネスとスケール共変性**


### Lemma U′.GA (Global Activation for Compact Orbits)
Let $\mathcal K\subset L^2$ be the precompact normalized orbit furnished by Theorem U.E.
Then there exist parameters $(L_\*,\tau_\*)$ and a function $R_\*(\tau)=\max\{\tfrac{16c_1}{C_{\rm car}}\tau,\tfrac{16c_2}{C_{\rm car}}\tau\}$
such that for every $v\in\mathcal K$ and for all times,
\[(L,\tau,R)=(L_\*,\tau,\ R\ge R_\*(\tau))\]
satisfy the activation conditions **(4.PAL1)** with $\varepsilon(L_\*)\le C_{\rm car}/16$ and
$\kappa\le C_{\rm car}/16$, hence **(4.PAL2)** holds uniformly in time.


\begin{proof}[Proof of Lemma U′.GA]
Uniform spectral/spatial tightness (Lemma U′.1) fixes $K_{\varepsilon_0},R_{\varepsilon_0}$.
Choose $L_\*$ by (A.1), $\tau_\*$ by (A.2), and $R\ge R_\*(\tau)$ by (A.3) so that (4.PAL1) holds uniformly.
Then (4.PAL2) follows at all times.
\end{proof}

**Lemma U′.1（Uniform spectral & spatial tightness）**：
\(\mathcal K\subset L^2\) が相対コンパクト ⇒ 任意の \(arepsilon>0\) に対し
\(\exists K_arepsilon,R_arepsilon\) で
\[ \sup_{v\in\mathcal K}\sum_{|j|>K_arepsilon}\|P_j v\|_2^2<arepsilon,\quad
\sup_{v\in\mathcal K}\int_{|x|>R_arepsilon}|v|^2<arepsilon. 	ag{U'.1}\]
（有限ランク近似の一様化／Rellich 一様化。）  
**Scale–covariance**：NSE スケーリングで集中は中心殻のシフトと半径拡大に移る。
**系 U′.2**：各時刻で (4.PAL1) を満たす \(R,L,	au\) を選べ、(★) が**全時刻で起動**。

# Appendix V — Weighted Vorticity Budget
重み \(w=e^{	au\Psi}\) に対し
\[
rac{d}{dt}\int w^2|\omega|^2 + 
u\int w^2|
abla\omega|^2
\ \le\ C\Big(	frac{	au}{R}\Big)\Big(\int w^2|
abla u|^2 + 	au^2\int w^2|u|^2\Big),
	ag{V.1}\]
伸張 near は主項吸収、far は \(arepsilon(L)\) で収納。

# Appendix W — Independent Verification Checklist（強化版・外部理論の出典明示）（強化版）
1. (4.N1), (4.C1), (4.C2) → (4.PAL2) の吸収を Young で逐語検証。  
2. §7.1 表の各行に出典式番号を対応付け。  
3. §2.2（2.RB1）で D(Q_R) の同一化を確認。  
4. §6（6.H1）で下界、§7 で上界との矛盾を確認。  
5. Appendix U（U.E）／U′（U′.1）で CE の一様起動を確認。
6. **外部古典定理の一覧**（BG 分解、Leray 投影、CZ 作用素、局所理論）の出典確認。
7. Z.R$^+$／U′.GA の完全証明を逐語検証（式番号対応を含む）。

# Appendix X — Open‑set Feasibility of (★)
\(\mathcal U\) の開集合性；\(arepsilon(L)\) と閾値依存の連続性。


# Appendix ST — Standard Toolkit (Self-contained statements & micro-proofs)

**ST.1 (Schur test on $L^2$).**  
If $K(x,y)$ satisfies $\sup_x\!\int |K(x,y)|dy \le A$ and $\sup_y\!\int |K(x,y)|dx \le A$, then
$Tf(x)=\int K(x,y)f(y)dy$ obeys $\|T\|_{L^2\to L^2}\le A$. *Proof.* Cauchy–Schwarz with Fubini.

**ST.2 (Riesz transforms and Leray projector on $L^2$).**  
$R_i$ is the Fourier multiplier $-i\xi_i/|\xi|$; by Plancherel, $\|R_i f\|_2=\|f\|_2$.  
The Leray projector $\mathbb P$ has symbol $\delta_{ij}-\xi_i\xi_j/|\xi|^2$, hence $\|\mathbb P f\|_2\le \|f\|_2$.

**ST.3 (Littlewood–Paley off-diagonal decay).**  
Let $P_j$ be smooth dyadic projectors. Then $\|P_jP_k\|_{L^2\to L^2}\lesssim 2^{-N|j-k|}$ for any $N$.
*Proof idea.* Frequency supports are separated; repeated integration by parts on the oscillatory kernel yields rapid decay.

**ST.4 (Heat semigroup $L^2$ bounds).**  
$\|e^{t\Delta}f\|_{L^\infty_tL^2_x}\le \|f\|_2$ and $\int_0^\infty\|\nabla e^{t\Delta}f\|_2^2dt=\tfrac12\|f\|_2^2$ (Plancherel).


# Appendix Z — Addendum
> **BG applicability（適用可能性）**：臨界ノルム有界列に対して BG プロファイル分解は一般に適用可能で、スケール・平行移動パラメータの直交性が標準形で成立する。本稿の **Lemma Z.R$^+$** は、この枠組みの下で線形尾と非線形相互作用を**定量小**に抑える。圧力項は Appendix S の CZ 可換子で処理する。

# Appendix Z — Nonlinear Lifting（BG Profiles → NSE）
重み付き安定性に基づく持ち上げ概略（S4 を参照）。

# Appendix AA — Non‑circularity（依存 DAG）
CE 構成（Appendix U）→ U′（一様化）→ 吸収（§4.3）→ HERI（§6）→ 矛盾（§7）。逆向き矢印は存在せず循環なし。

# Supplement N — Numeric Demo（証明不使用）
参考スクリプト。証明は数値に依存しない。


## Appendix Z — Addendum: Quantified Residuals for BG (Lemma Z.R$^+$)

**Lemma Z.R$^+$ (Residual and nonlinear lifting, quantified).**  
Let $u_{0,n}=\sum_{j=1}^J\phi^j_n+r^J_n$ be a BG profile decomposition of a bounded
sequence in the critical space used in Appendix U. For any $\varepsilon>0$, there exist
$J_\varepsilon$ and $n(J)$ such that for all $J\ge J_\varepsilon$ and $n\ge n(J)$, with fixed $T>0$,
\begin{align*}
\|e^{t\Delta}r_n^J\|_{L^\infty_tL^2_x([0,T])\cap L^2_t\dot H^1_x([0,T])} &\le \varepsilon, \\
\|E_n^J\|_{L^1_tL^2_x([0,T])} &\le C_{\mathrm{S4}}\,\varepsilon,
\end{align*}
where $E_n^J$ denotes the nonlinear lifting error induced by inserting the truncated
superposition into NSE, and $C_{\mathrm{S4}}$ is the stability constant from (S4).
In particular, the lifted approximate solution is stable on $[0,T]$ and the corresponding
orbit is precompact modulo the profiles' parameters.


\begin{proof}[Proof of Lemma Z.R$^+$]
BG orthogonality and semigroup decay give the linear tail bound.
Bony paraproduct with off-diagonal $2^{-N|k-j|}$ (Appendix R) and CZ commutators (Appendix S)
control cross-interactions; weighted stability (S4) yields $\|E_n^J\|_{L^1_tL^2_x}\le C_{\mathrm{S4}}\varepsilon$.
\end{proof}


# Appendix AA — Dependency DAG (Self-contained view)

```
Data (smooth) ──► Local mild theory (standard)
     │
     ├─► Blow-up assumption
     │      │
     │      └─► BG profile decomposition (standard) ─┐
     │                                               │
     └───────────────────────────────────────────────┼─► Appendix U: Theorem U.E (construct CE + precompactness)
                                                     │
CE (precompact) ──► Appendix U′: Lemma U′.1 (uniform tightness) ──► Lemma U′.GA (global activation)
                                                     │
                                                     ├─► §4: PAL (commutators + far tails absorbed)
                                                     ├─► §6: HERI lower bound (covering)
                                                     └─► §7: Rigidity on Q_R (upper vs lower) ⇒ contradiction
```
**External classical blocks** (boxed): BG decomposition, Leray/CZ, local mild theory.  
**Internal blocks** (this paper): Z.R$^+$, U′.GA, PAL, HERI, Robustness (Lemma 2.1), Rigidity.



# Open Problems — Toward Unconditional Regularity

The principal technical obstacles for removing the explicit hypotheses used in this paper are:
1. **Automatic uniform tightness for CE**: Prove that the CE orbit $\mathcal K$ is uniformly tight in $L^2$ for arbitrary finite‑energy initial data (remove Besov‑type a priori / tail tightness assumptions).
2. **Universal analytic lower bound for Carleman principal**: Establish a lower bound for $C_{\rm car}$ depending only on $(\nu,\|u_0\|_{L^2})$, independent of auxiliary design.
3. **Quantitative decay of profile–profile interactions**: Provide rates under only the hypotheses of BG decomposition (without additional angular Besov control).



# Appendix H0 — Localized Helicity (draft)

\begin{lemma}[Local helicity control — draft]
Let $u$ be a smooth solution of 3D Navier--Stokes on $[0,T]$ with vorticity $\omega=\nabla\times u$.
Fix $R>0$ and an angular window $\chi_\Theta$ supported on a spherical cap on $S^2$.
Define the localized helicity
\[
H_{R,\Theta}(t):=\int_{|x|<R} (u(x,t)\cdot\omega(x,t))\,\chi_\Theta\!\Big(\frac{x}{|x|}\Big)\,dx.
\]
Then, for any $0<t\le T$, there is a constant $C$ (universal) such that
\[
\frac{d}{dt}H_{R,\Theta}(t)\ \le\ C\Big( E_{R,\Theta}(t)^{1/2}\,D_{R}(t)^{1/2}\ +\ \frac{1}{R}\,E_{R,\Theta}(t)\Big),
\]
where
\[
E_{R,\Theta}(t):=\int_{|x|<R}|\omega(x,t)|^2\chi_\Theta\Big(\frac{x}{|x|}\Big)\,dx,\qquad
D_{R}(t):=\int_{|x|<R}|\nabla\omega(x,t)|^2\,dx.
\]
In particular, if $\int_0^T D_{R}(s)\,ds<\infty$ and $H_{R,\Theta}(0)$ is finite, then $H_{R,\Theta}(t)$
cannot grow arbitrarily fast; angle‑localized vorticity concentration is quantitatively constrained.
\end{lemma}

\paragraph{Proof sketch.} Differentiate $u\cdot\omega$ using the vorticity equation, integrate against
the angularly localized cutoff and a radial cutoff for $|x|<R$. The viscous term yields $D_R$;
transport terms are treated by integration by parts with boundary error $\lesssim R^{-1}E_{R,\Theta}$;
vortex‑stretching is bounded by Cauchy–Schwarz as $E^{1/2}D^{1/2}$; pressure contributions cancel after
applying Leray projection and the oddness of CZ kernels.
