# IDS 理論（一般複雑系フレーム）v0.3

- 日付: 2025-09-17
- 著者: Collaborative Draft (based on IDS-lite spec)
- 変更点（v0.2 → v0.3）:
  - 確率構造（過程・可測性・フィルトレーション）を追加
  - ハイブリッド系形式（Flow/Jump, 退出集合, 反ゼノ仮定）を追加
  - 識別可能性の仮定（RSC/RE・励起・非縮退）を本文に昇格
  - TDNG の収束補題（EMA/一般核）と階層結合下の安定条件を追加
  - CIE の FDR 制御に関する独立/PRDS/時系列依存への対処を明記

## 要旨（再掲）
自己参照的誤差処理（Deviation→Contextual Interpretation→Modification→Context Update）を核とする IDS を、複雑適応系の一般理論として再構成する。最小公理に基づき、(i) 井戸型（well-posedness）、(ii) 入力対状態安定（ISS）、(iii) 局所最適化コア（LocalDOC）の収束、(iv) 解釈写像 $E(\Delta,c)$ の識別可能性、(v) 変化検出（CIE）の FDR/遅延保証、(vi) 計算スケーリングの十分条件を与える。さらに、本版では確率構造・ハイブリッド形式・識別仮定・TDNG 収束・FDR 前提を厳密化する。

## 目次
1. 序論と位置づけ  
2. 公理（オブジェクトと空間）  
3. ダイナミクス（P/E, E(Δ,c), LocalDOC, TDNG, CIE）  
4. 不変性・正規化  
5. 保証定理（十分条件）  
6. 計測・推定プロトコル  
7. 実装仕様（API と参照実装）  
8. 検証設計（ベンチマークと指標）  
9. 関連理論との接続  
10. 拡張（部分観測・多主体・因果）  
付録 A: 記号表／仮定表、付録 B: 証明スケッチ要約、付録 C: 追加仮定の詳細（本版追加）

---

## 1. 序論（略）
v0.2 と同様。

## 2. 公理（追加を含む）
- 状態空間: 観測 $x(t)\in X$（可分バナッハ）、予測 $\hat x(t)\in X$。
- 文脈空間: $c(t)\in C\subset\mathbb R^d$（コンパクト）。階層 $h\in H=[h_{\min},h_{\max}]$（有界区間）。
- ズレ: $\Delta(t)=x(t)-\hat x(t)$（物理単位整合）。
- 文脈基底: $\{\phi_k\}_{k=1}^K$, $\phi_k:C\to[0,1]$ 連続, $\sum_k\phi_k(c)=1$。原型 $\{c_k\}$ は $C$ の $\delta$-ネット。
- 変換: $T_k:X\to Y$ は $L_T$-リプシッツ, $T_k(0)=0$。
- 解釈: $E(\Delta,c)=\sum_k \phi_k(c)\,T_k(\Delta)$（合同にリプシッツ）。
- 局所損失: $L:Y\to\mathbb R_+$ は $m$-強凸, $L$-滑らか。
- 規範更新（TDNG）: $n^{(h)}(t+1)=\int K^{(h)}(t,\tau\mid c)\,\Phi^{(h)}(\tau)\,d\tau$（$K$ は確率核, $\Phi$ 有界）。
- 階層結合: $\kappa(h_1,h_2)=\exp(-|h_1-h_2|/\lambda)$, $\lambda>0$。
- CIE 関数: 情報利得 $I_t$（例: スライディング窓 KL）と閾値 $\theta$ で $I_t>\theta$ を変化検出とする。

### 2.1 確率構造（新設）
- 確率空間 $(\Omega,\mathcal F, \{\mathcal F_t\}, \mathbb P)$。過程 $x(t), c(t), w(t)$ は $\{\mathcal F_t\}$-適合、可測。$w(t)$ はサブガウス（パラメータ $\sigma^2$）かつ二乗可積分。
- 写像 $U_\rho, V_\rho, E, L, K$ はボレル可測。切替規則（CIE）は $\mathcal F_t$-適合。
- CIE の多重検定: BH 手続きは p 値列の独立または PRDS（Positive Regression Dependence on a Subset）を満たす場合に FDR 制御が成立。

### 2.2 ハイブリッド系形式（新設）
- Flow 集合 $\mathcal C$、Jump 集合 $\mathcal D$、流れ写像 $F$、ジャンプ写像 $G$ を用い、
  $$\dot z = F(z,t) \quad (z\in\mathcal C), \qquad z^+\in G(z,t) \quad (z\in\mathcal D),$$
  で $z=(\hat x,R,\{n^{(h)}\})$ を記述。
- 反ゼノ仮定: 最小滞在時間（dwell-time）$\tau_d>0$ または平均滞在時間条件を仮定し、単位時間当たりの切替回数を有界化。
- 可解性: $F$ は局所リプシッツ、$G$ は閉写像で有界画像、$\mathcal C,\mathcal D$ は閉集合。

## 3. ダイナミクス（略）
v0.2 と同様（ただし上記ハイブリッド表現に従う）。

## 4. 不変性・正規化（略）

## 5. 保証定理（十分条件, 追補を含む）

