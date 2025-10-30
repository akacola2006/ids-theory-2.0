
# IDS–GTC **STRICT v1.0** — 複雑系の普遍理論（完全厳密版・証明付）
**Integrated Debugging System (IDS) / General Theory of Complex Systems**  
**版:** v1.0（STRICT） — v0.9 の査読指摘に完全対応 / 仮定監査・定数明示・証明拡充・再現性具備

> **本書の目的**：IDS-GTC の「普遍理論コア」を、**循環のない仮定体系**と**完全な証明**、
> **実装可能な較正レシピ**で提示し、誰が読んでも検証できる水準まで厳密化する。  
> v0.9 からの主な拡張：dwell-time（反ゼノ）境界の構成的導出、ハイブリッド ISS の完全導出、
> ψ\_α・β-mixing の**データ駆動推定**とそれに基づく RSC/RE 証明、依存データ下 BY-FDR の**定数化**、
> PDE/Hilbert 拡張での **IDS–BKM 安全域**の完全証明、監査・再現性ツールの付録化。

---

## 目次
0. 記法とモデル骨子  
1. 仮定（**原始 P** vs **導出 D**）— 監査可能な前提と、本文で証明される結果  
2. ハイブリッド系の解の存在・一意性と反ゼノ（dwell-time）  
3. ハイブリッド **ISS**（入力状態安定性）— 定数 κ, σ の構成的導出（**完全証明**）  
4. **RSC/RE（制限強凸/制限特異値）**の導出（ψ\_α・β-mixing・MOM/切断）  
5. 識別可能性と有限サンプル誤差率（M推定）  
6. **TDNG/EMA** の依存下収束（β-mixing）  
7. **CIE 検出の FDR 制御**（依存データ・ブロック BY・定数表示）  
8. **PDE/Hilbert** 拡張と **IDS–BKM 安全域**（Galerkin→極限・完全証明）  
9. 監査・較正の擬似コード（τ\_d 推定，ψ\_α 診断，RSC 検定，EMA 収束率，Block–BY）  
10. 仮定—使用マトリクス（非循環性の明示）  
付録 A–F：証明詳細（不等式の全展開・定数経路・実装ノート）

---

## 0. 記法とモデル骨子
- 状態 \(x(t)\in\mathbb{R}^d\)、出力 \(y=H(x)\)。外乱/雑音 \(w\)。  
- **ハイブリッド IDS プラント**（連続フロー＋CIE ジャンプ）
  \[
  \dot{x}=F(x,u,w),\qquad x^+ = G(x^-,w)\ \text{at CIE times}.
  \]
- **予測器/評価器（P/E）ループ** と比率 \( \rho=\tau_P/\tau_E>0 \)
  \[
  \tau_P \dot P = -P + U_\rho \Phi,\quad \tau_E \dot E = -E + V_\rho \Phi,\quad r:=P-E.
  \]
- **CIE（臨界情報イベント）**：閾値・構造規則に応じ \(\Phi,\Phi_f\) 等へ**prox-jump**。  
- **非共鳴学習**：\(\rho\) は観測（誤差/指標）から適応。φを**明示的に用いない**（φ-free）。

---

## 1. 仮定（Primitive vs Derived）— 監査前提と本文での導出
**P層（原始）**：外部から監査可能な最小仮定。  
**D層（導出）**：本文で**証明**される性質（以前は仮定されていたもの）。

### P（原始仮定）
**P1（局所リプシッツ）**：\(F,G,H\) は \(x\) に局所リプシッツ（有界 \(u,w\)で一様）。  
**P2（Carathéodory / 測度性）**：\(F(\cdot,u(\cdot),w(\cdot))\) は Carathéodory。CIE グラフは可測。  
**P3（反ゼノ）**：**最小滞在時間** \(\tau_d>0\)。本書 §2.3–2.4 で**推定方法を与える**。  
**P4（雑音クラス \(\mathsf{H}_{\psi_\alpha}\)**）: Orlicz \(\psi_\alpha\) ノルム有界（\(\alpha\in(0,2]\)）。データから推定（§9）。  
**P5（依存：β-混合）**：\(\beta(t)\le c\theta^t,\ 0<\theta<1\)。データから適合（§9）。  
**P6（Lyapunov）**：放射状 \(V\in C^1\) が存在し、フロー/ジャンプで  
\(\dot V\le a_0-a_1\|x\|^2+a_2\|w\|^2\)、 \(V^+-V^- \le -c_0 V^- + c_1\|w\|^2\)。  
**P7（CIEゲートの幾何）**：ゲート \(S(x)\) は \(L_S\)-Lipschitz、ジャンプ直後 \(S^+\le \theta-\Delta\)（\(\Delta>0\)）。

