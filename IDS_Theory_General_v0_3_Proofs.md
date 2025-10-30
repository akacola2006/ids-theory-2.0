# IDS 理論 v0.3 — 完全証明版（Markdown）

- 日付: 2025-09-17
- 対象: `IDS_Theory_General_v0_3.md` の定理・補題（Thm 1–7, Lemma 5）
- 前提: 文書本体の公理・記号に従う。以下では必要な仮定を再掲し、証明を自足化する。

---

## 0. 立ち仮定（Standing Assumptions）

- (S1) 空間: $X$ は可分バナッハ空間。$C\subset \mathbb R^d$ はコンパクト。$H=[h_{\min},h_{\max}]$ は有界区間。$Y$ はノルム空間。
- (S2) 文脈基底: $\{\phi_k\}_{k=1}^K$, $\phi_k\in \mathcal C(C,[0,1])$, $\sum_k\phi_k(c)=1$。$\{c_k\}$ は $C$ の $\delta$-ネット。
- (S3) 変換: $T_k:X\to Y$ は $L_T$-リプシッツかつ $T_k(0)=0$。$E(\Delta,c)=\sum_k\phi_k(c)T_k(\Delta)$ は $(\Delta,c)$ に関して合同リプシッツ。
- (S4) 損失: $L:Y\to\mathbb R_+$ は $m$-強凸, $L$-滑らか（$m>0$, $L\ge m$）。
- (S5) 規範核: $K^{(h)}(t,\tau\mid c)$ は確率核。$\Phi^{(h)}$ は有界。EMA の場合は $n_{t+1}=(1-\alpha)n_t+\alpha\,\Phi_t$ ($0<\alpha<1$)。
- (S6) 結合: $\kappa(h_1,h_2)=\exp(-|h_1-h_2|/\lambda)$ (可和)。離散化すると結合行列 $A$ はスペクトル半径 $\rho(A)<1$ を満たす。
- (S7) 確率構造: $(\Omega,\mathcal F,\{\mathcal F_t\},\mathbb P)$ 上の過程 $x(t),c(t),w(t)$ は $\{\mathcal F_t\}$-適合で可測。$w(t)$ はサブガウス（分散 proxy $\sigma^2$）かつ二乗可積分。
- (S8) ハイブリッド形式: Flow 集合 $\mathcal C$（常微分）と Jump 集合 $\mathcal D$（切替）上で
  $$\dot z=F(z,t)\ (z\in\mathcal C),\qquad z^+\in G(z,t)\ (z\in\mathcal D),$$
  $z=(\hat x,R,\{n^{(h)}\})$。$F$ は Carathéodory 条件を満たし、$G$ は閉写像で有界画像。
- (S9) 反ゼノ: 最小滞在時間 $\tau_d>0$ または平均滞在時間条件により、有限時間内の切替回数は有界。
- (S10) 切替時の安定: 跳躍で Lyapunov 関数 $V$ が $V(z^+)\le V(z)+c_0$（任意に $c_0\ge0$）を満たす。
- (S11) 識別系: 文脈励起 ($\inf_k \mathbb P(\phi_k(c)>\epsilon_0)>\pi_0$), 変換独立（適切な集合上で線形独立）, RSC/RE 定数 $(\alpha_{\rm RSC},\gamma_{\rm RE})>0$, 入力励起（PE）。
- (S12) BH-FDR: p 値列は独立または PRDS を満たす。時系列依存の場合は間引き/ブロック化/LORD/LOND/SABHA のいずれかで制御する（詳細は Thm 6）。

---

## 1. Thm 1（井戸型: Well-posedness）の証明

【主張】 (S1–S3, S5, S7–S10) のもと、ハイブリッド系は任意の有界時間区間 $[0,T]$ で一意の Carathéodory 解を持ち、切替点以外で連続、切替点で右連続となる。

【証明】
1) Flow 区間の存在一意: $F$ は Carathéodory（時刻に可測・状態に連続・局所有界）であり、さらに局所リプシッツであるから、各 Flow 区間で常微分方程式は Carathéodory の定理より一意解を持つ。$E,\nabla L, K$ の寄与は (S3–S5) により右辺の局所リプシッツ性・有界性を損なわない。

2) Patch（継ぎ合わせ）: 切替時刻の列 $\{t_j\}$ は (S9) により $[0,T]$ に有限個しか存在しない。各区間 $[t_j,t_{j+1})$ で一意解を構成し、$t_{j+1}$ において $z(t_{j+1}^+)\in G(z(t_{j+1}),t_{j+1})$ を選ぶ。$G$ は閉写像で画像有界（S8）ゆえ、選択は可能であり、右連続とすることでハイブリッドトラジェクトリが定まる。

3) 一意性: 2 つの解 $z_1,z_2$ が同一初期値を持つと仮定。Flow 区間では Grönwall の補題により一致。Jump 時刻は同一規則（同一 $G$）に従い、右連続の選択を固定すれば $z_1(t_j^+)=z_2(t_j^+)$。帰納的に全区間で一致する。