### Thm 1（井戸型; 追補）
- 仮定: 2.1–2.2 の確率構造・ハイブリッド仮定、$F$ は Carathéodory 条件（時刻に可測・状態に連続）を満たす。反ゼノ仮定。
- 結論: 任意の有界時間区間に一意の Carathéodory 解が存在。切替点以外で連続、切替点で右連続。

### Thm 2（ISS 安定; 追補）
- $V=\alpha\|\Delta\|^2+\beta\|R-R^*\|^2+\gamma\sum_h d(n^{(h)},n_*^{(h)})$ とし、$U_\rho,V_\rho$ は非膨張、$L$ は $m$-強凸。
- 結論: $\dot V\le -\kappa V+\sigma\|w\|^2$（$\kappa,\sigma>0$）。$w\equiv0$ なら指数安定。

### Thm 3（LocalDOC 収束; 既出）
- 固定モード/文脈では $\eta\in(0,2/L)$ で線形収束。不偏雑音下で $O(1/t)$。

### Thm 4（$E$ の識別可能性; 本文昇格）
- 仮定（識別最小条件）:
  1) 文脈励起: $c$ の分布は $C$ 上で $\delta$-ネットを十分にカバー（$\inf_k \mathbb P(\phi_k(c)>\epsilon_0)>\pi_0$）。
  2) 変換独立: $\{T_k\}$ は独立（適当な励起集合上で線形独立）。
  3) RSC/RE: デザイン行列は Restricted Strong Convexity/Eigenvalue を満たし、定数 $(\alpha_{\rm RSC},\gamma_{\rm RE})$ を持つ。
  4) 入力励起: $\Delta$ は持続的励起（PE）を満たす。
- 結論: 置換・スカラー同値を除き識別可能。MSE $\varepsilon$ を達成するための標本数 $N=\Omega\!\big(K d\,\log(1/\varepsilon)/\alpha_{\rm RSC}\big)$。

### Lemma 5（TDNG 収束; 新設）
- EMA 型: $n_{t+1}=(1-\alpha)n_t+\alpha\,\Phi_t$（$0<\alpha<1$、$\Phi_t$ 有界で $\mathbb E\,\Phi_t\to\bar\Phi$）。すると $\mathbb E\,n_t\to\bar\Phi$、かつ $\|n_t-\bar\Phi\|_2$ は指数減衰＋ノイズ項で上界。
- 一般核: $n_{t+1}=\int K(t,\tau\mid c)\,\Phi(\tau)\,d\tau$ が一様エルゴード（収縮率 $\rho<1$）なら一意の不変点へ収束。
- 階層結合: ベクトル $\mathbf n$ の更新が $\mathbf n_{t+1}=A\,\mathbf n_t+B\,\Phi_t$（$A$ は結合行列、$\rho(A)<1$）なら指数安定。Gershgorin 円板で $\rho(A)<1$ を十分条件として評価可。

### Thm 6（CIE 検出; 前提明記）
- BH-FDR の成立条件: p 値列が独立または PRDS のとき $\mathrm{FDR}\le q$。時系列依存では以下で対処：
  - 間引き（thinning）: 窓幅 $w$ に対してグリッド間隔 $g\ge w$ を取り、重複を避けて近似独立化。
  - ブロック BH: ブロックごとに代表 p 値を形成し BH を適用。
  - 代替手続き: LORD/LOND/SABHA など依存下で FDR を制御する逐次法を採用。
- 遅延界: 変化強度 $\delta$、サブガウス仮定の下で、$\mathbb E[\tau-t^*]\le O((\log(1/q))/\delta^2)$（係数は窓とブロック設計に依存）。

### Thm 7（計算スケーリング; 既出）
- 1 ステップ計算量 $O(K\,cost(T_k)+M B + p)$、メモリ $O(K d_x + M B + p)$。

## 6–10（略）
v0.2 と同様（本版の追補点を踏まえて読み替え）。

---

## 付録 A: 記号表／仮定表（追補）
- 確率: $(\Omega,\mathcal F,\{\mathcal F_t\},\mathbb P)$、PRDS、サブガウス。
- ハイブリッド: $(\mathcal C,\mathcal D,F,G)$、dwell-time $\tau_d$。
- 識別: RSC/RE 定数、PE 条件、$\delta$-ネット・非縮退。
- TDNG: 収縮率 $\rho<1$、スペクトル半径 $\rho(A)<1$。
- CIE: 間引き間隔 $g$、ブロック長、手続き（BH/LORD/LOND/SABHA）。

## 付録 B: 証明スケッチ要約（追補）
- 井戸型: Carathéodory + 反ゼノで解の延長、GST の枠組みで flow/jump を統一処理。
- ISS: Lyapunov にハイブリッド用の跳躍項を追加し、右側微分で評価。
- 識別: RSC/RE により経験リスクの強凸性を確保し、誤差分解と汎化境界（Rademacher 複雑度）でサンプル数を導出。
- TDNG: 収縮写像定理／マルコフ核の一様エルゴード性から収束。
- CIE: ブロック独立近似の下で BH の FDR 制御を踏襲、遅延は NLLR/KL の大偏差評価で界。

---

参考: v0.2（`IDS_Theory_General_v0_2.md`）、仕様（`SPEC_IDS_LITE_v0_1.md`）、実装 `idslite/`、合成パイプライン `examples/synthetic_pipeline.py`。