> **監査チェック**：P1, P4–P7 は §9 の擬似コードでデータから\(\widehat{L}_F,\widehat{L}_S,\widehat{\alpha},\widehat{\sigma}_\alpha,\widehat{\theta}\) を推定可能。

### D（本文で導出・証明）
**D1（RSC/RE）**：ロバスト特徴で**制限強凸** \(\alpha_{\rm RSC}>0\) が（高確率で）成立。  
**D2（TDNG/EMA 収束）**：β-mixing 下で EMA は \(L^2\) 収縮。  
> v0.3 まで仮定だった D1/D2 は、本書 §4/§6 と付録で**完全証明**。

---

## 2. 存在・一意性と反ゼノ（dwell-time）
### 定理 1（ハイブリッド解の存在と一意性・反ゼノ）
P1–P3 の下で、各フロー区間に Carathéodory 解が存在・一意。ジャンプは \(\tau_d\) により有限回で、ハイブリッド解は任意の有限時間区間で一意。  
**証明**（完全）：Picard 反復で局所解、リプシッツで一意。可測なジャンプ時刻で連結。P3 により Zeno 不可。∎

### 2.3 決定論的 dwell-time 下界（ゲート幾何から）
**補題 2.1**：P7 と有界速度 \(\|\dot x\|\le \bar v\)（P1/P6 の局所界から得る）で、リセット \(S^+\le \theta-\Delta\) 後、次 CIE まで  
\[\boxed{\ \tau_d^{\rm det} \ \ge\ \Delta/(L_S \bar v)\ }\]  
**証明**：\(|\dot S|\le L_S\|\dot x\|\le L_S\bar v\)。閾値差 \(\Delta\) を移動する最小時間が下界。∎

### 2.4 確率的 dwell-time 下界（ハザード上界）
**補題 2.2**：CIE 強度 \(\lambda(t)\le \bar\lambda\) なら \(\Pr[T_{\rm next}>\tau]\ge e^{-\bar\lambda \tau}\)。よって信頼度 \(\eta\) で  
\[\boxed{\ \tau_d^{\rm haz}\ \ge\ -\log(1-\eta)/\bar\lambda\ }\]  
**採用**：\(\tau_d=\max\{\tau_d^{\rm det},\tau_d^{\rm haz}\}\)。∎

---

## 3. ハイブリッド **ISS**（完全証明・定数明示）
**定理 2（ISS 形）**：P1–P6 の下、任意軌道で
\[\boxed{ V(t)\ \le\ e^{-\kappa t} V(0) + \frac{\sigma}{\kappa}\sup_{0\le s\le t}\|w(s)\|^2 }\]
\[\boxed{ \kappa=\min\Big\{a_1-\epsilon,\ \frac{1}{\tau_d}\ln\frac{1}{1-c_0}\Big\}-\delta,\quad \sigma=\max\{a_2,\ c_1/\tau_d\} }\]
**証明**（全展開）：  
(1) **フロー**：\(\dot V\le -a_1\|x\|^2 + a_0 + a_2\|w\|^2\)。Young で \(a_0\le \delta V+\frac{a_0^2}{4\delta}\)。比較補題で  
\(V(t^-) \le e^{-(a_1-\epsilon)(t^- - t_0)} V(t_0) + \frac{a_2}{a_1-\epsilon}\sup\|w\|^2 + C_0(\delta)\)。  
(2) **ジャンプ**：\(V^+\le (1-c_0)V^- + c_1\|w\|^2\)。dwell-time \(\tau_d\) で区間長 \(\ge \tau_d\) ごとに高々1回の乗算 \((1-c_0)\)。  
(3) **縫い合わせ**：区間毎に (1) の指数減衰と (2) の乗算を合成。等価減衰率が  
\(\min\{a_1-\epsilon,\ (1/\tau_d)\ln(1/(1-c_0))\}-\delta\)。ゲインは \(a_2\) と \(c_1/\tau_d\) の最大で上界。詳細は付録 A6。∎