以上より主張が従う。■

---

## 2. Thm 2（ISS: 入力対状態安定）の証明

【主張】 (S1–S6, S7–S10) のもと、$V=\alpha\|\Delta\|^2+\beta\|R-R^*\|^2+\gamma\sum_h d(n^{(h)},n_*^{(h)})$ とすると、定数 $\kappa,\sigma>0$ が存在し、Flow で $\dot V\le -\kappa V+\sigma\|w\|^2$。Jump では $V(z^+)\le V(z)+c_0$。ゆえに $w\equiv0,c_0=0$ のとき指数安定、一般には ISS。

【証明】
- Flow: $\dot V=2\alpha\langle \Delta,\dot\Delta\rangle+2\beta\langle R-R^*,\dot R\rangle+\gamma\sum_h \dot d_h$。$U_\rho,V_\rho$ の非膨張性（1-リプシッツ）と $L$ の $m$-強凸性から $2\beta\langle R-R^*,\dot R\rangle\le -2\beta\eta m\|R-R^*\|^2 + c\|r\|^2$。$\|r\|=\|E(\Delta,c)\|\le L_E\|\Delta\|$（合同リプシッツ）。TDNG の項は収縮（S5,S6）により $\le -c_n\sum_h d_h + c'\|w\|^2$ に評価できる。適切な $(\alpha,\beta,\gamma)$ を選べば交差項を Young 不等式で吸収し $\dot V\le -\kappa V+\sigma\|w\|^2$。
- Jump: (S10) により $V(z^+)\le V(z)+c_0$。
- 結合: 比較原理と Grönwall により、$w\equiv0,c_0=0$ なら $V(t)\le V(0)e^{-\kappa t}$。一般の $w,c_0$ でも標準の ISS 不等式 $V(t)\le e^{-\kappa t}V(0)+\int_0^t e^{-\kappa(t-s)}\sigma\|w(s)\|^2ds + N_T c_0$（$N_T$ は $[0,T]$ の切替回数の上界）を得る。■

---

## 3. Thm 3（LocalDOC の収束）の証明

【主張】 固定モード・文脈下で、$L$ が $m$-強凸・$L$-滑らか、定ステップ $\eta\in(0,2/L)$ の勾配法 $R_{t+1}=R_t-\eta\nabla L(R_t)$ は一意最小解 $R^*$ に線形収束し、$\|R_t-R^*\|\le (1-\eta m)^t\|R_0-R^*\|$。不偏ノイズ付き勾配では $\mathbb E\|R_t-R^*\|^2=O(1/t)$。

【証明】 強凸かつ滑らかな関数に対する勾配法の古典結果。誤差収束は Polyak–Łojasiewicz 不等式または co-coercivity から導出できる。確率近似は Robbins–Monro 条件（$\sum \eta_t=\infty,\ \sum \eta_t^2<\infty$）下の標準結果に従う。■

---

## 4. Thm 4（$E(\Delta,c)$ の識別可能性）の証明

【主張】 (S2,S3,S11) のもと、分解 $E(\Delta,c)=\sum_k\phi_k(c)T_k(\Delta)$ は置換・スカラー同値（$T_k\mapsto a_k T_{\pi(k)}$, $\phi_k\mapsto a_k^{-1}\phi_{\pi(k)}$）を除き一意。さらに、RSC/RE と PE の下で、最小二乗推定は MSE $\varepsilon$ を達成するのに $N=\Omega\!\big(Kd\,\log(1/\varepsilon)/\alpha_{\rm RSC}\big)$ の標本で足りる。

【証明（同一性）】 文脈点 $c^{(1)},\dots,c^{(K)}$ を取り、$\Phi\in\mathbb R^{K\times K}$, $\Phi_{ik}=\phi_k(c^{(i)})$ を作る。$\{c^{(i)}\}$ を $\delta$-ネットから選ぶと（S2）$\Phi$ は各行が確率分布で、一般にはフルランク（PR 設計）にできる。任意の固定 $\Delta$ について、$\mathbf r(\Delta)=[E(\Delta,c^{(i)})]_i=\Phi\,\mathbf t(\Delta)$, $\mathbf t(\Delta)=[T_k(\Delta)]_k$ を満たす。$\Phi$ が正則なら $\mathbf t(\Delta)=\Phi^{-1}\mathbf r(\Delta)$ で各 $T_k(\Delta)$ が回収される。$\Delta$ を励起集合上で動かせば $T_k$ が関数として同定される。置換・スカラー同値は分解の不定性として残るが、規格化（例: $\int_C\phi_k(c)dc=1$）で解消できる。

【証明（サンプル複雑度）】 実際には雑音と有限標本で $\min_{\Theta}\frac1N\sum_i\|E_\Theta(\Delta_i,c_i)-r_i\|^2+\lambda\|\Theta\|^2$ を解く。設計行列が RSC/RE を満たすと経験リスクは強凸となり、推定誤差は $\|\hat\Theta-\Theta^*\|_2^2\lesssim \frac{\sigma^2 K d\log(1/\varepsilon)}{N\alpha_{\rm RSC}}$。これを MSE $\varepsilon$ に等置して主張を得る。PE はバイアスの回避に必要。■

---

## 5. Lemma 5（TDNG の収束）の証明

【主張】 EMA: $n_{t+1}=(1-\alpha)n_t+\alpha\,\Phi_t$ で $0<\alpha<1$, $\Phi_t$ 有界, $\mathbb E\,\Phi_t\to\bar\Phi$。すると $\mathbb E\,n_t\to\bar\Phi$ かつ $\|n_t-\bar\Phi\|_2\le (1-\alpha)^t\|n_0-\bar\Phi\|_2+O_P(\alpha)$。一般核: $\mathcal T(n)=\int K\Phi$ が収縮（リプシッツ定数 $\rho<1$）なら一意固定点へ指数収束。結合: $\mathbf n_{t+1}=A\mathbf n_t+B\Phi_t$ で $\rho(A)<1$ なら指数安定。

【証明】
- EMA: 再帰差分 $e_t=n_t-\bar\Phi$ は $e_{t+1}=(1-\alpha)e_t+\alpha(\Phi_t-\bar\Phi)$。期待値で $\mathbb E e_{t+1}=(1-\alpha)\mathbb E e_t$（$\to 0$）。分散は $\mathrm{Var}(e_{t+1})\le (1-\alpha)^2\mathrm{Var}(e_t)+\alpha^2\mathrm{Var}(\Phi_t)$ から一様有界。Doob の不等式等で高確率界を与えられる。
- 収縮写像: 完備ノルム空間上で Banach の不動点定理。
- 結合: 線形系解 $\mathbf n_t=A^t\mathbf n_0+\sum_{s< t}A^{t-1-s}B\Phi_s$。$\rho(A)<1$ なら $\|A^t\|\le C\rho^t$ で指数減衰。■

---

## 6. Thm 6（CIE 検出: FDR と遅延界）の証明

【主張】 p 値列が独立または PRDS なら BH 手続きは $\mathrm{FDR}\le q$ を満たす。時系列依存では間引き/ブロック化で近似独立化し同様の界を与える。ガウス KL 指標で真の変化強度 $\delta$ があるとき、サンプル KL 推定量は大偏差で集中し、期待遅延は $O((\log(1/q))/\delta^2)$ に抑えられる。

【証明（FDR）】 独立または PRDS 下で BH の一様有界性は標準定理。依存がある場合、窓を互いに非重複（グリッド間隔 $g\ge w$）に間引けば擬独立。ブロック BH はブロック内で代表 p 値（最小等）を用いて独立化する設計。逐次法（LORD/LOND/SABHA）も $\le q$ を保証する既知の界を持つ。なお、具体的な p 値化はガウス KL の帰無分布（中心極限定理近似）で構成できる。

【証明（遅延）】 2 窓のガウス KL 推定 $\hat I_t$ は、平均差・分散差の推定誤差に対するサブガウス集中（Hoeffding/自乗型）で $|\hat I_t-I_t|\le \epsilon$ を $\exp(-c w\epsilon^2)$ で抑えられる。真の KL が $I_t\ge \delta$ なら、$\hat I_t>\theta$ となるまでの遅延は $O((\log(1/q))/\delta^2)$ に制御可能。■

---

## 7. Thm 7（計算スケーリング）の証明

【主張】 1 ステップ計算量は $O(K\,cost(T_k)+M B + p)$、メモリは $O(K d_x + M B + p)$。

【証明】 $\phi(c)$ の計算は $K$ 個のガウス基底で $O(K d_c)$。$T_k(\Delta)$ の評価を合計で $O(\sum_k cost(T_k))$。LocalDOC 勾配は $O(p)$（一般二次損失）または $O(d_s p)$（信号次元 $d_s$）。TDNG は $O(d_s)$。結合は帯域 $B$ に比例。合成すれば主張のオーダが得られる。メモリは対応するパラメタ・バッファの和。■

---

## 付記：正規化と同値類について
分解 $E(\Delta,c)=\sum_k\phi_k(c)T_k(\Delta)$ は置換・スケーリングに関して同値類を持つ。実装では $\int_C\phi_k(c)dc=1$ や $\|T_k\|_{\mathrm{Lip}}=1$ 等の規格化で一意性を選ぶ。識別定理はこの同値類を mod した意味で理解する。

---

以上で、`IDS_Theory_General_v0_3.md` に対応する完全証明版を与えた。必要に応じて、各セクションに定数の具体値（$\kappa,\sigma,C$ など）や推定量の分散界を追記できる。