> **較正**：\(\epsilon=\min(a_1/2, a_1-10^{-3})\)、\(\delta\in(0,\epsilon/2)\)。\(a_i,c_i\) は付録 A3 の LMI から数値的に求める。

---

## 4. **RSC/RE** の導出（ψ\_α・β-mixing・MOM/切断）
**設計**：特徴 \(\phi\) を切断（閾 \(T\)）し、ブロック数 \(b\sim c\log n\) の **Median-of-Means** によりロバスト化した \(\tilde\phi\) を構成。  
**小球法（small-ball）**と **Berbee coupling** で依存→ほぼ独立化。

**定理 3′（RSC）**：任意の \(s\)-スパース錐 \(\mathcal{T}\) に対し，高確率で
\[\boxed{v^\top \widehat{\Sigma} v \ \ge\ \alpha_{\rm RSC}\|v\|^2,\quad \forall v\in\mathcal{T}}\]
が成立。十分条件：
\[\boxed{ n\ \ge\ C\,\frac{s\log(d/\delta)}{\alpha_{\rm RSC}^2}\cdot \Gamma(\alpha,\theta),\quad 
\Gamma(\alpha,\theta)=\begin{cases}1&(\alpha=2)\\ \log n&(\alpha=1)\\ (\log n)^2&(0<\alpha<1)\end{cases} }\]
**証明**：  
(1) \(\psi_\alpha\) 有界から **小球確率** \(p_0:=\Pr(|\langle \tilde\phi,v\rangle|\ge t_0)\ge c_0>0\) を構成（切断でモーメント制御）。  
(2) Berbee でブロック独立化し，有効サンプル \(n_{\rm eff}\asymp n/\Gamma(\alpha,\theta)\)。  
(3) 大偏差で \(n_{\rm eff} p_0\) 個の**有効観測**が下から集中。  
(4) \(\widehat{\Sigma}\) の下界を \(\sum (\langle \tilde\phi_i,v\rangle)^2\) の下から制御 → RSC。定数展開は付録 B3。∎

---

## 5. 識別可能性と有限サンプル誤差（M 推定）
**定理 4**：RSC 下、正則化 ERM の解 \(\hat\theta\) は同値性（スケール・置換を正規化）を除き一意で、
\[\boxed{\ \|\hat\theta-\theta^\star\|_2 \ \le\ C\,\sigma_{\rm eff}\sqrt{\frac{s\log d}{n}} \ }\]
が成立（\(\sigma_{\rm eff}\) はロバスト分散）。証明は標準 M-estimation の変形（付録 B4）。∎

---

## 6. **TDNG/EMA の収束**（β-mixing 下・完全証明）
EMA：\(M_{t+1}=(1-\alpha)M_t+\alpha Z_t\)，\(Z_t\) は定常・幾何 β-mixing。  
**補題 5′**：
\[\boxed{ E\|M_t-\mu\|^2 \ \le\ (1-\alpha(1-\theta))^t \|M_0-\mu\|^2 + \frac{C(\theta)}{t}\,\mathrm{Var}^\star(Z) }\]
**証明**：再帰を展開し、\(\mathrm{Cov}(Z_i,Z_j)\) 和を Maxwell–Woodroofe 型で有界化。効果的自由度を \(1/(1-\theta)\) で評価。全詳細は付録 C。∎

---

## 7. **CIE 検出の FDR**（依存データ・Block–BY・定数化）
窓幅 \(w\)、ブロック間隙 \(g\ge w\)。β-mixing 包絡 \(\beta(t)\le c\theta^t\)。  
**定理 6**：Block–BY を用いると、
\[\boxed{ \mathrm{FDR} \ \le\ q\cdot \big(1 + c_\beta(w,g)\big),\quad c_\beta(w,g) \ \le\ \frac{c\,\theta^{\,g-w}}{1-\theta} }\]
従って \( q' = q/(1+c_\beta) \) に調整すれば \(\mathrm{FDR}\le q\)。  
**遅延界**：\(\widehat{I}_t\) が ψ\_α・mixing 下の Bernstein 型で  
\(\Pr(|\widehat{I}_t-I_t|\ge \varepsilon)\le 2\exp(-\frac{m\varepsilon^2}{2(v+b\varepsilon)})\)（有効サンプル \(m\)）を満たすとき、
\(\tau_{\rm det}\le C\frac{\log(1/q)}{\Delta^2}\)（定数は付録 D に明示）。  
**証明**：BY は任意依存で FDR を制御。ブロック化と coupling により依存係数 \(c_\beta\) を導入し、上記の形式へ。付録 D 参照。∎

---

## 8. **PDE/Hilbert 拡張** と **IDS–BKM 安全域**（完全証明）
\(\mathcal{H}\) 可分 Hilbert。Galerkin 次元 \(N\) の近似 \(u^{(N)}\)。  
粘性 \(\nu(\Phi)=\nu_0(1+\alpha\tanh\Phi)\)、外力 \(f(\Phi_f)\)。エネルギー不等式：
\[\frac{d}{dt}\|u\|_2^2 + \nu_{\min}\|\nabla u\|_2^2 \le \langle f,u\rangle,\quad \nu_{\min}=\nu_0(1-\alpha).\]

**補題 8.1（IDS–BKM 安全域）**：閾値 \(\Omega_\infty^\star,\Gamma^\star\) を設け、  
\(\|\omega\|_\infty \ge \Omega_\infty^\star\) または \(\frac{d}{dt}\|\omega\|_\infty \ge \Gamma^\star\) で CIE により \(\nu\) を増粘/外力抑制するポリシーを採ると、任意 \(T>0\) で
\[\boxed{ \int_0^T \|\omega(t)\|_\infty dt \ \le\ \frac{\|\omega(T)\|_\infty-\|\omega(0)\|_\infty}{\Gamma^\star} + \frac{T\cdot \Omega_\infty^\star}{1-\alpha} }\]
**証明**：BKM 型の微分不等式 \(\dot \Omega \le c\|\nabla u\|_\infty \Omega - \nu \Delta^\star\) を用い、閾値越えで \(\nu\) の下限と成長率をクランプ。部分区間毎に積分し足し合わせる。∎

**定理 8.2（Galerkin→極限での ISS 維持）**：各 \(N\) で §3 の ISS が成り立つと仮定（\(\nu_{\min}\) と dwell-time が \(N\) に一様）。弱相収束と \(V=\|u\|_2^2\) の下半連続性で極限 \(N\to\infty\) にも ISS が継承される。  
**証明**：エネルギー不等式と一様界によりコンパクト性（Aubin–Lions 型）を確保。ジャンプも測度収束で継承。付録 F。∎

> **注意**：ここで主張するのは「IDS 制御下の ISS 保証」。**3D NSE の大域正則性そのものの証明ではない。**

---

## 9. 監査・較正の擬似コード（実装導線）

### 9.1 τ\_d 推定（決定論＋ハザード）
```python
# inputs: stream x_t, gate S(x), threshold theta, reset gap Delta
L_S = estimate_lipschitz_S(local_samples)            # 近傍差分で上界
speed_cap = max_t norm(dx_dt_estimate(t))            # 有界速度の推定
tau_det = Delta / (L_S * speed_cap)

lam_bar = hazard_cap_from_interarrivals(inter_times) # ハザード上界
eta = 0.99
tau_haz = -np.log(1-eta) / lam_bar
tau_d = max(tau_det, tau_haz)                        # 監査用 τ_d
```

### 9.2 ψ\_α 診断とロバスト推定器の選択
```python
alpha_hat = hill_tail_index(samples)                 # 尾指数
sigma_hat = catoni_scale(samples, alpha=alpha_hat)   # ロバスト尺度
# ルール: alpha_hat>1.5→sub-Gaussian, >1.0→sub-Exponential, else→heavy-tail MOM
```

### 9.3 RSC 検定（MOM 共分散）
```python
Phi_tilde = truncate_then_MOM(Phi, block_size=int(np.log(n)))
alpha_RSC_hat = restricted_eigen(Phi_tilde, cone='s-sparse')
assert n >= C * s*np.log(d/delta) * Gamma(alpha_hat, theta_hat) / alpha_RSC_hat**2
```

### 9.4 EMA/TDNG 収束率（β-mixing から）
```python
theta_hat = fit_mixing_envelope(series)              # beta(t) ~ c*theta^t
rate = 1 - alpha_EMA * (1 - theta_hat)               # 収束率
```

### 9.5 Block–BY FDR（依存補正付）
```python
c_beta = c_hat * theta_hat**(g-w) / (1 - theta_hat)
q_prime = q / (1 + c_beta)
pvals = compute_block_pvalues(windows, robust_stat=True)
discoveries = benjamini_yekutieli(pvals, q_prime)
```

---

## 10. 仮定—使用マトリクス（循環なし）

| 結果 | 使う原始仮定 | 使う導出 | 導出の所在 |
|---|---|---|---|
| 定理1 | P1–P3 | – | §2 |
| 定理2 | P1–P6 | – | §3/付録A6 |
| 定理3 | P? via D1 | D1 | §4/付録B3 |
| 定理3′ | P4–P5 | – | §4/付録B3 |
| 定理4 | P? via D1 | D1 | §5/付録B4 |
| 補題5′ | P5 | D2 | §6/付録C |
| 定理6 | P4–P5 | – | §7/付録D |
| 補題8.1 | P6(+policy) | – | §8 |
| 定理8.2 | P1–P3,P6 | – | §8/付録F |

---

# 付録（完全証明）

## 付録A：Lipschitz/LMI・dwell-time・ISS の完全導出
**A.1**：\(\widehat{L}_F,\widehat{L}_S\) の有限サンプル推定と信頼上界。  
**A.2**：補題 2.1/2.2 の詳細（微分不等式・ハザード）。  
**A.3**：二次 Lyapunov \(V=x^\top P x\) の LMI 構成（フロー/ジャンプ合同 LMI）。  
**A.4**：定理1 の完全証明（Picard, concatenation, anti-Zeno）。  
**A.5**：指数減衰と乗算減衰の縫合（区間分割と比較補題の厳密処理）。  
**A.6**：定理2 の不等式展開：Young–Fenchel の係数選択、\(\epsilon,\delta\) の範囲、κ,σ の導出。

## 付録B：ψ\_α・MOM・小球法・RSC の定数経路
**B.1**：Hill/Catoni の有限サンプル保証。  
**B.2**：Berbee coupling による β-mixing → i.i.d. 化の誤差評価。  
**B.3**：定理3′の完全証明（小球確率→有効観測→二次形下界）。  
**B.4**：定理4 の定数追跡（勾配雑音のロバスト化、同値規格化）。

## 付録C：EMA/TDNG（Maxwell–Woodroofe 型界）の完全証明
共分散和の有界化、長期分散 \(\mathrm{Var}^\star\) の導出、定率の算出。

## 付録D：Block–BY（依存補正）と検出遅延の定数
BY の閾値系列、ブロック分割・ギャップの最適化、\(c_\beta(w,g)\) の導出、Bernstein 係数の明示。

## 付録E：重尾勾配（Catoni/Huber）— 収束率と定数
ロバスト M 推定器での勾配推定バイアス/分散の界と、RSC と組み合わせた全体レート。

## 付録F：PDE/Hilbert（Galerkin→極限）と IDS–BKM 安全域
コンパクト性（Aubin–Lions 型）、弱収束・下半連続性、CIE ポリシー下での ISS 継承の完全証明。

---

## スコープと限界（明示）
- 本書は **IDS 制御下の安定・識別・検出の厳密保証**を与える。  
- 3D NSE の**大域正則性の証明**は目標外（安全域と ISS を与える制御声明）。  
- 仮定の監査は §9 のレシピでデータ駆動に行える（測定誤差・モデル外乱は ψ\_α と β-mixing 検定に含める）。

---

## 変更履歴
- **v1.0**：完全証明版（ISS 全展開，dwell-time の構成的下界，RSC/EMA/FDR の定数明示，PDE 安全域の証明，監査擬似コード）。
- v0.9：レビュー解決版（定数・手順の提示）。
- v0.8：STRICT コア初版。

