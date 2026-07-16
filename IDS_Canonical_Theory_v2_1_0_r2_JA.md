# IDS理論 正典 v2.1.0-r2

**公開リビジョン:** public-r6.2

## 情報駆動ストレス・デバッグ・自己組織化理論

**Canonical Reconstruction of IDS: Information-Driven Stress / Debug / Self-organization**

**作成日:** 2026-07-09（v1.0）

**改訂日:** 2026-07-10（v1.1 — 表示修正・監査注記追加）

**改訂日:** 2026-07-10（v1.2 — §18 ゲージ情報幾何への再配置、仮説 H7・OP-13/14・命題 J 追加）

**改訂日:** 2026-07-10（v1.3 — H7 接続精密化・G2 Chentsov 表現修正・原理 J 改称・G6 次数注意・§18.10 攻略順序追加）

**改訂日:** 2026-07-12（v1.4 — 追補『自己粗視化・幾何学的ストレス』を §19 として統合、台帳併合、欠陥三型の対応確定、OP-H2＝OP-13 統合）

**改訂日:** 2026-07-12（v1.5 — 非可換粗視化バンドル（intrinsic-volume／local-exponent の二段の壁）を独立監査の上 §20 として統合、OP-MG0 新設）

**改訂日:** 2026-07-12（v1.6 — 『残差放射・担体化・再符号化原理』を §21 として統合、欠陥族を五型（naturality defect）へ統一、OP-RE1–8・命題 T/U 追加）

**改訂日:** 2026-07-12（v1.6.1 — 外部講評反映：\(J_R/J_\Psi/B\) の型分離、線形化橋 \(B=D\mathcal E|_{[r_*]}\) 明記、functoriality／coherence 欠陥族へ精密化、参照修正（§8.4・定理16／定理22）、Type III 定義、予測の非退化条件化、波動型保存担体へ改称、拡張二次収支汎関数、\(\operatorname{spr}(T)\)、原理 T/U 改称、正典文の四層化・英文要旨更新）

**改訂日:** 2026-07-12（v1.6.2 — 確定版：\(G\)-skew 化（\(G_RJ_R+J_R^{*}G_R=0\)・重みつき随伴 \(V^{\dagger}=G_R^{-1}V^{*}G_\Psi\)）、結合記号 \(B\to V\)（§18 基底空間との衝突解消）、Type III の型安全化（標準代表元形）、\(\widetilde{\mathcal E}/\mathcal E\) の条件付き降下規約、定理 16 との符号規約、H3 更新）

**改訂日:** 2026-07-12（v1.6.3 — §18.10 Step 1 を chain–dynamic defect 整合恒等式（定理24）として閉包、最小2-複体で chain anomaly と真の Type III を分離実証、§18.11 に正規化局所複素構造 \(\mathbb I=J(-J^2)^{-1/2}\)・輸送欠陥 \(\Xi_A=D_A\mathbb I\)・ホロノミー欠陥 \(\Xi_\gamma\) を統合、H8・OP-CX1/2・命題V・原理W追加）

**改訂日:** 2026-07-12（v1.7.0 — Type III 昇格定理・圧縮型 promotion/decoder を正典化、IDS ホログラフィーを global intertwining＋subregion nonclosure＋recoverability へ訂正、有限非可換層の到達状態を整理、MG0 条件付きパッケージと SU(2) 再構成ノートの停止線を監査統合、制御商空間 \(Q_{\rm ctrl}\)・projected mixing・安全予算定理を追加、OP-SC1／OP-GS1／OP-RE7 の部分閉包を凍結）

**改訂日:** 2026-07-12（v1.7.1 — 制御商を物理ゲージ軌道商上の task-relative quotient として型安全化、制御関連射影のゲージ共変性、task–coarse promotion／erasure defect、誘導 task–gauge connection と曲率公式、安全予算のゲージ不変性を有限正則層で定理化。rank-change・非不変 task・動的 task・大域非線形降下は OP-TG1–4 として隔離）

**改訂日:** 2026-07-13（v1.8.0 — 静的残差商と動的自己再入を split residual bridge で接続し、bridge-hidden sector 上の完全 Feshbach 還元とゲージ・スケール自然性を有限線形層で定理化し、自己再生スペクトル関数を定義。外部 template なしの因果閉包・joint turnover・向き付き一様横断 gap を模型の構成／検証条件へ、スペクトルストレス適応則を未導出の追加原理へ分離。OP-RE2 の有限可換線形層を閉包）

**改訂日:** 2026-07-14（v2.0.0 — 情報エンタルピー・scale-unitary gap transfer・bounded decoder・Failure-Mode Completeness・non-Abelian tariff chain・finite-star exact action atlasを統合。uniformity一般を再発明せず、actual 4D の停止点を Physical Non-Abelian Tariff Descent へ更新し、RGを補助経路、direct multiscale tariffを主経路として正典化）

**改訂日:** 2026-07-14（v2.0.0-r1 — A12への無関係なresolvent条件混入を除去。finite-star mixed-action正符号を【F／AUDIT】へ格下げしpoint-\(\beta\)射程を明記。PNATD form差を共通form domain上の二側相対不等式＋kernel compatibilityへ修正。Feshbach／tail／chartは「制御定理利用可能」と「actual係数認証済み」を分離。検証表示を構造・完全性監査へ限定し、34/34 provenanceをbundle同梱）

**改訂日:** 2026-07-16（v2.1.0 — 情報熱接続層（IT層）を §29 として統合。垂直非退化な一般 Ehresmann 層、アフィン接続 \(\Xi=dv+Av+\beta\)、定理34の線形特殊化、行列積分因子の局所存在、エントロピー較正、平坦アフィンホロノミーの捩れコホモロジー・中心化群モジュライ分類を追加。Wankel型を Type I 系の thermal holonomy memory へ再分類し、thermal Type III は promotion／decoder を伴う昇格構造として未解決に隔離）

**改訂日:** 2026-07-16（v2.1.0-rc2 — 第三次外部講評反映により凍結を撤回し rc へ復帰。(1) 定理 IT-4(5) の「\(t\) 自身が厳密な不変量」を原点変更限定へ弱め、完全ゲージ下の不変量を \(GL(r)\) 軌道（rank 1 では単位を除いた非零性）へ訂正。(2) 「\(F_A=0,D_AP\neq0\) が thermal holonomy memory の rank \(r\) 実例族」という誤主張を撤回——一般に \(F_{\rm ctrl}=P(D_AP)\wedge(D_AP)P\neq0\) で曲率由来——し、1次元基底上の Möbius–Berry 証人（例 IT-E1、\(\operatorname{Hol}=-1\)・平坦・非自明束）で置換。(3) 系 IT-3A.1 を「較正零予算からの生成」へ改称し原点相対性を条件化。(4) rank \(r>1\) のエントロピー生成候補式を正錐 \(K_S\)／スカラー化 \(\langle\lambda,\cdot\rangle\) で型修正。(5) §29 内の追補語・§29.13 の矛盾文・§1.1 C3 行を編集統合）

**改訂日:** 2026-07-16（v2.1.0-r2 — rc2 最終監査を完了し public-r6.2 として正式凍結。例 IT-E1 を普遍被覆上の局所フレームで記述し、Möbius 直線束をトートロジカル実直線束の引き戻しとして型安全化。定理 IT-4(5) の rank 1 完全ゲージ不変量を、一般には \(H^1\) の実射影類（向き保存ゲージでは正の ray 類）とし、\(b_1(U)=1\) の場合のみ零／非零へ縮約する形に修正。不可逆生成候補を許容過程接錐 \(\mathcal C_{\rm proc}\) 上で評価する形式へ改め、\(\mathcal C_{\rm proc},K_S,\lambda\) の正準構成を OP-IT2 へ隔離。版番号を再利用せず、r1／rc2 を履歴版へ退役し detached checksum を発行）

**位置づけ:** v2.1.0-r2 情報熱接続統合版である現行研究正典。v2.0.0-r1 の定量的物理閉包を不変に継承し、情報エンタルピー収支と hidden exchange の接続幾何を §29 で接合する。IT 層は、一般 Ehresmann／アフィン／線形の三層を区別し、平坦性から局所断熱不変量を、較正条件から情報エントロピーを、大域ホロノミーから熱記憶を分類する横断統合層である。4D Yang–Mills の停止点は Physical Non-Abelian Tariff Descent のまま変更せず、質量ギャップ解決を宣言しない。

v2.1.0-r2 は、rc2 の第三次外部講評と最終型監査を反映した正式凍結版である。現行正本を public-r6.2 とし、v2.1.0-r1 と v2.1.0-rc2 は来歴追跡用の superseded historical release として保持する。

---

# 0. 正典化の目的と基本姿勢

本書は、これまで断片的・分岐的に展開されてきた IDS 理論を、**一つの正典的な数理体系**として再構成するための文書である。

IDS は、単に「情報」「ストレス」「デバッグ」という言葉を並べたものではない。現在の最も強い核は、次の一文に凝縮される。

> **IDS理論とは、有限資源をもつ開放階層系において、観測可能なスカラー・ストレスが散逸し、潜在構造が正錐上で蓄積し、粗視化で消えない非可積分 Hodge 残差類が構造として保存・輸送・生成される過程を扱う理論である。**

さらに、ストレス・デバッグ理論としては、次の形が中心である。

\[
\boxed{
\text{Stress}
=
\text{現在の記述体系で勾配化できない残差圧}
}
\]

\[
\boxed{
\text{Debug}
=
\text{残差類を散逸・保存・再注入・粗視化変換によって再組織化する操作}
}
\]

\[
\boxed{
\text{Resilience}
=
\text{粗視化・摂動・観測変更を越えて残差構造が安定に持続する能力}
}
\]

そして、現在の正典的中核は、黄金比 \(\varphi\) ではなく、

\[
\boxed{
[\omega]\in C^1/\operatorname{im}d_0
}
\]

である。黄金比は重要だが、IDS の定義ではない。黄金比は、最小二項 swap–aggregation 処理器の Perron 署名、または self-dual additive balance の最小可解例として現れる特殊な処理モードである。

---

# 1. 正典化計画

## 1.1 分層原則

IDS 理論は、すべてを同じ確度で扱うと破綻する。したがって、本書では全主張を以下の階層に分ける。

| 階層 | 名称 | 内容 | 扱い |
| --- | --- | --- | --- |
| C0 | 数理コア | 有限資源、正錐、自然勾配、Hodge 残差、許容粗視化 | 定義と定理 |
| C1 | 残差力学 | \(\dot\rho=-L\rho+a\)、Type I/II、観測者共固定点 | 条件付き定理 |
| C2 | 因果・レジリエンス | \((K,\eta)\sim(L,J)\)、spectral gap、hypocoercivity | 定理＋仮説 |
| C3 | 物理ブリッジ | Causal-Hodge Bridge, Green–Kubo, DHT/HFE, 情報熱接続（IT層・§29） | 追加公理つきモデル。IT 有限滑層は定理＋三巡外部講評＋r2 凍結監査 |
| C4 | 非可換・制御商拡張 | 有限ゲージ軌道、flat 変形複体、Type III promotion、制御関連商、task–gauge 誘導接続 | 有限正則層は定理＋外部監査、特異・連続・量子層は未解決 |
| C5 | 哲学・時間論 | creative oblivion, future/past boundary, dialogical reality | 解釈・仮説 |

この分層により、未証明の物理的・哲学的拡張が、証明済みコアを汚染しない。

## 1.2 正典化の方針

1. **φを公理に入れない。**
   
      \(\varphi\) は結果として現れる。定義に埋め込まない。
2. **スカラー・ストレスと構造的ストレス残差を分離する。**
   
      スカラー汎関数 \(\mathcal S\) は散逸を支配する。粗視化で保存されるのは \([\omega]\in C^1/\operatorname{im}d_0\) である。
3. **可換層と非可換層を混ぜない。**
   
      abelian Hodge 残差商は証明済み核である。有限 flat 非可換層ではゲージ変形複体・Kuranishi 商・twisted Type III まで到達したが、非平坦連続・量子層では線形商を使わずゲージ軌道・BRST／observable algebraへ移る。
4. **粗視化を情報喪失ではなく、構造選別として扱う。**
   
      許容粗視化は勾配成分を消し、残差類だけを輸送する。消去的粗視化はアノマリーを生成する。
5. **デバッグを誤差消去ではなく、残差再組織化として定義する。**
   
      デバッグは \(\rho\) をゼロにすることではない。場合によっては非ゼロ構造 \(\rho^\ast\) を安定化する。

---

# 2. 最短正典要約

IDS の現在の正典を一枚に圧縮すると、次である。

## 2.1 状態

系は、少なくとも次のデータを持つ。

\[
\mathfrak I
=
\bigl(
X,
C^\bullet(X),
g,
K,
M,
\mathcal S,
\Phi,
\mu,
L,
J,
a
\bigr).
\]

ここで、

- \(X\)：観測複体、セル複体または単体複体。
- \(C^\bullet(X)\)：コチェイン複体。
- \(g\)：Hodge 計量または観測者誘導計量。
- \(K\)：潜在正錐。
- \(M\)：観測多様体、例：単体 \(\Delta^{n-1}\)、SPD 錐。
- \(\mathcal S:M\to\mathbb R_{\ge0}\)：スカラー・ストレス汎関数。
- \(\Phi\)：粗視化写像。
- \(\mu\)：観測者集合または観測者分布。
- \(L=\delta_1d_1\)：曲率 Laplacian。
- \(J\)：保存生成子、向き場。
- \(a\)：消去的粗視化アノマリー。

**v1.8.0 自己再生拡張.** 自己再生 return を主張する模型では、上の最小データに

\[
(\iota,\varpi,P_{\rm res},P_{\rm ctrl},G,
\mathfrak e,\mathcal U^{\rm ret},\tau^{\rm ret},\mathscr R^{\rm ret})
\]

を加える。これは全 IDS 模型に必須の C0 データではなく、A14・§21.18 の自己再生模型クラスに必要な比較・return データである。

## 2.2 残差

観測された 1-cochain / edge flow \(\omega\in C^1(X)\) に対し、

\[
C^1(X)
=
\operatorname{im}d_0
\oplus
\ker\Delta_1
\oplus
\operatorname{im}\delta_1
\]

と Hodge 分解する。

\[
\omega=d_0\phi+h+\delta_1\psi.
\]

IDS の構造的ストレス残差は、

\[
\mathfrak r(\omega)
=(I-P_{\rm grad})\omega
=h+\delta_1\psi.
\]

そして本体は代表元ではなく商類

\[
\boxed{
[\omega]
\in
R^1(X):=C^1(X)/\operatorname{im}d_0
}
\]

である。

## 2.3 デバッグ方程式

最小可換残差力学は、

\[
\boxed{
\dot\rho=-L\rho+a,
\qquad
L=\delta_1d_1.
}
\]

因果の向き場を含めると、

\[
\boxed{
\dot\rho=-L\rho+J\rho+a.
}
\]

ここで、

\[
K \leftrightarrow L,
\qquad
\eta \leftrightarrow J.
\]

無向因果骨格 \(K\) は散逸作用素 \(L\) として実現され、向き場 \(\eta\) は保存生成子 \(J\) として実現される。

## 2.4 構造

構造とは、安定な非ゼロ共固定点である。

\[
\boxed{
0=-L_{\mu^\ast}\rho^\ast+J_{\mu^\ast}\rho^\ast+a_{\mu^\ast},
\qquad
0=B(\mu^\ast,\rho^\ast),
\qquad
\rho^\ast\ne0.
}
\]

最小 \(J=0\) の場合、

\[
\rho^\ast=h+L^+a.
\]

- \(h\in H^1(X)\)：Type I、位相的構造。
- \(L^+a\)：Type II、アノマリー維持構造。

- **Type III**：固定スケールの第三成分ではなく、fine の減衰／余完全セクターが coarse の調和セクターへ昇格した系譜的型。制約忘却型では
  \[
  \mathcal T_{\mathrm{III}}
  =\bar H^1\ominus H^1
  =\operatorname{im}\delta_1\cap\ker\bar d_1.
  \]

## 2.5 制御関連商

微視仮説 \(\theta\in\Theta\) を完全復元する代わりに、許容介入 \(u\in\mathcal U\) の下で未来の応答と安全余裕を変えないものを同一視する。

\[
\theta\sim_{\rm ctrl}\theta'
\iff
\mathcal O_\theta^u=\mathcal O_{\theta'}^u\ \forall u\in\mathcal U,
\qquad
g(\theta)=g(\theta').
\]

\[
\boxed{Q_{\rm ctrl}:=\Theta/\!\sim_{\rm ctrl}}
\]

これは完全な微視的 witness ではなく、予測・制御に必要な最小行動同値類を復元するための対象である。物理ゲージ群 \(\mathcal G\) が作用し、行動写像がゲージ不変なら、正しい順序は

\[
\Theta\longrightarrow[\Theta/\mathcal G]\longrightarrow Q_{\rm ctrl}^{\rm phys}
\]

である。制御商は gauge fixing（軌道代表元の選択）ではなく、物理軌道商上の task-relative quotient である。正則な Hilbert 層では制御-null方向を除いた射影 \(P_{\rm ctrl}\) を用い、識別可能性 \(\beta_n\)、射影相関和 \(S_n^{\rm ctrl}\)、累積誤差 \(\mathfrak E_n\) により安全な粗視化停止条件を定める（定理27–34、§18.12・§19.17）。

## 2.6 レジリエンス

IDS 的レジリエンスは、

\[
\boxed{
\text{Resilience}
=
\text{stable persistence of }[\rho]
\text{ under perturbation, observation, and coarse-graining.}
}
\]

定量的には、

\[
\Delta_{\rm res}
=
\lambda^+_{\min}(L)
\]

が回復速度を支配する。\(\Delta_{\rm res}>0\) は、IDS 版 mass gap / resilience gap である。

---


## 2.7 情報熱接続

IT 構造を持つ模型では、操作可能変数を基底、hidden 情報エンタルピー座標をファイバーとする束上に、垂直非退化な情報熱交換形式

\[
\Xi_I=d\mathcal H_I+W_I
\]

を置き、その核

\[
\mathscr H_I=\ker\Xi_I
\]

を情報断熱接続とする。平坦性 \(\Omega_I=0\) は局所情報断熱不変量と行列積分因子の存在に同値であり、情報エントロピーと呼ぶには最大エントロピー reference・凹性・data-processing 等の較正条件 IT-C を追加する。

構造化されたアフィン層では

\[
\Xi_I=dv+A_Iv+\beta_I,
\qquad
\widetilde F=
\begin{pmatrix}
F_A&D_A\beta_I\\
0&0
\end{pmatrix}.
\]

\(\widetilde F\) 全体が幾何学的本体であり、線形 task--gauge 曲率と加法的仕事曲率は選択したアフィン原点に相対的な二ブロックである。平坦で非自明な大域熱記憶は、線形ホロノミー表現で捩られた \(H^1\) と中心化群作用により分類される（定理 IT-4、§29）。

# 3. 公理系

以下の公理は「物理的に世界が必ずこうである」という主張ではなく、IDS 型システムを定義するための数理構造である。

## A0. 観測複体公理

系の観測は、有限の向きづけられたセル複体または単体複体 \(X\) 上に表現できる。

\[
C^0(X)\xrightarrow{d_0}C^1(X)\xrightarrow{d_1}C^2(X),
\qquad
d_1d_0=0.
\]

ここで \(C^1\) は辺上のフロー、差分、ストレス流、応答場を表す。

## A1. 有限観測資源公理

観測可能な資源配分は、単体に属する。

\[
x\in\Delta^{n-1},
\qquad
x_i>0,
\qquad
\sum_i x_i=1.
\]

これは、観測可能な資源・注意・重み・確率が有限であることを表す。

## A2. 潜在正構造公理

潜在構造重みは正錐に属する。

\[
u\in\mathbb R^n_{>0}.
\]

観測配分は正規化射影で与えられる。

\[
x=\Pi(u)=\frac{u}{\sum_i u_i}.
\]

潜在重みは蓄積してよい。観測配分は有限でなければならない。

## A3. スカラー・ストレス汎関数公理

観測多様体 \(M\) 上に、非負のストレス汎関数がある。

\[
\mathcal S:M\to\mathbb R_{\ge0}.
\]

最小限の条件は、下半連続性と下限達成である。微分可能な場合は自然勾配が定義される。

重要：\(\mathcal S\) の定義に \(\varphi\) を入れてはならない。

## A4. 座標不変散逸公理

イベントの間、観測状態は自然勾配流に従ってストレスを下げる。

\[
\dot x=-\operatorname{grad}_g\mathcal S(x).
\]

ここで \(g=\nabla^2\psi\) は mirror potential \(\psi\) から来る計量でよい。

## A5. 局所 swap–aggregation 公理

離散イベントでは、潜在重みが cone-positive な写像で更新される。

\[
u^+=Mu,
\qquad
M(K)\subset K.
\]

最小二項の場合は、

\[
F=
\begin{pmatrix}
0&1\\
1&1
\end{pmatrix}
=SG,
\]

\[
S=
\begin{pmatrix}0&1\\1&0\end{pmatrix},
\qquad
G=
\begin{pmatrix}1&1\\0&1\end{pmatrix}.
\]

\(S\) は可逆な swap、\(G\) は不可逆な aggregation である。

## A6. 構造的残差公理

観測フロー \(\omega\in C^1(X)\) の本質的な構造は、勾配成分で割った残差類である。

\[
[\omega]\in C^1(X)/\operatorname{im}d_0.
\]

代表元として、

\[
\mathfrak r(\omega)=(I-P_{\rm grad})\omega
\]

を用いる。

## A7. 許容粗視化公理

粗視化写像 \(\Phi:C^1(X_{\rm fine})\to C^1(X_{\rm coarse})\) が許容であるとは、勾配を勾配へ送ることである。

\[
\Phi(\operatorname{im}d_0^{\rm fine})
\subseteq
\operatorname{im}d_0^{\rm coarse}.
\]

このとき、\(\Phi\) は残差商へ降下する。

## A8. 消去的粗視化アノマリー公理

隠れ自由度を消去する粗視化は、一般に A7 を満たさない。その欠陥がアノマリーである。

\[
\mathfrak A_\Phi
=q\circ\Phi\circ d_0
:
C^0_{\rm fine}\to C^1_{\rm coarse}/\operatorname{im}d_0^{\rm coarse}.
\]

\(\mathfrak A_\Phi\ne0\) のとき、微視的には勾配だったものが粗視化後に非勾配残差として現れる。

## A9. 残差デバッグ公理

残差類 \(\rho\in R^1=C^1/\operatorname{im}d_0\) は、最小的には

\[
\dot\rho=-\delta_1d_1\rho+a
\]

で進化する。ここで \(a\) は消去的粗視化アノマリー由来の有効強制である。

## A10. 観測者共変公理

観測者は受動的な読み取り装置ではなく、粗視化核 \(K_o\) と計量 \(g_o\) を通じて残差の分解に関与する。観測者集合は測度 \(\mu\) で表す。

\[
\mu\in\mathcal P(\mathcal O),
\qquad
\bar K_\mu=\int K_o\,d\mu(o).
\]

観測者分布は Hodge 計量を誘導し、残差力学と相互作用する。

## A11. 因果分解公理

因果構造は、無向影響骨格 \(K\) と向き場 \(\eta\) に分解される。

\[
\mathcal C=(K,\eta).
\]

IDS 可換層では、

\[
K\leftrightarrow L=\delta_1d_1,
\qquad
\eta\leftrightarrow J.
\]

## A12. 保存生成子許容公理

保存生成子 \(J\) は、少なくともゲージ勾配部分空間を保ち、残差商へ降下しなければならない。

\[
J(\operatorname{im}d_0)
\subseteq
\operatorname{im}d_0.
\]

商上の誘導生成子を \(\bar J\)、coexact sectorを \(C\)、曲率Laplacianの制限を
\(L_C=L|_C\) とする。弱許容条件は、作用二次形式を保存する

\[
L_C\bar J_C+\bar J_C^{T}L_C=0
\]

である。保存生成子の許容性は再入・return層の条件とは独立に定義する。

調和部を破壊しない強許容条件として、拡張計量

\[
G=L|_{C}\oplus g|_H
\]

に関して

\[
G\bar J+\bar J^TG=0
\]

を課す。

## A13. 正典的誠実性公理

すべての主張は次のいずれかに分類されなければならない。

- **定理**：公理と既知数学から証明済み。
- **定義**：理論の構成上の選択。
- **条件付き定理**：追加仮定のもとで証明済み。
- **仮説**：未証明だが検証可能。
- **解釈**：哲学的・概念的な読み。
- **未解決問題**：証明・検証が残る。

## A14. 自己再生構成公理（モデル選択的）

ある模型を **自己再生的** と呼ぶとき、外部 task／template 入力をゼロにした自律更新 \(\Phi_0\) と、操作的に先に指定された残差同一性・系境界・許容介入を持たなければならない。状態だけでなく、残差の実現・読出し、関連性射影、計量、内在的 return event、終点を始点へ戻す state comparison identification、線形化 return operator が、宣言された内部状態と資源から次周期へ生成されることを要求する。

この公理は、すべての系が自己再生するという存在主張ではない。自己再生を主張する模型族を選ぶための構成条件である。また、物質・エネルギー流をゼロにするという意味ではない。許容する環境・内部自由エネルギー・資源流は系境界の内側または明示された境界条件へ含め、外部から完成した task／template／作用素を毎周期書き戻す free oracle だけを禁ずる。

作用素スペクトルは再入機構と安定性を診断するが、内生的生成を単独では証明しない。従って A14 は、§21.18 の residual bridge 定理群とは論理的に独立な因果構成公理として置く。

また turnover は部品ごとの単独交換だけで済ませず、旧 token と相互 backup を含む再生成対象全体の joint cut を許容介入族に含める。不可逆な尺度写像は同値そのものではなく共通比較 fiber への transport とし、同値類はその fiber 上の可逆同型群で定める。

---


## A15. 情報熱束公理（モデル選択的）

IDS 模型は、操作可能変数の基底 \(B_I\)、hidden 情報エンタルピー・ファイバーを持つ滑らかな束 \(\pi_I:\mathcal E_I\to B_I\)、および垂直制限が同型となる束値 1 形式 \(\Xi_I\) を備えるとき IT 構造を持つという。

\[
\Xi_I|_{V_p}:V_p\xrightarrow{\cong}\mathcal V_{\pi(p)},
\qquad
\mathscr H_I:=\ker\Xi_I.
\]

これは全 IDS 模型への普遍存在主張ではない。大域座標を持つ A15 と、局所アフィンアトラス／solder 型形式による A15′ を区別する。有限次元・滑らかな正則層の詳細、ゲージ規約、定理は §29 に置く。

# 4. 基本定義

## 4.1 スカラー・ストレスと構造的ストレス

IDS には二種類のストレスがある。

### スカラー・ストレス

\[
\mathcal S(x)
\]

観測多様体上のポテンシャル。自然勾配流を通じて散逸する。

### 構造的ストレス残差

\[
[\omega]\in C^1/\operatorname{im}d_0.
\]

粗視化を越えて比較される本体。勾配化できないため、局所ポテンシャルで消せない。

したがって、

\[
\boxed{
\mathcal S
\text{ は散逸を支配し、}
[\omega]
\text{ は構造を支配する。}
}
\]

## 4.2 バグ

IDS におけるバグとは、ある階層・ある観測計量・ある粗視化のもとで、勾配化できず残差商に現れる不整合である。

\[
\mathrm{Bug}_{X,g}(\omega)
:=
[\omega]_{X}
\in
C^1(X)/\operatorname{im}d_0.
\]

バグは絶対的欠陥ではない。別の粗視化では消える場合もあれば、逆に増幅される場合もある。

## 4.3 デバッグ

デバッグとは、残差類の変換である。

\[
\mathsf{Debug}:
(R^1,L,J,a,\mu)\to(R^1,L',J',a',\mu').
\]

最小的には、

\[
\dot\rho=-L\rho+J\rho+a.
\]

デバッグは、\(\rho\to0\) だけではない。安定な非ゼロ構造 \(\rho^\ast\ne0\) への移行もデバッグである。

## 4.4 構造

構造とは、時間・粗視化・観測者更新のもとで安定な非ゼロ共固定点である。

\[
\rho^\ast\ne0,
\qquad
0=-L_{\mu^\ast}\rho^\ast+J_{\mu^\ast}\rho^\ast+a_{\mu^\ast},
\qquad
0=B(\mu^\ast,\rho^\ast).
\]

## 4.5 Type I / Type II / Type III

固定スケールの平衡分解は

\[
\rho^\ast=h+L^+a
\]

である。

- **Type I**：\(h\in H^1(X)\)。現在のスケールで位相的に保護される状態型。
- **Type II**：\(L^+a\in\operatorname{Range}L\)。現在のスケールで強制・流束により維持される状態型。

**Type III は固定スケールの第三の Hodge 成分ではない。** fine で Type II／余完全だったモードが、粗視化後に Type I／調和となったという生成履歴を表す **系譜的型**である。

### 4.5.1 制約忘却型 Type III【定理25】

同一の \(C^0,C^1,d_0\) と内積を保ち、2-cell 制約だけを

\[
d_1\longmapsto\bar d_1=P d_1
\]

と忘却する。fine / coarse 調和空間を

\[
H^1=\ker d_1\cap(\operatorname{im}d_0)^\perp,
\qquad
\bar H^1=\ker\bar d_1\cap(\operatorname{im}d_0)^\perp
\]

とすると、\(H^1\subseteq\bar H^1\) であり、

\[
\boxed{
\mathcal T_{\mathrm{III}}^{\mathrm{forget}}
:=\bar H^1\ominus H^1
=\operatorname{im}\delta_1\cap\ker\bar d_1
}
\]

である。これは集合差 \(\bar H^1\setminus H^1\) ではなく直交補部分空間である。

粗い理論ではこのセクターは真に harmonic である。ただし、その起源が fine の減衰セクターにあるため Type III と呼ぶ。従って正典語は「見かけの位相化」ではなく、

\[
\boxed{\text{local fine curvature / constraint response}\ \longrightarrow\ \text{coarse global harmonic memory}}
\]

である。

### 4.5.2 一般消去診断

一般の消去的写像 \(\Phi\) では商への降下がない場合があるため、標準代表元

\[
\widehat\rho_f=(I-P_{{\rm grad},f})\rho_f
\]

に対して

\[
P_{H,f}\widehat\rho_f=0,
\qquad
P_{H,c}(I-P_{{\rm grad},c})\Phi(\widehat\rho_f)\ne0
\]

を Type III 候補の診断条件とする。ただし、部分空間同定・射影極限まで証明済みなのは上の制約忘却型、および定理26の有限圧縮型である。

### 4.5.3 圧縮型 Type III【定理26】

非単射粗視化 \(K:\mathcal H\to\bar{\mathcal H}\) に対し、fine 減衰セクターから coarse 零モードへ入る promotion map を

\[
\Gamma_K=\bar P K(I-P),
\qquad
P=P_{\ker L},\quad\bar P=P_{\ker\bar L}
\]

と定める。標準 recoverable source / target は

\[
\mathcal S_K=\operatorname{Ran}\Gamma_K^*,
\qquad
\mathcal T_K=\operatorname{Ran}\Gamma_K
\]

であり、decoder は \(D_K=\Gamma_K^+\) である。回復安定性は \(1/\sigma_{\min}^+(\Gamma_K)\) により決まる。

## 4.6 レジリエンス

系がレジリエントであるとは、残差構造が摂動後に、同じ粗視化同値類または同じ構造型へ戻ることである。

局所線形化で、

\[
\dot y=-Ly
\]

ならば、

\[
\|y(t)\|\le e^{-\lambda^+_{\min}(L)t}\|y(0)\|.
\]

よって

\[
\Delta_{\rm res}=\lambda^+_{\min}(L)
\]

を resilience gap と呼ぶ。

## 4.7 IDS ホログラフィー

IDS ホログラフィーは、内部構造が境界表現へ符号化されるという原理である。ただし正典条件は単なる写像

\[
[\omega_{\rm bulk}]\mapsto[\omega_\partial]
\]

ではなく、

\[
\boxed{
\text{global intertwining}
+
\text{subregion nonclosure}
+
\text{recoverability}
}
\]

である（§10）。欠陥だけでは情報損失とホログラフィーを区別できない。

## 4.8 未来と過去の相互作用

IDS では、過去は履歴として \(h\in H^1\) や \(a(t)\) に刻まれる。未来は、予測・目的・終端条件・観測者の期待として、現在のデバッグ経路を選別する。

数理的には、これは retrocausal signal ではなく、**二境界値問題**または **forward-backward smoothing** として扱う。

\[
\rho^\ast
=
\arg\min_{\rho}
\left\{
\int_{t_0}^{t_1}
\frac12\|\dot\rho+L\rho-a\|^2dt
+
\Phi_{\rm past}(\rho(t_0))
+
\Phi_{\rm future}(\rho(t_1))
\right\}.
\]

ここで未来は、物理的に過去へ信号を送るのではなく、境界条件として最適経路を制約する。

---

# 5. 定理と証明

本節では、正典の核となる定理を列挙し、できる限り自足的な証明を与える。

---

## 定理 1. 有限 Hodge–Helmholtz 分解

**主張。** 有限内積つきコチェイン複体

\[
C^0\xrightarrow{d_0}C^1\xrightarrow{d_1}C^2,
\qquad d_1d_0=0
\]

において、随伴 \(\delta_k=d_k^\ast\) と Hodge Laplacian

\[
\Delta_1=d_0\delta_0+\delta_1d_1
\]

を定めると、

\[
C^1=\operatorname{im}d_0\oplus\ker\Delta_1\oplus\operatorname{im}\delta_1.
\]

**証明。**

有限次元 Hilbert 空間では、任意の線形写像 \(A\) について

\[
(\operatorname{im}A)^\perp=\ker A^\ast
\]

が成り立つ。\(d_1d_0=0\) より、任意の \(f\in C^0\), \(\psi\in C^2\) について

\[
\langle d_0f,\delta_1\psi\rangle
=
\langle d_1d_0f,\psi\rangle=0.
\]

したがって \(\operatorname{im}d_0\perp\operatorname{im}\delta_1\)。また、

\[
\langle \Delta_1\alpha,\alpha\rangle
=
\|\delta_0\alpha\|^2+\|d_1\alpha\|^2.
\]

ゆえに

\[
\ker\Delta_1=\ker\delta_0\cap\ker d_1.
\]

有限次元線形代数により、\(C^1\) は exact, coexact, harmonic 成分の直交和に分解する。∎

---

## 定理 2. 残差商の標準代表元

**主張。** 残差商

\[
R^1=C^1/\operatorname{im}d_0
\]

の各類 \([\omega]\) は、\((\operatorname{im}d_0)^\perp\) に一意な最小ノルム代表元を持つ。その代表元は

\[
\mathfrak r(\omega)=(I-P_{\rm grad})\omega=h+\delta_1\psi
\]

である。

**証明。**

\(P_{\rm grad}\) を \(\operatorname{im}d_0\) への直交射影とする。任意の \(\omega\) は

\[
\omega=P_{\rm grad}\omega+(I-P_{\rm grad})\omega
\]

と分解する。第一項は \(\operatorname{im}d_0\) に属するため、商ではゼロである。第二項は同じ商類を表す。

同じ商類の任意の代表元は

\[
\mathfrak r(\omega)+d_0f
\]

であるが、\(\mathfrak r(\omega)\perp\operatorname{im}d_0\) だから

\[
\|\mathfrak r(\omega)+d_0f\|^2
=
\|\mathfrak r(\omega)\|^2+
\|d_0f\|^2.
\]

したがって最小ノルム代表元は一意に \(\mathfrak r(\omega)\) である。Hodge 分解により、これは \(h+\delta_1\psi\) に等しい。∎

### 系 2.1. 標準 residual section

商写像 \(\pi_R:C^1\to R^1\) に対し、

\[
s_R:R^1\to(\operatorname{im}d_0)^\perp,
\qquad
s_R([\omega])=(I-P_{\rm grad})\omega
\]

は well-defined な線形切断であり、

\[
\boxed{\pi_Rs_R=I_{R^1}.}
\]

従って任意の代表元上の写像 \(F:C^1\to V\) から \(F\circ s_R:R^1\to V\) という有限 Hodge 計量相対的な実現を構成できる。ただし、これは \(F(r+d_0f)=F(r)\) を意味しない。物理写像 \(F\) 自身の自然な商降下は定理35の必要十分条件 \(Fd_0=0\) で別に判定する。

---

## 定理 3. 純勾配変形は残差類を変えない

**主張。** \(\partial_t\omega_t=d_0f_t\) ならば、

\[
\frac{d}{dt}[\omega_t]=0.
\]

**証明。**

商空間 \(R^1=C^1/\operatorname{im}d_0\) では、任意の exact cochain はゼロである。

\[
\frac{d}{dt}[\omega_t]
=[\partial_t\omega_t]
=[d_0f_t]
=0.
\]

∎

**意味。** 局所ポテンシャルで説明できる変形は、構造的残差を生成しない。残差を変えるには、非勾配力学または消去的粗視化アノマリーが必要である。

---

## 定理 4. 許容粗視化は残差商へ降下する

**主張。** 線形粗視化写像

\[
\Phi:C^1(X_f)\to C^1(X_c)
\]

が

\[
\Phi(\operatorname{im}d_0^f)
\subseteq
\operatorname{im}d_0^c
\]

を満たすならば、商写像

\[
\bar\Phi:R^1_f\to R^1_c
\]

が一意に定義される。

**証明。**

\([\omega]=[\omega']\) とする。すると \(\omega'-\omega=d_0^ff\) である。仮定より

\[
\Phi(\omega')-\Phi(\omega)
=
\Phi(d_0^ff)
\in
\operatorname{im}d_0^c.
\]

したがって

\[
[\Phi(\omega')]=[\Phi(\omega)]
\]

であり、\(\bar\Phi([\omega])=[\Phi(\omega)]\) は代表元の取り方によらず well-defined である。∎

---

## 定理 5. 粗視化は可積分偏差を消す

**主張。** \(R_f=I-P_{{\rm grad},f}\), \(R_c=I-P_{{\rm grad},c}\) とする。\(\Phi\) が許容なら、任意の \(\omega\in C^1(X_f)\) について

\[
\boxed{
R_c\Phi\omega
=
R_c\Phi R_f\omega.
}
\]

**証明。**

\[
\omega=P_{{\rm grad},f}\omega+R_f\omega.
\]

線形性により、

\[
\Phi\omega
=
\Phi P_{{\rm grad},f}\omega+
\Phi R_f\omega.
\]

\(P_{{\rm grad},f}\omega\in\operatorname{im}d_0^f\) だから、許容性より

\[
\Phi P_{{\rm grad},f}\omega
\in
\operatorname{im}d_0^c.
\]

\(R_c\) は \(\operatorname{im}d_0^c\) を消すので、

\[
R_c\Phi P_{{\rm grad},f}\omega=0.
\]

従って

\[
R_c\Phi\omega
=R_c\Phi R_f\omega.
\]

∎

**意味。** マクロに残る非可積分構造は、ミクロの非可積分残差だけに依存する。これは IDS 粗視化原理の中核定理である。

---

## 定理 6. アノマリーゼロと許容性の同値性

**主張。** 商写像 \(q:C^1_c\to R^1_c\) に対し、

\[
\mathfrak A_\Phi=q\circ\Phi\circ d_0^f
\]

と定義する。このとき

\[
\mathfrak A_\Phi=0
\quad\Longleftrightarrow\quad
\Phi(\operatorname{im}d_0^f)
\subseteq
\operatorname{im}d_0^c.
\]

**証明。**

\(\mathfrak A_\Phi=0\) とは、任意の \(f\in C^0_f\) について

\[
q\Phi d_0^ff=0
\]

である。これは

\[
\Phi d_0^ff\in\ker q=\operatorname{im}d_0^c
\]

を意味する。よって許容性が成り立つ。逆向きは定義から直ちに従う。∎

---

## 定理 7. 自然勾配流の Lyapunov 散逸

**主張。** \(\dot x=-\operatorname{grad}_g\mathcal S(x)\) ならば、

\[
\frac{d\mathcal S}{dt}
=-\|\operatorname{grad}_g\mathcal S\|_g^2
\le0.
\]

**証明。**

連鎖律により、

\[
\frac{d\mathcal S}{dt}
=d\mathcal S(\dot x)
=\langle\operatorname{grad}_g\mathcal S,\dot x\rangle_g.
\]

\(\dot x=-\operatorname{grad}_g\mathcal S\) を代入して、

\[
\frac{d\mathcal S}{dt}
=-\langle\operatorname{grad}_g\mathcal S,
\operatorname{grad}_g\mathcal S\rangle_g
=-\|\operatorname{grad}_g\mathcal S\|_g^2.
\]

∎

**意味。** \(\mathcal S\) はイベント間で単調非増加である。ただし、これは残差類 \([\omega]\) が必ず消えることを意味しない。

---

## 定理 8. 二項 minimax は黄金比シェアを与える

**主張。**

\[
J(\rho)=\max\{1-\rho,\rho^2\},
\qquad
0<\rho<1
\]

の一意最小点は

\[
\rho^\ast=\frac1\varphi
=\frac{\sqrt5-1}{2}
\]

であり、最小値は \(1/\varphi^2\) である。

**証明。**

\(1-\rho\) は単調減少、\(\rho^2\) は単調増加である。最大値の最小化は交点で達成される。

\[
1-\rho=\rho^2
\quad\Longleftrightarrow\quad
\rho^2+\rho-1=0.
\]

正の解は

\[
\rho^\ast=\frac{-1+\sqrt5}{2}=\frac1\varphi.
\]

このとき

\[
J(\rho^\ast)=1-\frac1\varphi=\frac1{\varphi^2}.
\]

∎

**注意。** これは binary self-similar relay cost という特定構造の定理であり、任意のシステムが黄金比へ行くという主張ではない。

---

## 定理 9. swap–aggregation は Perron 比 \(\varphi\) を持つ

**主張。**

\[
F=\begin{pmatrix}0&1\\1&1\end{pmatrix},
\qquad
u_{t+1}=Fu_t,
\qquad
u_0\in\mathbb R^2_{>0}
\]

とする。このとき、

\[
\lim_{t\to\infty}\frac{u_{2,t}}{u_{1,t}}=\varphi,
\]

かつ

\[
\Pi(u_t)\to(\varphi^{-2},\varphi^{-1}).
\]

**証明。**

特性多項式は

\[
\lambda^2-\lambda-1=0.
\]

固有値は \(\varphi\) と \(-\varphi^{-1}\) である。\(F\) は primitive な非負行列であり、Perron–Frobenius 定理により、任意の正初期ベクトルは優固有ベクトル方向へ射影収束する。

優固有ベクトルは

\[
v=(1,\varphi)^T.
\]

従って比は \(\varphi\) に収束する。正規化すると、

\[
\Pi(v)=\frac{(1,\varphi)}{1+\varphi}
=\frac{(1,\varphi)}{\varphi^2}
=(\varphi^{-2},\varphi^{-1}).
\]

∎

---

## 定理 10. Birkhoff–Hopf 型 projective 安定性

**主張。** 正錐 \(K\) 上の cone-positive 写像列 \(A_t\) について、ある \(q\) に対しすべての \(q\)-block 積 \(B_t=A_{t+q-1}\cdots A_t\) が内点へ写し、Hilbert projective diameter が一様有界なら、射影軌道は初期値に依らない一意な極限モードへ収束する。

**証明スケッチ。**

Hilbert projective metric

\[
d_H(u,v)=
\log
\frac{\max_i(u_i/v_i)}{\min_i(u_i/v_i)}
\]

はスカラー倍に不変である。Birkhoff–Hopf 定理により、有限 projective diameter \(\Delta(B_t)\) を持つ正写像は

\[
d_H(B_tu,B_tv)
\le
\tanh\left(\frac{\Delta(B_t)}{4}\right)d_H(u,v)
\]

を満たす。一様有界性により収縮定数 \(\tau<1\) が取れる。反復すれば距離は指数的にゼロへ落ちる。よって射影極限は初期値に依らない。∎

---

## 定理 11. 曲率 Laplacian は商上 well-defined

**主張。**

\[
L=\delta_1d_1
\]

は \(R^1=C^1/\operatorname{im}d_0\) 上で well-defined である。

**証明。**

代表元を \(\rho\) から \(\rho+d_0f\) に変えると、

\[
d_1(\rho+d_0f)=d_1\rho+d_1d_0f=d_1\rho.
\]

したがって

\[
\delta_1d_1(\rho+d_0f)=\delta_1d_1\rho.
\]

よって \(L\) は商類にのみ依存する。∎

---

## 定理 12. 最小残差力学の平衡と二型分解

**主張。** \(L=\delta_1d_1\succeq0\), \(a\in\operatorname{Range}(L)\) とし、

\[
\dot\rho=-L\rho+a.
\]

このとき平衡は

\[
\rho^\ast=h+L^+a,
\qquad
h\in\ker L\cong H^1(X)
\]

であり、\(\operatorname{Range}(L)\) 成分は \(\lambda^+_{\min}(L)\) の率で指数収束する。

**証明。**

有限次元自己共役半正定値作用素 \(L\) に対し、空間は

\[
R^1=\ker L\oplus\operatorname{Range}(L)
\]

に直交分解する。\(\rho=h+y\) と書く。\(a\in\operatorname{Range}(L)\) なので

\[
\dot h=0,
\qquad
\dot y=-Ly+a.
\]

平衡は \(Ly=a\) の解であり、最小ノルム解は \(y=L^+a\)。従って

\[
\rho^\ast=h+L^+a.
\]

誤差 \(e(t)=y(t)-L^+a\) は

\[
\dot e=-Le
\]

を満たす。\(\operatorname{Range}(L)\) 上で \(L\) の最小正固有値を \(\lambda^+_{\min}\) とすれば、

\[
\|e(t)\|\le e^{-\lambda^+_{\min}t}\|e(0)\|.
\]

∎

**意味。** Type I 構造は \(h\in H^1\)。Type II 構造は \(L^+a\)。前者は位相的記憶、後者はアノマリー維持秩序である。

---

## 定理 13. resilience gap

**主張。** \(\Delta_{\rm res}:=\lambda^+_{\min}(L)>0\) なら、平衡近傍の摂動は指数的に戻る。

**証明。**

定理 12 の誤差方程式 \(\dot e=-Le\) を用いる。スペクトル分解により、

\[
e(t)=\sum_{\lambda_k>0}c_ke^{-\lambda_kt}v_k.
\]

したがって

\[
\|e(t)\|
\le
 e^{-\Delta_{\rm res}t}\|e(0)\|.
\]

∎

**意味。** これは IDS 版 mass gap の最小形である。ギャップがあると、残差構造は小摂動に対して戻る速度を持つ。

---

## 定理 14. \(S\)-skew 条件

**主張。** 作用

\[
S(\rho)=\frac12\langle\rho,L\rho\rangle
=\frac12\|d_1\rho\|^2
\]

に対し、流れ \(\dot\rho=J\rho\) が \(S\) を保存するための必要十分条件は

\[
LJ+J^TL=0.
\]

**証明。**

\[
\frac{dS}{dt}
=
\langle L\rho,J\rho\rangle
=
\rho^TLJ\rho.
\]

これが任意の \(\rho\) でゼロであるための必要十分条件は、行列 \(LJ\) の対称部がゼロであること、すなわち

\[
LJ+(LJ)^T=LJ+J^TL=0.
\]

∎

---

## 定理 15. 強許容保存生成子の分類

**主張。**

\[
R^1=C\oplus H,
\qquad
\dim C=c,
\qquad
\dim H=h,
\]

かつ

\[
L=L_c\oplus0,
\qquad
L_c\succ0
\]

とする。強許容 \(J\) の Lie 環は

\[
\mathfrak g_{\rm strong}
\cong
\mathfrak{so}_{L_c}(c)
\oplus
\mathfrak{so}(h),
\]

したがって

\[
\dim\mathfrak g_{\rm strong}
=
\frac{c(c-1)}2+
\frac{h(h-1)}2.
\]

**証明。**

ブロック表示で

\[
J=
\begin{pmatrix}
J_{cc}&J_{ch}\\
J_{hc}&J_{hh}
\end{pmatrix}.
\]

弱許容の \(S\)-skew 条件 \(LJ+J^TL=0\) から、

\[
L_cJ_{cc}+J_{cc}^TL_c=0,
\qquad
L_cJ_{ch}=0.
\]

\(L_c\) は可逆なので \(J_{ch}=0\)。\(J_{hc}\) と \(J_{hh}\) は弱許容だけでは自由である。

強許容では拡張計量

\[
G=L_c\oplus I_h
\]

に関して

\[
GJ+J^TG=0
\]

を要求する。ブロックごとに、

\[
L_cJ_{cc}+J_{cc}^TL_c=0,
\]

\[
L_cJ_{ch}+J_{hc}^T=0,
\]

\[
J_{hh}+J_{hh}^T=0.
\]

弱許容より \(J_{ch}=0\) だから \(J_{hc}=0\)。よって残る自由度は \(L_c\)-skew な \(J_{cc}\) と通常 skew な \(J_{hh}\) のみである。次元公式が従う。∎

**意味。** 強許容な「矢」は、余完全部と調和部を混合しない。\(H^1\) は矢の自由度を統制する。

---

## 定理 16. hypocoercive resilience の最小機構

**主張。**

\[
A=D+\Omega,
\qquad
D=D^T\succeq0,
\qquad
\Omega^T=-\Omega
\]

とする。\(D\) が退化しても、Kalman/Hörmander 型条件

\[
\operatorname{span}
\{D^{1/2},\Omega D^{1/2},\Omega^2D^{1/2},\dots\}
=
\mathbb R^n
\]

が成り立つなら、\(e^{-tA}\) は全空間で減衰する。

**証明スケッチ。**

\(D\) は直接散逸方向を与える。\(\Omega\) はエネルギーを直接散逸しないが、状態を回転させる。括弧条件は、\(\Omega\) の反復作用により、非散逸方向が散逸方向へ到達可能であることを意味する。これは hypocoercivity の標準定理であり、退化散逸と保存的回転の合成が全空間の指数減衰を生む。∎

**IDS 的意味。** 直接デバッグできない残差も、因果の向き場が散逸可能方向へ回せば回復可能になる。

---

## 定理 17. 可制御性 Gramian によるノイズ耐性境界

**主張。** \(\operatorname{ReSpec}(A)>0\) とし、

\[
G_A=\int_0^\infty e^{-tA}e^{-tA^T}dt
\]

を定義する。ノイズ共分散 \(N\preceq\nu^2|P|I\) なら、定常共分散は

\[
\Sigma\preceq\nu^2|P|G_A.
\]

したがって Peierls 型条件は

\[
\tau_{\rm loc}-\frac12\nu^2\|G_A\|>\log\mu_v.
\]

**証明。**

線形系の定常共分散は

\[
\Sigma=\int_0^\infty e^{-tA}N e^{-tA^T}dt.
\]

仮定 \(N\preceq\nu^2|P|I\) と正作用素順序保存より、

\[
\Sigma
\preceq
\nu^2|P|\int_0^\infty e^{-tA}e^{-tA^T}dt
=
\nu^2|P|G_A.
\]

これを sub-Gaussian 活性上界に代入すると、表面数増大率 \(\mu_v^n\) を上回る局所テンション条件として上式が得られる。∎

---

## 定理 18. bare SPD 幾何は \(\varphi\) を選ばない

**主張。** SPD 錐 \(\mathrm{SPD}(n)\) の full congruence 対称性

\[
\Sigma\mapsto A\Sigma A^T,
\qquad
A\in GL(n)
\]

だけから、\(\varphi I\) のような特別な点は選ばれない。

**証明。**

もし \(P\in\mathrm{SPD}(n)\) がすべての \(A\in GL(n)\) について不変なら、特に \(A=tI\) に対して

\[
t^2P=P
\]

がすべての \(t>0\) で成り立つ必要がある。\(P\ne0\) なのでこれは不可能である。したがって full congruence のみでは特別点は存在しない。∎

---

## 定理 19. self-dual additive residual balance は \(\varphi G\) を選ぶ

**主張。** \(G\in\mathrm{SPD}(n)\) を基準点とし、

\[
\iota_G(\Sigma)=G\Sigma^{-1}G
\]

とする。self-dual additive residual balance

\[
\Sigma-G=G\Sigma^{-1}G
\]

の唯一解は

\[
\Sigma=\varphi G.
\]

**証明。**

白色化して

\[
X=G^{-1/2}\Sigma G^{-1/2}
\]

と置く。方程式は

\[
X-I=X^{-1}
\]

となる。両辺に \(X\) を掛けて、

\[
X^2-X-I=0.
\]

\(X\) は SPD なので対角化可能であり、固有値 \(\lambda>0\) は

\[
\lambda^2-\lambda-1=0
\]

を満たす。正の根は \(\varphi\) のみ。よって \(X=\varphi I\)、すなわち \(\Sigma=\varphi G\)。∎

**注意。** これは SPD 幾何だけの定理ではなく、self-dual additive balance を追加した条件付き定理である。

---

## 定理 20. 潜在 Perron 構造の SPD push-forward

**主張。** \(A\in GL(n)\) が単純優固有値 \(\lambda_1\) を持ち、\(|\lambda_1|>|\lambda_j|\) であるとする。\(\Sigma_k=A^k\Sigma_0(A^k)^T\) なら、正規化 covariance ray は優固有ベクトル \(v_1\) に対応する rank-one ray へ収束し、支配スケールは \(|\lambda_1|^{2k}\) で成長する。

特に \(A=F\) なら、成長率は \(\varphi^{2k}\) である。

**証明スケッチ。**

\(A=V\Lambda V^{-1}\) と書く。

\[
A^k\Sigma_0(A^k)^T
=V\Lambda^k(V^{-1}\Sigma_0V^{-T})\Lambda^kV^T.
\]

\((1,1)\) 成分が \(\lambda_1^{2k}\) で支配し、他の項は \((|\lambda_j|/|\lambda_1|)^k\) の因子で相対的に消える。従って正規化極限は \(v_1v_1^T\) の ray である。\(F\) の優固有値は \(\varphi\) なので covariance scale は \(\varphi^{2k}\)。∎

---

## 定理 21. Causal-Hodge Bridge の低加速度閉包

**主張。** 追加ブリッジ仮定として

\[
a_{\rm model}=a_{\rm bar}+a_I\mathcal B_r[\hat{\mathfrak r}_G]
\]

を置き、

\[
x_b=\frac{a_{\rm bar}}{a_I}\ll1
\]

かつ Equal-Stress Closure

\[
\mathcal B_r[\hat{\mathfrak r}_G]\sim\sqrt{x_b}
\]

を仮定する。このとき

\[
a_{\rm model}\approx\sqrt{a_Ia_{\rm bar}}.
\]

**証明。**

\[
a_{\rm model}
=a_Ix_b+a_I\sqrt{x_b}.
\]

\(x_b\ll1\) では \(x_b\ll\sqrt{x_b}\) だから、

\[
a_{\rm model}
\approx a_I\sqrt{x_b}
=a_I\sqrt{\frac{a_{\rm bar}}{a_I}}
=\sqrt{a_Ia_{\rm bar}}.
\]

∎

**注意。** これは IDS Core の定理ではなく、Causal-Hodge Bridge という物理拡張の条件付き定理である。さらに二点を明記する。（1）結論 \(a_{\rm model}\approx\sqrt{a_Ia_{\rm bar}}\) は MOND の deep-MOND 極限関係式 \(a\approx\sqrt{a_0a_{\rm bar}}\) と形式的に一致する。したがって本定理は既知の現象論的スケーリングの再現であり、新規性は関係式そのものではなく \(a_I=c_I^2/L_I\) を残差構造から導く枠組みの側にある。（2）Equal-Stress Closure \(\mathcal B_r[\hat{\mathfrak r}_G]\sim\sqrt{x_b}\) は結論をほぼ直接含意する仮定であり、本定理の実質は導出ではなく閉包仮定の動機づけにある。反証可能性の負荷は閉包仮定の独立検証（OP-7）が担う。

---

## 定理 22. 非可換曲率項は線形残差商では well-defined でない

**主張。** 線形残差商 \(\rho\sim\rho+d_0f\) 上では、非線形曲率

\[
F(\rho)=d_1\rho+\rho\wedge\rho
\]

は一般に well-defined でない。

**証明。**

代表元を \(\rho'=\rho+d_0f\) に変えると、

\[
F(\rho')
=d_1\rho+d_1d_0f
+(\rho+d_0f)\wedge(\rho+d_0f).
\]

\(d_1d_0=0\) なので線形項は不変だが、二次項は

\[
\rho\wedge\rho
+\rho\wedge d_0f
+d_0f\wedge\rho
+d_0f\wedge d_0f.
\]

一般に追加項はゼロでも exact でもない。したがって \(F(\rho)\) は商類 \([\rho]\) のみに依存しない。∎

**帰結。** 現在の IDS 残差セクターは abelian Hodge 対象として扱うべきである。非可換化には、\(\rho\sim\rho+d_0f\) をゲージ軌道

\[
A\mapsto gAg^{-1}+gdg^{-1}
\]

へ置き換える必要がある。

---

## 定理 23. 二境界デバッグは過去と未来の制約を同時に使う

**主張。** 線形残差経路 \(\rho(t)\) について、作用

\[
\mathcal A[\rho]
=
\int_{t_0}^{t_1}
\frac12\|\dot\rho+L\rho-a\|^2dt
+
\Phi_0(\rho(t_0))
+
\Phi_1(\rho(t_1))
\]

を最小化する経路は、初期制約 \(\Phi_0\) と終端制約 \(\Phi_1\) の双方に依存する。

**証明。**

変分 \(\rho\to\rho+\epsilon\eta\) を取り、

\[
R=\dot\rho+L\rho-a
\]

と書く。

\[
\delta\mathcal A
=
\int_{t_0}^{t_1}\langle R,\dot\eta+L\eta\rangle dt
+\langle\nabla\Phi_0,\eta(t_0)\rangle
+\langle\nabla\Phi_1,\eta(t_1)\rangle.
\]

部分積分により、内部方程式は

\[
-\dot R+L^TR=0
\]

であり、境界条件は

\[
-R(t_0)+\nabla\Phi_0=0,
\qquad
R(t_1)+\nabla\Phi_1=0.
\]

したがって解は初期境界と終端境界の双方に依存する。∎

**意味。** 未来が過去へ信号を送るのではない。未来目標・予測・終端条件が、現在の最適デバッグ経路を選別する。これは smoothing, control, variational mechanics と同じ構造である。

---

## 定理 24. chain–dynamic defect 整合恒等式

**主張。** 細粒度・粗粒度のコチェイン複体を

\[
C_f^i\xrightarrow{d_i^f}C_f^{i+1},
\qquad
C_c^i\xrightarrow{d_i^c}C_c^{i+1}
\]

とし、次数ごとの粗視化と時間発展を

\[
K_i:C_f^i\to C_c^i,
\qquad
T_i^f:C_f^i\to C_f^i,
\qquad
T_i^c:C_c^i\to C_c^i
\]

とする。chain defect、dynamic defect、および各スケール内部の chain–evolution defect を

\[
A_i:=d_i^cK_i-K_{i+1}d_i^f,
\qquad
R_i:=K_iT_i^f-T_i^cK_i,
\]

\[
\mathfrak C_i^f:=d_i^fT_i^f-T_{i+1}^fd_i^f,
\qquad
\mathfrak C_i^c:=d_i^cT_i^c-T_{i+1}^cd_i^c
\]

と定義する。このとき型の整合した恒等式

\[
\boxed{
A_iT_i^f-T_{i+1}^cA_i
=
d_i^cR_i-R_{i+1}d_i^f
-K_{i+1}\mathfrak C_i^f
+\mathfrak C_i^cK_i
}
\]

が成り立つ。

**証明。** 左辺を展開すると、

\[
\begin{aligned}
A_iT_i^f-T_{i+1}^cA_i
={}&d_i^cK_iT_i^f-K_{i+1}d_i^fT_i^f\\
&-T_{i+1}^cd_i^cK_i+T_{i+1}^cK_{i+1}d_i^f.
\end{aligned}
\]

一方、

\[
\begin{aligned}
d_i^cR_i-R_{i+1}d_i^f
={}&d_i^cK_iT_i^f-d_i^cT_i^cK_i\\
&-K_{i+1}T_{i+1}^fd_i^f+T_{i+1}^cK_{i+1}d_i^f.
\end{aligned}
\]

両式の差は

\[
K_{i+1}(T_{i+1}^fd_i^f-d_i^fT_i^f)
+
(d_i^cT_i^c-T_{i+1}^cd_i^c)K_i
=
-K_{i+1}\mathfrak C_i^f+\mathfrak C_i^cK_i
\]

であるから、主張が従う。 \(\square\)

**系 24.1（Bianchi 型整合関係）。** 細粒度・粗粒度の時間発展がそれぞれ chain map、すなわち

\[
\mathfrak C_i^f=\mathfrak C_i^c=0
\]

なら、

\[
\boxed{
A_iT_i^f-T_{i+1}^cA_i
=
d_i^cR_i-R_{i+1}d_i^f
}
\]

となる。

**系 24.2。** 上の仮定のもとで \(A_i=0\) なら dynamic defect は chain map、

\[
d_i^cR_i=R_{i+1}d_i^f
\]

となる。逆に \(R_i=0\) なら chain defect は時間発展によって共変に輸送され、

\[
A_iT_i^f=T_{i+1}^cA_i
\]

となる。\(A=R=0\) の場合、\(K\) は dynamical cochain complexes の射である。

---


## 定理 25. 計量複体対の Type III 昇格定理

**設定。** 有限次元 Hilbert 空間上の複体

\[
C^0\xrightarrow{D^0}C^1\xrightarrow{D^1}C^2,
\qquad D^1D^0=0
\]

と、制約行を忘却した

\[
\bar D^1=P D^1,
\qquad \bar D^1D^0=0
\]

を考える。\(P\) は coarse constraint space への直交射影または行選択とする。

\[
H^1=\ker D^1\cap(\operatorname{im}D^0)^\perp,
\qquad
\bar H^1=\ker\bar D^1\cap(\operatorname{im}D^0)^\perp.
\]

このとき

\[
\boxed{
\mathcal T_{\mathrm{III}}
:=\bar H^1\ominus H^1
=\operatorname{im}(D^1)^*\cap\ker\bar D^1
}
\]

であり、さらに

\[
\boxed{
\operatorname{im}(D^1)^*
=
\operatorname{im}(\bar D^1)^*
\oplus
\mathcal T_{\mathrm{III}}.
}
\]

従って

\[
\boxed{
C^1
=
\operatorname{im}D^0
\oplus H^1
\oplus\mathcal T_{\mathrm{III}}
\oplus\operatorname{im}(\bar D^1)^*.
}
\]

**証明。** fine Hodge 分解

\[
C^1=\operatorname{im}D^0\oplus H^1\oplus\operatorname{im}(D^1)^*
\]

を用いる。\(x\in\bar H^1\ominus H^1\) なら \(x\perp\operatorname{im}D^0\) かつ \(x\perp H^1\) なので \(x\in\operatorname{im}(D^1)^*\)、また \(x\in\ker\bar D^1\)。逆に \(x\in\operatorname{im}(D^1)^*\cap\ker\bar D^1\) なら \(x\perp H^1\) かつ \(x\perp\operatorname{im}D^0\) なので \(x\in\bar H^1\ominus H^1\)。第二式は

\[
(\operatorname{im}(\bar D^1)^*)^\perp=\ker\bar D^1,
\qquad
\operatorname{im}(\bar D^1)^*\subseteq\operatorname{im}(D^1)^*
\]

から従う。\(\square\)

**系 25.1（階数公式）。**

\[
\boxed{
\dim\mathcal T_{\mathrm{III}}
=
\operatorname{rank}D^1-
\operatorname{rank}\bar D^1.
}
\]

**系 25.2（長時間検出器）。**

\[
L=(D^1)^*D^1,
\qquad
\bar L=(\bar D^1)^*\bar D^1
\]

とすると

\[
\boxed{
e^{-tL}-e^{-t\bar L}
\xrightarrow[t\to\infty]{}
-P_{\mathcal T_{\mathrm{III}}}.
}
\]

この定理は可換 Hodge 系と flat connection 上の twisted complex の双方を含む。

---

## 定理 26. 有限圧縮型 Type III と標準 decoder

有限次元 Hilbert 空間 \(\mathcal H,\bar{\mathcal H}\) 上で

\[
L\succeq0,
\qquad
\bar L\succeq0,
\qquad
K:\mathcal H\to\bar{\mathcal H}
\]

とし、

\[
P=P_{\ker L},
\qquad
\bar P=P_{\ker\bar L},
\qquad
Q=I-P,
\qquad
\Gamma_K=\bar P KQ
\]

と置く。

\[
\mathcal S_K=\operatorname{Ran}\Gamma_K^*,
\qquad
\mathcal T_K=\operatorname{Ran}\Gamma_K.
\]

\(\Gamma_K\) を \(Q\mathcal H\to\bar P\bar{\mathcal H}\) の作用素として読む。このとき

\[
Q\mathcal H
=
\ker(\Gamma_K|_{Q\mathcal H})
\oplus\mathcal S_K
\]

かつ

\[
\boxed{
\Gamma_K|_{\mathcal S_K}:
\mathcal S_K\xrightarrow{\cong}\mathcal T_K.
}
\]

標準 decoder は

\[
\boxed{D_K=\Gamma_K^+|_{\mathcal T_K}}
\]

であり、

\[
D_K\Gamma_Kx=x
\qquad(x\in\mathcal S_K),
\]

\[
\boxed{\|D_K\|=1/\sigma_{\min}^+(\Gamma_K)}
\]

である（\(\Gamma_K=0\) の場合は \(\mathcal S_K=\mathcal T_K=0\)、標準 decoder を零写像とする）。

また

\[
R_K(t)=Ke^{-tL}-e^{-t\bar L}K
\]

なら、\(x\in Q\mathcal H\) に対して

\[
\boxed{-R_K(\infty)x=\Gamma_Kx.}
\]

**証明。** \(\Gamma_K:Q\mathcal H\to\bar P\bar{\mathcal H}\) に Moore–Penrose / singular-value decomposition を適用すると、\((\ker(\Gamma_K|_{Q\mathcal H}))^\perp_{Q\mathcal H}=\operatorname{Ran}\Gamma_K^*\) であり、\(\Gamma_K\) はこの直交補から像への全単射である。decoder とノルム公式は非零特異値の逆数から従う。半群極限は \(e^{-tL}\to P\)、\(e^{-t\bar L}\to\bar P\) を用いる。\(\square\)

---

## 定理 27. 制御関連商の普遍性

微視仮説空間を \(\Theta\)、許容介入集合を \(\mathcal U\)、介入 \(u\) の下での将来応答を \(\mathcal O^u:\Theta\to Y_u\)、レジリエンス指標を \(g:\Theta\to\mathbb R\) とする。行動写像

\[
\mathcal B(\theta)
=
\bigl((\mathcal O^u(\theta))_{u\in\mathcal U},g(\theta)\bigr)
\]

を定め、

\[
\theta\sim_{\rm ctrl}\theta'
\iff
\mathcal B(\theta)=\mathcal B(\theta')
\]

とする。このとき商写像 \(q:\Theta\to Q_{\rm ctrl}=\Theta/\!\sim_{\rm ctrl}\) は次の普遍性を持つ。

1. \(\mathcal B\) は一意な単射 \(\bar{\mathcal B}:Q_{\rm ctrl}\to\mathcal B(\Theta)\) を通じて因子化する。
2. 任意の統計 \(Z:\Theta\to\mathcal Z\) について、全ての \(\mathcal O^u\) と \(g\) が \(Z\) を通じて因子化するなら、\(q\) も \(Z\) を通じて一意に因子化する。

従って \(Q_{\rm ctrl}\) は、指定された介入族と安全指標を保存する**最も粗い行動十分商**である。

**証明。** 第一項は商の定義から直ちに従う。第二項では \(Z(\theta)=Z(\theta')\) なら \(\mathcal B(\theta)=\mathcal B(\theta')\)、従って \(q(\theta)=q(\theta')\) であるため、像 \(Z(\Theta)\) 上に一意な写像が誘導される。\(\square\)

距離空間 \(\mathcal B(\Theta)\) の距離を引き戻せば、\(Q_{\rm ctrl}\) は自然な task-relative metric を持つ。

---

## 定理 28. Projected mixing の次元閾値

正則な Hilbert 層で \(\mathcal B\) が微分可能とし、

\[
\mathcal N_{{\rm ctrl},\theta}=\ker D\mathcal B_\theta
\]

が閉部分空間であるとする。\(P_{\rm ctrl}\) を \(\mathcal N_{{\rm ctrl},\theta}^\perp\) への直交射影とする。

\(d\) 次元格子上の残差場 \(r_x\) が

\[
\left\|
\operatorname{Cov}
(P_{\rm ctrl}r_x,P_{\rm ctrl}r_y)
\right\|
\le
C(1+|x-y|)^{-2\Delta_{\rm ctrl}}
\]

を満たすなら、

\[
\boxed{
\Delta_{\rm ctrl}>\frac d2
\quad\Longrightarrow\quad
S^{\rm ctrl}
:=
\sup_x\sum_y
\left\|\operatorname{Cov}
(P_{\rm ctrl}r_x,P_{\rm ctrl}r_y)
\right\|<\infty.
}
\]

四次元では閾値は \(\Delta_{\rm ctrl}>2\) である。

**証明。** 半径 \(R\) の格子殻の点数は \(O(R^{d-1})\) なので、Schur 和は

\[
\sum_{R\ge1}R^{d-1-2\Delta_{\rm ctrl}}
\]

で上から抑えられ、\(d-1-2\Delta_{\rm ctrl}<-1\) すなわち \(2\Delta_{\rm ctrl}>d\) で収束する。\(\square\)

**注意。** これは制御関連 sector の多スケール可和性の十分条件であり、全理論の mass gap、因果識別、Clay 問題との同値を意味しない。

---

## 定理 29. 識別可能性からの安全予算

\(F_n:Q_{\rm ctrl}\to Y_n\) が下側 Lipschitz 条件

\[
d_{Y_n}(F_n(q),F_n(q'))
\ge
\beta_n d_{\rm ctrl}(q,q'),
\qquad
\beta_n>0
\]

を満たし、\(g:Q_{\rm ctrl}\to\mathbb R\) が

\[
|g(q)-g(q')|
\le
L_g d_{\rm ctrl}(q,q')
\]

を満たすとする。このとき任意の真値 \(q\) と推定値 \(\hat q\) について

\[
\boxed{
g(\hat q)
\ge
g(q)-\frac{L_g}{\beta_n}
 d_{Y_n}(F_n(\hat q),F_n(q)).}
\]

観測 \(y\) が

\[
d(y,F_n(q))\le\eta_n,
\qquad
d(y,F_n(\hat q))\le\xi_n
\]

を満たすなら、総誤差 \(\mathfrak E_n:=\eta_n+\xi_n\) に対して

\[
g(\hat q)
\ge
g(q)-\frac{L_g}{\beta_n}\mathfrak E_n.
\]

従って安全率 \(0<\vartheta<1\) と最低許容値 \(g_{\min}\) に対し

\[
\boxed{
\mathfrak E_n
\le
\vartheta\frac{\beta_n}{L_g}
\bigl(g(q)-g_{\min}\bigr)
}
\]

かつ \(g(q)>g_{\min}\) なら \(g(\hat q)>g_{\min}\) が保証される。

**証明。** 下側 Lipschitz 条件と三角不等式から

\[
d_{\rm ctrl}(q,\hat q)
\le
\frac{d(F_n(q),F_n(\hat q))}{\beta_n}
\le
\frac{\eta_n+\xi_n}{\beta_n}.
\]

これを \(g\) の Lipschitz 評価へ代入する。\(\square\)

---

## 定理 30. 多段安全誤差の再帰上界

非負誤差列が

\[
e_{j+1}\le A_je_j+\varepsilon_j,
\qquad A_j\ge0
\]

を満たすなら、\(N>n\) に対して

\[
\boxed{
e_N
\le
\left(\prod_{\ell=n}^{N-1}A_\ell\right)e_n
+
\sum_{j=n}^{N-1}
\varepsilon_j
\prod_{\ell=j+1}^{N-1}A_\ell.
}
\]

従って future tail が収束する場合、右辺を定理29の \(\mathfrak E_n\) として安全予算に比較できる。

**証明。** 再帰式を逐次代入する帰納法。\(\square\)



## 定理 31. 制御商の物理ゲージ降下

有限次元 Riemann 多様体 \((\Theta,h)\) に compact Lie 群 \(\mathcal G\) が滑らかかつ等長に作用し、行動写像

\[
\mathcal B(\theta)
=
\bigl((\mathcal O_\theta^u)_{u\in\mathcal U},g(\theta)\bigr)
\]

が物理ゲージ不変、

\[
\mathcal B(\gamma\cdot\theta)=\mathcal B(\theta)
\qquad(\gamma\in\mathcal G)
\]

であるとする。このとき：

1. 物理ゲージ軌道の接方向は制御-null方向に含まれる。

\[
T_\theta(\mathcal G\cdot\theta)
\subseteq
\ker D\mathcal B_\theta.
\]

2. \(\mathcal B\) は物理ゲージ軌道商を通じて因子化する。

\[
\mathcal B=\bar{\mathcal B}\circ q_{\mathcal G}.
\]

3. 制御商は物理軌道商上で定義できる。

\[
\boxed{
Q_{\rm ctrl}^{\rm phys}
:=
(\Theta/\mathcal G)/\!\sim_{\rm ctrl}.
}
\]

作用が非自由な場合、\(\Theta/\mathcal G\) は通常の滑らかな商多様体でなく、orbit-type stratification または quotient stack \([\Theta/\mathcal G]\) として読む。

**証明。** \(\xi\in\operatorname{Lie}(\mathcal G)\) の基本ベクトル場を \(\xi_\Theta\) とする。ゲージ不変性を微分すると

\[
D\mathcal B_\theta\bigl(\xi_\Theta(\theta)\bigr)
=
\frac d{dt}\Big|_{0}
\mathcal B(e^{t\xi}\cdot\theta)
=0.
\]

従って軌道接方向は \(\ker D\mathcal B_\theta\) に含まれる。因子化と第二の商は商写像の普遍性から従う。\(\square\)

**規律。** \(Q_{\rm ctrl}\) は gauge fixing ではない。gauge fixing は一つの物理ゲージ軌道から代表元を選ぶ局所切断であり、制御商は同じ未来応答を持つ物理状態をさらに同一視する目的依存の商である。

---

## 定理 32. 制御関連射影のゲージ共変性

定理31の仮定に加え、正則層 \(S\subset\Theta\) 上で \(D\mathcal B\) の rank が一定とする。

\[
N_\theta^{\rm ctrl}:=\ker D\mathcal B_\theta,
\qquad
E_\theta^{\rm ctrl}:=(N_\theta^{\rm ctrl})^{\perp_h}
\]

とし、\(E_\theta^{\rm ctrl}\) への直交射影を \(P_\theta=P_{{\rm ctrl},\theta}\) とする。このとき任意の \(\gamma\in\mathcal G\) について

\[
N_{\gamma\theta}^{\rm ctrl}
=D\gamma_\theta N_\theta^{\rm ctrl},
\qquad
E_{\gamma\theta}^{\rm ctrl}
=D\gamma_\theta E_\theta^{\rm ctrl},
\]

従って

\[
\boxed{
P_{\gamma\theta}D\gamma_\theta
=
D\gamma_\theta P_\theta.
}
\]

**証明。** \(\mathcal B\circ\gamma=\mathcal B\) の微分から

\[
D\mathcal B_{\gamma\theta}D\gamma_\theta
=D\mathcal B_\theta.
\]

よって \(D\gamma_\theta\) は kernel を kernel へ送る。逆元で逆包含を得る。群作用は等長なので直交補も保存し、射影の共変性が従う。\(\square\)

**意味。** \(P_{\rm ctrl}\) は代表元を選ぶ gauge fixing ではなく、ゲージ共変な control-relevant subbundle の射影である。従って大域 gauge slice を仮定せずに定義できる。

---

## 定理 33. task–coarse defect の二分解

fine／coarse の正則接空間に制御関連射影 \(P_f,P_c\) があり、粗視化の線形化を

\[
K:T\Theta_f\to T\Theta_c
\]

とする。次を定義する。

\[
\Gamma_K^{\rm ctrl}
:=P_cK(I-P_f)
\qquad
\text{(null \(\to\) relevant promotion)},
\]

\[
\Lambda_K^{\rm ctrl}
:=(I-P_c)KP_f
\qquad
\text{(relevant \(\to\) null erasure)}.
\]

このとき

\[
\boxed{
P_cK-KP_f
=
\Gamma_K^{\rm ctrl}-\Lambda_K^{\rm ctrl}.
}
\]

さらに：

1. \(\Gamma_K^{\rm ctrl}=0\) と \(K(N_f^{\rm ctrl})\subseteq N_c^{\rm ctrl}\) は同値であり、これは正則層の**接空間レベル**で \(K\) が制御商へ降下するための必要十分条件である。
2. \(\Lambda_K^{\rm ctrl}=0\) と \(K(E_f^{\rm ctrl})\subseteq E_c^{\rm ctrl}\) は同値である。
3. 両欠陥がゼロなら

\[
P_cK=KP_f,
\]

すなわち粗視化と task selection は接空間レベルで完全に可換する。

**証明。** \(I=P_f+(I-P_f)=P_c+(I-P_c)\) を挿入すれば

\[
P_cK-KP_f
=P_cK(I-P_f)-(I-P_c)KP_f.
\]

残りは射影の像と核の定義から従う。\(\square\)

**注意。** 非線形写像 \(K:\Theta_f\to\Theta_c\) が大域的に制御商へ降下するには、接空間条件だけでなく、同値類保存

\[
\theta\sim_{{\rm ctrl},f}\theta'
\Longrightarrow
K\theta\sim_{{\rm ctrl},c}K\theta'
\]

が必要である。これは OP-TG4 に残す。

**正典的名称。** \(\Gamma_K^{\rm ctrl}\) は **control promotion defect**、\(\Lambda_K^{\rm ctrl}\) は **control erasure defect** と呼ぶ。前者は task-relative Type III の線形候補、後者は安全な粗視化に対する直接の損失検出器である。

物理ゲージ作用と \(K\) が intertwine し、\(P_f,P_c\) が定理32の意味で共変なら、両欠陥も共変であり、その rank・非零特異値・作用素ノルムはゲージ代表元に依存しない。

### 系 33.1. return specialization

固定された有限正則 task 層で fine／coarse の始終点を内在的 return identification により同定し、

\[
P_f=P_c=P_{\rm ctrl},
\qquad
K=\mathscr R^{\rm ret}
\]

と置く。このとき

\[
\Gamma_{\mathscr R}^{\rm ctrl}
=
P_{\rm ctrl}\mathscr R^{\rm ret}(I-P_{\rm ctrl}),
\]

\[
\Lambda_{\mathscr R}^{\rm ctrl}
=
(I-P_{\rm ctrl})\mathscr R^{\rm ret}P_{\rm ctrl}
\]

は、一周の間の control-null \(\to\) relevant promotion と relevant \(\to\) null erasure である。\(\Gamma_{\mathscr R}^{\rm ctrl}\ne0\) なら full return は一般に control quotient 上の通常の自己写像へ降下しない。従って非自明な再入を保持するには、商の手前の full space を残し、定理36の bridge-hidden Feshbach 還元を用いる。

ただし \(P_{\rm ctrl}\) と residual realization projector \(P_{\rm res}\) は同一とは限らない。前者は task relevance、後者は静的残差同一性を表す。

---

## 定理 34. 誘導 task–gauge connection と曲率

計量付き物理ゲージベクトル束 \(V\to S\) に接続 \(D_A\) があり、\(P=P_{\rm ctrl}\) が滑らかな一定 rank のゲージ共変直交射影であるとする。制御関連部分束

\[
E_{\rm ctrl}:=\operatorname{Ran}P
\]

上に

\[
\boxed{
\nabla^{\rm ctrl}s:=P D_As
\qquad(s\in\Gamma(E_{\rm ctrl}))
}
\]

を定める。これはゲージ共変な接続であり、その曲率は

\[
\boxed{
F_{\rm ctrl}
=
P F_A P
+
P(D_AP)\wedge(D_AP)P.
}
\]

**証明。** \(Ps=s\) を満たす section \(s\) に対して

\[
(\nabla^{\rm ctrl})^2s
=P D_A(PD_As).
\]

\(D_A(P^2)=D_AP\) から

\[
P(D_AP)P=0
\]

を得る。Leibniz 則を用いて展開すると

\[
(\nabla^{\rm ctrl})^2s
=PF_As+P(D_AP)\wedge(D_AP)s,
\]

従って表示式が従う。\(\square\)

この式は二つの曲率源を分離する。

\[
\boxed{
\text{task–gauge curvature}
=
\text{task が見る物理曲率}
+
\text{関連性の選び方自体の曲率}.
}
\]

- \(D_AP=0\)：task relevance は物理輸送で保存され、\(F_{\rm ctrl}=PF_AP\)。
- \(F_A=0\) でも \(D_AP\neq0\)：物理接続が平坦でも、task family の変化だけで operational holonomy が生じ得る。

スケール座標 \(s\) と task 座標 \(\tau\) を持つ基底上では mixed component は

\[
\boxed{
(F_{\rm ctrl})_{s\tau}
=
P(F_A)_{s\tau}P
+
P[D_sP,D_\tau P]P.
}
\]

これは「粗視化してから retask」と「retask してから粗視化」の非可換性を測る。

### 系 34.1. 安全予算の物理ゲージ不変性

定理29の \(F_n,g,d_{\rm ctrl}\) が物理ゲージ軌道商へ降下し、誤差 \(\mathfrak E_n\) がゲージ不変ノルムで測られるなら、\(\beta_n,L_g,\mathfrak E_n\) は代表元に依存しない。従って

\[
\boxed{
\mathfrak E_n
\le
\vartheta\frac{\beta_n}{L_g}(g_n-g_{\min})
}
\]

は物理ゲージ不変な停止条件である。\(\square\)

---

## 定理 35. 残差実現の代表元独立性と split residual bridge

有界作用素

\[
C^0\xrightarrow{d_0}C^1
\]

を持つ実または複素 Banach 空間を考え、\(\operatorname{im}d_0\) は閉であるとする。有限次元ではこの仮定は自動的である。残差商と商写像を

\[
\mathcal X:=C^1/\operatorname{im}d_0,
\qquad
\pi_R:C^1\to\mathcal X
\]

とする。Banach 空間 \(V\) への有界線形写像 \(\widetilde\iota:C^1\to V\) について、次は同値である。

\[
\boxed{
\widetilde\iota(r+d_0f)=\widetilde\iota(r)
\quad\Longleftrightarrow\quad
\widetilde\iota d_0=0
\quad\Longleftrightarrow\quad
\exists!\,\iota\in\mathcal B(\mathcal X,V),
\ \widetilde\iota=\iota\pi_R .
}
\]

さらに、有界な residual decoder

\[
\varpi:V\to\mathcal X,
\qquad
\boxed{\varpi\iota=I_{\mathcal X}}
\]

が存在するとする。

この decoder の存在は一般の Banach 空間では自動でない。これは \(\iota\) が bounded below な単射で、その閉像 \(\operatorname{Ran}\iota\) が \(V\) で有界に complemented されることと同値である。従って split 性は、代表元独立性から導かれる結論ではなく bridge data に対する追加仮定である。

物理的読出しが有界線形な代表元 decoder \(\widetilde\varpi:V\to C^1\) を出力する場合は、\(\varpi:=\pi_R\widetilde\varpi\) と置く。従って decoder の出力は最初から残差商で比較され、出力代表元の exact 成分に依存しない。split 条件 \(\varpi\iota=I\) は、入力した残差類を同じ類として忠実に回復する条件である。

このとき

\[
P_{\rm res}:=\iota\varpi,
\qquad
Q_{\rm res}:=I_V-P_{\rm res}
\]

は有界射影であり、

\[
\boxed{
V
=
\operatorname{Ran}\iota
\mathbin{\widehat\oplus}
\ker\varpi .
}
\]

ここで \(\widehat\oplus\) は topological direct sum を表す。この組 \((\iota,\varpi)\) を **split residual bridge**、\(P_{\rm res}\) を residual realization projector と呼ぶ。

**証明。** 最初の同値は商空間の普遍性である。\(\varpi\iota=I\) なら

\[
P_{\rm res}^2
=\iota(\varpi\iota)\varpi
=P_{\rm res}.
\]

任意の \(v\in V\) は

\[
v=\iota\varpi v+(v-\iota\varpi v)
\]

と分かれ、第二項は \(\ker\varpi\) に入る。交わりがゼロであることは \(\varpi\iota=I\) から従う。\(\square\)

**Hilbert 規約.** \(V,\mathcal X\) が Hilbert 空間で、計量作用素が bounded・self-adjoint・uniformly positive、かつ \(\iota\) が閉像を持つ有界単射なら、自己生成計量に関する標準左逆

\[
\boxed{
\varpi
=
(\iota^\dagger\iota)^{-1}\iota^\dagger
}
\]

を選べる。このとき \(P_{\rm res}\) はその計量に関する直交射影である。ただし、物理的 residual decoder が介入・観測によって独立に指定されている場合は、なお \(\varpi\iota=I_{\mathcal X}\) を満たすことを検証した上で、その decoder を優先する。

**型の規律.** \(P_{\rm res}\)、定理32の \(P_{\rm ctrl}\)、定理36で得られる Riesz 射影 \(\Pi_{\rm self}\) は異なる。

- \(P_{\rm res}\)：何を同じ静的残差として実現・読出しするか。
- \(P_{\rm ctrl}\)：何が指定 task の未来応答を変えるか。
- \(\Pi_{\rm self}\)：full return のスペクトルを解いた後に得られる自己モード。

これらをスペクトル計算後に都合よく同一視してはならない。

---

## 定理 36. 残差商上の完全 Schur–Feshbach 再入定理

定理35の split residual bridge を持つ有界 return operator

\[
\mathscr R^{\rm ret}:V\to V
\]

を考える。以下の spectrum、resolvent、Riesz 射影は複素 Banach 空間上で取る。元の模型が実なら標準複素化した作用素で定義し、共役対称性を課して実構造へ戻す。bridge-hidden sector を

\[
\boxed{
\mathcal H_{\rm br}:=\ker\varpi=\operatorname{Ran}Q_{\rm res}
}
\]

とする。これは、従来の hidden／carrier sector だけでなく、visible であっても residual decoder が読まない補空間をすべて含む。

bridge 座標同型

\[
\mathcal J_{\rm br}:\mathcal X\oplus\mathcal H_{\rm br}\to V,
\qquad
\mathcal J_{\rm br}(r,h)=\iota r+h
\]

は bounded な同型であり、

\[
\mathcal J_{\rm br}^{-1}v
=
(\varpi v,Q_{\rm res}v).
\]

この座標のもとで、\(\mathscr R^{\rm ret}\) は

\[
\mathcal J_{\rm br}^{-1}\mathscr R^{\rm ret}\mathcal J_{\rm br}
=
\begin{pmatrix}
\mathsf a&\mathsf\gamma\\
\mathsf\lambda&\mathsf n
\end{pmatrix}
\]

と一意に書ける。ただし

\[
\mathsf a=\varpi\mathscr R^{\rm ret}\iota,
\qquad
\mathsf\lambda=Q_{\rm res}\mathscr R^{\rm ret}\iota,
\]

\[
\mathsf\gamma
=\varpi\mathscr R^{\rm ret}|_{\mathcal H_{\rm br}},
\qquad
\mathsf n
=Q_{\rm res}\mathscr R^{\rm ret}|_{\mathcal H_{\rm br}}.
\]

\(z\notin\operatorname{Spec}(\mathsf n)\) に対して、**残差再入 self-energy** と **残差 Schur pencil** を

\[
\boxed{
\Sigma_{\rm br}^{\rm self}(z)
:=
\mathsf\gamma
(zI_{\mathcal H_{\rm br}}-\mathsf n)^{-1}
\mathsf\lambda
\in\mathcal B(\mathcal X),
}
\]

\[
\boxed{
m_{\rm br}(z)
:=
zI_{\mathcal X}
-\mathsf a
-\Sigma_{\rm br}^{\rm self}(z)
}
\]

と定める。このとき

\[
\boxed{
\mathscr R^{\rm ret}\mathcal J_{\rm br}(r,h)
=z\mathcal J_{\rm br}(r,h)
\quad\Longleftrightarrow\quad
\begin{cases}
m_{\rm br}(z)r=0,\\[1mm]
h=(zI-\mathsf n)^{-1}\mathsf\lambda r .
\end{cases}
}
\]

また \(z\notin\operatorname{Spec}(\mathsf n)\) のもとで

\[
zI-\mathscr R^{\rm ret}\text{ が可逆}
\quad\Longleftrightarrow\quad
m_{\rm br}(z)\text{ が可逆},
\]

かつ

\[
\boxed{
\varpi(zI-\mathscr R^{\rm ret})^{-1}\iota
=
m_{\rm br}(z)^{-1}.
}
\]

**証明。** \(D(z)=zI-\mathsf n\) と置けば

\[
zI-\mathcal J_{\rm br}^{-1}\mathscr R^{\rm ret}\mathcal J_{\rm br}
=
\begin{pmatrix}
I&-\mathsf\gamma D(z)^{-1}\\
0&I
\end{pmatrix}
\begin{pmatrix}
m_{\rm br}(z)&0\\
-\mathsf\lambda&D(z)
\end{pmatrix}.
\]

第一因子は常に可逆であり、第二因子の可逆性は \(m_{\rm br}(z)\) と \(D(z)\) の可逆性に同値である。kernel 方程式と圧縮 resolvent 公式も同じ因子分解から従う。\(\square\)

有限次元では、さらに

\[
\boxed{
\det(zI-\mathscr R^{\rm ret})
=
\det(zI-\mathsf n)\det m_{\rm br}(z).
}
\]

従ってこれは visible 方程式の射影近似ではなく、静的残差商 \(\mathcal X\) 上の完全な Feshbach 還元である。

**能動的再入モード.** \(r_*\ne0\)、\(z_*\notin\operatorname{Spec}(\mathsf n)\) が

\[
m_{\rm br}(z_*)r_*=0,
\qquad
\mathsf\lambda r_*\ne0,
\qquad
\boxed{
\Sigma_{\rm br}^{\rm self}(z_*)r_*\ne0
}
\]

を満たすとき、\((z_*,r_*)\) を **残差能動的再入モード** と呼ぶ。第二条件は bridge-hidden sector への退出、第三条件は同じ残差商への非零再入を表す。単に full visible sector へ戻るだけで \(\varpi\) に消される成分は自己再入と数えない。

**系 36.1（射影の非同一性）.** 能動的再入モードを含む孤立 self cluster の Riesz 射影を \(\Pi_{\rm self}\) とする。もし \(P_{\rm res}=\Pi_{\rm self}\) なら、Riesz 射影は \(\mathscr R^{\rm ret}\) と可換するため \(\mathsf\lambda=\mathsf\gamma=0\) となる。従って能動的再入があれば

\[
\boxed{P_{\rm res}\ne\Pi_{\rm self}}
\]

は公理でなく帰結である。

**収束規律.** 定義は resolvent 形を本体とする。有界 \(\mathsf n\) について

\[
\Sigma_{\rm br}^{\rm self}(z)
=
\sum_{k\ge0}z^{-k-1}\mathsf\gamma\mathsf n^k\mathsf\lambda
\]

と展開できるのは、例えば \(|z|>\operatorname{spr}(\mathsf n)\) で作用素ノルム級数が収束するときに限る。一般の resolvent set 全体でこの級数表示を仮定しない。

---

### 系 36.2. hidden-path 感度と一つの介入付きスペクトル関数

hidden path の結合を操作する介入変数 \(s\in[0,1]\) を導入し、

\[
m_{\rm br}(z;s)
=
zI-\mathsf a-s\Sigma_{\rm br}^{\rm self}(z)
\]

とする。以下では \(\mathcal X\) を Hilbert 空間とし、\(G_R\) は bounded・self-adjoint・uniformly positive な計量作用素、

\[
\lVert r\rVert_{G_R}^2:=\langle r,G_Rr\rangle
\]

とする。左零モードは双対核（複素 Hilbert 空間では随伴核）に取る。\(s=1\) は実系、\(s=0\) は bridge-hidden feedback を切断した反実仮想である。ここで \(s\) は任意の path 座標ではなく、\(\Sigma_{\rm br}^{\rm self}\) 全体へ直接掛ける**無次元 affine coupling multiplier** として正規化する。尺度間比較でも「完全切断 \(0\)、未介入 \(1\)、中間値は同じ線形混合規約」を用いる。\(s=f(u)\) という再パラメータ化を許せば端点が同じでも感度は \(f'(1)\) 倍されるため、その場合の微分値を同じ \(\beta_{\rm path}\) と比較してはならない。内在計量 \(G_R\) に関する **自己再生スペクトル関数** を

\[
\boxed{
\chi_{\rm SR}(z,s)
=
\begin{cases}
\|m_{\rm br}(z;s)^{-1}\|_{G_R}^{-1},
&m_{\rm br}(z;s)\text{ が可逆},\\[1mm]
0,&m_{\rm br}(z;s)\text{ が非可逆}
\end{cases}
}
\]

と定める。これは固有零点だけでなく非正規な擬スペクトル感度を含む。

ここで定義域は \(z\notin\operatorname{Spec}(\mathsf n)\) である。\(z\in\operatorname{Spec}(\mathsf n)\) では Feshbach chart 自体が特異であり、\(\chi_{\rm SR}=0\) と約束せず、別 chart または full resolvent へ戻る。

有限次元では

\[
D_{\rm SR}(z,s):=\det m_{\rm br}(z;s)
\]

を補助的な解析関数として用いてよい。無限次元では、基準作用素で正規化した pencil が \(I+\) trace-class になるなど Fredholm determinant の仮定を別途明示した場合に限り \(\det_F\) を用い、determinant の存在を一般公理にしない。

\(z(s)\) と非零 \(r(s)\) が \(s=1\) の近傍で \(C^1\) な単純零点枝をなし、

\[
r^\#\in
\ker m_{\rm br}(z_*;1)^*\setminus\{0\}
\]

が左零モードで

\[
\left\langle r^\#,
[I-\partial_z\Sigma_{\rm br}^{\rm self}(z_*)]r_*
\right\rangle\ne0
\]

なら、暗黙微分により

\[
\boxed{
\left.\frac{dz}{ds}\right|_{s=1}
=
\frac{
\langle r^\#,\Sigma_{\rm br}^{\rm self}(z_*)r_*\rangle
}{
\langle r^\#,[I-\partial_z\Sigma_{\rm br}^{\rm self}(z_*)]r_*\rangle
}.
}
\]

従って

\[
\beta_{\rm path}
:=
\left|\left.\frac{dz}{ds}\right|_{s=1}\right|
\]

と定める。無限次元ではこの \(C^1\) 単純枝の存在は追加仮定であり、例えば解析的 Fredholm pencil・index \(0\)・孤立単純零点から得る。上の affine multiplier 規約を固定したとき、\(\beta_{\rm path}>0\) は hidden path が residual self eigenvalue へ実際に寄与することの state similarity に不変な局所検出器である。intervention の再パラメータ化には不変でない。\(\Sigma r_*\ne0\) でも左自己モードとの重なりがゼロなら \(\beta_{\rm path}=0\) になり得る。この値は一次感度だけを測るので、\(\beta_{\rm path}=0\) から高次または有限振幅の path 効果がないとは結論しない。

---

## 定理 37. residual bridge のゲージ・スケール自然性

二つの複体と bridge-return データを添字 \(a,b\) で表す。有界 chain map \(U_0,U_1\) が

\[
U_1d_{0,a}=d_{0,b}U_0
\]

を満たすとする。この chain map は残差商上に

\[
\bar U[r]=[U_1r]
\]

を誘導する。さらに有界写像 \(U_V:V_a\to V_b\) が

\[
U_V\iota_a=\iota_b\bar U,
\qquad
\varpi_bU_V=\bar U\varpi_a,
\]

\[
U_V\mathscr R_a^{\rm ret}
=
\mathscr R_b^{\rm ret}U_V
\]

を満たすとする。このとき \(U_V\) は bridge-hidden sector を bridge-hidden sector へ送り、その制限 \(U_H\) について

\[
\mathsf a_b\bar U=\bar U\mathsf a_a,
\qquad
\mathsf n_bU_H=U_H\mathsf n_a,
\]

\[
\mathsf\lambda_b\bar U=U_H\mathsf\lambda_a,
\qquad
\mathsf\gamma_bU_H=\bar U\mathsf\gamma_a.
\]

両側で \(z\notin\operatorname{Spec}(\mathsf n_{a,b})\) なら

\[
\boxed{
\Sigma_{{\rm br},b}^{\rm self}(z)\bar U
=
\bar U\Sigma_{{\rm br},a}^{\rm self}(z),
\qquad
m_{{\rm br},b}(z;s)\bar U
=
\bar U m_{{\rm br},a}(z;s).
}
\]

**証明。** \((zI-\mathsf n_b)U_H=U_H(zI-\mathsf n_a)\) と両 resolvent の存在から

\[
(zI-\mathsf n_b)^{-1}U_H
=
U_H(zI-\mathsf n_a)^{-1}
\]

を得る。これを block intertwining へ代入すればよい。\(\square\)

**スケール規律.** 一般の RG 粗視化では \(\bar U,U_V\) は非可逆でよく、上式を **scale intertwining** と呼ぶ。可逆な universality／fixed-point sector に限り共役共変性となる。さらに両残差空間が Hilbert 空間で、\(G_{R,a},G_{R,b}\) が bounded・self-adjoint・uniformly positive、\(\bar U\) が bounded な同型であり、

\[
G_{R,b}=\bar U^{-*}G_{R,a}\bar U^{-1}
\]

（\(\bar U^{-*}:=(\bar U^{-1})^*\)）により \(\bar U\) が等長同型なら

\[
\boxed{
\chi_{{\rm SR},b}(z,s)=\chi_{{\rm SR},a}(z,s).
}
\]

非可逆粗視化では関数値の同一性を自動的に主張せず、intertwining defect と安全予算を測る。

---

## 定理 38. return operator 単独による内生的自己生成の識別不能性

Banach 多様体 \(X\) 上の \(C^1\) return map \(F:X\to X\) と return fixed point \(F(x_*)=x_*\) を考え、

\[
\mathscr R^{\rm ret}:=DF|_{x_*}
\]

が有界であるとする。次の二つの実現を取る。

1. 内部実現：\(x^+=F(x)\)。
2. 外部 oracle 実現：装置内部の更新は \(x^+=u\) だけであり、外部入力が毎周期 \(u=F(x)\) を書き込む。

両者の観測 return map は同じ \(F\) である。従って map-level の全入出力不変量は一致する。さらに同じ接空間 split bridge を用いれば、線形化 return operator \(DF|_{x_*}\)、そのスペクトル、resolvent、\(\Sigma_{\rm br}^{\rm self}\)、\(\chi_{\rm SR}\) も一致し得る。しかし第一は内部閉路、第二は外部 template の逐次コピーである。

従って、return operator のみの任意の汎関数 \(\mathfrak F(\mathscr R^{\rm ret})\) は、内生的自己生成と外部再生を一般には識別できない。

**証明。** 二つの実現は同じ \(C^1\) 入出力写像 \(F\) を持つため、その写像と導関数だけから構成される全不変量が一致する。一方、外部入力を \(0\) にする介入を行えば第二実現だけが \(F\) を失う。従って識別には作用素外の因果境界情報が必要である。\(\square\)

**帰結.** 自己再生の正典条件はスペクトル関数一つでは完結しない。\(\chi_{\rm SR}\) は再入機構と頑健性の検出器であり、外部 template なしの因果閉包と joint turnover 後の内生復元は A14 および§21.18 の独立条件である。

# 6. IDS 粗視化原理

IDS の最も重要な原理は、粗視化で何が残るかを決める原理である。

## 6.1 原理の主張

\[
\boxed{
\text{粗視化で保存されるのは、生の情報量でもスカラー・ストレスでもなく、非可積分残差類である。}
}
\]

すなわち、

\[
\omega
\longmapsto
[\omega]
\in C^1/\operatorname{im}d_0.
\]

## 6.2 なぜスカラー値ではないか

同じノルム値

\[
\|\mathfrak r(\omega)\|^2
\]

を持つ二つの残差が、全く異なるホモロジー構造・循環構造・境界応答を持つことがある。したがって、スカラーは測定値であって本体ではない。

## 6.3 許容粗視化と消去的粗視化

### 許容粗視化

\[
\Phi(\operatorname{im}d_0)
\subseteq
\operatorname{im}d_0.
\]

これは残差類を正しく輸送する。

### 消去的粗視化

隠れ自由度を積分消去する。一般に

\[
\Phi(\operatorname{im}d_0)
\not\subseteq
\operatorname{im}d_0.
\]

このとき、微視的に exact だったものが、粗視化後に residual になる。

\[
\mathfrak A_\Phi\ne0.
\]

このアノマリーが自己組織化の源である。

## 6.4 粗視化とデバッグ

デバッグは、単に局所誤差を消すことではない。粗視化レベルを変更し、どの残差が構造として残るかを再選別する操作である。

\[
\text{Debug}
=
\text{change of residual class under controlled coarse-graining.}
\]

---

# 7. 因果構造とストレス・デバッグ

## 7.1 因果を矢印グラフに還元しない

IDS の因果構造は、まず無向影響骨格 \(K\) として現れる。

\[
K=
\text{どの自由度が互いに制約し得るか}.
\]

矢 \(\eta\) は追加構造である。

\[
\eta=
\text{影響がどちらへ流れるか、どの循環が不可逆に見えるか}.
\]

したがって、

\[
\text{causality}
\ne
\text{directed acyclic graph only}.
\]

## 7.2 \((K,\eta)\sim(L,J)\)

可換 IDS 層では、

\[
K\leftrightarrow L=\delta_1d_1.
\]

\(L\) は自己共役散逸作用素であり、どの残差がどの残差を制約するかを表す。

向き場は

\[
\eta\leftrightarrow J.
\]

\(J\) は \(S\)-skew または強許容な保存生成子である。

## 7.3 三段階の矢

### Level 0：矢なし

\[
J=0,
\qquad
M=L.
\]

純散逸。適切な計量で勾配流として読める。

### Level 1：計量相対的な矢

\[
J\ne0,
\]

だが \(M=L-J\) が実対角化可能で、ある計量では自己共役化できる。矢は表現依存である。

### Level 2：内在的な矢

スペクトルが非実、または Jordan ブロックを持ち、どの実内積でも自己共役化できない。矢はスペクトル不変量として刻まれる。

## 7.4 因果デバッグ方程式

統合形は、

\[
\boxed{
\dot\rho=-L\rho+J\rho+a.
}
\]

- \(-L\rho\)：散逸デバッグ。
- \(J\rho\)：保存的循環、向き、回転、transport。
- \(a\)：粗視化アノマリー、外部強制、未解決情報注入。

**注（v1.6）.** 残差が担体として外部化され、系間・階層間で再符号化される動的循環（残差放射・担体化・再符号化原理）は §21 を参照。

## 7.5 因果レジリエンス原理

\[
\boxed{
\text{系がレジリエントであるとは、非可積分残差類が因果骨格 }K
\text{ と向き場 }\eta
\text{ の下で安定な粗視化互換アトラクタを持つことである。}
}
\]

数式では、

\[
0=-L\rho^\ast+J\rho^\ast+a,
\qquad
\Phi_\ast[\rho^\ast]=[\rho^\ast],
\qquad
\lambda^+_{\min}(L)>0.
\]

---

# 8. レジリエンスの五類型

## 8.1 Type I：位相的レジリエンス

\[
\rho^\ast=h\in H^1(X).
\]

これは閉じているが exact ではない残差である。

\[
d_1h=0,
\qquad
h\notin\operatorname{im}d_0.
\]

純散逸では消えない。

## 8.2 Type II：非平衡レジリエンス

\[
\rho^\ast=L^+a.
\]

これはアノマリー注入と散逸の釣り合いで維持される。生命、社会、経済、乱流的秩序に近い。

## 8.2A Type III：系譜的レジリエンス

\[
\mathcal T_{\mathrm{III}}
=\bar H^1\ominus H^1
\]

は、fine の減衰モードが coarse の調和モードへ昇格した構造である。現在の coarse scale では Type I として保護されるが、その生成履歴が粗視化依存である。制約忘却型は定理25、圧縮型は定理26で扱う。


## 8.3 Spectral resilience

\[
\Delta_{\rm res}=\lambda^+_{\min}(L)>0.
\]

ギャップがあれば摂動から戻る速度がある。

## 8.4 Hypocoercive resilience

直接散逸がない方向でも、向き場 \(\Omega\) が散逸方向へ回転させれば回復が起こる。

\[
A=D+\Omega.
\]

\[
\operatorname{span}
\{D^{1/2},\Omega D^{1/2},\Omega^2D^{1/2},\dots\}
=\text{全空間}.
\]

これは「壊れた情報を、直せる経路へ回す」能力である。

---

# 9. mass gap の IDS 的再定式化

## 9.1 最小定義

IDS における mass gap の最小形は、残差 Laplacian の正スペクトル下限である。

\[
\boxed{
\Delta_{\rm IDS}
=
\inf\operatorname{Spec}^+(\delta_1d_1).
}
\]

\(\Delta_{\rm IDS}>0\) は、非ゼロ残差励起がゼロモードから分離されることを意味する。

## 9.2 レジリエンスとの同一性

\[
\boxed{
\text{mass gap}
=
\text{resilience gap}
=
\text{nonzero recovery rate of residual structure.}
}
\]

ただし、これは IDS 可換残差層における定義であり、Yang–Mills mass gap の直接証明ではない。

## 9.3 HFE/DHT branch

HFE 型の階層場

\[
M D_t\Lambda+R[\Lambda]
=
\nabla\cdot(T\nabla\Lambda)-\frac{\delta V}{\delta\Lambda}
\]

に対し、階層固有モード展開

\[
\Lambda(x,t,n)=\sum_k A_k(x,t)\Psi_k(n)
\]

を行うと、長時間で遅いモードが支配する。DHT の \(N=2\) はこの遅い支配モード数として解釈される。

この枝では、

\[
\Delta_{\rm HFE}=\lambda_2-\lambda_1
\]

または \(\lambda_{\min}^+\) が mass gap 的対象になる。

## 9.4 Yang–Mills への正しい距離

現在の可換残差理論は

\[
S(\rho)=\frac12\|d\rho\|^2
\]

であり、非線形 \(\rho\wedge\rho\) は入らない。Yang–Mills へ進むには、

1. 残差類をゲージ軌道へ置き換える。
2. 接続 \(A\) と曲率 \(F_A=dA+A\wedge A\) を導入する。
3. 平坦接続モジュライ近傍で可換理論を接空間として回収する。
4. 共変 Laplacian \(\Delta_A\) の正スペクトル下限を研究する。
5. 量子化後の真空スペクトル分離を証明する。

したがって、正典的には、

\[
\boxed{
\text{IDS は Yang–Mills mass gap を「解いた」のではなく、mass gap を残差構造のレジリエンスギャップとして再定式化する。}
}
\]

---

# 10. IDS ホログラフィーの正典形

IDS ホログラフィーを、単なる「bulk 情報の coarse boundary residual」または粗視化欠陥そのものとは定義しない。正典形は次の三条件である。

\[
\boxed{
\text{global intertwining}
+
\text{subregion nonclosure}
+
\text{recoverability}
}
\]

## 10.1 Global intertwining

bulk code sector から boundary 表現への符号化を

\[
V:\mathcal H_{\rm bulk}^{\rm code}\to\mathcal H_\partial
\]

とする。完全な大域符号化では

\[
\boxed{U_\partial(t)V=VU_{\rm bulk}(t)}
\]

であり、dynamic defect は

\[
R_V(t)=VU_{\rm bulk}(t)-U_\partial(t)V=0
\]

である。従って、非可換性欠陥それ自体をホログラフィーと呼ばない。

## 10.2 Subregion nonclosure

境界部分領域 \(A\) への制限を \(\Pi_A\) とすると、一般に

\[
R_{\Pi_A}(t)
=
\Pi_AU_\partial(t)-U_A(t)\Pi_A
\ne0
\]

となり得る。これは局所領域が大域論理情報に対して力学的に閉じていないことを測る。

## 10.3 Recoverability

部分領域データから code sector を復元できるため、decoder \(D_A\) が

\[
\boxed{D_A\Pi_AV=I_{\rm code}}
\]

を満たすことを要求する。近似版では適切な operator / channel norm で誤差を評価する。

有限線形圧縮では定理26の \(\Gamma_K^+\) が標準 decoder を与える。

## 10.4 Holographic Type III

fine Type II から coarse Type I への昇格だけでは、単なる情報破壊と区別できない。圧縮型で

\[
X\subseteq\operatorname{Range}L,
\qquad
KX\subseteq\ker\bar L,
\qquad
\exists D:\ DK|_X=I_X
\]

が成立するとき、その recoverable promotion を **holographic Type III** と呼べる。制約忘却型 \(K=I\) では復元は自明であり、非自明な量子誤り訂正型符号化ではない。

## 10.5 境界

IDS ホログラフィーは AdS/CFT の導出ではない。また boundary を「情報量の少ない粗い bulk」と同一視しない。正典が主張するのは、**局所的に不可視となった構造が、大域符号化と復元可能性によって保存され得る**という抽象原理である。

# 11. Causal-Hodge Bridge

## 11.1 目的

Causal-Hodge Bridge は、非可積分 Hodge 残差を物理的観測量へ写すための追加ブリッジである。

銀河スケールでは、

\[
a_{\rm obs}(r)=a_{\rm bar}(r)+a_I\mathcal B_r[\hat{\mathfrak r}_G](r).
\]

ここで、

\[
a_I=\frac{c_I}{\tau_I}=\frac{c_I^2}{L_I}.
\]

## 11.2 IDS 側の流れ

情報幾何応答を

\[
J_G=-M_{\rm eff}\nabla\mathcal S
\]

とし、Hodge 分解

\[
J_G=d\phi+\delta\psi+h
\]

を行う。

非可積分 IDS 残差は、

\[
\mathfrak r_G=(I-P_{\rm grad})J_G=\delta\psi+h.
\]

## 11.3 Equal-Stress Closure

低加速度領域で、可積分な baryonic stress と非可積分 residual stress が釣り合うと仮定する。

\[
E_{\rm bar}\sim x_b,
\qquad
E_{\rm res}\sim R^2.
\]

Equal-stress より、

\[
R^2\sim x_b,
\qquad
R\sim\sqrt{x_b}.
\]

従って RAR/BTFR 型のスケーリングが得られる。

## 11.4 実証状態

既存ノートでは、SPARC での Hodge topology test、per-galaxy \(a_I\) correction、SWELLS cross-domain test が記録されている。正典的な扱いは次である。

- スカラー RAR 形は有望。
- 非可積分 closure residual の兆候はあるが、5σ discovery ではない。
- universal \(a_I\) は単純には成立せず、\(a_I=c_I^2/L_I\) の \(L_I\) 側が galaxy-dependent とみる方が自然。
- lensing-dynamics consistency \(\Sigma=1\) は高レバレッジ falsification route。

---

# 12. 非可換 IDS：到達状態と開放境界

§18 のゲージ情報幾何は器を与え、外部監査済み非可換正典系列は有限・flat 層の具体化を与える。ここでは「研究計画」だけでなく、到達済み部分と未到達部分を分離する。

## 12.1 有限 flat 層【到達済み】

有限 oriented 2-complex、compact group \(G\)、flat connection \(A\) に対し、vertex gauge 変形と face-flatness の線形化

\[
C^0(\operatorname{ad}A)
\xrightarrow{D_A^0}
C^1(\operatorname{ad}A)
\xrightarrow{D_A^1}
C^2(\operatorname{ad}A),
\qquad
D_A^1D_A^0=0
\]

が成立する。

\[
H^1(X;\operatorname{ad}A)
=
\ker D_A^1/\operatorname{im}D_A^0
\]

は coarse moduli space の通常の接空間ではなく、**ゲージ商スタックの無限小変形空間**である。coarse moduli の局所 germ は

\[
\boxed{\kappa_A^{-1}(0)/\operatorname{Stab}(A)}
\]

で記述される。可約点では stabilizer quotient により物理錐が折り畳まれ、cohomology 次元の増加は物理自由度の増加を意味しない。

## 12.2 Twisted Type III【到達済み】

flat \(A\) を固定して face constraint を忘却すると、定理25を \(D_A^0,D_A^1\) に適用できる。

\[
\boxed{
\mathcal T_{\mathrm{III}}^{\operatorname{ad}}(A)
=
\bar H_A^1\ominus H_A^1
=
\operatorname{im}(D_A^1)^*\cap\ker\bar D_A^1.
}
\]

階数公式・直交分解・半群射影極限も同文で成立する。物理的 promotion object は stabilizer で割った層別錐であり、障害つき点では Kuranishi 方程式が切る相対 germ となる。

## 12.3 非平坦有限層【部分到達】

face holonomy \(Q_f(A)\) の微分について

\[
\mathcal D_A^1D_A^0\phi
=
(I-\operatorname{Ad}_{Q_f(A)})\phi_{b(f)}
\]

が成立し、flat 極限で複体を回復する。全次数の gauge coherence は有限 lattice gauge groupoid の BRST 微分 \(s^2=0\) で表される。従って非平坦層を通常の cohomology と呼ばず、curved / BRST / observable-algebra 層として扱う。

bounded observable dynamics では generator defect と Duhamel identity、定常欠陥、center-Fourier selection rule が有限模型で閉じている。

## 12.4 連続・相互作用層【限定到達】

到達済みなのは、

- Whitney／FEEC による continuum flat/free Hodge 層、
- fixed flat local system、
- 二次元 heat-kernel Yang–Mills の exact projective family、
- \(d\ge3\) の局所 branching defect calculus、
- intrinsic-volume と small-field counterterm の条件付き評価、

である（§20）。

未到達なのは、

- 四次元 renormalized block family の全スケール一様構成、
- 非平坦連続 BRST/BV と Gribov 大域幾何、
- reflection-positive continuum transfer system、
- 物理的 full vacuum-complement gap、

である。

## 12.5 有限 task–gauge 正則層【到達済み】

物理ゲージ作用に対して行動写像が不変で、\(D\mathcal B\) が一定 rank を持つ正則層では、制御-null bundle、ゲージ共変射影 \(P_{\rm ctrl}\)、task–coarse promotion／erasure defect、および誘導 task–gauge connection が定義できる（定理31–34）。

\[
\Theta\longrightarrow[\Theta/\mathcal G]
\longrightarrow Q_{\rm ctrl}^{\rm phys}
\]

が正しい商の順序であり、\(Q_{\rm ctrl}\) は gauge fixing ではない。rank-change、非不変 task、動的 task、大域非線形降下は OP-TG1–4 に残る。

## 12.6 正典的境界

\[
\boxed{
\text{有限 flat 非可換 IDS と有限正則 task–gauge 層は局所定理層として成立する。}
}
\]

\[
\boxed{
\text{四次元量子 Yang--Mills、特異 task quotient、完全な非平坦連続 IDS は未解決である。}
}
\]

# 13. 未来と過去の相互作用

## 13.1 問題設定

IDS の時間論で重要なのは、「未来が過去へ物理信号を送る」という意味の逆因果ではない。重要なのは、**現在のデバッグ経路が、過去の記憶と未来の制約の双方から決まる**ということである。

## 13.2 過去の形

過去は、以下として現在に残る。

1. 調和残差 \(h\in H^1\)。
2. 消去済み自由度の記憶項 \(a(t)\)。
3. 観測者分布 \(\mu_t\) の履歴。
4. 潜在重み \(u_t\) の蓄積。
5. 境界ログ。

## 13.3 未来の形

未来は、以下として現在を制約する。

1. 終端条件。
2. 目標関数。
3. 予測誤差の期待値。
4. 未観測だが後で観測されるデータ。
5. 社会的・倫理的・設計上の望ましい fixed point。

## 13.4 forward-backward smoothing としての未来

確率過程では、全観測 \(y_{0:T}\) を用いた平滑化分布は

\[
p(x_t\mid y_{0:T})
\propto
\alpha_t(x_t)\beta_t(x_t),
\]

ここで、

\[
\alpha_t=p(x_t\mid y_{0:t}),
\qquad
\beta_t=p(y_{t+1:T}\mid x_t).
\]

\(\beta_t\) は未来観測から来る。これは物理的逆因果ではなく、推論における二方向制約である。

IDS のデバッグも同様に、過去履歴と未来目標の双方から現在の \(\rho_t\) を再評価する。

## 13.5 創造的過去改変

過去の事実を変えるのではない。過去の残差類の意味づけを変える。

\[
[\omega_{\rm past}]_{X,g}
\longrightarrow
[\omega_{\rm past}]_{X',g'}.
\]

粗視化や観測計量が変わると、同じ履歴が別の残差構造として再表現される。心理的統合、科学革命、社会制度改革、AI の自己修正ログはこの形式を持つ。

## 13.6 未来が現在をデバッグする

設計目標 \(\Phi_1(\rho(t_1))\) があると、現在の最適デバッグ経路はそれに合わせて変わる。

\[
\rho_{\rm debug}
=
\arg\min
\left(
\text{past inconsistency}
+
\text{future incompatibility}
+
\text{debug cost}
\right).
\]

この意味で、未来は現在を「デバッグ」する。ただし物理的信号ではなく、境界条件・予測・選択圧である。

## 13.7 時間の矢と creative oblivion

完全記憶は可逆であり、マクロな時間の矢を作らない。粗視化により情報が消えるから、エントロピー勾配と時間方向が生まれる。

\[
\text{Arrow of time}
=
\text{arrow of coarse-grained irreversibility}.
\]

IDS では、忘却は単なる欠損ではなく、構造生成の条件である。

---

# 14. 概念的広がり

## 14.1 AI と自己デバッグ

LLM や自律 AI における IDS は、次のように読める。

- 予測誤差：出力と世界・文脈のズレ。
- 規範誤差：出力と安全性・正確性・有用性のズレ。
- CIE：重大情報イベント、デバッグ起動点。
- LocalDOC：局所残差を扱うデバッグ作用素。
- TDNG：時間依存規範生成。
- self_debug_session：履歴を読み、残差パターンを再編成するプロセス。

IDS 的 AI は、単に誤答を減らす機械ではない。残差類を観測し、粗視化し、再符号化し、次の応答構造を更新する自己デバッグ系である。

## 14.2 心理と身体

心理的ストレスは、現在の自己モデルで勾配化できない経験残差として現れる。

- トラウマ：\(H^1\) 的に閉じたが exact でない記憶循環。
- 反復行動：同じ residual class の再励起。
- 身体症状：内部残差の境界表示。
- 統合：粗視化・言語化・身体化による残差再表現。

## 14.3 社会と制度

社会的ストレスは、制度が勾配化できない残差として現れる。

- 制度バグ：局所最適では消えない非可積分摩擦。
- 炎上：境界ログ上の residual spike。
- 革命：粗視化座標系の変更。
- レジリエント民主主義：残差を抑圧せず、可視化して安定な共固定点へ導く制度。

## 14.4 生命

生命は Type II 構造の典型である。

\[
\rho^\ast=L^+a.
\]

外部流束が止まれば構造は崩れる。しかし流束がある限り、散逸と再注入の釣り合いで秩序が維持される。

## 14.5 宇宙論

宇宙論的 IDS は、情報喪失・Green–Kubo 応答・粘性・負圧・DHT・HFE を通じて、暗黒エネルギー的・暗黒物質的成分を再解釈する。

ただし、これは強い物理ブリッジを含むため、Core IDS とは分離する必要がある。

## 14.6 アルゴリズム IDS

IDS Final Theory v3.0 系では、Hodge-QFT, spectral folding, phase-preserving dynamics が扱われる。

ここでの IDS は、残差・位相・階層折り畳みを用いた探索・周期検出の計算論的応用である。これは数学的に刺激的だが、暗号学的脅威などは主張しないのが正典的に安全である。

---

# 15. 仮説群

## H1. 一般アトラクタ仮説

任意の有限観測複体族と、適切な観測者更新 \(\mu_t\) に対して、消去的アノマリーが persistent で range condition を満たすなら、非ゼロ共固定点が存在する。

## H2. Holographic residual reconstruction 仮説

大域符号化が力学を intertwine し、境界部分領域が非閉であっても、指定された code sector が decoder により復元可能となる条件が存在する。単なる境界残差の非零性や dynamic defect の非零性は十分条件ではない（§10、OP-4）。

## H3. Causal-resilience universality 仮説

生命・社会・AI・物理系におけるレジリエンスは、Type I/II/III/hypocoercive の組合せで分類できる（Type III は §4.5、v1.6.1 で定義）。

## H4. Noncommutative IDS linearization — 有限 flat 層は定理、連続層は仮説

有限 2-complex の flat connection では、ゲージ変形複体 \(D_A^0,D_A^1\) と twisted Hodge 分解が可換 IDS を接空間として回収することは到達済みである。無限次元・連続・非平坦・量子層への延長を H4 の未解決部分とする。

## H5. Future-past debug principle 仮説

高度な知能・科学・社会制度は、過去履歴だけでなく未来境界条件を内部化した二境界デバッグ系としてモデル化できる。

## H6. Physical bridge amplitude law 仮説

Causal-Hodge Bridge の振幅

\[
a_I=\frac{c_I^2}{L_I}
\]

において、\(c_I\) は普遍的または弱変動し、\(L_I\) が系固有の情報相関長として変動する。

## H7. スキーム接続仮説

粗視化スキーム（有効記述の座標・くりこみ条件）の局所族が階層束の局所自明化と遷移関数を与え、スキーム変更はゲージ変換として作用する。さらに**スキームの微小変化に対する比較規則（水平分布・平行輸送規則）**を指定することで、スケール束上の接続 \(A\) が誘導される。スキーム非依存量はゲージ不変量であり、IDS 残差の非自明性は、どのスキーム選択でも消去できない比較規則の曲率である（§18.4）。

## H8. 共変局所複素構造束仮説

物理的に有効な非可換 IDS の保存セクターには、rank が一定で非零スペクトルがゼロから分離された領域上で、\(G\)-skew 保存生成子 \(J\) を正規化した局所複素構造

\[
\mathbb I=J(-J^2)^{-1/2}
\]

の束が存在し得る。その接続非両立

\[
\Xi_A:=D_A\mathbb I
\]

および閉路欠陥 \(\Xi_\gamma\) は、保存回転構造がスケール間輸送で保持されないことを表す gauge-covariant obstruction であり、arrow detector \(M_A\)・担体輸送・粗視化欠陥へ結合し得る。

---

# 16. 未解決問題

**番号対応の注意.** 本書の OP 番号は正典独自であり、粗視化ノート（coarse_graining_and_causal_structure_public_v1）の OP 番号とは一致しない。対応：本書 OP-1 ↔ 同 OP-1、本書 OP-2 ↔ 同 OP-4、本書 OP-5 ↔ 同 OP-5。同ノート固有の未解決問題（強許容 J の連続極限・符号数の定理化・創発時空）は OP-10〜OP-12 として本書に継承する。

## OP-1. 非可換化 — 有限局所層の閉包と連続量子層

**部分閉包。** 有限 flat 2-complex では、ゲージ軌道の線形化、stack tangent \(H^1(X;\operatorname{ad}A)\)、Kuranishi / stabilizer 局所形、twisted Type III、有限圧縮 promotion、非平坦 curved identity、BRST coherence、bounded observable defect まで到達した（§12、定理25–26、資料台帳10）。

**残件。**

1. 非平坦 continuum BRST/BV と gauge-orbit strata の大域構成。
2. Gribov 問題を含む smooth generalized-connection measure。
3. unbounded interacting generator と quantum-channel promotion。
4. reflection-positive 4D continuum family と full physical gap。

従って OP-1 は「非可換化そのもの」ではなく、**finite local theorem package を continuum interacting quantum theoryへ一様に持ち上げる問題**として更新する。

## OP-2. 一般アトラクタ存在

\(M\succeq0\) を含む一般化散逸

\[
\dot\rho=-M\delta d\rho+a
\]

において、range condition と spectral gap をどの条件で保証できるか。

## OP-3. Metric-independent curl characterization

curl 成分は計量依存である。どの部分が観測者変更に対して構造的に残るかを、計量非依存に特徴づけよ。

## OP-4. IDS holographic theorem

次の三条件を統一定理化せよ。

\[
\boxed{
\text{global intertwining}
+
\text{subregion nonclosure}
+
\text{recoverability}
}
\]

単なる \(R_{\Pi_A}\ne0\) をホログラフィーの十分条件としてはならない。cochain complex、operator algebra、sheaf、quantum error-correcting code の間で、どの code sector がどの boundary subregion から復元可能かを特徴づける。有限線形雛形は定理26で閉じている。

## OP-5. Hypocoercive non-perturbative bound

\(\Omega\) が弱くなる極限で Gramian が発散しないための追加構造を見つけよ。または発散が普遍であることを証明せよ。

## OP-6. Mass gap bridge

可換 IDS の resilience gap を、非可換 Yang–Mills 型質量ギャップへ橋渡しする厳密な量子化手順を与えよ。

## OP-7. Causal-Hodge empirical confirmation

SPARC/BIG-SPARC、SWELLS、Euclid/LSST を用い、closure residual non-integrability と \(\Sigma=1\) を検証せよ。

## OP-8. Future-past debug formalism

二境界最適化、Bayesian smoothing、active inference、制御理論を統合し、未来制約が現在のデバッグをどう選別するかを形式化せよ。

## OP-9. IDS ethics

社会や AI において、どの残差を消してよく、どの残差を保存・翻訳すべきかを定式化せよ。

## OP-10. 強許容 \(J\) の連続極限

有限複体上の強許容分類（定理 15）が、無限セル複体・連続極限で存続するかを確立せよ。一般化散逸 \(M\succeq0\) への拡張と計量選択の共変性を含む。

## OP-11. 符号数の定理化（2-平面共通因子問題）

反対称カレント \(Q\) が向けるのは軸ではなく 2-平面束である。系のすべてのカレント 2-平面が共通の 1 次元因子を持つとき、かつそのときに限り単一の時間軸が選ばれ、有効計量の符号数が \((1,d-1)\) 型となることを定理化せよ。

## OP-12. 創発時空

前与の基底多様体なしに、粗視化のみから大域因果構造 \(K\) の共形幾何（Lorentz 多様体）を創発させる数学的定式化を与えよ。

## OP-13. K–A 両立条件とスキーム接続の構成

不可逆粗視化族 \(K\) から比較接続 \(A\) を構成する正準手続きを与え、接続曲率 \(F_A\)・粗視化交換子 \(K_sK_t-K_tK_s\)・gauge-fixed residual sector の三候補（§18.5）が一致するための両立条件（G5）を定理化せよ。最小の入口は §18.10 Step 1（chain defect \(A_K\) と dynamic defect \(R_K\) の可換計算）である。**進捗（v1.6.3）：** 両欠陥の型安全な整合恒等式は定理24として閉じた。残る本体は、不可逆 \(K\) から接続 \(A\) を構成し、これらの欠陥を曲率へ同定する橋である。なお H7 の精密化（v1.3）により、構成すべきは局所自明化だけでなく**微小スキーム変化の平行輸送規則**である。（§19 の追補 OP-H2 と同一問題として統合。）

## OP-14. コチェイン層と確率束の接合

証明済み核の舞台 \(C^\bullet(X)\) と、§18 の確率分布階層束 \(\mathcal P_b\) の間の関手的対応（辺フロー＝スコア差・対数尤度勾配の実現）を明示し、可換層の定理群を束の言葉へ翻訳せよ。

## OP-CX1：局所複素構造束の正則性と特異点

非零スペクトル部分束上の

\[
\mathbb I=J(-J^2)^{-1/2}
\]

が滑らかに定義されるための constant-rank 条件・一様スペクトル分離・連続極限を確立し、固有値がゼロを横切る rank-change 点における回転構造の特異性を分類せよ。

## OP-CX2：複素構造輸送欠陥の障害理論

\[
\Xi_A=D_A\mathbb I,
\qquad
\Xi_\gamma=
\operatorname{Hol}_A(\gamma)\mathbb I_x
\operatorname{Hol}_A(\gamma)^{-1}-\mathbb I_x
\]

を gauge-covariant な障害類へ降下させ、\([F_A,\mathbb I]\)、arrow detector \(M_A\)、chain／dynamic／emission／reception defects、および物理的担体輸送との関係を定理化せよ。

以下は §19（追補統合）由来の未解決問題である（名前空間つき番号）。


## OP-TG1：task–gauge 特異層と rank change

\(\operatorname{rank}D\mathcal B\) が変化する点で \(P_{\rm ctrl}\) は滑らかな束射影でなくなる。orbit-type stratification、quotient stack、normal cone を用いて定理32–34を層別に拡張し、曲率の分布的・錐的極限を分類せよ。

## OP-TG2：非不変／同変 task

\(\mathcal B(\gamma\theta)=\mathcal B(\theta)\) ではなく、出力ゲージ群 \(\mathcal H\) に対する

\[
\mathcal B(\gamma\theta)=\rho(\gamma)\mathcal B(\theta)
\]

しか持たない場合、stack map \([\Theta/\mathcal G]\to[\mathcal Y/\mathcal H]\) の fiber quotient として制御商を定義し、識別可能性と安全予算を共変化せよ。

## OP-TG3：動的 task と時間依存射影

\(P_{\rm ctrl}(t,\theta,\pi)\) が状態・時刻・政策に依存するとき、\(D_tP_{\rm ctrl}\) が安全予算、hypocoercivity、Type III promotion、誘導曲率へ与える追加項を定理化せよ。

## OP-TG4：大域非線形 task–coarse 降下

定理33は正則接空間の微分条件である。非線形粗視化 \(K:\Theta_f\to\Theta_c\) が

\[
\theta\sim_{{\rm ctrl},f}\theta'
\Longrightarrow
K\theta\sim_{{\rm ctrl},c}K\theta'
\]

を満たし、大域制御商写像を誘導するための必要十分条件、特異層を含む functoriality、復元可能性を定理化せよ。

## OP-SC1：自己粗視化の十分統計 — 集合論的商は部分閉包

定理27により、指定された許容介入族とレジリエンス指標を保存する最も粗い行動十分商

\[
Q_{\rm ctrl}=\Theta/\!\sim_{\rm ctrl}
\]

は集合論的・普遍的対象として閉じた。

残る問題は、

1. \(Q_{\rm ctrl}\) が有限次元・可測・滑らか・計算可能な表現を持つ条件、
2. 有限標本からの推定可能性、
3. 介入集合 \(\mathcal U\) の変更に対する安定性、
4. 反例保存チャネルを含む最小符号化、

である。

## OP-SC2：自己粗視化の停止条件

\[
\theta_{t+1}=\mathcal U(\theta_t,\cdots)
\]

が安定固定点、周期、無限後退、自己参照発散のいずれになるかを分類せよ。

## OP-CS1：SAT 粗視化の witness lifting

どの制約クラスで、存在保存と多項式 witness 復元が同時に成立するか。

## OP-CS2：計算資源保存則

物理緩和が探索時間を短縮するとき、空間、精度、エネルギー、初期化、読み出しへ計算量が移送されていないかを定理化せよ。

## OP-H1：階層 associator のコホモロジー

\[
\Omega_{\ell,L,M}
\]

を 2-cocycle または higher-category associator として定式化し、その自明性条件を与えよ。

## OP-H2：粗視化接続（OP-13 へ統合）

本問題は OP-13（K–A 両立条件とスキーム接続の構成）と同一であり、OP-13 に統合する。

## OP-GS1：障害空間 — task-relative 部分商は部分閉包

全物理的障害空間

\[
\mathfrak O_{\mathcal R}=\mathcal Z_{\mathcal R}/\mathcal N_{\mathcal R}
\]

の対象・位相・ノルム・共変性は未解決である。

一方、指定された未来応答と安全指標に関して null な差を落とす task-relative quotient \(Q_{\rm ctrl}\) は定理27で厳密化された。これは \(\mathfrak O_{\mathcal R}\) 全体の解ではなく、**制御目的に対する可観測商**である。両者を結ぶ関手と、task family を増やした極限が full obstruction space を回収する条件を求める。

## OP-GS2：障害・持続・結合の独立性

三条件が互いに独立である最小反例と、同時成立の十分条件を構成せよ。

## OP-MG0：uniform multiscale control — 条件付きパッケージと実模型停止線の分離

二つの資料を混同しない。

### (A) 条件付き MG0-cond パッケージ

`OP_MG0_COMPLETE_SOLUTION.md` は、界面仮説 H-B2b+(β) と整合条件 (P1)–(P5) の下で、適応政策 \(\pi\) が五条件 C1–C5 を同時に閉じるという条件付き主定理を提示する。政策は

- \(\pi\)-R1：RP cone 内の counterterm 操作、
- \(\pi\)-R2：KP / large-field 閾値、
- \(\pi\)-R3：bootstrap 領域離脱時の停止、
- \(\pi\)-R4：反射対称 blocking、

からなる。

H-Δ

\[
|\langle r_xr_y\rangle|
\le C(1+|x-y|)^{-2\Delta},
\qquad \Delta>2
\]

は四次元 Schur 可和性を与える解析的界面である。この閾値計算自体は定理28の full-sector 特殊化として凍結する。

### (B) 実在 Wilson–SU(2) 証明鎖

`SU2_mass_gap_project_reconstruction_2026-07-12.md` では、fixed-window の G2''、E1*、STEP-PINCER、さらに

\[
\mathrm{UV\!-\!ITER}
=
\mathrm{CLASS\!-\!STAB}\wedge\mathrm{GATE\!-\!UNIF},
\qquad
\mathrm{OS\!-\!REST}
\]

が未閉である。

### 正典判定

1. \(\pi\)-R1–R4 は設計規則として採用する。
2. H-Δ は Schur 可和性の十分条件として採用する。
3. MG0-cond は明示された全仮定の下での**条件付き theorem schema**として扱う。
4. H-Δ 単独と 4D Yang–Mills existence / mass gap の同値は主張しない。
5. 実模型の停止線 G2''／UV-ITER／OS-REST は OPEN のまま維持する。
6. 定理27–30の制御診断 \((\beta_n,S_n^{\rm ctrl},\mathfrak E_n)\) を \(\pi\)-R3 の bootstrap 領域へ追加できる。

## OP-MG1：No-Fake-Gap 定理

どの粗視化族が、物理的 mass gap を人工的に生成しないかを定理化せよ。

## OP-MG2：center sector bridge

center twist / vortex free energy の一様下界から、局所ゲージ不変相関の指数減衰へ至る厳密な橋を構成せよ。

## OP-GR1：共変平均とホロノミー

異点テンソルの平行移動・平均化における経路依存を、粗視化障害類へ落とす定理を構成せよ。

## OP-GR2：暗黒重力射影

\[
T_{\mu\nu}^{\rm geom}
=
\Pi_{\rm grav}[\Sigma_{\mathcal R}]
\]

を導出し、保存則・エネルギー条件・lensing・局所極限を同時に満たすか検証せよ。

以下は §21（担体化統合）由来の未解決問題である。

## OP-RE1 — 放出可能性の必要十分条件

どの残差類が輸送セクターへ結合するか。

商への降下が成立した放出演算子 \(\mathcal E:R^1\to\Psi\) に対して、

\[
\ker\mathcal E
\]

と位相残差、拘束残差、調和残差の関係を分類する。降下前は、代表元上の候補写像 \(\widetilde{\mathcal E}\) とそのゲージ不変核を扱う。

---

## OP-RE2 — 担体化と代表元独立性 — 有限可換線形層は閉包

**v1.8.0 部分閉包.** 有限次元、または \(\operatorname{im}d_0\) が閉な Banach／Hilbert 線形層では、定理35により

\[
\widetilde{\mathcal E}(r+d_0\phi)
=
\widetilde{\mathcal E}(r)
\quad\Longleftrightarrow\quad
\widetilde{\mathcal E}d_0=0
\]

が商降下の必要十分条件である。split decoder が存在する場合、定理36により同じ残差商へ戻る完全 bridge-hidden Feshbach 還元まで閉じる。

**未閉部分.** 非線形放出写像の大域降下、非閉 range、非平坦非可換ゲージ軌道／stack、特異 task 層、物理的 emission map が上の条件を満たすための力学的必要十分条件は未解決である。標準切断 \(s_R\) による実現は計量相対的構成であり、物理写像自身の自然性を自動的には証明しない。

---

## OP-RE3 — 波動型保存性の分類

どの作用素系が、

\[
\mathbb K^{*}=-\mathbb K,
\qquad
\mathbb K^2=-\Delta_{\mathrm{eff}}
\]

を満たし、有限伝播速度を持つか分類する。

---

## OP-RE4 — 総合収支則

残差、担体、環境、散逸、幾何更新を含む拡張汎関数

\[
\mathcal H_{\mathrm{total}}
\]

を構成し、その単調性または保存性を調べる。

---

## OP-RE5 — 残差カスケードの非線形臨界

線形利得 \(\operatorname{spr}(T)\) を超えて、

- saturation
- hysteresis
- phase transition
- self-organized criticality
- geometry feedback

を含む非線形臨界条件を求める。

---

## OP-RE6 — スケール間担体変換

微視的担体群が、どの条件で一つの巨視的担体へ統合されるか。

\[
\{\psi_\alpha^{\mathrm{micro}}\}
\longrightarrow
\psi^{\mathrm{macro}}
\]

の普遍則を求める。

---

## OP-RE7 — 因果源逆推定 — 制御商上の安定性は部分閉包

受信側応答から源残差と伝播作用素を同時推定する完全問題は未解決である。

ただし、推定対象を \(Q_{\rm ctrl}\) へ縮約し、観測写像 \(F_n\) が下側 Lipschitz 定数 \(\beta_n>0\) を持つ場合、定理29により商上の安定逆推定と安全予算が得られる。

残る問題は、

1. source と propagation の同時パラメータ化で \(\beta_n>0\) を保証する介入設計、
2. hidden gauge / latent symmetry を含む quotient observability、
3. 非線形・非定常・担体カスケード下の一様条件数、
4. task-relative 復元から full witness lifting への条件、

である。

## OP-RE8 — 非可換接続との統合

接続 \(A\)、曲率 \(F_A\)、共変微分 \(D_A\) の下で、

\[
\mathcal E_A,\quad
\mathcal A_A,\quad
J_A
\]

がゲージ共変に降下する条件を求める。

特に、

\[
D_A^1D_A^0
=
\operatorname{ad}(F_A)
\]

による複体破壊と、担体化–粗視化非可換欠陥の関係を調べる。

---

## OP-SR1 — turnover 内生性の操作的同定

旧 realization token の保持、内部 template からの再構成、環境からの reload を区別できる joint intervention family と provenance observable を構成する。全 singleton に加え、分散 backup を同時に除く total cut を含め、定理38の input–output 非識別性を破る最小因果データを分類する。

---

## OP-SR2 — 一様 self／transverse bound の存在

具体的な物理・生物・情報模型で、

\[
\sup_n\|z_*^{-n}(\mathscr R^{\rm ret})^n\Pi_{\rm self}\|<\infty,
\qquad
\|z_*^{-n}(\mathscr R_\perp^{\rm ret})^n\|
\le C_*(1-\eta_*)^n
\]

を解像度・尺度・hidden restoration に一様に証明する。

---

## OP-SR3 — 非可逆 RG における self-spectrum の自然性

次元を落とす scale intertwiner の下で \(m_{\rm br}(z;s)\) の零点、擬スペクトル、path sensitivity がどこまで保存されるかを、self-sector gain／decoder による non-erasure、相対 naturality defect、return-time scaling、安全予算を含めて分類する。

---

## OP-SR4 — 無限次元・確率 cocycle 拡張

非閉 range、unbounded return、連続スペクトル、random operator product に対して split bridge と Feshbach chart を拡張する。平均作用素の spectrum と almost-sure Lyapunov spectrum を混同しない定式化を与える。

---

---

---

# 17. 将来の見込み

## 17.1 数理面

最も重要なのは、可換コアの完全形式化である。

1. Hodge 残差商の圏論化。
2. 許容粗視化写像の圏の構成。
3. アノマリーを 2-cocycle または obstruction class として定式化。
4. 残差力学の一般アトラクタ定理。
5. 強許容 \(J\) の連続極限。
6. noncommutative IDS の平坦接続線形化。
7. 局所複素構造束 \(\mathbb I=J(-J^2)^{-1/2}\) の正則性・rank-change 特異点分類。
8. 輸送欠陥 \(\Xi_A,\Xi_\gamma\) と曲率・arrow detector・担体化欠陥の統一障害理論。

## 17.2 物理面

1. Causal-Hodge Bridge の 5σ 確認または棄却。
2. \(a_I\) の galaxy-dependent law。
3. lensing-dynamics \(\Sigma=1\) 検証。
4. HFE/DHT と質量ギャップの厳密分離。
5. Green–Kubo/negative pressure ブリッジの再検査。

## 17.3 AI 面

1. LLM の self-debug_session 実装。
2. CIE 検出器の設計。
3. 残差ログを Hodge 分解する memory graph。
4. TDNG による規範更新の安定性解析。
5. AI の hallucination を非可積分残差として扱う診断系。

## 17.4 社会面

1. 分散台帳 IDS。
2. 社会ストレス残差の可視化。
3. 自己デバッグ型民主主義。
4. 未来世代を終端条件として含む政策デバッグ。
5. レジリエンス・ギャップに基づく制度評価。

## 17.5 哲学面

1. creative oblivion の精密化。
2. 未来条件が現在を選ぶ理論。
3. 観測者と構造の共固定点としての現実。
4. 不完全性を構造生成条件として扱う存在論。

---

# 18. ゲージ情報幾何への再配置

**ステータス.** §18.1–18.9 は語彙の再配置（C0）と非可換研究計画の精密化（C4）である。§18.10–18.11 には v1.6.3 の定理24・有限行列例・条件付き局所複素構造があり、§18.12 には v1.7.1 の定理31–34による有限正則 task–gauge 層がある。特異層・大域非線形降下・連続量子実現は未解決である。

## 18.1 中核宣言

SPD 構造は放棄されるのではなく、降格される。

\[
\boxed{
\text{SPD を「各ファイバーの局所情報計量」へ降格し、比較規則（ゲージ接続）を「上位構造」へ昇格する}
}
\]

旧構図「入れ子状 SPD」は、次に整理される。

\[
\boxed{
\text{確率分布多様体の階層束}
+\text{Fisher/SPD 局所計量}
+\text{不可逆粗視化写像}
+\text{粗視化ゲージ接続}
+\text{曲率残差}
}
\]

一行で言えば：

\[
\boxed{
\text{IDS}=\text{粗視化された確率分布多様体のゲージ情報幾何}
}
\]

\[
\boxed{
\textbf{IDS is the gauge-information geometry of coarse-grained probability manifolds.}
}
\]

ただし「ゲージ理論が SPD を置換する」のではない。**ゲージ理論は SPD 情報幾何を束化・共変化・非可換化する。**ゲージ理論単体は \(p\ge0,\ \int p\,dx=1\) という確率の足場を持たないから、基礎対象はあくまで確率分布多様体である。

## 18.2 最小幾何データ \((K,G,A)\) と task 拡張 \(P_{\rm ctrl}\)

**G1（階層束）.** スケール／粗視化軸の空間 \(B\)（一般に多次元）上の束 \(\pi:\mathcal P\to B\)。各ファイバー \(\mathcal P_b\) は確率分布多様体。

**G2（局所情報計量と Chentsov 正準性）.** 各 \(\mathcal P_b\) の接空間に Fisher 型情報計量 \(G_b\in\mathrm{SPD}(T\mathcal P_b)\) を入れる。Chentsov 型の定理（既知定理；有限標本空間では十分統計量・Markov 射への不変性のもとで Fisher 計量が定数倍を除き一意。一般化は Lê, arXiv:1306.1465 等）により、**Markov 射に対する情報単調性・十分統計量不変性を要請する限り、許される計量は Fisher 型に絞られる**。注意：単一の粗視化写像 \(K\) が \(G\) を一意に決めるのではない。\(G\) を選ぶのは**粗視化の圏に対する自然性の要請**であり、SPD 構造は任意の計量選択ではなく、粗視化圏に自然な情報計量として現れる。その上で data processing 単調性

\[
G_{b'}(K_*u,\,K_*u)\ \le\ G_b(u,u)
\]

が「粗視化は計量を縮める」を定理の形で与える。

**G3（不可逆粗視化）.** スケール間写像 \(K_{b\to b'}:\mathcal P_b\to\mathcal P_{b'}\)：Markov kernel・射影・条件付き期待値・RG 写像。一般に不可逆で、群ではなく半群・圏をなす。**粗視化はゲージ変換ではない。**

**G4（ゲージ接続）.** 粗視化後に残る自由度をスケール間・局所フレーム間で比較する接続 \(A\)。共変微分と曲率は

\[
D_A=d+A,
\qquad
F_A=D_A^2=dA+A\wedge A.
\]

非可換性の座は \(A\wedge A\)（局所表示では \([A_\mu,A_\nu]\)）にある。

**G5（K–A 両立条件；未定理化）.** 二つの非可換性

\[
D_sD_t-D_tD_s=F_{st},
\qquad
K_sK_t-K_tK_s
\]

が同一の残差対象を定めるための両立条件。この条件の定式化と証明が OP-13 である。

**G6（Gap Detector）.** 共変 Hodge Laplacian

\[
\Delta_A=d_A^*d_A+d_Ad_A^*
\]

は自己共役・半正定値：\(\operatorname{Spec}(\Delta_A)\subset\mathbb R_{\ge0}\)。残差セクターの硬さ（gap）を測る。**注意：** \(F_A\ne0\) なら \(d_A^2=F_A\wedge\cdot\ne0\) であり複体をなさないので、「コホモロジー」とは呼ばず **residual sector / gauge-fixed sector** と呼ぶ。\(H^1(X;\mathrm{ad}\,A)\) の語は平坦接続上でのみ用いる。なお非可換値では \(d_A^2\) は曲率の作用 \(\operatorname{ad}(F_A)\) として働く。Ad 不変内積のもとでファイバー方向の \(\operatorname{ad}_X\) は歪自己共役だが、\(\operatorname{ad}(F_A)\) は次数を \(+2\) 上げる作用素であり、全 cochain 内積上の（歪）自己共役性を語るには Hodge star・次数符号・随伴の規約の明示が必要である。

**G7（Arrow Detector）.** 矢・非正規性・Jordan 臨界・複素化は

\[
M_A=\Delta_A-cJ_A
\]

で測る（\(J_A\) は強許容保存生成子の共変類似；一般に非自己共役）。\(\Delta_A\) は gap detector、\(M_A\) は arrow detector — **両者を混同しない**。

**G8（Task Projection）.** 許容介入族と安全指標が行動写像 \(\mathcal B\) を定めるとき、正則層上の制御関連部分束を

\[
E_{\rm ctrl}=(\ker D\mathcal B)^{\perp_G},
\qquad
P_{\rm ctrl}:T\Theta\to E_{\rm ctrl}
\]

で定める。\(P_{\rm ctrl}\) は gauge fixing ではなく、物理ゲージ軌道上で未来制御に関係する方向を選ぶゲージ共変射影である（定理31–32）。従って task 依存の最小幾何データは

\[
(K,G,A;P_{\rm ctrl})
\]

となる。

## 18.3 四つの同値・縮約の峻別

本章の採用後、正典には少なくとも四種の同値・縮約が併存する。混同を禁止する。

| 同値／縮約 | 対象 | 性格 | 所属 |
| --- | --- | --- | --- |
| 統計的再パラメータ化 | ファイバー内座標 | 可逆・Chentsov 不変性の対象 | G2 |
| 可換シフト \(\rho\sim\rho+d_0f\) | cochain | 可逆・線形（証明済み核の商） | §5 |
| スケール間フレーム変換 | 束のフレーム | 可逆・非可換（物理／スキームゲージ群） | G4 |
| task-relative behavior quotient | 物理状態または物理軌道商 | 未来応答を保存する目的依存の多対一商；gauge fixing ではない | G8・§18.12・§19.17 |

不可逆な粗視化 \(K\)（G3）はこのいずれでもない。gauge fixing はゲージ軌道から代表元を選ぶ局所切断であり、task quotient とは別物である。また各ファイバー内には情報幾何の双対接続（Amari の \(\alpha\)-接続）という別の接続構造が既に存在する。**ファイバー内接続、across-scale の \(A\)、task-induced connection は型を分ける。**

## 18.4 スキーム接続仮説（H7）

\(K\) だけでは \(A\) は決まらない。**粗視化スキーム**（有効記述の座標・くりこみ条件の選択）の**局所族**は、束の局所自明化と遷移関数——すなわち**束構造とゲージ変換則**——を与える。ただし**局所自明化だけでは接続はまだ決まらない**。スキームを微小に変化させたとき何を同一の自由度として輸送するかという**比較規則（水平分布・平行輸送規則）**を併せて指定して、初めて接続 \(A\) が誘導される。

\[
\boxed{
\text{H7：粗視化スキームの局所族と、その微小変化に対する比較規則が、スケール束上の接続 }A\text{ を誘導する}
}
\]

\[
\boxed{
\text{スキーム非依存量}=\text{ゲージ不変量},
\qquad
\text{IDS 残差の非自明性}=\text{どのスキーム選択でも消せない曲率}
}
\]

これは「くりこみスキーム依存性＝ゲージ自由度」という場の理論に散在する発想の正典化である。\(K\) から \(A\) を構成する正準手続きの定理化は OP-13。

## 18.5 IDS 残差の非可換候補（暫定）

非可換層での IDS 残差の候補は三つある：

\[
R_{\mathrm{IDS}}\sim F_A,
\qquad
R_{\mathrm{IDS}}\sim K_sK_t-K_tK_s,
\qquad
R_{\mathrm{IDS}}\sim(\Delta_A\ \text{の gauge-fixed residual sector}).
\]

**三者は一般に非同値**であり、G5 の両立条件の下で一致することが期待されるにとどまる（OP-13）。**証明済みの残差定義は依然として可換層の \([\omega]\in C^1/\operatorname{im}d_0\) であり**、上の三候補はその非可換拡張候補（未解決）である。

**曲率には二方向が要る（注意）.** 単一のスケール軸のみでは、線上の接続は局所的にゲージで自明化できる。曲率・ホロノミーを立てるには複数の粗視化軸・空間方向・時間方向・層方向が必要である。lag 作用素 \(\Omega^k\)（変数×スケール）は既にこの二方向構造の可換版である。

## 18.6 旧理論の位置：平坦・可換極限

\[
\boxed{
\text{SPD-Hodge IDS}
\subset
\text{Gauge-Information IDS}
}
\]

\(A=0\)、または接続が平坦かつ可換化・自明化可能な極限で、新構図は旧 SPD-Hodge 正典へ退化する。これは仮説 H4（非可換線形化）の言い換えであり、非可換研究計画（§12.4）の手順 4 の整合性テストと同一である。旧正典の SPD 定理群（定理 18–20）は**ファイバー・レベルの定理**として一つも失われずに保存される。

## 18.7 矢の三段階のゲージ版

- **Level 0（Flat SPD regime）**：\(A\) 自明化可能・\(F_A=0\)。世界は SPD 情報幾何で足りる。矢はないか、単なる散逸勾配。
- **Level 1（計量相対の矢）**：非対称は見えるが、\(WM_A=M_A^TW\) を満たす \(W\succ0\) が存在し自己共役化できる。矢は表現相対的。
- **Level 2（内在的ゲージの矢）**：いかなる \(W\succ0\) でも消せない非正規性・ホロノミー・複素スペクトル（\(\operatorname{spec}M_A\not\subset\mathbb R\) または Jordan 例外点の通過）。

\[
\boxed{
\text{時間の矢}=\text{粗視化ゲージ接続の内在的曲率がスペクトルに刻まれた相}
}
\]

（提案。可換層の Level 0/1/2（§7.3）と整合し、その共変版である。）

## 18.8 正典文

> IDS 理論において、SPD 構造は放棄されるものではなく、確率分布多様体の各ファイバーに定義される局所情報計量として再配置される。旧来の SPD-Hodge 形式は、ゲージ接続が自明または平坦であり、スケール間の比較規則が可換化可能な場合の特殊理論である。一般の開放階層系では、粗視化に伴って自由度の同一視規則そのものが変化するため、基礎対象は単一の SPD 多様体ではなく、確率分布多様体の階層束とその上の粗視化接続である。この接続の曲率、ホロノミー、および許容粗視化で消去不能な共変残差が IDS 残差を定義する。したがって、IDS の自然な幾何学的器は SPD 幾何ではなく、SPD 情報計量を内包するゲージ情報幾何である。 さらに task-relative 層では、物理ゲージ軌道上で未来応答を変えない方向を商に落とし、残る制御関連部分束を \(P_{\rm ctrl}\) で選び、scale・task 間で共変輸送する。

## 18.9 採用条件（規律）

1. **SPD を廃棄しない** — Fisher 情報計量・共分散・内積として保存する。
2. **ゲージ変換と粗視化を混同しない** — 粗視化は不可逆写像 \(K\)、ゲージは比較規則 \(A\)。
3. **\(\Delta_A\) と \(M_A\) を分ける** — 前者は gap detector、後者は arrow detector。
4. **非平坦で「\(H^1\)」と言わない** — \(F_A\ne0\) なら residual / gauge-fixed sector と呼ぶ。
5. **単一スケール軸だけで曲率を語らない** — 二方向以上が必要。
6. **質量ギャップを「証明済み」と言わない** — 共変残差セクターの一様スペクトル下界としての再定式化である（§9.4）。
7. **コチェイン層と確率束の接合を明示する** — 証明済み核の舞台 \(C^\bullet(X)\) と本章の \(\mathcal P_b\) の対応（辺フロー＝スコア差・対数尤度勾配としての実現）は OP-14 であり、完了までは両者を別の足場として扱う。
8. **制御商を gauge fixing と呼ばない** — 物理軌道商の後に置かれる task-relative quotient である（定理31）。
9. **task–gauge 曲率は正則層でのみ凍結する** — constant rank・滑らかなゲージ共変射影を外す場合は OP-TG1–4 へ戻す。

## 18.10 攻略順序（OP-1 と OP-13 の分離実行）

両問題を混線させないため、数値・記号実験は次の順で行う。

**Step 1（OP-13 入口・可換）.** 付録 A の最小複体上で、chain defect と dynamic defect

**進捗（v1.6.3）.** 抽象的な型安全計算は定理24で閉じ、有限行列模型・chain anomaly・真の Type III 例は §18.11 に統合した。

\[
A_K=\bar d\,K-K\,d,
\qquad
R_K=K\,T-\bar T\,K
\]

（\(K\)：次数ごとの粗視化 \(K_i:C^i_{\rm fine}\to C^i_{\rm coarse}\)、\(d,\bar d\)：細・粗スケールの微分、\(T,\bar T\)：細・粗スケールの時間発展）を型安全に計算し、両欠陥の型の違いを確認する。\(R_K\) は軸交換子 \(K_sK_t-K_tK_s\)（§18.5）の（スケール，時間）成分に相当する。

**注記（証明済み核との結線）.** 許容粗視化アノマリー \(\mathfrak A_\Phi=q\circ\Phi\circ d_0\)（公理 A8、\(\Phi=K_1\)）は chain defect の次数 0 ブロックの商影に他ならない：\(q\circ\bar d_0=0\) より

\[
\mathfrak A_\Phi=-\,q\circ(A_K)_0,
\qquad
(A_K)_0=\bar d_0K_0-K_1d_0
\]

（符号は規約）。すなわち既存の証明済みアノマリーは \(A_K\) の最初の成分であり、OP-13 の新対象は正典核の直接の延長である。

**Step 2（OP-1 入口）.** \(\mathfrak{su}(2)\) 値の 2-loop bouquet（§11.3 型の \(H^1\) 支配複体）で stabilizer gap を見る。2-loop bouquet は full residual gap ではなく **stabilizer gap** を見る装置であることに注意。

**Step 3.** 2-cell を持つ複体（付録 A）で共変 Laplacian \(\Delta_A^{(1)}\) の residual gap を測る。ここで初めて \(\Delta_A\) を gap detector として本格使用する。

**Step 4（OP-1B）.** \(M_A=\Delta_A-cJ_A\) で Jordan 例外点・複素化（arrow transition）を見る。\(\Delta_A\) では見えない矢の遷移を \(M_A\) が担う。

この順序なら、OP-13（型の整理）と OP-1（非可換の壁）を混線させずに同時前進できる。

---

## 18.11 chain–dynamic defect の閉包と局所複素構造輸送

**ステータス.** §18.11.1–2 の代数恒等式と有限行列計算は証明・直接計算済みであり、§18.10 Step 1 の抽象部分を閉じる。§18.11.3 の正規化複素構造は追加仮定の下での条件付き構成、輸送欠陥は定義・C4研究計画である。

### 18.11.1 欠陥の型と整合関係

chain defect と dynamic defect はそれぞれ

\[
A_i=d_i^cK_i-K_{i+1}d_i^f:
C_f^i\to C_c^{i+1},
\]

\[
R_i=K_iT_i^f-T_i^cK_i:
C_f^i\to C_c^i
\]

である。前者は次数を \(+1\) 上げ、後者は次数を保存するため、同じ「非可換差」であっても型は異なる。定理24により、内部力学が chain map の場合には

\[
\boxed{
A_iT_i^f-T_{i+1}^cA_i
=
d_i^cR_i-R_{i+1}d_i^f
}
\]

が成り立つ。したがって両欠陥は独立に非零になり得るが、任意ではなく Bianchi 型整合関係に拘束される。

### 18.11.2 付録A複体における最小実計算

細粒度側を付録Aの複体とし、粗粒度側を三頂点 \(a,b,c\)、三辺

\[
f_0=(a,b),\qquad f_1=(b,c),\qquad f_2=(c,a)
\]

および一つの三角 2-cell を持つ複体とする。

\[
d_0^c=
\begin{pmatrix}
-1&1&0\\
0&-1&1\\
1&0&-1
\end{pmatrix},
\qquad
d_1^c=
\begin{pmatrix}
1&1&1
\end{pmatrix}.
\]

頂点 \(0,3\) を \(a\) へ統合する粗視化を

\[
K_0=
\begin{pmatrix}
\frac12&0&0&\frac12\\
0&1&0&0\\
0&0&1&0
\end{pmatrix},
\]

\[
K_1=
\begin{pmatrix}
1&0&0&0&0\\
0&1&0&0&0\\
0&0&1&0&-1
\end{pmatrix},
\qquad
K_2=
\begin{pmatrix}
1&0
\end{pmatrix}
\]

とすると、

\[
A_0=d_0^cK_0-K_1d_0^f
=
\begin{pmatrix}
\frac12&0&0&-\frac12\\
0&0&0&0\\
-\frac12&0&1&-\frac12
\end{pmatrix},
\]

\[
A_1=d_1^cK_1-K_2d_1^f
=
\begin{pmatrix}
0&0&1&0&0
\end{pmatrix}.
\]

よってこの自然に見える頂点統合は chain map ではない。

#### chain anomaly の最小例

粗粒度残差方向への標準射影を \(q_c\) とし、\(x=(x_0,x_1,x_2,x_3)^T\) とすると、

\[
q_cA_0x
=
\frac{x_2-x_3}{3}
\begin{pmatrix}1\\1\\1\end{pmatrix},
\qquad
\mathfrak A_\Phi(x)
=
-q_cA_0x.
\]

したがって細粒度で exact だった頂点ポテンシャル差が、非許容な頂点統合後には粗粒度の非勾配循環として現れる。これは chain anomaly の最小例であるが、細粒度標準残差がゼロなので、現行定義の Type III そのものではない。

#### 真の Type III 最小例

次に粗粒度側の 2-cell を除去して三角グラフとする。このとき

\[
H_c^1=\operatorname{span}\left\{
\begin{pmatrix}1\\1\\1\end{pmatrix}
\right\}.
\]

細粒度側では \(H_f^1=0\) であり、coexact な標準残差

\[
\widehat\rho_f
=
(d_1^f)^*
\begin{pmatrix}1\\0\end{pmatrix}
=
\begin{pmatrix}1\\1\\0\\0\\-1\end{pmatrix}
\]

を取ると、

\[
P_{H,f}\widehat\rho_f=0,
\qquad
K_1\widehat\rho_f
=
\begin{pmatrix}1\\1\\1\end{pmatrix}
\in H_c^1\setminus\{0\}.
\]

これは細粒度の非調和残差が制約忘却後に粗粒度の調和残差へ昇格する、§4.5 の Type III を直接実現する。

#### 独立性

\(T_i^f=T_i^c=I\) とすれば \(R_i=0\) だが上の \(A_i\) は非零である。逆に同一複体上で \(K_i=I\) とし \(T_i^f\neq T_i^c\) とすれば \(A_i=0\) だが \(R_i\neq0\) となる。ゆえに

\[
\boxed{
A_K\text{ と }R_K\text{ は独立だが、定理24の整合恒等式によって結合される}
}
\]

### 18.11.3 正規化局所複素構造

実ベクトル束 \(E\to B\) に SPD 計量 \(G\) と \(G\)-skew 生成子

\[
GJ+J^*G=0
\]

があるとする。ある領域で \(\operatorname{rank}J\) が一定で、非零スペクトル部分束

\[
E^\times=(\ker J)^{\perp_G}
\]

上の \(-J^2=J^{\dagger_G}J\) がゼロから一様に分離されているとき、機能解析的平方根により

\[
\boxed{
\mathbb I
=
J(-J^2)^{-1/2}
:
E^\times\to E^\times
}
\]

を定義できる。

**命題 CX-1（条件付き局所複素構造）。** 上の仮定の下で、

\[
\mathbb I^2=-I_{E^\times},
\qquad
G\mathbb I+\mathbb I^*G=0.
\]

したがって \(\mathbb I\) は \(E^\times\) 上の \(G\)-直交局所複素構造である。constant-rank と一様スペクトル分離は、\(\mathbb I\) が滑らかな束写像になるための十分条件である。

**証明。** \((-J^2)^{-1/2}\) は \(J^2\) の関数であるため \(J\) と可換する。よって

\[
\mathbb I^2
=
J^2(-J^2)^{-1}
=-I.
\]

また \(J^{\dagger_G}=-J\) と functional calculus より \(\mathbb I^{\dagger_G}=-\mathbb I\) である。 \(\square\)

固有値がゼロを横切り rank が変化する点では、この正規化は特異になり、回転構造の次元が変わる。この特異点分類は OP-CX1 に属する。

### 18.11.4 複素構造輸送欠陥

接続 \(D_A\) による局所複素構造の共変微分を

\[
\boxed{
\Xi_A:=D_A\mathbb I=d\mathbb I+[A,\mathbb I]
}
\]

と定義する。作用素としては \([D_A,\mathbb I]\) と同じ型を持つ。

- \(\Xi_A=0\)：接続が複素構造を保存する。これは平坦性を意味しない。
- \(\Xi_A\neq0\)：輸送とともに回転面そのものが変化する。

曲率との整合関係は

\[
D_A^2\mathbb I=[F_A,\mathbb I].
\]

したがって \(\Xi_A=0\) なら

\[
[F_A,\mathbb I]=0
\]

であるが、\(F_A=0\) である必要はない。曲率が非零でも \(\mathbb I\) を保存する unitary-type connection は存在し得る。

基点 \(x\) の閉路 \(\gamma\) に対して、ホロノミー欠陥を

\[
\boxed{
\Xi_\gamma
=
\operatorname{Hol}_A(\gamma)\mathbb I_x
\operatorname{Hol}_A(\gamma)^{-1}
-\mathbb I_x
}
\]

と定義する。非自明なホロノミー自体は複素構造破壊を意味せず、\(\Xi_\gamma\neq0\) のときに限り一周後の回転構造が一致しない。

この意味で、非可換 IDS における「虚数」の厳密な候補は単一の \(i\) ではなく、

\[
\boxed{
\text{接続によって輸送される局所複素構造の束と、その輸送・ホロノミー障害}
}
\]

である。これは C4【条件付き構成＋研究仮説】であり、時間の矢そのものではない。時間の矢は保存回転が散逸・不可逆粗視化・曲率と非可換に結合した合成構造として検出される。

---


## 18.12 task–gauge compatibility と誘導曲率

**ステータス.** 有限次元・一定 rank の正則層における定理31–34の幾何学的要約。特異商、非不変 task、動的 task、大域非線形降下は OP-TG1–4。

### 18.12.1 商の順序

物理ゲージ群 \(\mathcal G\) と制御同値を同一視してはならない。正しい順序は

\[
\boxed{
\Theta
\longrightarrow
[\Theta/\mathcal G]
\longrightarrow
Q_{\rm ctrl}^{\rm phys}.
}
\]

第一段は物理的冗長性を除き、第二段は許容介入の下で未来の応答を変えない物理状態を同一視する。\(Q_{\rm ctrl}\) は gauge fixing ではない。

### 18.12.2 task–coarse の二欠陥

\[
\Gamma_K^{\rm ctrl}=P_cK(I-P_f),
\qquad
\Lambda_K^{\rm ctrl}=(I-P_c)KP_f.
\]

- \(\Gamma_K^{\rm ctrl}\)：fine で制御-nullだった方向が coarse で relevant になる **control promotion**。
- \(\Lambda_K^{\rm ctrl}\)：fine で relevant だった方向が coarse で null になる **control erasure**。

\[
P_cK-KP_f
=
\Gamma_K^{\rm ctrl}-\Lambda_K^{\rm ctrl}.
\]

両者がゼロなら、task selection と粗視化は正則接空間上で可換する。

### 18.12.3 誘導接続

制御関連部分束 \(E_{\rm ctrl}=\operatorname{Ran}P\) 上の接続は

\[
\nabla^{\rm ctrl}=P D_A,
\]

曲率は

\[
\boxed{
F_{\rm ctrl}
=
P F_A P
+
P(D_AP)\wedge(D_AP)P.
}
\]

第一項は task が見る物理曲率、第二項は「何を重要とみなすか」という部分束そのものの捩れである。従って物理接続が平坦でも \(D_AP\neq0\) なら operational holonomy が生じ得る。

スケール \(s\) と task \(\tau\) の混合成分は

\[
(F_{\rm ctrl})_{s\tau}
=
P(F_A)_{s\tau}P
+
P[D_sP,D_\tau P]P.
\]

これは「粗視化してから retask」と「retask してから粗視化」の非可換性を測る。


### 18.12.3A v2.1 情報熱接続としての再導出

定理 IT-3（§29.6）により、上の \(F_{\rm ctrl}\) は制御関連ベクトル束の全空間上の線形情報熱形式

\[
\Xi_{\rm ctrl}=dv+A_{\rm ctrl}v
\]

が定める Ehresmann 接続の曲率であり、規約 \(\Omega=\operatorname{vert}[X^h,Y^h]\) のもとで

\[
\Omega_{\rm ctrl}(X,Y)|_v=-F_{\rm ctrl}(X,Y)v
\]

となる。さらにアフィン拡張 \(dv+A v+\beta\) では、task--gauge 曲率と仕事／hidden-exchange 曲率が単一のアフィン曲率 \(\widetilde F\) のブロックとして統合される。ただしブロック分解はアフィン原点相対であり、\(\widetilde F\) 全体のみを幾何学的本体とする。

### 18.12.4 正典文

\[
\boxed{
\begin{aligned}
&\textbf{IDS の task–gauge 層とは、物理ゲージ軌道上で}\\
&\textbf{未来の制御を変えない方向を商に落とし、}\\
&\textbf{残る制御関連部分束を scale・task 間で共変輸送する幾何である。}
\end{aligned}
}
\]

最短形：

\[
\boxed{
\textbf{世界のゲージ曲率と、何を重要とみなすかの曲率は、誘導接続の中で出会う。}
}
\]

# 19. 自己粗視化・閉包欠陥・幾何学的ストレス（追補統合）

**出自.** 本章は独立追補『IDS 正典追補 v1.0 — 自己粗視化・制約ソルバー・階層時空・幾何学的ストレス』（2026-07-12）を v1.4 で正典へ統合したものである。追補の反証可能性台帳・ステータス台帳・命題 K–R・未解決問題・用語は、正典の対応する台帳（§16・§22–25）へ併合した。§19.9 は正典 §9（mass gap 再定式化）の精密化（No-Fake-Gap・二重構造）として、§19.10 は物理拡張（§11）の重力側の規律として読む。

**統合注記（v1.4 整合性）.** 統合にあたり次の五点を確定する。

**1. 欠陥の三型と §18.10 との対応.** 本章の動力学的閉包欠陥 \(\Sigma_{\mathcal R}=\mathcal R\circ U-U_{\rm eff}\circ\mathcal R\) は、§18.10 Step 1 の dynamic defect \(R_K=KT-\bar TK\)（対応 \(K=\mathcal R\), \(T=U\), \(\bar T=U_{\rm eff}\)）と同一対象である。これにより正典の欠陥は三型に整理される。

| 型 | 定義 | 測るもの | 所在 |
| --- | --- | --- | --- |
| chain defect | \(A_K=\bar d\,K-K\,d\) | 微分構造との非両立（\(\mathfrak A_\Phi=-q\circ(A_K)_0\)） | §18.10 |
| dynamic defect | \(\Sigma_{\mathcal R}=\mathcal R U-U_{\rm eff}\mathcal R\) | 力学との非両立（閉包欠陥） | 本章 §19.6 |
| associator | \(\Omega_{\ell,L,M}=\mathcal R_{L\to M}\mathcal R_{\ell\to L}-\mathcal R_{\ell\to M}\) | 塔の合成経路依存（2-cocycle 候補） | 本章 §19.3 |

なお associator は §18.5 の軸交換子 \(K_sK_t-K_tK_s\)（二つの粗視化**軸の間**の非可換性）とは別物であり、**単一軸上の合成**に関する欠陥である。両者の関係の定式化は OP-H1 と G5 に属する。

**2. 差の定義域.** \(\Sigma_{\mathcal R}\) の「差」は線形構造を前提とする。確率分布多様体など非線形空間では、接空間・埋め込み・ダイバージェンスのいずれで差を測るかを指定して初めて定義される。この指定は OP-GS1（障害空間の厳密定義）の一部である。

**3. 最良閉包に対する残差.** \(\Sigma_{\mathcal R}\) は有効力学 \(U_{\rm eff}\) の選択に依存する。幾何学的ストレスは、許容閉包クラス \(\mathcal U_{\rm adm}\) 上の**最良閉包に対する残差**として読む：

\[
U_{\rm eff}^{\rm opt}
\in
\operatorname*{arg\,min}_{U_{\rm eff}\in\mathcal U_{\rm adm}}
\bigl\|\,[\mathcal R U-U_{\rm eff}\mathcal R]\,\bigr\|_{\mathfrak O_{\mathcal R}},
\qquad
[\Sigma_{\mathcal R}]
:=
[\mathcal R U-U_{\rm eff}^{\rm opt}\mathcal R].
\]

悪い有効模型の選択に起因する見かけの残差は、\(\mathcal N_{\rm local}\)（局所再定義）と併せてここで除かれる。商ノルムの存在自体は OP-GS1 に依存する。

**4. 平坦・可換極限の整合性要請.** 粗視化障害空間 \(\mathfrak O_{\mathcal R}=\mathcal Z_{\mathcal R}/\mathcal N_{\mathcal R}\) は、線形・可換・平坦極限で正典核の残差商 \(R^1=C^1/\operatorname{im}d_0\) へ退化しなければならない（仮説 H4 と同型の整合性テスト）。この退化の明示を OP-GS1 の要件に含める。

**5. OP の統合.** 追補の OP-H2（粗視化接続の構成）は OP-13 と同一問題であり、OP-13 へ統合した。他の追補 OP は名前空間つき（OP-SC／CS／H／GS／MG／GR）で §16 に併合した。

**本章の目的.** 本章は、次の思考の連鎖を正典化する。

\[
\text{自己粗視化}
\longrightarrow
\text{逆問題・制約充足}
\longrightarrow
\text{世界／量子系をソルバーとして見る視点}
\longrightarrow
\text{階層的時空}
\longrightarrow
\text{ホロノミー・コホモロジー}
\longrightarrow
\text{幾何学的ストレス}
\]

出発点は直観的である。

> 系は自分の全微視履歴を保持するのではなく、次の予測・制御・改善に必要な構造だけを自己内部へ圧縮するのではないか。

この操作を **自己粗視化** と呼ぶ。さらに、物理世界そのものも、局所制約を満たす状態へ進み、観測者・生命・知能はその過程を内部モデルとして再利用する局所ソルバーとみなせる可能性がある。

しかし、以下を混同してはならない。

1. 物理系がある制約を自然に満たすこと。
2. 任意の SAT インスタンスを多項式時間・多項式資源で解くこと。
3. 粗視化によって「解の存在」を保存すること。
4. 粗視化された解から微視的 witness を効率よく復元すること。
5. 数学的な mass gap と、単なる平滑化・情報廃棄による見かけの gap。
6. 一般相対論の局所的破綻と、粗視化後の有効方程式の変化。

本章の役割は、魅力的な直観を捨てずに、成立している数学と未証明の橋を分離することである。

---

---

## 19.1 正典的境界

### 19.1.1 本章が採用するもの

- 粗視化を単なる情報損失でなく、**構造選別**として扱う。
- 自己粗視化を、自己モデルと粗視化規則の共進化として定式化する。
- 微視的力学と有効力学の非可換差を、閉包欠陥として定義する。
- 幾何学的ストレスの本体を、生のテンソルでなく、消去不能な**障害類**として置く。
- ホロノミー、コホモロジー、粗視化スペクトル、相互情報量の役割を分ける。
- 質量ギャップでは「局所モードの収縮」と「大域的障害セクターの残存」を分離する。
- 重力では局所 GR の成功を保存し、巨視的平均化・閉包で追加項が生じる可能性を調べる。
- 先行理論と重なる部分を明示し、統合部分だけを新規候補として扱う。

### 19.1.2 本章が主張しないもの

- \(P=NP\) の証明。
- 自己粗視化が一般 SAT を多項式時間で解くという証明。
- 世界が文字通り古典 SAT ソルバーであるという実証。
- 量子計算機が RSA を破れないことから、新物理が直ちに従うという主張。
- Yang–Mills 存在と質量ギャップ問題の解決。
- ダークマターが粗視化幾何だけで説明されたという主張。
- 局所ローレンツ不変性または一般相対論が観測的に破綻しているという主張。
- ホロノミーや非自明コホモロジーが存在すれば、自動的に有効重力源になるという主張。
- 異分野で同じ数式テンプレートが現れることから、同じ物理的実体が存在するとする主張。

---

## 19.2 最短正典要約

本章の中心は、次の四行である。

\[
\boxed{
\text{自己粗視化}
=
\text{自己の微視状態・履歴・規則を、将来の予測・制御に必要な有効構造へ写す反復過程}
}
\]

\[
\boxed{
\Sigma_{\mathcal R}
=
\mathcal R\circ U
-
U_{\mathrm{eff}}\circ\mathcal R
}
\]

\[
\boxed{
\text{幾何学的ストレス}
=
[\Sigma_{\mathcal R}]
\in
\frac{\text{保存可能な粗視化閉包欠陥}}
{\text{ゲージ}+\text{exact}+\text{局所再定義}+\text{null 成分}}
}
\]

\[
\boxed{
\text{物理的に有効な残差}
=
\text{消せない}
+
\text{階層を越えて残る}
+
\text{マクロ観測量へ結合する}
}
\]

この定義では、「残るもの」は必ずしも大振幅ではない。残る理由は、局所平均で相殺されず、輸送経路・位相・保存則・非可換性・閉包障害に保護されることにある。

---

## 19.3 基本対象：階層的粗視化塔

### 19.3.1 スケール付き状態空間

各スケール \(\ell\) に状態空間 \(\mathcal X_\ell\) を置く。

\[
\mathcal X_{\ell_0},
\mathcal X_{\ell_1},
\dots,
\mathcal X_{\ell_n},
\qquad
\ell_0<\ell_1<\cdots<\ell_n.
\]

細かいスケールから粗いスケールへの写像を、

\[
\mathcal R_{\ell\to L}:
\mathcal X_\ell\to\mathcal X_L
\]

とする。

理想的な階層では、

\[
\mathcal R_{L\to M}\circ\mathcal R_{\ell\to L}
=
\mathcal R_{\ell\to M}
\]

が成り立つ。しかし、粗視化規則、閉包、観測者、ゲージ固定が異なると、この合成則が破れることがある。

### 19.3.2 階層結合欠陥

三つのスケール \(\ell<L<M\) に対して、

\[
\Omega_{\ell,L,M}
:=
\mathcal R_{L\to M}\circ\mathcal R_{\ell\to L}
-
\mathcal R_{\ell\to M}
\]

を **階層結合欠陥** と呼ぶ。

\[
\Omega_{\ell,L,M}=0
\]

なら、粗視化塔は経路独立である。

\[
\Omega_{\ell,L,M}\neq0
\]

なら、中間スケールを経由するか直接粗視化するかで有効状態が変わる。この欠陥は、粗視化空間上の曲率・associator・2-cocycle 候補である。

**ステータス:** 定義。一般の物理的意味は仮説。

### 19.3.3 階層時空の正典的意味

「量子、実験室、銀河で別の時空法則が存在する」という言い方は強すぎる。正典的には、

> 同じ微視的世界を異なる粗視化スケールで記述すると、保持される状態変数、閉包項、記憶項、非局所応答が変わるため、有効時空力学がスケール依存になる可能性がある。

とする。

したがって階層時空とは、無関係な法則の寄せ集めでなく、

\[
\left(
\mathcal X_\ell,
U_t^{(\ell)},
\mathcal R_{\ell\to L},
\Omega_{\ell,L,M}
\right)
\]

からなる整合的な有効理論の塔である。

---

## 19.4 自己粗視化

### 19.4.1 定義

状態履歴を \(x_{\le t}\)、内部有効状態を \(z_t\)、自己粗視化規則のパラメータを \(\theta_t\) とする。

\[
z_t
=
\mathcal C_{\theta_t}(x_{\le t}),
\]

\[
\theta_{t+1}
=
\mathcal U(\theta_t,z_t,\varepsilon_t),
\]

ここで \(\varepsilon_t\) は予測誤差、制御誤差、反例、失敗ログなどである。

\[
\boxed{
\text{自己粗視化とは、系が自己を表す有効状態 }z_t
\text{ だけでなく、粗視化規則 }\theta_t
\text{ 自体も更新する過程である。}
}
\]

単なる要約との差は、粗視化後の表現が将来の振る舞いを変え、さらに粗視化規則そのものが修正される点にある。

### 19.4.2 四層

#### 状態の自己粗視化

\[
\text{多数の内部変数}
\longrightarrow
\text{少数の有効状態}
\]

例：活力、不確実性、探索傾向、危険度。

#### 履歴の自己粗視化

\[
\text{個々の試行ログ}
\longrightarrow
\text{成功条件・失敗パターン・例外規則}
\]

#### 規則の自己粗視化

\[
\text{多数の局所ルール}
\longrightarrow
\text{少数の上位方針}
\]

#### 発達の自己粗視化

\[
\text{変更点の列}
\longrightarrow
\text{自分がどの方向へ変化したかという自己モデル}
\]

### 19.4.3 良い自己粗視化

良い自己粗視化は、圧縮率だけでは決まらない。候補目的関数は、

\[
\mathcal J(\theta)
=
\mathcal L_{\rm pred}
+
\lambda_{\rm ctrl}\mathcal L_{\rm control}
+
\lambda_{\rm comp}\mathcal C(z)
+
\lambda_{\rm exc}\mathcal L_{\rm exception}.
\]

- \(\mathcal L_{\rm pred}\)：将来予測誤差。
- \(\mathcal L_{\rm control}\)：目標状態へ導く制御誤差。
- \(\mathcal C(z)\)：表現複雑度。
- \(\mathcal L_{\rm exception}\)：重要な少数例外を消した損失。

したがって、

\[
\boxed{
\text{良い自己粗視化}
=
\text{予測可能性}
+
\text{制御可能性}
+
\text{圧縮}
+
\text{反例保持}
}
\]

である。

### 19.4.4 自己粗視化の危険

自己粗視化は知能の条件になり得るが、同時に自己欺瞞の機構でもある。

- 失敗例を粗視化で消す。
- 都合の悪い因果をノイズ扱いする。
- 予測しやすい自己像だけを残す。
- 過去の自己モデルへ新しいデータを強制的に合わせる。
- 粗視化後の成功を、微視的真実と取り違える。

したがって自己粗視化には、**反例保存チャネル**と **粗視化監査** が必要である。

---

## 19.5 逆問題と制約ソルバー

### 19.5.1 粗視化と逆問題

粗視化写像

\[
\mathcal C:X\to Z
\]

は、多数の微視状態を同じ有効状態へ送る。

\[
\mathcal C^{-1}(z)
=
\{x\in X:\mathcal C(x)=z\}.
\]

逆問題は、観測 \(z\) と追加制約から、元の \(x\) またはその同値類を復元する問題である。

粗視化が逆問題ソルバーになるためには、単に情報を捨てるだけでなく、

1. 不可能な候補を早期に除外する。
2. 解の存在性を保存する。
3. 候補集合を短く表現する。
4. 必要な witness を効率よく持ち上げる。

必要がある。

### 19.5.2 SAT へ接続するための必要条件

CNF 式 \(F\) に対して粗視化変換 \(C\) と持ち上げ \(R\) を考える。

最低限、

\[
F\in\mathrm{SAT}
\iff
C(F)\in\mathrm{SAT}
\]

が必要である。

さらに \(C(F)\) の充足割当 \(y\) から、

\[
R(F,y)=x,
\qquad
F(x)=1
\]

を得る必要がある。

一般 SAT の多項式時間アルゴリズムを主張するなら、

\[
|C(F)|\le \operatorname{poly}(|F|),
\]

\[
T_C,T_{\rm solve},T_R
\le
\operatorname{poly}(|F|)
\]

を任意の \(F\) について証明しなければならない。

\[
\boxed{
\text{解存在性を保存する粗視化}
\neq
\text{witness を効率よく復元できる粗視化}
}
\]

ここが計算量論上の壁である。

### 19.5.3 世界ソルバー仮説

**弱い世界ソルバー仮説**

> 物理法則は局所制約を定義し、物理過程はそれらと整合する軌道を実現する。

これは広い意味で自然である。

- 保存則。
- 境界条件。
- 作用原理。
- 安定性条件。
- 局所相互作用。
- 幾何学的整合性。

**強い世界ソルバー仮説**

> 世界は任意の離散制約充足問題を、多項式時間・多項式物理資源で解く。

これは全く別の主張であり、現在支持されていない。

物理系が「解を出す」場合でも、

- 緩和時間が指数的。
- 系の体積が指数的。
- 精度・エネルギー・初期化コストが指数的。
- 解ではなく局所最小へ落ちる。
- 出力読み出しが困難。

である可能性がある。

### 19.5.4 量子ソルバー仮説

量子力学には、

- 重ね合わせ。
- 干渉。
- 位相。
- エンタングルメント。
- 測定。

があり、古典計算とは異なる探索構造を与える。

しかし、

\[
\text{重ね合わせ}
\neq
\text{全候補の答えを一度に読み出せること}
\]

である。

Shor のアルゴリズムは、理想的な量子回路モデルで整数因数分解を多項式時間に行う。だが因数分解は NP 完全と知られている問題ではなく、Shor の成功・失敗だけで \(P\) 対 \(NP\) は決まらない。

また、現実の大規模 RSA が破れないことは、まず、

- 量子ビット数。
- 誤り率。
- 誤り訂正。
- 回路深さ。
- 実装資源。

の不足を意味する。標準量子力学そのものの破綻を示すには、十分に制御された誤り訂正系で、理論的資源見積もりから再現性ある逸脱が必要である。

---

## 19.6 粗視化と力学の非可換性

### 19.6.1 動力学的閉包欠陥

微視的時間発展を

\[
U_t^{\rm micro}:\mathcal X_{\rm micro}\to\mathcal X_{\rm micro},
\]

粗視化を

\[
\mathcal R:\mathcal X_{\rm micro}\to\mathcal X_{\rm macro},
\]

仮定したマクロ時間発展を

\[
U_t^{\rm eff}:\mathcal X_{\rm macro}\to\mathcal X_{\rm macro}
\]

とする。

\[
\boxed{
\Sigma_{\mathcal R}(t;x)
=
\mathcal R\!\left(U_t^{\rm micro}x\right)
-
U_t^{\rm eff}\!\left(\mathcal R x\right)
}
\]

を **動力学的閉包欠陥** と呼ぶ。

\[
\Sigma_{\mathcal R}=0
\]

なら、選んだ有効変数で力学が閉じる。

\[
\Sigma_{\mathcal R}\neq0
\]

なら、捨てた自由度が、

- 記憶。
- ノイズ。
- 有効力。
- 非局所カーネル。
- 相関ストレス。
- 初期条件依存。
- トポロジカル障害。

として戻る。

### 19.6.2 Mori–Zwanzig 型の一般形

投影 \(P\) で関連変数を選ぶと、厳密な縮約力学は概念的に、

\[
\dot z(t)
=
\underbrace{\Omega z(t)}_{\text{即時閉包}}
+
\underbrace{\int_0^t K(t-s)z(s)\,ds}_{\text{記憶}}
+
\underbrace{F(t)}_{\text{直交力}}
\]

となる。

これは「粗視化後の力学は一般に Markov 的に閉じない」という既知の原型である。

IDS の独自候補は、この記憶・直交力・相関項のうち、どの部分がゲージ・局所再定義を越えて残る**構造的障害類**なのかを分類する点にある。

---

## 19.7 幾何学的ストレス

### 19.7.1 暫定定義

\[
\Sigma_{\mathcal R}
=
\mathcal R\circ\mathcal E
-
\bar{\mathcal E}\circ\mathcal R
\]

を、方程式 \(\mathcal E\) と粗視化の非可換差とする。

ただし、生の \(\Sigma_{\mathcal R}\) には、

- 座標選択。
- ゲージ選択。
- 代表元選択。
- 局所カウンター項。
- 粗視化スキーム。
- 数値誤差。
- 単なる平滑化損失。

が混入する。

そこで、許容される閉包欠陥の空間を \(\mathcal Z_{\mathcal R}\)、物理的に自明な null 成分を \(\mathcal N_{\mathcal R}\) とし、

\[
\mathfrak O_{\mathcal R}
:=
\mathcal Z_{\mathcal R}/\mathcal N_{\mathcal R}
\]

を **粗視化障害空間** と呼ぶ。

\[
\boxed{
[\Sigma_{\mathcal R}]
\in
\mathfrak O_{\mathcal R}
}
\]

が幾何学的ストレスの本体候補である。

### 19.7.2 null 成分

\[
\mathcal N_{\mathcal R}
=
\mathcal N_{\rm gauge}
+
\mathcal N_{\rm exact}
+
\mathcal N_{\rm local}
+
\mathcal N_{\rm numerical}.
\]

- \(\mathcal N_{\rm gauge}\)：ゲージ変換で消える。
- \(\mathcal N_{\rm exact}\)：局所ポテンシャルへ吸収できる。
- \(\mathcal N_{\rm local}\)：有効パラメータの局所再定義へ吸収できる。
- \(\mathcal N_{\rm numerical}\)：離散化・有限標本・推定誤差で説明できる。

したがって「残差がゼロでない」だけでは発見にならない。

\[
\boxed{
\text{発見}
=
\text{事前登録された方向の残差が、null・decoy・既知再定義を破って残ること}
}
\]

### 19.7.3 三条件

幾何学的ストレスが物理的に意味を持つためには、少なくとも三条件が必要である。

#### 障害性

\[
[\Sigma_{\mathcal R}]\neq0.
\]

#### 持続性

誘導粗視化作用 \(\mathcal R_*\) に対し、

\[
\kappa([\Sigma])
=
\limsup_{n\to\infty}
\left\|
\mathcal R_*^n[\Sigma]
\right\|^{1/n}
\]

を定義する。

- \(\kappa\ll1\)：急速に忘却。
- \(\kappa\approx1\)：階層を越えて残存。
- \(\kappa>1\)：粗視化過程で増幅。

#### 力学的結合

\[
\Pi_{\rm phys}[\Sigma]\neq0.
\]

残っていても、観測可能量・運動方程式・応答関数へ結合しなければ、物理的には沈黙している。

### 19.7.4 正典的定義

\[
\boxed{
\begin{aligned}
\text{幾何学的ストレスとは、}&\\
&\text{輸送・力学・粗視化の非可換性から生じ、}\\
&\text{ゲージ、exact 成分、局所再定義、null モデルで消えず、}\\
&\text{階層を越えて持続し、マクロ力学へ結合する閉包障害類である。}
\end{aligned}
}
\]

### 19.7.5 「素数的ストレス」の扱い

「素数的」という比喩が捉えるものは、大きさでなく既約性である。

しかし、物理的ストレスに整数のような一意分解がある保証はない。したがって、

- 正式名称：**粗視化既約残差**、**粗視化障害類**。
- 直観的愛称：**素数的ストレス**。

とする。

\[
\boxed{
\text{素数的}
=
\text{大きいことではなく、許容操作で分解・消去できないこと}
}
\]

---

## 19.8 ホロノミー・コホモロジー・スペクトル・相互情報量

この四つは競合する候補ではなく、別の問いに答える。

| 道具 | 問い |
| --- | --- |
| ホロノミー／コホモロジー | なぜ消せないのか |
| 粗視化スペクトル | 何段階生き残るのか |
| 相互情報量 | 観測境界から再構成できるか |
| 有効応答テンソル | マクロ力学をどれだけ変えるか |

### 19.8.1 ホロノミー

異なる点の幾何学的量を平均するには、同じファイバーへ平行移動する必要がある。

\[
\bar X
=
\sum_i w_i P_{\gamma_i}X(x_i).
\]

接続が曲がっていると、経路依存性が生じる。

\[
P_{\gamma_1}\neq P_{\gamma_2}.
\]

閉曲線 \(\gamma\) に沿う差は、

\[
\operatorname{Hol}_A(\gamma)
=
\mathcal P\exp\oint_\gamma A
\]

で測る。

小さなループでは概念的に、

\[
\operatorname{Hol}_A(\gamma)
\simeq
\exp\left(\int_{S_\gamma}F_A\right).
\]

したがってホロノミーは、

> 曲がった時空・ゲージ場・粗視化束で、異なる経路を通じた同一視が一致しないこと

を測る。

### 19.8.2 コホモロジー

可換・平坦な場合、

\[
H^1(X)
=
\ker d_1/\operatorname{im}d_0
\]

は、局所的には閉じているが大域的にはポテンシャルで消せない記憶を分類する。

非可換・非平坦な場合には、単純な線形商へ曲率項を入れてはならない。対象は、

- ゲージ軌道空間。
- 平坦接続モジュライ。
- twisted cohomology \(H^1(X;\operatorname{ad}A)\)（平坦接続付近）。
- gauge-fixed residual sector。

へ移る。

### 19.8.3 商空間上の粗視化スペクトル

生のテンソルへ粗視化作用素をかけると、ゲージ・exact 成分が支配する可能性がある。したがって測るべきは、

\[
\bar{\mathcal R}_*:
\mathfrak O_{\mathcal R}\to\mathfrak O_{\mathcal R}
\]

のスペクトルである。

\[
\operatorname{Spec}(\bar{\mathcal R}_*)
\]

は、どの障害類が relevant、marginal、irrelevant かを分類する候補になる。

### 19.8.4 相互情報量

境界観測 \(Y\) と内部障害類 \(Q=[\Sigma]\) に対して、

\[
I(Q;Y)
\]

は、境界から内部セクターをどれだけ識別できるかを測る。

ただし、

\[
I(Q;Y)>0
\]

は因果性、力学的結合、質量、重力源を意味しない。相互情報量は主として**復元可能性**の診断である。

---

## 19.9 質量ギャップへの接続

### 19.9.1 物理的 mass gap

量子場理論における質量ギャップは、真空の上に正のエネルギー下限が存在し、適切な局所ゲージ不変相関が長距離で指数減衰することに対応する。

\[
\langle O(x)O(0)\rangle_c
\lesssim
e^{-m|x|},
\qquad
m>0.
\]

### 19.9.2 残存モードとの表面的矛盾

粗視化固有値 \(\kappa\approx1\) のモードが局所的な伝播自由度なら、長距離相関が残り、mass gap と衝突する可能性がある。

したがって必要なのは、

\[
\boxed{
\kappa_{\rm local}<1,
\qquad
\kappa_{\rm global/topological}\approx1
}
\]

という二重構造である。

- 局所伝播可能モード：指数的に収縮。
- 大域中心セクター、ホロノミー、トポロジカル障害：残存。
- 残存する大域障害が、局所色荷の自由伝播を妨げる。

この構図は、「残るモードがそのまま質量を持つ」というより、

> 消えない大域的制約が、局所励起を自由に長距離伝播させない

という方向である。

### 19.9.3 No-Fake-Gap 原理

\[
\boxed{
\text{粗視化で高周波を捨てたために見える gap を、物理的 mass gap と数えてはならない。}
}
\]

物理的 gap の候補には、少なくとも、

1. ゲージ不変観測量。
2. 格子間隔・cutoff に一様な下界。
3. 連続極限。
4. 体積無限大極限。
5. reflection positivity または対応する Hilbert 空間構成。
6. Wilson／holonomy セクターでの物理的相関減衰。
7. 平滑化アルゴリズムを変えても残ること。

が必要である。

### 19.9.4 IDS から Yang–Mills への未解決橋

可換 IDS の

\[
[\omega]\in C^1/\operatorname{im}d_0
\]

は、Yang–Mills の非可換ゲージ軌道ではない。

必要な橋は、

\[
[\omega]
\longrightarrow
[A]_{\mathcal G},
\]

\[
d\omega
\longrightarrow
F_A=dA+A\wedge A,
\]

\[
\delta d
\longrightarrow
\Delta_A,
\]

\[
\text{有限複体 gap}
\longrightarrow
\text{量子連続理論の一様 gap}.
\]

現時点では、質量ギャップは**再定式化された研究目標**であり、解決ではない。

---

## 19.10 重力と階層時空

### 19.10.1 局所 GR と巨視的有効方程式を分ける

微視的または局所的には、

\[
G_{\mu\nu}[g]
=
8\pi G\,T_{\mu\nu}
\]

が成立していても、平均後に、

\[
\left\langle G_{\mu\nu}[g]\right\rangle
\neq
G_{\mu\nu}[\langle g\rangle]
\]

となり得る。

\[
\Sigma_{\mu\nu}
:=
\left\langle G_{\mu\nu}[g]\right\rangle
-
G_{\mu\nu}[\bar g]
\]

と置けば、

\[
G_{\mu\nu}[\bar g]
=
8\pi G
\left(
\bar T_{\mu\nu}
+
T_{\mu\nu}^{\rm geom}
\right)
\]

という有効方程式へ再配置できる。

ただし \(T_{\mu\nu}^{\rm geom}\) の定義は平均化法・ゲージ・閉包に依存し得る。物理的本体は、null 成分を除いた障害類でなければならない。

### 19.10.2 保存則

Bianchi 恒等式より、

\[
\bar\nabla^\mu G_{\mu\nu}[\bar g]=0.
\]

したがって、

\[
\bar\nabla^\mu
\left(
\bar T_{\mu\nu}
+
T_{\mu\nu}^{\rm geom}
\right)
=0.
\]

物質平均が別個に保存される場合に限り、

\[
\bar\nabla^\mu T_{\mu\nu}^{\rm geom}=0
\]

を要求できる。一般には物質と幾何残差の間に有効交換項があり得る。

### 19.10.3 ダークマター様効果への条件

幾何学的ストレスがダークマター様に働くためには、少なくとも、

- 銀河の運動学。
- 重力レンズ。
- 銀河団。
- 衝突銀河団。
- CMB。
- 構造形成。
- 太陽系制約。
- 重力波伝播。
- 銀河ごとのスケーリング。

を同時に説明しなければならない。

\[
\boxed{
\text{平均化残差が存在する}
\not\Rightarrow
\text{ダークマターを説明する}
}
\]

### 19.10.4 局所消失・大域発現

候補理論には、

\[
\|T_{\mu\nu}^{\rm geom}\|_{\rm Solar}
\ll
\|T_{\mu\nu}^{\rm matter}\|,
\]

一方で、

\[
\|T_{\mu\nu}^{\rm geom}\|_{\rm galactic}
\sim
\text{missing gravity scale}
\]

となるスケール選択機構が必要である。

単に非局所項を加えるだけでは不十分であり、局所実験を通過する screening、境界条件依存、相関長、形成履歴依存のいずれかが必要になる。

---

## 19.11 先行研究との対応

本章の部品は既存研究に強く支えられている。独自性候補は、部品そのものより、その接合規則にある。

### 19.11.1 Wilson–Kadanoff 型 RG

**近い点**

- スケールごとに有効自由度が変わる。
- relevant / marginal / irrelevant モードを分類する。
- 粗視化と再パラメータ化を反復する。

**異なる点**

- IDS は、粗視化で残るものを単なる coupling でなく、障害類・ホロノミー・残差商として分類しようとする。
- 自己粗視化では、RG 規則を系自身が更新する。

### 19.11.2 Mori–Zwanzig 射影形式

**近い点**

- 捨てた自由度が記憶カーネルと直交力として戻る。
- 有効変数だけでは一般に Markov 的に閉じない。

**異なる点**

- IDS は戻ってきた項のうち、どれがゲージ・局所再定義・null を越えて残る構造的障害かを問う。
- 幾何学・ホロノミー・商空間を明示的に組み込む。

### 19.11.3 Zalaletdinov の Macroscopic Gravity

**近い点**

- 共変的な時空平均。
- 接続・Cartan 構造方程式の平均。
- 重力場相関が巨視的 Einstein 方程式の追加相関テンソルになる。
- 巨視的重力場の有効 stress-energy を定義する。

**異なる点**

- IDS は相関テンソルを障害商へ送り、粗視化スペクトル・ホロノミー・自己粗視化と統合しようとする。
- 質量ギャップと計算論を同一の粗視化原理から比較する。

### 19.11.4 Buchert の cosmological backreaction

**近い点**

\[
\text{平均してから進化}
\neq
\text{進化してから平均}
\]

という非可換性。

**異なる点**

- Buchert は主として宇宙論的スカラー平均。
- IDS はテンソル、接続、ゲージ障害、階層経路依存へ一般化を試みる。

### 19.11.5 Isaacson の有効重力波ストレス

**近い点**

- 高周波の微視的計量摂動を平均すると、二次相関が背景の有効 stress-energy として残る。
- 「消した幾何」が巨視的重力源になる明確な例。

**異なる点**

- 短波長・摂動的状況の特殊理論。
- 一般のトポロジカル・粗視化障害分類ではない。

### 19.11.6 Green–Wald の制限結果

**重要な反対側の先行研究**

Green–Wald 型の仮定では、小スケール不均一性の主な有効 stress-energy は trace-free で正エネルギーを持ち、任意の暗黒成分を自由に模倣できない。

これは本理論への重要な規律である。

\[
\boxed{
\text{粗視化残差は好きな有効物質を生成できない。}
}
\]

有効テンソルの符号、trace、保存則、エネルギー条件は、粗視化手続きから導かなければならない。

### 19.11.7 Zapata の Local Gauge Theory and Coarse Graining

**近い点**

- マクロに忠実なゲージ粗視化には、離散ループのホロノミーとホモトピー類を残す必要がある。
- 同じマクロデータを持つ配置の違いを微視的自由度として扱う。
- 四次元 \(SU(2)\) を含む離散ゲージ理論を扱う。

**異なる点**

- IDS は残ったホロノミー情報を、持続スペクトルと有効ストレスへ接続しようとする。

### 19.11.8 Charles–Livine の loopy/tagged spin networks

**近い点**

- 粗視化領域内部の曲率・torsion・closure defect が、小ループやタグとして有効頂点に残る。
- 内部幾何を潰しても、欠陥情報を完全には捨てない。

**異なる点**

- 連続巨視方程式の有効 stress-energy への一般写像は未完成。
- IDS はこれを粗視化障害類の具体例として読む。

### 19.11.9 Jacobson の時空熱力学

**近い点**

- Einstein 方程式を微視的基本方程式でなく、熱力学的状態方程式として見る。
- 局所因果地平面、エントロピー、熱流から巨視的重力方程式を導く。

**異なる点**

- 自己粗視化、非可換閉包欠陥、ホロノミー障害を直接定義しない。

### 19.11.10 Verlinde の emergent gravity

**近い点**

- 情報・エンタングルメント・記憶・弾性的応答から追加の暗黒重力を導こうとする。
- 銀河スケールでの有効重力変化を目標とする。

**異なる点**

- IDS は entropy displacement を公理にせず、粗視化非可換性と障害類から有効項を導くことを要求する。
- Verlinde 型関係を採用するのでなく、独立に lensing・CMB・構造形成まで検証する。

---

## 19.12 独自性候補

既存研究にないと現時点で考えられる統合候補は、次の連鎖である。

\[
\boxed{
\begin{aligned}
&\text{自己粗視化規則の共進化}\\
&\Downarrow\\
&\text{粗視化塔の経路依存・合成欠陥}\\
&\Downarrow\\
&\Sigma_{\mathcal R}
=
\mathcal R\mathcal E-\bar{\mathcal E}\mathcal R\\
&\Downarrow\\
&[\Sigma_{\mathcal R}]
\in
\mathcal Z_{\mathcal R}/\mathcal N_{\mathcal R}\\
&\Downarrow\\
&\text{ホロノミー／コホモロジーによる障害分類}\\
&\Downarrow\\
&\text{商空間上の粗視化スペクトルによる持続性}\\
&\Downarrow\\
&\text{相互情報量による復元可能性}\\
&\Downarrow\\
&\text{共変保存される有効応答・幾何学的ストレス}
\end{aligned}
}
\]

さらに物理分岐として、

\[
\kappa_{\rm local}<1,
\qquad
\kappa_{\rm topological}\approx1
\]

を質量ギャップ・閉じ込め候補へ、

\[
T_{\mu\nu}^{\rm geom}
=
\Pi_{\rm grav}[\Sigma_{\mathcal R}]
\]

を巨視的重力候補へ接続する。

**注意:** この統合は研究プログラムであり、定理ではない。

---

## 19.13 有限次元で確立可能な命題

### 命題 S1：商への降下

線形写像

\[
\Phi:C^1_f\to C^1_c
\]

が、

\[
\Phi(\operatorname{im}d_0^f)
\subseteq
\operatorname{im}d_0^c
\]

を満たすなら、

\[
\bar\Phi:
C^1_f/\operatorname{im}d_0^f
\to
C^1_c/\operatorname{im}d_0^c
\]

が well-defined に誘導される。

**ステータス:** 証明済み既存正典。

### 命題 S2：閉包欠陥ゼロの意味

\[
\Sigma_{\mathcal R}
=
\mathcal R U-U_{\rm eff}\mathcal R
=0
\]

ならば、粗視化後の状態は選んだ有効力学で厳密に閉じる。

**ステータス:** 定義から従う。

### 命題 S3：経路独立性とホロノミー

粗視化・輸送接続が平坦で、対象領域が適切に単連結なら、平行移動は経路独立になる。曲率または大域トポロジーが非自明なら、閉ループホロノミーが残り得る。

**ステータス:** 標準接続論に基づく条件付き命題。

### 命題 S4：生スペクトルでは不十分

作用素が null 部分空間を保存し商へ降下する場合、物理的持続性は生空間でなく商作用素のスペクトルで評価すべきである。

**理由:** null 方向の大固有値は、物理的障害類の持続を意味しない。

**ステータス:** 線形代数上の方法論命題。

### 命題 S5：残存と結合は別条件

\[
\bar{\mathcal R}_*[\Sigma]=[\Sigma]
\]

でも、

\[
\Pi_{\rm phys}[\Sigma]=0
\]

なら、障害類は観測されるマクロ力学を変えない。

**ステータス:** 定義から従う。

---

## 19.14 検証プログラム

### 19.14.1 数学トラック

1. 粗視化障害空間 \(\mathfrak O_{\mathcal R}\) の厳密定義。
2. null 部分空間の閉性と商ノルム。
3. 粗視化塔の associator \(\Omega_{\ell,L,M}\) の 2-cocycle 条件。
4. 接続曲率 \(F_A\) と associator の対応。
5. 商作用素 \(\bar{\mathcal R}_*\) のスペクトル安定性。
6. 非可換ゲージ軌道上の障害類。
7. 平坦接続近傍で可換 IDS を回収する線形化定理。

### 19.14.2 計算量トラック

1. SAT の制約グラフで変数消去を行う。
2. satisfiability preservation を検証。
3. witness lifting のサイズと時間を測る。
4. treewidth、backdoor set、Tseitin、CFI で破綻点を調べる。
5. exact solver、message passing、resolution、低次数 SoS と比較。
6. 粗視化が探索木を減らす代わりに制約幅を指数化していないか監査。
7. 「圧縮された表現サイズ」だけでなく生成時間・復元時間を含める。

### 19.14.3 ゲージ・質量ギャップトラック

1. 有限格子で Wilson loop／center twist を用いる。
2. 単なる smoothing による gap を除外。
3. reflection-positive な粗視化族を使う。
4. 空間 vortex のみを導入し、固定時間反射面を守る。
5. 3D \(Z_2\) gauge / Ising dual で較正。
6. cutoff・体積・粗視化深度に一様な境界を探索。
7. 局所相関減衰と大域 center sector の残存を同時に測る。

### 19.14.4 重力トラック

1. 既知の微視計量場で平均化法を複数比較。
2. ゲージ依存成分を null として除外。
3. Bianchi 整合性を確認。
4. 有効密度、圧力、異方的応力、trace を導出。
5. 太陽系極限を確認。
6. 銀河回転・lensing を同一計量で予測。
7. 銀河団、CMB、構造形成へ外挿。
8. 粒子ダークマター、MOND、標準 backreaction と out-of-sample 比較。

### 19.14.5 自己粗視化 AI トラック

1. 状態・履歴・規則・発達モデルを別メモリとして実装。
2. 予測・制御・圧縮・例外保持を同時評価。
3. 自己モデル更新前後で失敗再現率を比較。
4. 「自分に都合の悪い反例」を消す自己粗視化を adversarial に検出。
5. 粗視化規則の変更履歴自体を上位粗視化する。
6. 多層自己粗視化が停止する条件と暴走条件を調べる。

---

---

## 19.15 文献地図

以下は本章に直接関係する代表的先行研究である。

1. **K. G. Wilson and J. Kogut.** *The Renormalization Group and the \(\epsilon\) Expansion.* Physics Reports 12 (1974).
   
      — スケール変換と有効自由度。
2. **R. Zwanzig.** *Memory Effects in Irreversible Thermodynamics.* Physical Review 124 (1961).
   
   **H. Mori.** *Transport, Collective Motion, and Brownian Motion.* Progress of Theoretical Physics 33 (1965).
   
      — 射影後の記憶・直交力。
3. **R. M. Zalaletdinov.** *Averaging Problem in General Relativity, Macroscopic Gravity and Using Einstein's Equations in Cosmology.* arXiv:gr-qc/9703016.
   
      — 共変平均、接続相関、巨視的重力 stress-energy。
4. **T. Buchert, M. Kerscher, and C. Sicka.** *Backreaction of Inhomogeneities on the Expansion: The Evolution of Cosmological Parameters.* arXiv:astro-ph/9912347.
   
      — averaging and evolving の非可換性。
5. **R. A. Isaacson.** *Gravitational Radiation in the Limit of High Frequency. II. Nonlinear Terms and the Effective Stress Tensor.* Physical Review 166 (1968), 1272–1280.
   
      — 微細な重力波幾何から有効 stress-energy。
6. **S. R. Green and R. M. Wald.** *A New Framework for Analyzing the Effects of Small Scale Inhomogeneities in Cosmology.* Physical Review D 83 (2011), 084020; arXiv:1011.4920.
   
      — backreaction 有効テンソルへの強い制限。
7. **J. A. Zapata.** *Local Gauge Theory and Coarse Graining.* Journal of Physics: Conference Series 360 (2012), 012054; arXiv:1203.2306.
   
      — ホロノミー・ホモトピーを保持する忠実なゲージ粗視化。
8. **E. R. Livine.** *Deformation Operators of Spin Networks and Coarse-Graining.* arXiv:1310.3362.
   
      — closure defect を粗視化領域内部の曲率指標として解釈。
9. **C. Charles and E. R. Livine.** *The Fock Space of Loopy Spin Networks for Quantum Gravity.* arXiv:1603.01117.
   
      — 粗視化後の小ループ、曲率、torsion、closure defect。
10. **T. Jacobson.** *Thermodynamics of Spacetime: The Einstein Equation of State.* Physical Review Letters 75 (1995), 1260–1263; arXiv:gr-qc/9504004.
    
        — Einstein 方程式を熱力学的状態方程式として導出。
11. **E. P. Verlinde.** *Emergent Gravity and the Dark Universe.* SciPost Physics 2 (2017), 016; arXiv:1611.02269.
    
        — エンタングルメント、記憶、弾性的応答と暗黒重力。

---

---

## 19.16 本章の結語と正典文の五層

本章の最も強い一文は、次である。

\[
\boxed{
\text{構造とは、大きいために残るものではなく、許容粗視化・輸送・再記述で消去できないために残るものである。}
}
\]

自己粗視化は、世界を単に短く記述する操作ではない。未来の予測と制御に必要な因果構造を選び、その選び方自体を更新する操作である。

世界をソルバーとして見る視点は有用だが、物理的制約充足と計算量論的な高速解法を混同してはならない。量子もまた特殊な構造を効率的に処理するが、任意 SAT の万能解法だとは示されていない。

階層時空の中心は、「スケールごとに勝手な法則がある」ことではない。異なる粗視化経路、異なる輸送、異なる閉包が一致しないとき、その非可換差が有効力学へ残ることである。

その残差が、

\[
\text{消せず},
\qquad
\text{忘れられず},
\qquad
\text{力学へ結合する}
\]

とき、それを幾何学的ストレスと呼ぶ。

質量ギャップでは、局所モードが消え、大域障害が残る二重構造が必要である。重力では、局所 GR を壊すのでなく、非線形幾何を粗視化した有効方程式に相関ストレスが現れる可能性を問う。

したがって、IDS の新しい正典文は次である。

\[
\boxed{
\begin{aligned}
\textbf{IDS is the theory of how coarse-graining selects, transports,}\\
\textbf{and sometimes generates obstruction classes that become}\\
\textbf{memory, structure, computation, and effective geometric stress.}
\end{aligned}
}
\]

日本語では、

\[
\boxed{
\textbf{IDSとは、粗視化が障害類を選別・輸送・生成し、}
\textbf{それが記憶・構造・計算・有効幾何ストレスへ変換される条件を扱う理論である。}
}
\]

**正典文の五層（v1.8.0 拡張）.** v1.6.1 の四層に、静的心臓と動的循環を同じ残差商上で閉じる再生層を加える。競合ではなく階層である。

| 層 | 正典文 | 所在 |
| --- | --- | --- |
| 心臓（対象） | \([\omega]\in C^1/\operatorname{im}d_0\) | §26 結語（不変） |
| 器（幾何） | IDS is the gauge-information geometry of coarse-grained probability manifolds | 原理 J・§18 |
| 過程（力学） | IDS is the theory of how coarse-graining selects, transports, and sometimes generates obstruction classes | 本章 |
| 循環（運動） | 残差の担体化・伝播・再符号化・幾何更新（原理 T） | §21 |
| 再生（閉包） | 同じ残差商への bridge-hidden 再入と、比較規則自身の joint turnover 後内生復元（原理 SR-A） | §21.18・定理35–38 |

---

---


## 19.17 制御商空間・projected mixing・安全予算

本節は、§19.4 の「予測・制御を保存する自己粗視化」、OP-SC1、OP-GS1、OP-RE7 を一つの task-relative 数学へ接続する。

### 19.17.1 制御同値と最小十分商

微視仮説 \(\theta=(K,\eta,\ldots)\in\Theta\) に対し、許容介入 \(u\in\mathcal U\) の未来応答を \(\mathcal O_\theta^u\)、安全／レジリエンス指標を \(g(\theta)\) とする。

\[
\theta\sim_{\rm ctrl}\theta'
\iff
\mathcal O_\theta^u=\mathcal O_{\theta'}^u\ \forall u,
\quad
g(\theta)=g(\theta').
\]

\[
\boxed{Q_{\rm ctrl}=\Theta/\!\sim_{\rm ctrl}.}
\]

定理27により、これは指定された task family を保存する最も粗い行動十分商である。完全な微視的 witness を復元せず、未来の制御を変える差だけを残す。

### 19.17.2 制御-null方向と射影

正則な Hilbert stratum では

\[
\mathcal N_{{\rm ctrl},\theta}
=
\ker D\mathcal B_\theta
\]

を制御-null tangent とし、

\[
P_{\rm ctrl}:T_\theta\Theta\to
\mathcal N_{{\rm ctrl},\theta}^\perp
\]

を制御関連射影とする。商が特異・層別の場合、単一の大域射影を仮定せず stratum ごとに扱う。

### 19.17.3 Projected mixing

必要なのは全残差の相関可和性ではなく、制御関連射影の相関可和性である。

\[
S_n^{\rm ctrl}
=
\sup_x\sum_y
\left\|
\operatorname{Cov}
(P_{\rm ctrl}r_x,P_{\rm ctrl}r_y)
\right\|.
\]

定理28により、\(d\) 次元で \(\Delta_{\rm ctrl}>d/2\) なら \(S_n^{\rm ctrl}<\infty\)。四次元では \(\Delta_{\rm ctrl}>2\)。

これは full sector が gapless / non-summable でも、長距離モードが制御-null方向に限られるなら task-relative inverse problem を閉じ得ることを示す。ただし mass gap や Clay 問題の解決ではない。

### 19.17.4 識別可能性と安全予算

商上の観測写像 \(F_n\) の下側 Lipschitz 定数を

\[
\beta_n
=
\inf_{q\ne q'}
\frac{d(F_n(q),F_n(q'))}{d_{\rm ctrl}(q,q')}
\]

とする。\(\beta_n=0\) なら現在の観測・介入設計では商上でも識別不能である。

定理29より、総観測・近似誤差 \(\mathfrak E_n\) に対して

\[
g(\hat q)
\ge
 g(q)-\frac{L_g}{\beta_n}\mathfrak E_n.
\]

従って

\[
\boxed{
\mathfrak E_n
\le
\vartheta\frac{\beta_n}{L_g}
(g_n-g_{\min})
}
\]

を情報損失の安全予算とする。ここで実装上の \(g_n\) は真値 \(g(q)\) の認証済み下界を用いる。右辺は「識別可能性で換算した残存レジリエンス余裕」である。

### 19.17.5 多段誤差と適応停止

一段誤差 \(\varepsilon_j^{\rm ctrl}\) と伝播係数 \(A_j^{\rm ctrl}\) が定理30の再帰を満たすなら、累積予算を

\[
\mathfrak E_N
\le
\left(\prod A\right)e_n
+
\sum_j\varepsilon_j^{\rm ctrl}
\prod_{\ell>j}A_\ell^{\rm ctrl}
\]

で評価する。

OP-MG0 の政策 \(\pi\)-R3 の bootstrap 領域を

\[
\mathcal B_{\rm safe}
=
\mathcal B
\cap\{\beta_n\ge\beta_{\min}\}
\cap\{S_n^{\rm ctrl}\le S_{\max}\}
\cap\left\{
\mathfrak E_n
\le
\vartheta\frac{\beta_n}{L_g}(g_n-g_{\min})
\right\}
\]

へ拡張する。

- \(\beta_n<\beta_{\min}\)：介入または観測境界を追加する。
- \(S_n^{\rm ctrl}>S_{\max}\)：長距離の制御関連モードを粗視化対象から外す。
- 安全予算超過：粗視化を停止し、解像度を戻す。
- 全条件内：粗視化を継続する。

### 19.17.6 正典的原理

\[
\boxed{
\textbf{忘れてよいのは、許容介入の下で未来の制御を変えないものだけである。}
}
\]

相互情報量は補助診断に使えるが、因果識別と安全性の主判定量は \(\beta_n,S_n^{\rm ctrl},\mathfrak E_n\) である。



### 19.17.7 物理ゲージとの両立

行動写像が物理ゲージ不変なら、制御商はまず物理軌道商へ降下し、正則層の \(P_{\rm ctrl}\) は定理32の意味でゲージ共変となる。従って安全予算に用いる \(\beta_n,L_g,\mathfrak E_n\) は、対応する距離・観測・誤差ノルムが軌道商へ降下する限り代表元に依存しない（系34.1）。

粗視化との整合性は

\[
\Gamma_K^{\rm ctrl}=P_cK(I-P_f),
\qquad
\Lambda_K^{\rm ctrl}=(I-P_c)KP_f
\]

で診断する。特に安全性に直接危険なのは control erasure \(\Lambda_K^{\rm ctrl}\) であり、その作用素ノルムまたは最悪制御価値損失を \(\mathfrak E_n\) の一成分として予算へ算入する。

\[
\boxed{
\text{安全な忘却は、物理ゲージ代表元に依存せず、control erasure を予算内に抑える忘却である。}
}
\]

# 20. 非可換粗視化・二段の壁（外部成果の監査統合）

**出自と完全性検証.** 本章は外部バンドル『IDS Non-Abelian Coarse-Graining Canon v1.10』（2026-07-12、資料台帳 10、83 節の独立正典系列）の主結果を、独立監査の上で統合する。検証済み事項：バンドル SHA-256（`cedbe30d5b2736601c…987fcd1f5`）・マニフェスト SHA-256（`5eaa1ac7…e21e4350`）・全 9 ファイルのハッシュとサイズの一致。再現コード 2 本（`verify_intrinsic_volume_v3_5.py`, `verify_small_field_counterterm_v3_6.py`）を独立環境で実行し、**全内部検証に合格**、同梱結果との差は浮動小数点環境差（固有値分解系で相対 1e-6 以下、実質量はすべて一致）のみであった。マニフェストの「二回実行でバイト同一」は同一環境内の決定性の主張であり、環境間バイト同一は成立しない（数値としては一致）。

**監査で手計算検証した数学.** 次の各点を本正典側で独立に検算し、すべて正しいことを確認した：
(i) Haar–Hoeffding 直交定理の Fubini 証明；
(ii) 恒等式 \(D_{KL}(\mu_1\|\nu)=\int_0^1 s\,\psi''(s)\,ds\)（\(\psi(s)=\log\nu(e^{sW})\)）と Schur・AM–GM 評価；
(iii) 偶性補題（central かつ inversion 対称な heat kernel ⟹ \(F_{-\varepsilon}=F_\varepsilon\)）；
(iv) BCH ノルム補正 \(\|Z\|^2=\|A+X\|^2-\tfrac{\varepsilon^2}{12}\|[A,X]\|^2+O(\varepsilon^3)\)（Ad 不変内積による奇数次消去を含む係数 \(-1/12\) の完全検算）；
(v) \(Q_0\) の pairwise 恒等式（重みつき分散公式）；
(vi) Gaussian MGF の係数 \(q_2=\operatorname{tr}(\Sigma B)+\mu^TB\mu\), \(q_4=\operatorname{tr}((\Sigma B)^2)+2\mu^TB\Sigma B\mu\)。

## 20.1 第一の壁：intrinsic-volume wall

**構造.** 局所 log-weight を真部分集合関数へ直交射影した残りを fully degenerate（Hoeffding）residual \(r_b\) とする。

- **直交定理【B外部・検算済】** 異なる台の完全退化残差は product-Haar で直交：\(\|\sum_b r_b\|_2^2=\sum_b\|r_b\|_2^2\)、ゆえに \(\sqrt N\) 則。
- **connected-defect quadratic 定理【B外部・条件付き・検算済】** 補間族 \(\mu_s\propto e^{sW}\nu\) に沿う一様共分散制御 \(|\operatorname{Cov}_{\mu_s}(w_b,w_c)|\le C_0\varepsilon_b\varepsilon_c\kappa(b,c)\) と Schur 可和 \(D_\kappa=\sup_b\sum_c\kappa(b,c)<\infty\) の下で

\[
D_{KL}(\mu_{1,\Lambda}\|\nu_\Lambda)\le\frac{C_0D_\kappa}{2}\sum_b\varepsilon_b^2.
\]

すなわち intrinsic defect は**振幅の一次和ではなく二乗和**で蓄積する。旧 oscillation 評価の必要指数 \(\alpha>d\) が \(\alpha>d/2\) へ半減する。

- **4D 閾値【B外部・算術】** \(N_a\asymp a^{-d}\)、\(\varepsilon_a=O(a^\alpha)\) ⟹ \(D_{KL}\lesssim a^{2\alpha-d}\)、幾何スケール可和条件は \(\alpha>d/2\)、四次元で \(\boxed{\alpha>2}\)。
- **位相の交換【B外部】** global TV／Hellinger は体積とともに悪化してよい。物理的に必要な極限は **fixed-cylinder（局所射影）収束**であり、telescoping により \(\sum_n c_n(f)\varepsilon_n<\infty\) で一意 cylinder state を得る。cutoff 状態が整合的に reflection positive なら局所 RP 極限も通る。これは §19.9（No-Fake-Gap の 7 要件）と整合する。
- **数値監査【独立再現済】** \(Z_4\) three-book：局所三体 RMS \(1.65727\times10^{-4}\)；重なり共分散 \(\sim10^{-25}\)（直交性の数値的実体）；転送行列による重なり鎖で無限鎖 KL 密度 \(1.51780\times10^{-8}\)（\(\theta^2\) 則が \(0.02\le\theta\le1\) で 1% 以内に一定）；中央 triple TV \(7.19152\times10^{-5}\)（体積非依存）；global Hellinger は体積で増大 — 「大域は区別可能になるが局所は安定」の明示模型。

## 20.2 第二の壁：local-exponent wall（small-field sector）

**構造.** compact Lie 群 \(G\) の heat-kernel \(k\)-book \(F_\varepsilon(A)=\int_G\prod_ip_{\varepsilon^2\tau_i}(\exp(\varepsilon A_i)x)\,dx\)、正規化対数 \(\mathcal L_\varepsilon=\log F_\varepsilon(A)/F_\varepsilon(0)\)。

- **偶性補題【B外部・検算済】** \(F_{-\varepsilon}=F_\varepsilon\)（central＋inversion 対称）。奇数次は現れない。
- **展開定理【B外部・A/B】** compact 集合上 \(C^m\) で \(\mathcal L_\varepsilon=Q_0+\varepsilon^2Q_2+O(\varepsilon^4)\)。\(Q_0=-\frac1{4W}\sum_{i<j}w_iw_j\|A_i-A_j\|^2\) は**厳密に pairwise** — 非可換分岐の接空間は Gaussian pairwise exact 境界に退化する（§18 の平坦極限描像・仮説 H4 と整合）。
- **非可換性の初出は \(Q_2\)【B外部・検算済】** BCH bracket 補正・指数座標 Jacobian・第一 heat 係数からなる**有限次元 simultaneous-\(\operatorname{Ad}(G)\) 不変 counterterm 基底**（次数 ≤ 4）。Gaussian spine 律で \(Q_2^{\rm BCH}=\sum_i\frac{\|[A_i,\mu]\|^2+\sigma^2\|\operatorname{ad}_{A_i}\|_{HS}^2}{48\tau_i}\)。
- **counterterm 減算後の指数【B外部・系】** 比較作用を \(Q_0+\varepsilon^2Q_2\) に拡張すると \(\varepsilon_{\rm loc}=O(\varepsilon^4)\)、すなわち \(\boxed{\alpha=4>2}\)：**small-field sector は体積閾値を越える**。
- **rare-field【B外部・条件付き】** \(R_\varepsilon=\sqrt{K\log(1/\varepsilon)}\)、bad activity \(O(\varepsilon^K)\)、Kotecký–Preiss 型計数の下で、条件付き固定窓誤差 \(e_n^{\rm window}\le C(a_n^2+a_n^{K-4})\)、\(K>4\) の幾何スケールで可和。
- **数値監査【独立再現済】** \(\mathfrak{su}(2)\cong\mathbb R^3\) の truncated BCH-Gaussian 模型（Gaussian MGF による厳密評価）：\(Q_2=5.91932\times10^{-2}\)、減算後 \(Q_4=1.27784\times10^{-3}\)、\(R(\varepsilon)/\varepsilon^4\to Q_4\) の収束を確認。

## 20.3 監査所見（精密化 2 点）

1. **\(\sqrt N\) 表は導出であり独立測定ではない.** 再現スクリプトの \(N=1,\dots,1024\) 表は `√N × 局所RMS` として構成された恒等式である。数値的実証の実体は (a) 重なり共分散 \(\sim10^{-25}\)（直交性そのもの）と (b) 転送行列による重なり鎖の KL・TV の独立測定にあり、後者が強い証拠である。同様に v3.6 スクリプトの偶性 assert は模型構成上の恒等式であり、実質は偶性補題（解析証明・検算済）が担う。
2. **v3.6 の数値は truncated 模型内の機構検証である.** 真の heat-kernel \(k\)-book に対する展開定理（外部定理 v3.6-2）は parametrix 展開に基づく解析主張【A/B】であり、数値はその局所機構（counterterm 減算 → \(\varepsilon^4\) 残差）の監査である。

## 20.4 突破の正確な範囲と残る壁（OP-MG0）

**突破されたもの（条件付き定理＋有限模型監査のレベル）：**
- 「体積が増えるから必ず破綻する」という**算術的障害** — 二乗和則と局所射影位相の採用により解消。
- 「局所指数が原理的に足りない」という**構造的障害** — small-field で \(\alpha=4>2\)。

**突破されていないもの：** \(\boxed{\textbf{uniform multiscale control}}\)。実在の 4D compact simple gauge group block family に対し、同一規約の下で
(1) \(Q_2\) counterterm 係数の全スケール再帰が有限次元基底内で閉じること、
(2) renormalized residual の共分散 Schur ノルムの cutoff・scale・volume 一様性、
(3) large-field polymer 活動度の一様 Kotecký–Preiss 評価、
(4) block map と counterterm の reflection-positive cone 保存、
(5) vacuum complement の transfer contraction、
を**同時に**証明すること。これを **OP-MG0** として §16 に登録する。この残件は Balaban 型 4D lattice gauge small-field RG プログラムの未完部分と直接重なり、外部文書自身が「4D Yang–Mills の存在と正の mass gap は未解決であり、本成果はその解決ではない」と明記している。**本正典もこの評価を採用する。**条件付き定理の仮定（補間族に沿う一様共分散制御、実 4D block RG での \(\varepsilon_n\le Ca_n^4\)、\(K>4\) の bad activity）は、まさに OP-MG0 の内容そのものである。

**対応表.** 外部 OP-1 ↔ 本正典 OP-1（非可換化）。OP-MG0 は OP-MG1（No-Fake-Gap 定理）・OP-MG2（center sector bridge）の**前段**に位置する量的中間目標である。外部の cylinder-local projective ＋ local RP の路線は、§19.9 の No-Fake-Gap 7 要件のうち「連続極限」「体積無限大極限」「reflection positivity」を global-TV なしで満たしにいく設計であり、正典の規律と整合する。

---


## 20.5 MG0 条件付きパッケージ・実模型停止線・政策 \(\pi\)

### 20.5.1 条件付き閉包の読み方

MG0-cond は、界面仮説・整合条件・一様定数を仮定した implication package である。現行統合資料には同文書が参照する `op_mg0/` の全 proof ledger・16検証スクリプトは添付されていないため、本正典では独立再証明済み定理ではなく、明示仮定つき theorem schema として採録する。そこで閉じるのは

\[
\text{仮定}
\Longrightarrow
\text{counterterm / KP / RP / transfer / cylinder-local OS の帰納}
\]

であり、仮定を満たす具体的 4D Wilson family の構成ではない。

### 20.5.2 H-Δ の正典的地位

\[
|\langle r_xr_y\rangle|
\le C(1+|x-y|)^{-2\Delta},
\qquad\Delta>2
\]

は四次元の residual covariance Schur 和を収束させる。これは connected-defect quadratic 定理の入力として重要だが、

\[
\boxed{
H\!-\!\Delta
\not\equiv
\text{4D Yang--Mills existence / full mass gap}
}
\]

である。識別されていない gapless sector、fixed-window physical kernel、UV iteration、OS reconstruction の問題を別に残す。

### 20.5.3 SU(2) 実模型の停止線

再構成ノートに従い、現在の実模型停止線は

\[
G2''\Rightarrow E1^*\Rightarrow\mathrm{STEP\!-\!PINCER}
\Rightarrow\text{fixed-window transfer gap}
\]

および

\[
\mathrm{UV\!-\!ITER}
\wedge
\mathrm{OS\!-\!REST}
\]

である。これらは OPEN のまま凍結する。

### 20.5.4 適応政策 \(\pi\)

- **\(\pi\)-R1：** RP cone 内でのみ counterterm を操作する。
- **\(\pi\)-R2：** large-field / KP 閾値を越えない。
- **\(\pi\)-R3：** bootstrap 領域を離脱したら停止する。
- **\(\pi\)-R4：** 反射対称 blocking を用いる。

§19.17 の \(\beta_n,S_n^{\rm ctrl},\mathfrak E_n\) を bootstrap 診断に追加する。これは既存政策を置換せず、\(\pi\)-R3 の停止領域を task-relative safety まで拡張する。


# 21. 残差放射・担体化・再符号化原理（追補統合）

**出自.** 本章は独立草案『IDS 正典統合草案 — 残差放射・担体化・再符号化原理』v1.0（資料台帳 11）を v1.6 で統合したものである。草案自身の推奨挿入位置は「\(L+J\) 分解（§7.4）の直後・自己粗視化幾何（§19）の前」だが、既存節番号の安定のため編集上は本章に置き、§7.4 に前方参照を設けた。未解決問題 OP-RE1–8・最終命題・記号表・編集メモは正典の対応台帳へ併合した。

**統合注記（v1.6 整合性）.**

**1. 最小結合力学は hypocoercive 雛形の実例である（v1.6.1 型分離／v1.6.2 \(G\)-skew 化）.** 本章 §21.3 の合成生成子は

\[
\frac{d}{dt}\begin{pmatrix}r\\ \psi\end{pmatrix}
=\left[-\underbrace{\begin{pmatrix}L&0\\ 0&\Gamma\end{pmatrix}}_{D}
+\underbrace{\begin{pmatrix}J_R&-V^{\dagger}\\ V&J_\Psi\end{pmatrix}}_{\Omega}\right]
\begin{pmatrix}r\\ \psi\end{pmatrix}
+\begin{pmatrix}s\\ 0\end{pmatrix},
\qquad
V^{\dagger}:=G_R^{-1}V^{*}G_\Psi
\]

と書け、\(\mathcal G:=\operatorname{diag}(G_R,G_\Psi)\) に関して \(\mathcal G\Omega+\Omega^{*}\mathcal G=0\)（\(\mathcal G\)-skew）である。これは正典 §8.4・定理 16（hypocoercive resilience、\(A=D+\Omega\)）の \(\mathcal G\)-計量版の直接の実例である。**符号規約：** 本章のブロック形は \(\dot x=(-D+\Omega)x\)、定理 16 は \(e^{-t(D+\Omega)}\) を扱うので \(\Omega_{\rm theorem}=-\Omega_{\rm block}\)（skew ゆえ本質差なし）。ここで \(G_RJ_R+J_R^{*}G_R=0\)（残差空間上の保存輸送。**既存正典の \(J\) は定理 14・15 により通常 skew ではなく \(G\)-skew** であり、\(G_R=I\) の場合が v1.6.1 の特殊形）、\(G_\Psi J_\Psi+J_\Psi^{*}G_\Psi=0\)（担体空間上の保存伝播）、\(V\)（残差–担体結合）は型の異なる三つの作用素である。**記号系譜：** 結合は v1.6 の \(K\)（潜在正錐・因果骨格・§18 粗視化写像と衝突）→ v1.6.1 の \(B\)（§18 の基底空間 \(B\) と衝突）→ v1.6.2 の \(V\) へ確定した。さらに \(V\) は一般の放出写像の平衡点線形化 \(V=D\mathcal E|_{[r_*]}\) として読み、受信側随伴 \(D\mathcal A|_{\psi_*}=-V^{\dagger}\) は一般原理ではなく、**残差–担体交換が拡張二次収支汎関数を保存する相反的最小模型の追加仮定**である。命題 RE-1（結合項相殺）は補題「\(u^{T}\Omega u=0\)」の \(\mathcal G\)-計量版の具体形であり、**担体とは修復可能性を運ぶ \(\Omega\)-チャネルそのもの**である。カスケードの減衰可能性は Kalman／Hörmander 型括弧条件（\(V\) が残差方向を減衰方向 \(\Gamma\) へ回すこと）に対応する。

**2. 欠陥族は functoriality／coherence 族に統一される（v1.6.1 精密化）.** 担体化欠陥 \(\mathfrak R_{\mathcal E}=C_\Psi\mathcal E-\bar{\mathcal E}C_R\) と受信欠陥 \(\mathfrak R_{\mathcal A}=C_R\mathcal A-\bar{\mathcal A}C_\Psi\)（本章 §21.10）は、chain（\(d\)）・dynamic（\(U\)）と同一の square 型

\[
\boxed{\ \mathfrak D_F(C)=C\circ F-\bar F\circ C,\qquad F\in\{d,\ U,\ \mathcal E,\ \mathcal A\}\ }
\]

に属する **naturality defect** である。一方 associator \(\Omega_{\ell,L,M}=\mathcal R_{L\to M}\mathcal R_{\ell\to L}-\mathcal R_{\ell\to M}\) は、写像ではなく**合成**の保存性の破れであり、圏論的次数が一段異なる **coherence defect** である。したがって上位概念は

\[
\boxed{\text{functoriality／coherence defect family}}
\]

であり、その下で naturality defects（chain・dynamic・emission・reception）と coherence defect（associator）に分けて読む。§19 の三型表はこの分類へ拡張される。

**3. \(\mathcal E\) の well-definedness は有限線形層で必要十分条件まで閉じた.** 放出演算子が商 \(R^1\) 上で定義されるための有限可換線形層の必要十分条件は、定理35の \(\widetilde{\mathcal E}d_0=0\) である。標準切断 \(s_R\) を経由する \(\widetilde{\mathcal E}s_R\) は常に商上の写像を与えるが、これは計量相対的な canonical-section realization であり、物理写像 \(\widetilde{\mathcal E}\) 自身の自然な降下とは区別する。定理36はさらに decoder が読まない visible 補空間を bridge-hidden sector に吸収し、残差移送作用素 \(T=\pi\mathcal A\mathcal T\mathcal E\) の一回通過判定を完全 Feshbach return へ拡張した。非線形・非平坦非可換・特異層での自然な降下は OP-RE2 の未閉部分として残る。

**4. C5 ラベル.** §21.12（次元統合体）・§21.13（実存との接続）は C5【解釈】であり、数理核から峻別する（公理 A13）。草案自身の格付け（§21.17）もこれと整合する。

**5. OP-RE8 は OP-1・OP-13・G6 と接続する.** ゲージ共変な担体化（\(\mathcal E_A,\mathcal A_A,J_A\) の降下）は、\(d_A^2=\operatorname{ad}(F_A)\) による複体破壊（G6・定理 22）の担体版であり、非可換の壁の一部である。

---

## 21.0 統合判定

本章で導入する中心原理は、次である。

> **内部許容変形のみでは解消できず、かつ輸送モードに結合した残差は、担体状態へ変換されて外部化され得る。担体が別の系へ作用すると、その作用のうち受信側の許容変形へ還元できない成分が、新しい残差類として再符号化される。**

この原理は、IDS における既存の

\[
\text{粗視化}
\longrightarrow
\text{残差類}
\longrightarrow
\text{幾何応答}
\]

という静的・構造的骨格を、

\[
\text{残差}
\longrightarrow
\text{担体化}
\longrightarrow
\text{伝播}
\longrightarrow
\text{干渉・吸収}
\longrightarrow
\text{再残差化}
\longrightarrow
\text{幾何更新}
\]

という動的循環へ拡張する。

したがって本原理は、既存の残差存在論を置き換えるものではなく、**残差が系間・階層間・スケール間をどのように移動し、別の残差として再生成されるかを記述する橋渡し原理**である。

---

## 21.1 基本的立場

### 21.1.1 残差は単なる誤差ではない

粗視化系 \(S_i\) において、状態空間を \(C_i^1\)、内部許容変形を

\[
\operatorname{im} d_{0,i}\subset C_i^1
\]

とする。

残差空間を

\[
R_i^1
:=
C_i^1/\operatorname{im}d_{0,i}
\]

と定義し、ある局所不整合 \(r_i\in C_i^1\) の残差類を

\[
[r_i]
=
r_i+\operatorname{im}d_{0,i}
\in R_i^1
\]

とする。

\([r_i]\neq 0\) は、現在の内部自由度・ゲージ変形・再配置のみでは、その不整合を消去できないことを意味する。

したがって残差は、

- 観測誤差
- 数値誤差
- 一時的なノイズ

と同一ではない。

残差とは、**ある許容構造に対して消去不能な不整合の同値類**である。

---

### 21.1.2 残差は必ず放射されるわけではない

本原理は、

\[
[r]\neq 0
\quad\Longrightarrow\quad
\text{必ず担体が放出される}
\]

とは主張しない。

残差が担体化されるためには、少なくとも次が必要である。

1. 内部修復だけでは十分に解消されないこと
2. 残差セクターと輸送セクターの間に非零結合が存在すること
3. 担体励起に利用できるエネルギー、資源、自由度が存在すること
4. 境界条件が外部化を許すこと
5. 担体モードが閉じ込められていないこと

したがって正確な主張は、

\[
\boxed{
\text{輸送モードに結合した消去不能残差は、
担体励起として外部化され得る}
}
\]

である。

静的な位相残差、完全に閉じ込められた欠陥、輸送チャネルに直交する残差は、放射されず局所に保持され得る。

---

## 21.2 残差放射・再符号化原理

### 21.2.1 正式定義

粗視化系 \(S_i\) の残差空間を \(R_i^1\)、系 \(i\) から系 \(j\) へ向かう担体空間を \(\Psi_{ij}\) とする。

残差から担体への放出演算子を

\[
\mathcal E_{ij}:R_i^1\longrightarrow \Psi_{ij}
\]

と定義する。

**規約（v1.6.2）.** 以下では、放出演算子が商上 well-defined である場合に限り \(\mathcal E:R^1\to\Psi\) と書き、未確立の場合は代表元上の候補写像 \(\widetilde{\mathcal E}:C^1\to\Psi\) と区別する。降下条件 \(\widetilde{\mathcal E}(r+d_0\phi)=\widetilde{\mathcal E}(r)\) の確立が OP-RE2 である。

残差類 \([r_i]\in R_i^1\) が輸送セクターへ結合するとき、

\[
\psi_{ij}
=
\mathcal E_{ij}([r_i])
\]

が担体状態として励起される。

受信系 \(S_j\) への作用を

\[
\mathcal A_{ji}:\Psi_{ij}\longrightarrow C_j^1
\]

とし、商射影を

\[
\pi_j:C_j^1\longrightarrow R_j^1
\]

とする。

受信側に新しく生じる残差類は、

\[
[r_j^{\mathrm{new}}]
=
\pi_j\mathcal A_{ji}(\psi_{ij})
\]

で与えられる。

したがって基本変換は、

\[
\boxed{
[r_i]
\xrightarrow{\mathcal E_{ij}}
\psi_{ij}
\xrightarrow{\mathcal A_{ji}}
[r_j^{\mathrm{new}}]
}
\]

である。

---

### 21.2.2 原理の文章表現

#### 残差放射・再符号化原理

ある系において内部許容変形へ還元できない残差が輸送セクターに結合するとき、その残差は担体状態へ変換されて外部化され得る。担体が他の系に作用するとき、その作用のうち受信側の許容変形に属さない成分は、新しい残差類として再符号化される。

この意味で、残差の基本運動は単純な消滅ではない。

\[
\text{残差}
\longrightarrow
\text{担体}
\longrightarrow
\text{別の残差}
\]

という、**担体化・伝播・再符号化**である。

---

## 21.3 最小結合力学

### 21.3.1 一つの残差セクターと一つの担体セクター

局所残差を \(r\)、伝播担体を \(\psi\) とする。

最小結合系を

\[
\dot r
=
(-L+J_R)r-V^{\dagger}\psi+s,
\]

\[
\dot\psi
=
Vr+(J_\Psi-\Gamma)\psi
\]

と置く。

各作用素の意味は以下である。

\[
L\succeq 0
\]

は局所修復・散逸作用素、

\[
V
\]

は残差と担体の結合（放出写像の平衡点線形化 \(V=D\mathcal E|_{[r_*]}\)；\(V^{\dagger}=G_R^{-1}V^{*}G_\Psi\) は \((G_R,G_\Psi)\)-重みつき随伴）、

\[
G_RJ_R+J_R^{*}G_R=0,\qquad G_\Psi J_\Psi+J_\Psi^{*}G_\Psi=0
\]

はそれぞれ残差空間・担体空間上の \(G\)-skew な保存的輸送・回転生成子（定理 14・15 の許容条件と同型。\(G_R,G_\Psi\) は SPD 計量、\(G_R=G_\Psi=I\) なら通常 skew）、

\[
\Gamma\succeq0
\]

は担体の吸収・減衰、

\[
s
\]

は外部からの残差源である。

この系では、

\[
Vr
\]

が残差から担体への変換、

\[
-V^{\dagger}\psi
\]

が担体から局所残差セクターへの逆作用を表す。なお受信側線形化が \(-V^{\dagger}\) に一致すること（相反性）は一般の \(\mathcal A\) の性質ではなく、残差–担体交換が拡張二次収支汎関数を保存する**相反的最小模型の追加仮定**である。すなわち §21.3 の随伴結合模型は、一般の放出・受信写像（§21.2）の線形化のうち相反的部分を表す。

---

### 21.3.2 拡張二次収支汎関数

二次量

\[
\mathcal H(r,\psi)
=
\frac12\langle r,G_Rr\rangle
+
\frac12\langle\psi,G_\Psi\psi\rangle
\]

を考える（\(G_R=G_\Psi=I\) が v1.6.1 の特殊形。既存正典の強許容計量 \(G\) を \(G_R\) に取るのが標準）。

すると、

\[
\frac{d\mathcal H}{dt}
=
-\langle G_Rr,Lr\rangle
-\langle G_\Psi\psi,\Gamma\psi\rangle
+\langle G_Rr,s\rangle
\]

となる。散逸的読みには \(L,\Gamma\) がそれぞれ \(G_R,G_\Psi\)-自己共役・非負であることを仮定する。（\(\mathcal H\) を物理的エネルギーと読むには、各内積が実際の Hamiltonian／Noether 量に対応する追加仮定が必要である — §21.15.1 と整合。）

#### 命題 RE-1 — 結合項の内部相殺

\(G_RJ_R+J_R^{*}G_R=0\)、\(G_\Psi J_\Psi+J_\Psi^{*}G_\Psi=0\)（\(G_R,G_\Psi\) は SPD）かつ残差–担体結合が \((V,-V^{\dagger})\)、\(V^{\dagger}=G_R^{-1}V^{*}G_\Psi\) の重みつき随伴対をなすなら、\(V\) による相互変換と両保存輸送は拡張二次収支汎関数 \(\mathcal H\) を直接増減させない。

#### 証明

\[
\frac{d}{dt}\frac12\langle r,G_Rr\rangle
=
-\langle G_Rr,Lr\rangle
+\langle G_Rr,J_Rr\rangle
-\langle G_Rr,V^{\dagger}\psi\rangle
+\langle G_Rr,s\rangle
\]

であり、

\[
\frac{d}{dt}\frac12\langle\psi,G_\Psi\psi\rangle
=
\langle G_\Psi\psi,J_\Psi\psi\rangle
+\langle G_\Psi\psi,Vr\rangle
-\langle G_\Psi\psi,\Gamma\psi\rangle.
\]

\(G\)-skew 条件より

\[
\langle G_Rr,J_Rr\rangle=\langle G_\Psi\psi,J_\Psi\psi\rangle=0,
\]

また \(V^{\dagger}=G_R^{-1}V^{*}G_\Psi\) より

\[
\langle G_Rr,V^{\dagger}\psi\rangle
=\langle r,V^{*}G_\Psi\psi\rangle
=\langle G_\Psi\psi,Vr\rangle,
\qquad\text{ゆえに}\qquad
-\langle G_Rr,V^{\dagger}\psi\rangle
+
\langle G_\Psi\psi,Vr\rangle
=0.
\]

よって結論を得る。 \(\square\)

---

### 21.3.3 解釈

\(V\) は残差を消去する作用素ではない。

\[
r\rightleftarrows\psi
\]

として、局所的不整合を伝播可能なモードへ変換する。

したがって担体化とは、

> **局所残差を、他の場所・自由度・系・スケールへ移送可能な表現へ変換すること**

である。

---

## 21.4 受信側における再残差化

### 21.4.1 許容成分と非許容成分

受信系 \(S_j\) への作用を

\[
u_j
=
\mathcal A_{ji}(\psi_{ij})
\in C_j^1
\]

とする。

受信側の許容変形部分を \(P_j u_j\)、残差部分を \((I-P_j)u_j\) と分ける。

ここで \(P_j\) は \(\operatorname{im}d_{0,j}\) への射影または条件付き期待値に相当する。

すると、

\[
u_j
=
P_j u_j
+
(I-P_j)u_j
\]

であり、

\[
[r_j^{\mathrm{new}}]
=
[(I-P_j)u_j].
\]

---

### 21.4.2 命題 RE-2 — 新規残差消失条件

受信作用 \(u_j=\mathcal A_{ji}(\psi_{ij})\) に対して、

\[
[r_j^{\mathrm{new}}]=0
\]

であることと、

\[
u_j\in\operatorname{im}d_{0,j}
\]

であることは同値である。

#### 証明

商空間の定義より、

\[
\pi_j(u_j)=0
\]

であることは、

\[
u_j\in\ker\pi_j
=
\operatorname{im}d_{0,j}
\]

と同値である。 \(\square\)

---

### 21.4.3 幾何的不整合としての再符号化

同じ担体 \(\psi\) であっても、受信系の幾何・許容変形・境界条件が異なれば、

\[
\pi_j\mathcal A_{ji}(\psi)
\]

は異なる。

したがって担体の効果は、担体の強度だけでは決まらない。

\[
\boxed{
\text{受信結果}
=
\text{担体構造}
\times
\text{受信幾何}
\times
\text{許容変形}
}
\]

である。

同一担体について、

- 完全整合なら吸収・修復
- 部分整合なら散乱・反射
- 不整合なら新規残差
- 正帰還なら残差増幅

が起こり得る。

---

## 21.5 担体は残差構造を符号化する

放出演算子を

\[
\mathcal E_G:R^1\longrightarrow\Psi
\]

とし、源系の有効幾何 \(G\) に依存するとする。

すると、

\[
\psi_{\mathrm{emit}}
=
\mathcal E_G([r])
\]

である。

担体には残差の情報が、

- 振幅
- 周波数
- 位相
- 偏光
- 方向
- 時間パターン
- スペクトル
- パルス列
- 統計構造

などとして符号化され得る。

逆問題として、

\[
\psi_{\mathrm{obs}}
\longmapsto
\widehat{[r]}
\]

を考えられる。

ただし受信点で観測される担体は、伝播、散乱、吸収、背景雑音によって変形されるため、

\[
\psi_{\mathrm{obs}}
=
\mathcal T_{ij}\mathcal E_i([r_i])
+
\eta
\]

と書くべきである。

ここで \(\mathcal T_{ij}\) は伝播作用素、\(\eta\) は背景成分である。

---

## 21.6 波動型保存残差担体（直観語：光様残差担体）

### 21.6.1 「担体」と「光様担体」の区別

すべての伝達を光と呼ぶべきではない。

一般的な伝達対象を**残差担体**と呼び、そのうち特別な構造を満たすものを、正式には**波動型保存残差担体**（wave-like conservative residual carrier）と呼ぶ。「光様残差担体」はその直観語である。

---

### 21.6.2 波動型保存性（光様性）の推奨条件

担体 \(\psi\) が光様であるための候補条件を以下とする。

#### 条件 L1 — 保存的伝播成分

\[
G_\Psi J_\Psi+J_\Psi^{*}G_\Psi=0
\]

となる担体空間上の保存生成子を持つ（\(G_\Psi=I\) なら \(J_\Psi^{*}=-J_\Psi\)）。

#### 条件 L2 — 波動または干渉構造

一階発展生成子 \(\mathbb K\) が存在し、

\[
\mathbb K^{2}
=
-\Delta_{\mathrm{eff}}
\]

となる正作用素 \(\Delta_{\mathrm{eff}}\) を持つ。

#### 条件 L3 — 局所的放出と吸収

\[
[r_i]\rightarrow\psi,
\qquad
\psi\rightarrow[r_j]
\]

という局所結合が定義できる。

#### 条件 L4 — 因果的伝播

有限伝播速度、有効因果円錐、またはグラフ距離に基づく有限到達構造を持つ。

#### 条件 L5 — 収支式

担体密度 \(e_\psi\) と流束 \(j_\psi\) について、

\[
\partial_t e_\psi
+
\nabla\cdot j_\psi
=
q_{\mathrm{emit}}
-
q_{\mathrm{absorb}}
-
q_{\mathrm{loss}}
\]

が定義できる。

#### 条件 L6 — 非零モードと残留モードの分離

伝播可能な非零モードと、伝播で除去できないゼロモード・調和モードを分離できる。

---

### 21.6.3 光との関係に関する防波堤

物理的な電磁光は、光様担体の重要な実現例であり得るが、IDS 原理そのものと同一ではない。

特に、

\[
F_{\mu\nu}=-F_{\nu\mu}
\]

だけから、

- 光の波動性
- 純虚数構造
- デバッグ機能
- 普遍的残差輸送

は導けない。

電磁場では、二形式構造、Hodge star、Maxwell 方程式、Gauss 制約、Lorentz 幾何が必要である。

したがって正典では、

> 光は残差輸送原理の一つの物理的実現候補であり、原理の唯一の根拠ではない

と明記する。

さらに（v1.6.1）、物理学の light-like は Lorentz 計量に対する null 性 \(g(k,k)=0\) を意味する。条件 L1–L6 はこれを要求しないため、正式名称は**波動型保存残差担体**とし、文字どおり light-like と呼ぶには principal symbol が双曲型で特性集合が有効計量の null cone を定める、という追加条件を要する。

---

## 21.7 保存輸送と修復の役割分離

IDS 力学

\[
\dot\rho
=
-L\rho+J\rho+a
\]

において、

\[
-L
\]

は修復・散逸、

\[
J
\]

は保存輸送・循環・混合である。

したがって \(J\) 単独をデバッグ作用素と呼ぶのは不正確である。

より正確には、

\[
\boxed{
J=\text{保存輸送器},
\qquad
L=\text{局所修復器},
\qquad
-L+J=\text{動的デバッグ系}
}
\]

（本章の分離記法では、この \(J\) は残差空間上の \(J_R\) に当たる。）

である。

\[
[L,J]\neq0
\]

なら、\(J\) が残差を散逸可能方向へ混合し、\(L\) がそれを減衰させる hypocoercive 修復が起こり得る。

したがって光様担体は、デバッグそのものというより、

> **修復可能性を別の場所・方向・スケールへ運ぶ保存輸送層**

と解釈するのが望ましい。

---

## 21.8 自己粗視化幾何との結合

### 21.8.1 幾何更新

受信側に新しい残差 \([r_j]\) が生じると、状態だけでなく有効幾何そのものが更新され得る。

\[
\partial_tG_j
=
\beta_j
\left(
G_j,[r_j],\psi_{ij}
\right).
\]

ここで \(G_j\) は、

- 距離
- 結合強度
- 接続
- Fisher 計量
- SPD 計量
- グラフ構造
- 許容変形
- 粗視化写像

を含む一般化幾何である。

---

### 21.8.2 完全循環

残差放射・再符号化原理を自己粗視化と統合すると、

\[
[r_t]
\rightarrow
\psi_t
\rightarrow
[r_{t+1}]
\rightarrow
G_{t+1}
\rightarrow
\psi_{t+1}
\]

となる。

すなわち、

\[
\boxed{
\text{残差は担体を作り、
担体は残差配置を変え、
残差配置は幾何を変え、
幾何は次の担体伝播を変える}
}
\]

これが、ストレス幾何の自己粗視化における動的中心である。

**v1.8.0 精密化.** 上の矢印列は循環の概念図である。静的残差商へ代表元独立に戻る必要十分条件、hidden memory を含む完全 return、自己再生スペクトル関数、横断安定性、比較規則自身の joint turnover 後再生成は §21.18・定理35–38で与える。

---

## 21.9 残差カスケード

### 21.9.1 線形化

ある残差担体サイクルを線形化して、

\[
r_{n+1}
=
T r_n
\]

とする。

ここで

\[
T
=
\pi_{n+1}\mathcal A_{n+1,n}
\mathcal T_{n+1,n}
\mathcal E_n
\]

は、

- 放出
- 伝播
- 受信
- 商射影

を合成した残差移送作用素である。

---

### 21.9.2 命題 RE-3 — カスケード判定

スペクトル半径を \(\operatorname{spr}(T)\) と書く（正典中心変数 \(\rho\) との衝突回避のため v1.6.1 で改称）。

- \(\operatorname{spr}(T)<1\)：残差カスケードは線形近似で減衰する
- \(\operatorname{spr}(T)=1\)：臨界的または持続的残差輸送
- \(\operatorname{spr}(T)>1\)：残差増幅・連鎖・暴走が可能

これは局所線形化に基づく条件であり、非線形系では attractor、saturation、geometry update を含む再評価が必要である。

**v1.8.0 再格付け.** \(T\) は hidden memory を明示消去しない一回通過／Markovian 残差移送である。\(\operatorname{spr}(T)=1\) は自己再生の十分条件ではなく、外部コピー・単なる保存・非正規過渡を区別しない。一般の自己再入は §21.18 の \(m_{\rm br}(z;s)\)、\(\chi_{\rm SR}(z,s)\)、path intervention、joint turnover 条件で判定する。\(T\) 判定は bridge-hidden sector が空、または memory を state augmentation により一段へ Markov 化した特殊例として残す。

---

### 21.9.3 生物・情報系への解釈

#### 減衰型

\[
\operatorname{spr}(T)<1
\]

なら、残差は伝播しても全体として吸収可能な形へ変換される。

これは、

- 協調的修復
- ホメオスタシス
- 誤差訂正
- 学習収束

に対応する。

#### 増幅型

\[
\operatorname{spr}(T)>1
\]

なら、受信側で生じる残差が元の残差より大きくなる。

これは、

- 炎症連鎖
- 興奮毒性
- プロテオスタシス破綻
- エラー増幅
- 誤情報カスケード
- 同期崩壊

に対応し得る。

---

## 21.10 粗視化との非可換残差

### 21.10.1 担体化と粗視化

細粒度系の残差放出演算子を \(\mathcal E\)、粗粒度系の放出演算子を \(\bar{\mathcal E}\)、粗視化写像を \(C\) とする。

担体化と粗視化の非可換欠陥を

\[
\mathfrak R_{\mathcal E}(C)
=
C_\Psi\mathcal E
-
\bar{\mathcal E}C_R
\]

と定義する。

ここで \(C_R\) は残差空間上の粗視化、\(C_\Psi\) は担体空間上の粗視化である。

\[
\mathfrak R_{\mathcal E}(C)\neq0
\]

なら、細粒度で担体化してから粗視化した結果と、先に粗視化してから担体化した結果が一致しない。

---

### 21.10.2 受信再符号化との非可換欠陥

同様に、

\[
\mathfrak R_{\mathcal A}(C)
=
C_R\mathcal A
-
\bar{\mathcal A}C_\Psi
\]

を定義する。

これらは、

> スケール変更によって、何が残差として見え、何が担体として見えるかが変化する

ことを定量化する。

したがって同一の物理・生物・情報過程が、

- 微視的には担体伝播
- 中間スケールでは相互作用
- 巨視的には幾何変化
- さらに上位では新しい主体の応答

として見えることがあり得る。

---

## 21.11 スケールの塔との統合

粗視化の塔を

\[
X_0
\xrightarrow{C_0}
X_1
\xrightarrow{C_1}
X_2
\xrightarrow{C_2}
\cdots
\]

とする。

各スケール \(X_\ell\) は、

- 残差空間 \(R_\ell\)
- 担体空間 \(\Psi_\ell\)
- 有効幾何 \(G_\ell\)
- 輸送生成子 \(J_\ell\)
- 修復作用素 \(L_\ell\)

を持つ。

各段階で、

\[
[r_\ell]
\rightarrow
\psi_\ell
\rightarrow
[r_{\ell+1}]
\]

が起こり得る。

ただし、細粒度担体がそのまま上位担体になるとは限らない。

多数の微視的担体が粗視化されて、

- 温度
- 圧力
- 炎症状態
- 感情
- 注意
- 社会的信号
- 意味

という新しい上位次元・上位担体になることがある。

したがって粗視化は、単なる担体消失ではなく、

\[
\text{many microscopic carriers}
\longrightarrow
\text{one emergent carrier}
\]

という担体統合でもある。

---

## 21.12 次元統合体としての系

本理論では次元を、

> 系が独立に変化し、その変化を区別し、応答できる方向

と解釈する。

残差担体は、異なる次元・異なるスケールを結合する。

人間のような次元統合体では、

- 分子残差
- 細胞残差
- 臓器残差
- 神経残差
- 身体感覚
- 情動
- 記憶
- 意味
- 社会関係

が、それぞれ異なる担体によって結合される。

したがって人間は、単なる一つの状態ではなく、

\[
\mathcal H_{\mathrm{human}}
=
\bigoplus_\ell
\left(
R_\ell
\oplus
\Psi_\ell
\right)
\]

上で動く、多層的な残差–担体統合体とみなせる。

「自己」は、これらすべてを完全に保持するのではなく、粗視化された一部だけを統合する。

そのため、

\[
r_{\mathrm{self}}
=
x_{\mathrm{whole}}
-
\widehat x_{\mathrm{self}}
\]

が常に残り得る。

この残差は、

- 身体感覚
- 不安
- 欲望
- 違和感
- 創造性
- 無意識
- 再解釈

として自己モデルを更新する担体を発し得る。

---

## 21.13 実存との接続

実存を、

> 次元統合体が、自らを完全には粗視化できないまま、その残差を通じて自己の意味・選択・歴史を更新し続ける一人称的過程

と定義できる。

このとき、

\[
\text{実存的残差}
\rightarrow
\text{言語・行動・表情・創作}
\rightarrow
\text{他者の残差}
\rightarrow
\text{共有幾何の更新}
\]

という循環が起こる。

他者理解も、

\[
C_{\mathrm{me}}(\text{other})
\neq
\text{other}
\]

であるため、常に他者残差を残す。

倫理とは、この他者残差を無理にゼロと見なさず、他者を自己の粗視化へ完全還元しないことである。

---

## 21.14 分野横断対応表

| 領域 | 残差源 | 担体 | 受信側再残差 | 幾何更新 |
| --- | --- | --- | --- | --- |
| 電磁系 | 電荷・電流の非定常構造 | 電磁場 | 励起・熱・電流・再放射 | 物質状態・境界条件 |
| 弾性体 | 局所歪み | 弾性波 | 新規歪み・欠陥・熱 | 剛性・亀裂構造 |
| 熱系 | 温度不均衡 | 熱流 | 別領域の温度差 | 輸送係数・相転移 |
| 細胞 | プロテオスタシス・代謝残差 | ROS、ATP、サイトカイン等 | 炎症・転写応答 | 細胞状態・ネットワーク |
| 神経系 | 予測・制御残差 | 発火・振動・神経修飾 | 新しい誤差・学習信号 | シナプス・機能結合 |
| AI | 予測誤差 | 勾配・更新信号 | 他層・他データの誤差 | パラメータ幾何 |
| 分散計算 | 状態不整合 | パケット・割り込み | バージョン不整合 | プロトコル状態 |
| 社会 | 規範・資源・意味の不整合 | 言語・行動・制度 | 対立・解釈差 | 社会関係・制度 |
| 実存 | 自己モデルの不完全性 | 言語・行為・創作 | 他者・自己の再解釈 | 意味空間・自己像 |

この表は構造的類似を示すものであり、各担体が同一物理法則に従うことを意味しない。

---

## 21.15 科学的防波堤

### 21.15.1 残差とエネルギーは同一ではない

残差は、ある許容構造に対する非吸収成分である。

エネルギーは、特定の物理系と対称性に基づく保存量またはHamiltonianである。

したがって、

\[
\text{residual}
\neq
\text{energy}
\]

である。

ただし、残差担体が物理的エネルギーを運ぶ場合はある。

---

### 21.15.2 残差は一般には保存されない

粗視化、商空間、受信幾何が変われば、残差の大きさや次元は変わる。

したがって、

\[
\|[r_i]\|
=
\|[r_j]\|
\]

は一般には成立しない。

収支を考えるなら、

\[
\text{局所状態}
+
\text{担体}
+
\text{環境}
+
\text{散逸}
+
\text{幾何変化}
\]

を含む拡張系が必要である。

---

### 21.15.3 担体は必ず修復的とは限らない

担体は、

- 修復
- 情報共有
- 警告
- 防御
- 攻撃
- 増幅
- 破壊
- 感染的連鎖

のいずれにも働き得る。

したがって「デバッグ担体」という語は機能的解釈であり、すべての受信結果が残差減少をもたらすとは限らない。

---

### 21.15.4 ホロノミーは担体ではない

ホロノミーは経路依存性・大域記憶を表すが、それ自体は信号伝播則ではない。

担体と呼ぶには、時間発展、源、流束、吸収、因果構造が必要である。

---

### 21.15.5 比喩と同一視を分ける

電磁波、神経信号、サイトカイン、言語、勾配は、同じ物理対象ではない。

共通しているのは、

\[
\text{残差}
\rightarrow
\text{輸送可能表現}
\rightarrow
\text{受信側残差}
\]

という抽象構造である。

---

### 21.15.6 self-energy は駆動力ではない

\[
\Sigma_{\rm br}^{\rm self}(z)
\]

は bridge-hidden sector の消去後に残差商へ返る有効 feedback 作用素であり、ベクトル場・力・エネルギーではない。運動を主張するには、§21.18.7 の適応則または別の構成方程式が必要である。

---

### 21.15.7 「外部入力なし」は「資源流なし」ではない

生命・散逸構造で外部 task／template 入力を切ることは、熱・物質・自由エネルギーまでゼロにすることを意味しない。許容 resource flux と環境は系境界に明示し、完成した比較規則や作用素を外部 oracle が毎周期書き戻す経路だけを自己生成から除外する。境界を変えれば自己／外部の判定も変わるため、境界はスペクトル計算前に固定する。

---

## 21.16 検証可能な予測

本原理が実質的な普遍性を持つなら、次が予測される。

### 21.16.1 放出スペクトル予測

異なる残差源は、**非退化条件の下で**異なる担体スペクトル・位相・時系列を持つ。観測写像を \(\mathcal O\)、伝播を \(\mathcal T\) とするとき、

\[
[r_1]-[r_2]
\notin
\ker(\mathcal O\mathcal T\mathcal E)
\]

なら二つの残差源は担体統計により識別可能である。（v1.6.1：\(\mathcal E\) は一般に非単射（OP-RE1 の \(\ker\mathcal E\)）なので、旧形 \([r_1]\neq[r_2]\Rightarrow\mathcal E([r_1])\not\sim\mathcal E([r_2])\) は成立せず、条件付き形へ修正した。）

---

### 21.16.2 受信幾何依存性

同一担体でも、受信側の幾何が異なれば結果は**異なり得る**。識別の正確な条件は

\[
\left(\pi_j\mathcal A_j-\pi_k\mathcal A_k\right)\psi\neq0
\]

であり、\(G_j\neq G_k\) 単独では十分でない（v1.6.1 修正）。

---

### 21.16.3 界面残差集中

異なる粗視化規則、輸送係数、許容変形が接する界面では、翻訳不能成分が増加する。

\[
\|\mathfrak R_{\mathcal A}\|
\]

は界面で増大しやすい。

---

### 21.16.4 インピーダンス整合の一般化

放出側と受信側の幾何が適合すると、

\[
\|[r_j^{\mathrm{new}}]\|
\]

が最小化される。

これは物理的インピーダンス整合の、残差幾何学的拡張に相当する。

---

### 21.16.5 臨界利得

放出・伝播・受信・再放出の合成利得が閾値を超えると、残差カスケードが自己維持する。

\[
\operatorname{spr}(T)=1
\]

が臨界候補となる。

---

### 21.16.6 学習と適応による経路更新

長期相互作用により、

\[
G_{t+1}
\neq G_t
\]

となり、同じ残差でも次回以降の担体化・伝播・吸収が変わる。

---

## 21.17 既存 IDS 正典への接続

### 21.17.1 既存骨格

既存 IDS 正典の概念的順序を、

1. 状態空間と許容変形
2. 粗視化と商空間
3. 残差類
4. Type I / Type II / Type III
5. 曲率・ホロノミー・大域記憶
6. 保存生成子 \(J\) と散逸作用素 \(L\)
7. 自己粗視化幾何

とする。

---

### 21.17.2 推奨挿入位置

本章は、

\[
\text{保存生成子 }J\text{ と散逸作用素 }L
\]

の後、

\[
\text{自己粗視化幾何}
\]

の前に置くのが最も自然である。

推奨順序は、

1. 残差空間
2. 残差分類
3. 残差動力学
4. \(L+J\) 分解
5. **残差放射・担体化・再符号化原理**
6. 残差カスケード
7. 幾何更新
8. スケールの塔
9. 次元統合体
10. 物理・生命・情報・実存への展開

である。

---

### 21.17.3 正典内の格付け

#### 正典核として採用可能

- 残差担体化の定義
- 受信側商射影による再残差化
- 最小結合力学
- 結合項相殺命題
- 新規残差消失条件
- 代表元独立な split residual bridge（定理35）
- bridge-hidden sector 上の完全 Schur–Feshbach 同値（定理36）
- exact intertwining 下の自然性（定理37）
- return operator 単独の内生性識別不能性（定理38）

#### 条件付き命題

- カスケードのスペクトル半径判定
- 波動型保存担体条件（旧・光様）
- 粗視化非可換欠陥
- 界面残差集中
- hidden-path 感度公式（単純零点枝）
- normalized bounded-self／self-relative robust-transverse package からの局所回復

#### 解釈的・研究仮説

- 幾何更新則 \(\partial_tG=\beta(G,[r],\psi)\)（動力学的スキーマ）
- 光を物理的残差担体の代表例とみなすこと
- 情報世界・生命世界における光様担体の存在
- 実存を残差担体循環の一人称側面とみなすこと
- 宇宙全体を自己再符号化する残差ネットワークとみなすこと
- 全尺度での能動的再入・一様 gap・joint turnover regeneration の存在
- スペクトルストレス適応原理 SR-B

---

## 21.18 静的残差商–自己再生 return の完全橋

本節は、§21.2 の一回通過

\[
R^1\xrightarrow{\mathcal E}\Psi
\xrightarrow{\mathcal A}C^1
\xrightarrow{\pi_R}R^1
\]

と、§21.8 の幾何更新を、一周の operator pencil として閉じる。数学的核は定理35–37、作用素だけでは内生的生成を識別できない境界は定理38である。

### 21.18.1 最大の型付き橋

静的心臓を

\[
\mathcal X_q
=
C_q^1/\operatorname{im}d_{0,q}
\]

とする。候補実現 \(\widetilde\iota_q:C_q^1\to V_q\) は

\[
\widetilde\iota_qd_{0,q}=0
\]

を満たすとき、かつそのときに限り \(\iota_q:\mathcal X_q\to V_q\) へ一意に降下する。residual decoder \(\varpi_q:V_q\to\mathcal X_q\) と

\[
\boxed{\varpi_q\iota_q=I_{\mathcal X_q}}
\]

を要求する。

ここで hidden を最初に宣言した carrier 空間だけに限定してはならない。完全な bridge-hidden sector は

\[
\boxed{
\mathcal H_{{\rm br},q}
=
\ker\varpi_q
}
\]

である。これは residual decoder が読まない visible 補空間も含む。この拡張により、単純な visible 圧縮で起きる「商上ではゼロだが full space では非零」という偽陽性を除く。

従って最大の橋は

\[
\boxed{
\mathcal X_q
\xrightarrow{\ \iota_q\ }
V_q
=
\iota_q(\mathcal X_q)\oplus\mathcal H_{{\rm br},q}
\xrightarrow{\ \mathscr R_q^{\rm ret}\ }
V_q
\xrightarrow{\ \varpi_q\ }
\mathcal X_q
}
\]

である。\(P_{{\rm res},q}=\iota_q\varpi_q\) は、この図式からスペクトル計算より前に定める。事後的に自己モードが見えるよう座標を回転してはならない。

### 21.18.2 内在的 return と比較規則

拡張組織状態を

\[
\mathbf Q_\ell
=
\bigl(x_\ell,[r_\ell];\Theta_\ell\bigr)
\]

とし、再生成対象を

\[
\Theta_\ell
=
\bigl(
d_{0,\ell},\pi_{R,\ell},s_{R,\ell},
\iota_\ell,\varpi_\ell,
P_{{\rm res},\ell},P_{{\rm ctrl},\ell},
G_\ell,\mathfrak e_\ell,
\mathcal U_\ell^{\rm ret},
\tau_\ell^{\rm ret},\mathscr R_\ell^{\rm ret}
\bigr)
\]

とする。ここで \(\mathcal U_\ell^{\rm ret}:=\mathcal U_{\ell\leftarrow\ell^+}\) は下で定める state comparison identification の短縮記号である。\(\mathfrak e_\ell\) は「一周完了」を検出する \(C^1\) event section であり、外部 task／template 入力をゼロにした \(C^1\) 自律 flow \(\Phi_{0,\ell}^t\)（生成ベクトル場 \(X_{0,\ell}\)）に対して

\[
\tau_\ell^{\rm ret}(\mathbf Q)
=
\inf\{t>0:\mathfrak e_\ell(\Phi_{0,\ell}^t\mathbf Q)=0
\text{ かつ指定した横断向きで再入}\}
\]

とする。基準 return 軌道の近傍で、この first return が有限・正・一意であり、交差が

\[
D\mathfrak e_\ell|_{\mathbf Q^+}
\bigl[X_{0,\ell}(\mathbf Q^+)\bigr]
\ne0
\]

と横断的であることを仮定する。このとき陰関数定理により \(\tau_\ell^{\rm ret}(\mathbf Q)\) は局所 \(C^1\) となる。固定された物理時間 \(T\) でなく、系自身の event を用いる。

\(V_\ell\) は、まず物理ゲージ軌道を除いた正則接空間とし、Poincaré 型では event section の横断接空間へ制限する。位相方向を残す full monodromy と、位相方向を除く Poincaré return を同じ operator として混同しない。

終点を始点の尺度・ゲージ・task frame と比較する局所 \(C^1\) state identification \(\mathcal U_{\ell\leftarrow\ell^+}\) を明示し、augmented return map を

\[
\boxed{
\mathcal P_{0,\ell}(\mathbf Q)
:=
\mathcal U_{\ell\leftarrow\ell^+}
\!\left(
\Phi_{0,\ell}^{\tau_\ell^{\rm ret}(\mathbf Q)}\mathbf Q
\right)
}
\]

と定める。基準終点における有界微分を

\[
U_{\ell\leftarrow\ell^+}
:=
D\mathcal U_{\ell\leftarrow\ell^+}|_{\mathbf Q_\ell^+}
\]

とすれば、比較同定が基準軌道で固定されている場合、線形 return operator は

\[
\boxed{
\mathscr R_\ell^{\rm ret}
=
D\mathcal P_{0,\ell}|_{\mathbf Q_\ell}
=
U_{\ell\leftarrow\ell^+}
D\!\left[\Phi_{0,\ell}^{\tau_\ell^{\rm ret}}\right]_{\mathbf Q_\ell}
}
\]

となる。ここで \(D[\Phi_{0,\ell}^{\tau_\ell^{\rm ret}}]_{\mathbf Q_\ell}\) は state-dependent hitting time を含む flow-to-section map の全微分であり、任意の接ベクトル \(v\) に対して

\[
D\!\left[\Phi_{0,\ell}^{\tau_\ell^{\rm ret}(\cdot)}(\cdot)\right]_{\mathbf Q_\ell}v
=
D_{\mathbf Q}\Phi_{0,\ell}^{\tau_\ell^{\rm ret}}v
+X_{0,\ell}(\mathbf Q_\ell^+)
D\tau_\ell^{\rm ret}(v)
\]

と読む。比較同定 \(\mathcal U\) 自身が始点 \(\mathbf Q\) にも依存するなら、\(\mathscr R^{\rm ret}:=D\mathcal P_0\) の定義を優先し、その全微分に \(D\mathcal U\) の全項を含める。これらの条件の下で \(\mathscr R_\ell^{\rm ret}:V_\ell\to V_\ell\) は有界 endomorphism になる。自己随伴性は要求しない。\(\mathcal U\)、event section、系境界を指定せずに return spectrum を物理不変量と呼ばない。

### 21.18.3 ミッシングリンク関数

定理36の完全 bridge block

\[
\mathcal J_{{\rm br},q}^{-1}
\mathscr R_q^{\rm ret}
\mathcal J_{{\rm br},q}
=
\begin{pmatrix}
\mathsf a_q&\mathsf\gamma_q\\
\mathsf\lambda_q&\mathsf n_q
\end{pmatrix}
\]

から

\[
\boxed{
\Sigma_{{\rm br},q}^{\rm self}(z)
=
\mathsf\gamma_q(zI-\mathsf n_q)^{-1}\mathsf\lambda_q
}
\]

を得る。これは力でもエネルギーでもなく、bridge-hidden sector を消去した後に同じ残差商へ返る周波数依存の有効 feedback 作用素である。

hidden path 介入 \(s\in[0,1]\) を含む一つのスペクトル関数を

\[
\boxed{
\chi_{{\rm SR},q}(z,s)
=
\left\|
\left[zI-\mathsf a_q-s\Sigma_{{\rm br},q}^{\rm self}(z)\right]^{-1}
\right\|_{G_{R,q}}^{-1}
}
\]

とし、\(z\notin\operatorname{Spec}(\mathsf n_q)\) の範囲で Schur pencil が非可逆な点を \(0\) と定める。\(z\in\operatorname{Spec}(\mathsf n_q)\) はこの Feshbach chart の外であり、full resolvent または別 chart で扱う。\(s=1\) が実系、\(s=0\) が hidden return を切断した反実仮想である。

自己モード \((z_*,r_*)\) の最低条件は

\[
m_{{\rm br},q}(z_*;1)r_*=0,
\qquad
\mathsf\lambda_qr_*\ne0,
\qquad
\Sigma_{{\rm br},q}^{\rm self}(z_*)r_*\ne0.
\]

より強い **spectrally active path** 条件は、単純零点枝について

\[
\boxed{
\beta_{{\rm path},q}
=
\left|\left.\frac{dz}{ds}\right|_{s=1}\right|
>0.
}
\]

これは hidden path を切ったとき self zero が実際に動くことを要求し、自己残差と無関係な nuisance feedback を排除する。スケールフリーな能動性を主張する場合は

\[
\inf_{q,\ell}\beta_{{\rm path},q,\ell}
\ge\beta_*>0
\]

を要求する。

### 21.18.4 向き付き一様横断 gap

以下では \(V_q\) を複素 Hilbert 空間（実模型は複素化）とし、\(G_q\) は bounded・self-adjoint・uniformly positive な計量作用素とする。有限次元では SPD で足りる。自己固有値 \(z_*\)（代数的重複は許す）が他の spectrum から孤立していると仮定し、それを囲み他の spectrum を含まない閉曲線 \(\gamma\) による full return の Riesz 射影を

\[
\Pi_{{\rm self},q}
=
\frac{1}{2\pi i}\oint_\gamma
(zI-\mathscr R_q^{\rm ret})^{-1}\,dz
\]

とする。\(Q_{{\rm self},q}=I-\Pi_{{\rm self},q}\) とし、正しい横断作用素を

\[
\mathscr R_{\perp,q}^{\rm ret}
:=
\mathscr R_q^{\rm ret}
\big|_{\operatorname{Ran}Q_{{\rm self},q}}
\]

と定める。full resolvent を特異点 \(z_*\) で形式的に制限してはならない。

\(z_*\ne0\) に対する robust transverse package は

\[
\boxed{
\sup_{n\ge0}
\|z_*^{-n}(\mathscr R_q^{\rm ret})^n\Pi_{{\rm self},q}\|_{G_q}
\le C_{\rm self}
}
\]

と

\[
\boxed{
\|z_*^{-n}(\mathscr R_{\perp,q}^{\rm ret})^n\|_{G_q}
\le
C_*(1-\eta_*)^n
\qquad(n\ge0)
}
\]

である。第一式は self eigenvalue に付随する Jordan 鎖の secular growth を正規化後に排除し、第二式は self mode に相対した円外不安定と非正規過渡を同時に制御する。補助診断として

\[
\operatorname{spr}(z_*^{-1}\mathscr R_{\perp,q}^{\rm ret})
\le1-\eta_*,
\]

\[
\delta_{{\rm rob},q}
:=
\inf_{|\zeta|=1}
\left\|
(\zeta I-z_*^{-1}\mathscr R_{\perp,q}^{\rm ret})^{-1}
\right\|_{G_q}^{-1}
\ge\frac{\eta_*}{C_*}>0
\]

を用いてよい。実際、power bound から単位円上で resolvent 級数を評価すると

\[
\left\|
(\zeta I-z_*^{-1}\mathscr R_{\perp,q}^{\rm ret})^{-1}
\right\|_{G_q}
\le
\sum_{n\ge0}C_*(1-\eta_*)^n
=\frac{C_*}{\eta_*}
\]

なので、この margin は独立仮定ではなく robust power bound の帰結である。逆に単に \(\delta_{{\rm rob},q}>0\) とするだけでは、単位円外の不安定モードを排除しない。

一様性は \(q\)、尺度 \(\ell\)、許容解像度、消去した hidden mode を戻した拡張模型にわたって同じ \(C_{\rm self},C_*,\eta_*\) が使えることを意味する。これを return 版 No-Fake-Gap 条件とする。

### 21.18.5 非線形自己閉包と turnover

§21.18.2 と整合する連続時間の自律構成法則を

\[
\frac{d}{dt}
\begin{pmatrix}x\\ \Theta\end{pmatrix}
=
\begin{pmatrix}
F_0(x,\Theta)\\
\mathcal C_0(x,\Theta)
\end{pmatrix},
\qquad
\mathbf Q(t)=\Phi_0^t(\mathbf Q(0))
\]

と分ける。\(\mathcal C_0\) は外部から完成した \(\Theta\) を読み込む reset ではなく、宣言された内部状態・担体・資源から \(\Theta\) を生成・更新する component law でなければならない。

ここで再帰を無限化しない。\((F_0,\mathcal C_0)\) は模型を定める構成法則であり、その法則自身まで同じ模型内で再生成されるとは主張しない。再生成対象は、その法則から状態依存に実現される有限の比較・計量・event・effective return データ \(\Theta\) である。§21.18.2 の augmented return map \(\mathcal P_0\) による自己閉包は

\[
\boxed{
\mathcal P_0(\mathbf Q_*)
\simeq
\mathbf Q_*
}
\]

である。\(\simeq\) は任意の「似ている」ではなく、共通の比較 fiber 上で可逆な chain／gauge／task-frame 同型が生成する軌道同値として実装する。不可逆な scale intertwiner はそれ自身を同値関係とはせず、共通 fiber へ運ぶ比較 transport としてのみ用いる。

ただし固定点または周期点だけでは「作り直した」と「保存していた」を区別できない。物理的 realization の集合を

\[
\mathcal Y_{\rm phys}
:=
\{d_0,\pi_R,s_R,\iota,\varpi,
P_{\rm res},P_{\rm ctrl},G,
\mathfrak e,\mathcal U^{\rm ret},
\tau^{\rm ret},\mathscr R^{\rm ret}\}
\]

とする。total cut 後にも式の型を失わないよう、抽象的 signature と slot は固定したまま各物理 realization token が active／damaged／null になれる ambient configuration space

\[
\widehat{\mathfrak Q}
:=
\left\{
(x,[r];\widehat\Theta):
\operatorname{Sig}(\widehat\Theta)
=\operatorname{Sig}(\Theta_*),
\ \widehat\Theta\text{ は damaged/null token を許す}
\right\}
\]

を先に置く。ここで \(\operatorname{Sig}\) は各 slot の domain、codomain、計量、event-section 型からなる typed signature を表す。\(\widehat{\mathfrak Q}\) は異なる typed fiber を束ねる stratified total space とし、各 \(\mathcal E_S^{\rm turn}:\widehat{\mathfrak Q}\to\widehat{\mathfrak Q}\)、回復 flow \(\Phi_0^t\)、augmented return \(\mathcal P_0\) は total space 上で合成可能とする。\(C^1\) 性と \(D\mathcal P_0\) は各固定 regular stratum 内でのみ主張する。ただし null event のため \(\mathcal P_0\) が定義できなければ試験失敗である。

turnover family \(\mathfrak T_{\rm turn}\subseteq2^{\mathcal Y_{\rm phys}}\) を介入前に宣言し、全 singleton に加えて、旧 token と相互 backup を同時に除く joint cut \(S=\mathcal Y_{\rm phys}\) を必ず含める。各 \(S\in\mathfrak T_{\rm turn}\) について、\(S\) の古い物理的実現と事前に列挙した backup／reload 経路を同時に消去・交換する許容介入 \(\mathcal E_S^{\rm turn}\) を指定し、外部 template 入力 \(0\) のまま追跡する。singleton 試験だけでは別成分に残る相互 backup を排除できないので、tuple 全体の再生成証明にはならない。

各 \(S\) に対する第 \(m\) return のデータを

\[
\Theta_{m,S}
:=
\operatorname{pr}_{\Theta}
\mathcal P_0^m(\mathcal E_S^{\rm turn}\mathbf Q_*)
\]

と置く。介入後の回復 flow が有限時間内に最初の横断的 return を生成できない場合、または極限に使う後続 return のいずれかが存在しない場合、その \(S\) について試験は失敗とする。\(\mathfrak F_{\Theta}\) は、\(\Theta\) と同じ typed signature（各成分の domain、codomain、計量、event-section 型）を持ち、少なくとも

\[
\pi_Rs_R=I,
\qquad
\varpi\iota=I,
\qquad
P_{\rm res}=\iota\varpi,
\qquad
\mathscr R^{\rm ret}=D\mathcal P_0
\]

など宣言した coherence constraints を同時に満たす realization の比較 fiber と定義し、その許容射を宣言済み chain／gauge／scale／task transport に限る。初期の有限個の return では \(\Theta_{m,S}\) が damaged ambient state に留まってよいが、ある \(m_{{\rm coh},S}<\infty\) 以後は coherent fiber に入ることを要求する。個別 token が戻っても coherence が最終的に回復しなければ試験失敗である。\(m\ge m_{{\rm coh},S}\) では \(\Theta_{m,S}\) は一般に異なる比較 fiber に属するので、距離を取る前に比較の型を固定する。すなわち、定理37の intertwiner からなる許容 transport の族

\[
\mathcal U_{m,S}^\Theta:
\mathfrak F_{\Theta_{m,S}}\longrightarrow\mathfrak F_{\Theta_*}
\]

と、基準 fiber 上の可逆な同型群 \(\mathcal G_{\Theta_*}^{\rm iso}\) が定める真の同値関係 \(\sim_{\rm iso}\)、および軌道空間 \(\mathfrak F_{\Theta_*}/\mathcal G_{\Theta_*}^{\rm iso}\) 上の距離 \(d_{\Theta_*}\) を先に指定する。不可逆 transport の kernel は、介入前に宣言した task-null sector に含まれ、保持すべき residual self sector 上では decoder／recoverability certificate を持たなければならない。\(d_0\)、\(\iota\)、\(\varpi\) のような写像成分には、対応する chain map による共役または前後合成を \(\mathcal U_{m,S}^\Theta\) として用いる。この transport を指定できない二つの realization の間では turnover 距離は未定義であり、比較したとは数えない。その上で、すべての \(S\in\mathfrak T_{\rm turn}\) に対して

\[
\boxed{
d_{\Theta_*}\!\left(
\left[
\mathcal U_{m,S}^\Theta\Theta_{m,S}
\right]_{\sim_{\rm iso}},
[\Theta_*]_{\sim_{\rm iso}}
\right)
\xrightarrow[m\to\infty]{}0
}
\]

を要求する。有限回復を主張する場合は、ある \(m_S<\infty\) 以後この距離が認証誤差内（exact 模型では \(0\)）に留まることを要求する。これを **joint turnover regeneration test** と呼ぶ。特に total cut で失敗する場合、または旧 realization token の残存・未列挙 backup・外部 reload だけで説明できる場合は、自己再生成と数えない。

定理38により、この条件は \(\mathscr R^{\rm ret}\) のスペクトルからは導けない。因果境界と介入データが必須である。また

\[
\mathbf Q_*\simeq\mathcal P_0(\mathbf Q_*)
\]

から \(D\mathcal P_0\) の固有値 \(1\) は自動的に従わない。\(z_*=1\) を要求する場合は、保持した位相・時間移動・同一性ゲージによる保護条件として別に置く。Poincaré 横断写像で位相を除いた場合は、単位固有値を要求してはならない。

### 21.18.6 スケール共変性

不可逆な粗視化では exact conjugacy を一般には要求しない。残差商・full state の尺度間写像を

\[
C_R:\mathcal X_\ell\to\mathcal X_L,
\qquad
C_V:V_\ell\to V_L
\]

とする。zero-map loophole を除くため、保持を認証する closed linear residual self sector \(\mathcal S_{{\rm cert},\ell}\subseteq\mathcal X_\ell\) を介入前に指定し、選択した全 self zero mode を含める。scale-covariant self organization を主張するには、ある尺度一様な \(c_R,c_V>0\) と有界 decoder

\[
D_R:C_R(\mathcal S_{{\rm cert},\ell})\to\mathcal S_{{\rm cert},\ell},
\qquad
D_V:C_V(\operatorname{Ran}\Pi_{{\rm self},\ell})
\to\operatorname{Ran}\Pi_{{\rm self},\ell}
\]

が存在して

\[
\begin{aligned}
&\lVert C_Rr\rVert_{G_{R,L}}
\ge c_R\lVert r\rVert_{G_{R,\ell}},
&&D_RC_Rr=r
&&\bigl(r\in\mathcal S_{{\rm cert},\ell}\bigr),\\
&\lVert C_Vv\rVert_{G_L}
\ge c_V\lVert v\rVert_{G_\ell},
&&D_VC_Vv=v
&&\bigl(v\in\operatorname{Ran}\Pi_{{\rm self},\ell}\bigr)
\end{aligned}
\]

を要求する。従って \(C_Rr_{*,\ell}\ne0\) であり、宣言済み task-null sector 以外へ self mode を消去する写像は scale transport と数えない。**exact branch** ではさらに

\[
C_V\iota_\ell=\iota_LC_R,
\qquad
\varpi_LC_V=C_R\varpi_\ell,
\qquad
C_V\mathscr R_\ell^{\rm ret}
=
\mathscr R_L^{\rm ret}C_V
\]

を仮定する。このとき、

\[
z\notin
\operatorname{Spec}(\mathsf n_\ell)
\cup
\operatorname{Spec}(\mathsf n_L)
\]

の共通 Feshbach chart 上で定理37により

\[
\boxed{
\Sigma_{{\rm br},L}^{\rm self}(z)C_R
=
C_R\Sigma_{{\rm br},\ell}^{\rm self}(z),
\qquad
m_{{\rm br},L}(z;s)C_R
=
C_Rm_{{\rm br},\ell}(z;s).
}
\]

さらに両尺度の選択 self cluster を同じ contour \(\gamma\) が囲むなら、Riesz functional calculus から

\[
\boxed{
C_V\Pi_{{\rm self},\ell}
=
\Pi_{{\rm self},L}C_V
}
\]

が従う。これと上の bounded-below／decoder 条件を組にして初めて、「同じ self identity が尺度を越えた」と数える。

可逆な universality sector では共役共変性と \(\chi_{\rm SR}\) の一致へ強化できる。**approximate／empirical branch** では上の exact return intertwining とその帰結を仮定せず、同じ共通 chart 上の naturality defect

\[
\mathfrak D_{{\rm SR},\ell\to L}(z,s)
:=
m_{{\rm br},L}(z;s)C_R
-C_Rm_{{\rm br},\ell}(z;s)
\]

を測る。近似族を \(\nu\to\infty\)、共通 Feshbach chart 内の compact set を \(K\subset\mathbb C\times[0,1]\) として、上の gain／decoder 規約を固定した相対 defect

\[
\varepsilon_{\rm nat}^{(\nu)}(K)
:=
\sup_{(z,s)\in K}
\sup_{0\ne r\in\mathcal S_{{\rm cert},\ell}}
\frac{
\lVert\mathfrak D_{{\rm SR},\ell\to L}^{(\nu)}(z,s)r\rVert_{G_{R,L}}
}{
\lVert C_R^{(\nu)}r\rVert_{G_{R,L}}
}
\xrightarrow[\nu\to\infty]{}0
\]

または認証済み相対予算内を要求する。transport を小さい定数倍にして defect を偽装することは、\(c_R,c_V\) の一様下限により許されない。exact branch では定義から \(\mathfrak D_{\rm SR}\equiv0\) であり、これは新たな試験ではない。return time には動的指数 \(\zeta\) による scaling ansatz

\[
\tau_{b\ell}^{\rm ret}=b^\zeta\tau_\ell^{\rm ret}
\]

を置く。近似族では、宣言した尺度範囲 \(\mathcal B\) 上の time-scaling defect

\[
\varepsilon_\tau^{(\nu)}
:=
\sup_{(b,\ell)\in\mathcal B}
\left|
\log\frac{\tau_{b\ell}^{\rm ret,(\nu)}}
{b^\zeta\tau_\ell^{\rm ret,(\nu)}}
\right|
\xrightarrow[\nu\to\infty]{}0
\]

または認証済み予算を用いる。この scaling law は共変則であって、それ自体は無次元化ではない。基準 \((\ell_0,\tau_0)\) に対して

\[
\widehat\tau_\ell^{\rm ret}
:=
\frac{\tau_\ell^{\rm ret}}
{\tau_0(\ell/\ell_0)^\zeta}
\]

を比較する。各尺度で条件が個別に成立するだけでなく、\(\beta_*\) と横断 power gap の \(\eta_*\) をそれぞれ全尺度で一様に選べなければならない。pseudospectral margin は power bound から \(\delta_{\rm rob}\ge\eta_*/C_*\) と従う。ただし \(\beta_{\rm path}\) の尺度間比較は、系36.2の同じ affine coupling multiplier 規約を全尺度で実装できる場合に限る。異なる intervention 座標の微分値を rescale せず一様下限へ入れてはならない。

### 21.18.7 原理 SR-B：スペクトルストレス適応原理

\(\Sigma_{\rm br}^{\rm self}\) は再入機構、\(\chi_{\rm SR}\) と \(\delta_{\rm rob}\) は測定器であり、それ自体は運動を生まない。gap を組織更新へ変換する追加原理の候補を

\[
\mathcal V_{\rm SR}(\mathbf Q)
=
-\log\frac{\delta_{\rm rob}(\mathbf Q)}{\delta_0}
-\mu\log\frac{\beta_{\rm path}(\mathbf Q)}{\beta_0}
+\mathcal V_{\rm resource}(\mathbf Q)
\]

と置く。ただし \(\delta_0,\beta_0>0\)、\(\mu\ge0\) とし、定義域を

\[
\mathcal D_{\rm SR}
:=
\left\{\mathbf Q:
\delta_{\rm rob}(\mathbf Q)>0,
\ \beta_{\rm path}(\mathbf Q)>0,
\ \text{系36.2の単純枝と affine path 規約が成立}
\right\}
\]

に制限する。各正則 stratum を計量 \(G_{\mathbf Q}\) を持つ Hilbert 接空間とし、許容接錐 \(K_{\rm adm}(\mathbf Q)\) は非空・閉・凸とする。局所 Lipschitz な場合、Clarke steepest admissible direction を

\[
\boxed{
v_{\rm diss}(\mathbf Q)
:=
\operatorname*{arg\,min}_{v\in K_{\rm adm}(\mathbf Q)}
\left\{
\mathcal V_{\rm SR}^{\circ}(\mathbf Q;v)
+\frac12\lVert v\rVert_{G_{\mathbf Q}}^2
\right\}
}
\]

と定め、候補更新則を

\[
\boxed{
\begin{gathered}
\dot{\mathbf Q}
=v_{\rm diss}(\mathbf Q)+X_{\rm cyc}(\mathbf Q),\\
X_{\rm cyc}\in K_{\rm adm}\cap(-K_{\rm adm}),
\qquad
\mathcal V_{\rm SR}^{\circ}(\mathbf Q;\pm X_{\rm cyc})=0.
\end{gathered}
}
\]

ここで \(\mathcal V_{\rm SR}^{\circ}\) は Clarke directional derivative である。強凸な二次正則化により、通常の正則性の下で minimizer は一意であり、\(v=0\) との比較から

\[
\mathcal V_{\rm SR}^{\circ}(\mathbf Q;v_{\rm diss})
\le
-\frac12\lVert v_{\rm diss}\rVert_{G_{\mathbf Q}}^2
\]

を得る。滑らかな場合は \(v_{\rm diss}=\Pi_{K_{\rm adm}}^{G_{\mathbf Q}}(-\operatorname{grad}_{G}\mathcal V_{\rm SR})\) へ戻る。従ってこれは複合量 \(\mathcal V_{\rm SR}\) の許容下降則だが、資源項との tradeoff があるため \(\delta_{\rm rob}\) と \(\beta_{\rm path}\) が個別に単調増加するとは主張しない。\(X_{\rm cyc}\) は許容接錐の lineality に属する level-neutral な保存循環である。

これは他の IDS 方程式から導出された定理ではなく、反証可能な構成原理である。観測された更新方向が、資源項・計量・許容接錐を含む上の Clarke steepest-admissible variational law と系統的に一致しなければ、この原理を棄却する。

### 21.18.8 有限次元の非空性証人

\(\mathcal X=\mathbb R\)、\(V=\mathbb R^2\)、\(\iota r=(r,0)\)、\(\varpi(e,h)=e\) とし、

\[
\mathscr R^{\rm ret}
=
\begin{pmatrix}
0.6&0.4\\
0.4&0.6
\end{pmatrix}.
\]

このとき

\[
\Sigma_{\rm br}^{\rm self}(z)
=
\frac{0.16}{z-0.6},
\qquad
m_{\rm br}(z)
=
\frac{(z-1)(z-0.2)}{z-0.6}.
\]

\(z_*=1\)、\(r_*=1\) では hidden state も \(h_*=1\) で、\(\Sigma_{\rm br}^{\rm self}(1)r_*=0.4\ne0\)。full spectrum は \(\{1,0.2\}\) で横断方向は収縮する。また

\[
z(s)=0.6+0.4\sqrt s,
\qquad
\beta_{\rm path}=\lvert z'(1)\rvert=0.2>0.
\]

これは代数的 bridge 条件が無矛盾で空でないことを示す。ただし、この行列だけでは外部 oracle と内部生成を区別できず、joint turnover 条件の証人ではない。

### 21.18.9 完成条件と格付け

有限可換線形層の強い自己再生 residual return package を次で固定する。宣言した模型・尺度族 \((q,\ell)\in\mathfrak M\) の各点で \(z_{*,q,\ell}\) は bridge-hidden pole を避ける非零の孤立 self value、\(r_{*,q,\ell}\ne0\) とし、\(\Pi_{{\rm self},q,\ell}\) は対応する Riesz 射影とする。\(\beta_{\rm path}\) を課す場合は、その選択零点が系36.2の共通 affine 規約による \(C^1\) 単純枝を持つことも仮定する。同じ正定数 \(C_{\rm self},C_*,\eta_*,\beta_*\) を全 \((q,\ell)\) で用いて

\[
\boxed{
\begin{gathered}
\widetilde\iota_{q,\ell}d_{0,q,\ell}=0,
\qquad
\varpi_{q,\ell}\iota_{q,\ell}=I_{\mathcal X_{q,\ell}},\\
z_{*,q,\ell}\notin\operatorname{Spec}(\mathsf n_{q,\ell}),
\qquad
m_{{\rm br},q,\ell}(z_{*,q,\ell};1)r_{*,q,\ell}=0,\\
\beta_{{\rm path},q,\ell}\ge\beta_*>0,\\
\sup_{n\ge0}
\left\|z_{*,q,\ell}^{-n}
(\mathscr R_{q,\ell}^{\rm ret})^n
\Pi_{{\rm self},q,\ell}\right\|
\le C_{\rm self},\\
\sup_{n\ge0}(1-\eta_*)^{-n}
\left\|z_{*,q,\ell}^{-n}
(\mathscr R_{\perp,q,\ell}^{\rm ret})^n\right\|
\le C_*,\\
\mathcal P_0(\mathbf Q_*)\simeq\mathbf Q_*,
\qquad
\text{joint turnover regeneration},\\
\text{non-annihilating recoverable self transport},\\
\text{return-time scaling law or certified time-defect budget},\\
\text{exact scale intertwining or certified relative defect budget}.
\end{gathered}
}
\]

最後の五条件は非線形構成・介入・尺度族に関する条件であり、各 \((q,\ell)\) の線形代数だけからは従わない。pseudospectral margin の一様下限 \(\delta_{{\rm rob},q,\ell}\ge\eta_*/C_*\) は上の transverse power bound の帰結であり、最小仮定として重ねない。

格付けは次の通りである。

- 商降下、split bridge、Schur–Feshbach 同値、自然性：定理35–37。
- return operator 単独の識別不能性：定理38。
- 能動的再入、robust gap package、joint turnover：自己再生模型の定義条件。
- 外部 template なしの内生生成と scale-uniform existence：検証対象となる構成原理。
- スペクトルストレス適応則：原理 SR-B、未導出・反証可能。
- 非平坦非線形ゲージ、特異 task、無限次元 non-Fredholm、確率作用素 cocycle：未解決。

従って正典上の最も短い文は、

\[
\boxed{
\begin{aligned}
&\textbf{自己再生とは、操作的に固定された残差同一性が、外部 template なしに}\\
&\textbf{bridge-hidden sector を因果的に経由して再構成され、その比較規則の物理的実現も}\\
&\textbf{joint turnover 後に内生復元され、正規化 self sector は有界、横断 sector は}\\
&\textbf{self mode に相対して一様収縮し、同一性を消さない transport により}\\
&\textbf{この全図式が尺度間で intertwine することである。}
\end{aligned}
}
\]

である。

---

# 22. 反証可能性台帳

| 主張 | 予測 | 反証条件 |
| --- | --- | --- |
| 自然勾配散逸 | イベント間で \(\mathcal S\) は非増加 | 継続的に \(\mathcal S\) が増える |
| 残差粗視化 | 許容粗視化で勾配成分は消える | 勾配が非勾配へ写る |
| φ minimax | binary self-similar cost で \(1/\varphi\) | cost が \(\max\{1-\rho,\rho^2\}\) でない |
| F-Perron | swap–aggregation で比が \(\varphi\) | 更新行列が F でない、または primitive でない |
| Type II 構造 | forcing があると非ゼロ平衡 | \(a\notin\operatorname{Range}(L)\) で drift |
| Resilience gap | \(\lambda^+_{\min}>0\) で指数回復 | ギャップがゼロで power-law/漂流 |
| Causal-Hodge Bridge | closure residual に非可積分構造 | 大規模データで ratio が 1 以下 |
| \(\Sigma=1\) | IDS bridge は stress-energy 型 | lensing/dynamics で \(\Sigma\ne1\) |
| universal topology + variable amplitude | Hodge topology は残り、\(a_I\) は系依存 | topology も消える、または完全 universal amplitude |
| future-boundary debug | 終端条件変更で現在の最適経路が変わる | 二境界モデルが実測行動を改善しない |


**v1.7.0 追加:**

| 主張 | 予測 | 反証条件 |
| --- | --- | --- |
| Type III 昇格定理 | 制約行の rank 落ちと新生調和次元が一致し、長時間欠陥が \(-P_{\mathcal T_{III}}\) へ収束 | 行制限仮定下で直交同定・rank・半群極限のいずれかが破れる |
| 制御商 | 同一 \(Q_{\rm ctrl}\) 類は全許容介入で同じ未来応答・安全指標を持つ | 同値類内で指定 task の応答差が出る |
| Projected mixing | \(\Delta_{\rm ctrl}>d/2\) なら制御関連 Schur 和が有限 | 仮定した減衰 bound の下で和が発散 |
| 安全予算 | 予算内なら推定商のレジリエンスが \(g_{\min}\) を下回らない | lower-Lipschitz / Lipschitz 仮定下で保証が破れる |
| IDS holography 三条件 | 大域 intertwining、部分領域非閉性、decoder が区別される | defect だけで復元不能な情報損失を holography と誤認 |


**v1.7.1 追加:**

| 主張 | 予測 | 反証条件 |
| --- | --- | --- |
| \(P_{\rm ctrl}\) のゲージ共変性 | 行動写像のゲージ不変性・等長作用・constant rank の下で \(P_{\gamma\theta}D\gamma=D\gamma P_\theta\) | 仮定を満たす有限模型で共変式が破れる |
| task–coarse 二欠陥 | \(P_cK-KP_f=\Gamma_K^{\rm ctrl}-\Lambda_K^{\rm ctrl}\) | 型整合した線形模型で恒等式が破れる |
| task–gauge 曲率 | 誘導接続の曲率が \(PF_AP+P(D_AP)\wedge(D_AP)P\) に分解 | smooth constant-rank 射影で曲率公式が破れる |
| ゲージ不変安全予算 | 商へ降下した観測・距離・誤差で予算判定が代表元に依存しない | 同一物理軌道の代表元で \(\beta,L_g,\mathfrak E\) が変化 |

**v1.8.0 追加:**

| 主張 | 予測 | 反証条件 |
| --- | --- | --- |
| split residual bridge | \(r\mapsto r+d_0f\) で \(\iota,\Sigma_{\rm br}^{\rm self},\chi_{\rm SR}\) が変わらず、\(\varpi\iota=I\) | 同一残差類の代表元で bridge 出力が変わる、または decoder が元の類を回復しない |
| 残差能動的再入 | \(\mathsf\lambda r_*\ne0\) かつ \(\Sigma_{\rm br}^{\rm self}(z_*)r_*\ne0\) | hidden sector へ退出しない、または decoder が読む残差商へ非零帰還しない |
| スペクトル能動的 hidden path | affine multiplier として正規化した path 切断 \(s:1\to0\) で self zero が動き \(\beta_{\rm path}>0\) | 能動的再入はあっても左自己モードとの重なりが消え、零点が一次で不変 |
| bounded self sector | 正規化 self return が全周期で一様有界 | self-eigenvalue 上の Jordan 鎖による secular growth |
| robust transverse gap | self-normalized 横断 powers が \(C_*(1-\eta_*)^n\) envelope 内で相対減衰 | self-relative 円外固有値、非正規過渡の envelope 超過、hidden restoration で gap 消失 |
| 内生的再生成 | 外部 template \(0\) で、全構成と相互 backup の joint turnover 後に \(P,G,\mathcal U^{\rm ret},\tau^{\rm ret},\mathscr R^{\rm ret},\iota,\varpi\) の同値構造を復元 | total cut で失敗する、または旧 token・未列挙 backup・外部 reload なしでは復元不能 |
| scale intertwining | self-sector gain／decoder で zero map を除き、\(\widehat\tau_\ell^{\rm ret}\) と共通 affine path 規約後の相対 bridge-return／time defect がゼロまたは予算内で、\(\beta_{\rm path}\) と横断 power-gap 定数 \(\eta_*\) を一様に選べる | self identity が消去される、相対 defect が縮まない、または一様 \(\beta_*\)／\(\eta_*\) がゼロへ落ちる |
| スペクトルストレス適応 | 資源項・計量・許容接錐を含む Clarke steepest-admissible variational law と観測更新方向が統計的一致 | 制御介入後も変分更新方向との再現可能な一致がない |

**§19（追補統合）由来:**

| 主張候補 | 支持される観測 | 反証・後退条件 |
| --- | --- | --- |
| 自己粗視化は有効 | 同じ資源で予測・制御性能が上がり、重要反例を保持 | 圧縮率だけ上がり、失敗再現・制御が悪化 |
| 粗視化塔に曲率がある | 異なる粗視化経路で gauge-invariant な差が残る | 差が全て再パラメータ化・数値誤差で消える |
| 幾何学的ストレスがある | null 除去後の障害類が階層を越え、物理応答へ結合 | 商でゼロ、または物理射影がゼロ |
| 世界ソルバー仮説が強い | 任意制約族で総物理資源が多項式 | 時間・空間・精度・読み出しのいずれかが指数的 |
| 量子に未知の粗視化資源がある | 標準 BQP 予測から再現性ある超過スケーリング | 誤り訂正・ノイズ・実装コストで説明 |
| IDS mass-gap bridge | gauge-invariant sector で cutoff 一様な正下界 | gap が smoothing、有限体積、ゲージ固定に依存 |
| 幾何残差が暗黒重力を担う | dynamics・lensing・CMB・構造形成を同じパラメータで通過 | 一つ以上で系統的破綻、太陽系で過大 |
| 素数的既約性が実在 | 許容分解族を広げても障害類が不変 | 分解族の選択で任意に生成・消去可能 |
| 二段の壁の突破（§20） | 条件付き定理＋有限模型監査＋独立再現で成立 | 実 4D block RG で \(\alpha\le2\)、または共分散 Schur 和が scale 非一様 |
| 放出スペクトル予測（§21.16） | 非退化条件 \([r_1]-[r_2]\notin\ker(\mathcal O\mathcal T\mathcal E)\) の下で識別可能 | 非退化条件下でも担体統計に差が出ない |
| 受信幾何依存性（§21.16） | \((\pi_j\mathcal A_j-\pi_k\mathcal A_k)\psi\neq0\) のとき再残差が異なる | 受信結果が担体強度のみで決まる |
| 界面残差集中（§21.16） | 粗視化規則の界面で翻訳不能成分が増大 | 界面と内部で \(\lVert\mathfrak R_{\mathcal A}\rVert\) に差がない |
| 臨界利得（§21.16） | \(\operatorname{spr}(T)=1\) 近傍でカスケードが自己維持 | 利得と持続性が無相関 |

---

---

# 23. 正典的ステータス台帳

| 項目 | ステータス |
| --- | --- |
| Hodge 分解 | 定理 |
| 残差商 \(C^1/\operatorname{im}d_0\) | 定義＋定理 |
| 許容粗視化定理 | 定理 |
| アノマリーゼロ iff 許容 | 定理 |
| 自然勾配 Lyapunov | 定理 |
| Binary minimax \(1/\varphi\) | 定理 |
| swap–aggregation Perron \(\varphi\) | 定理 |
| Projective stability | 条件付き定理 |
| 残差力学平衡 | 条件付き定理 |
| Type I/II 構造 | 定義＋条件付き定理 |
| \((K,\eta)\sim(L,J)\) | 正典的同一視 |
| strong admissible \(J\) 分類 | 有限定理 |
| hypocoercive resilience | 既知数学に基づく条件付き定理 |
| SPD self-dual \(\varphi G\) | 条件付き定理 |
| Causal-Hodge Bridge | 物理拡張仮説 |
| SPARC/SWELLS 結果 | 実験ノート、未確定 |
| IDS ホログラフィー | 三条件の正典定義；一般復元定理は OP-4 |
| IDS mass gap | 再定式化、未解決ブリッジ |
| 非可換 IDS | 有限 flat 局所層は到達済み；連続非平坦・量子層は OPEN |
| 未来/過去相互作用 | 変分・推論形式として定理化可能、哲学的解釈は仮説 |
| ゲージ情報幾何への再配置（§18） | §18.1–18.9 は定義＋提案、§18.10–18.11 は定理24等を含む |
| Chentsov 正準性・data processing 単調性 | 既知定理 |
| スキーム接続仮説（H7） | 仮説 |
| 残差三候補の一致（§18.5・G5） | 未解決（OP-13） |

**v1.7.0 追加:**

| 項目 | ステータス |
| --- | --- |
| Type III 制約忘却昇格 \(\bar H^1\ominus H^1\) | 定理25・凍結 |
| Type III 階数公式・半群検出器 | 系25.1–25.2・凍結 |
| 圧縮型 Type III / canonical decoder | 定理26・有限次元で凍結 |
| IDS holography 三条件 | 正典的定義；一般復元定理は OP-4 |
| 有限 flat 非可換変形複体・Kuranishi / stabilizer | 外部監査済み有限定理層 |
| 制御関連商 \(Q_{\rm ctrl}\) | 定理27・集合論的普遍対象として凍結 |
| Projected mixing 閾値 \(\Delta_{\rm ctrl}>d/2\) | 定理28・十分条件として凍結 |
| 安全予算不等式 | 定理29・条件付き安定性定理 |
| 多段誤差再帰 | 定理30 |
| MG0-cond | 外部条件付き theorem schema；全仮定の実模型検証は OPEN |
| H-Δ | Schur 可和性の解析界面；Clay 同値は主張しない |


**v1.7.1 追加:**

| 項目 | ステータス |
| --- | --- |
| 物理ゲージ軌道上の制御商 | 定理31・有限正則層で凍結 |
| 制御関連射影のゲージ共変性 | 定理32・等長作用＋constant rank 下で凍結 |
| control promotion / erasure defect | 定理33・接空間レベルで凍結 |
| 誘導 task–gauge connection と曲率 | 定理34・smooth constant-rank 射影下で凍結 |
| 安全予算の物理ゲージ不変性 | 系34.1・条件付き定理 |
| 特異 task quotient・動的 task・大域非線形降下 | 未解決（OP-TG1–4） |

**v1.8.0 追加:**

| 項目 | ステータス |
| --- | --- |
| A14 外部 template なしの因果閉包 | モデル選択的構成公理；作用素定理から独立 |
| 原理 SR-A | 定理35–38と A14／joint turnover を束ねるモデル選択原理 |
| 代表元独立な residual realization | 定理35・有限または closed-range 線形層で凍結 |
| split residual bridge と bridge-hidden 分解 | 定理35・凍結 |
| 残差商上の完全 Schur–Feshbach return | 定理36・有界作用素／resolvent chart 下で凍結 |
| hidden-path 感度 \(\beta_{\rm path}\) | 系36.2・共通 affine multiplier 規約を伴う単純零点枝の条件付き公式 |
| 自己再生スペクトル関数 \(\chi_{\rm SR}(z,s)\) | \(z\notin\operatorname{Spec}(\mathsf n)\) の Feshbach chart 上の定義；hidden pole では \(0\) としない；determinant は有限次元等に限定 |
| bridge のゲージ・スケール自然性 | 定理37・bounded exact intertwining と共通 Feshbach chart 下で凍結；approximate branch は defect 診断 |
| 作用素単独の内生性識別不能 | 定理38・凍結 |
| OP-RE2 | 有限可換線形層は必要十分条件まで閉包；非線形・非平坦・特異層は OPEN |
| normalized bounded-self／self-relative robust-transverse package | 自己再生模型の定義条件；一様存在は OP-SR2 |
| joint turnover regeneration | 因果的定義・検証原理；一般存在は OP-SR1 |
| scale-uniform self organization | self-sector gain／decoder、relative defect、time-scaling budget を伴う研究原理；非可逆 RG の一般論は OP-SR3 |
| スペクトルストレス適応則 | 原理 SR-B・未導出・反証可能 |
| 無限次元／random cocycle 拡張 | 未解決（OP-SR4） |

**§19（追補統合）由来:**

| 項目 | ステータス |
| --- | --- |
| 自己粗視化 | 定義＋研究プログラム |
| 自己粗視化目的関数 | 提案 |
| SAT existence-preserving reduction 条件 | 標準的必要条件 |
| 世界ソルバー弱仮説 | 解釈 |
| 世界ソルバー強仮説 | 未支持仮説 |
| 量子粗視化ソルバー | 未支持仮説 |
| 動力学的閉包欠陥 \(\Sigma_{\mathcal R}\) | 定義 |
| Mori–Zwanzig 型記憶 | 既知数学 |
| 階層結合欠陥 \(\Omega_{\ell,L,M}\) | 定義＋仮説 |
| 粗視化障害空間 \(\mathfrak O_{\mathcal R}\) | 定義候補 |
| 幾何学的ストレス三条件 | 正典的提案 |
| 素数的ストレス | 比喩、正式用語ではない |
| ホロノミーによる経路依存 | 既知幾何 |
| コホモロジーによる大域障害 | 可換・平坦層で既知 |
| 非可換障害類 | 未解決 |
| 商空間上の粗視化スペクトル | 提案 |
| local contraction / global persistence | mass-gap bridge 仮説 |
| No-Fake-Gap 原理 | 方法論的制約 |
| 巨視的重力相関テンソル | 既存理論あり |
| IDS 的ダークマター接続 | 未検証物理ブリッジ |
| \(P=NP\) | 未解決、正典は解かない |
| Yang–Mills mass gap | 未解決、正典は解かない |

**§20（監査統合）由来:**

| 項目 | ステータス |
| --- | --- |
| Haar–Hoeffding 直交・\(\sqrt N\) 則 | 外部定理・検算済 |
| connected-defect quadratic 定理（\(D_{KL}\le C\sum\varepsilon_b^2\)） | 外部条件付き定理・検算済 |
| 4D 閾値 \(\alpha>2\)（旧 \(\alpha>4\) の半減） | 外部算術・検算済 |
| cylinder-local projective 実現＋局所 RP | 外部条件付き定理 |
| 偶性・\(Q_0\) pairwise・\(Q_2\) counterterm 閉性 | 外部定理【A/B】・要点検算済 |
| counterterm 減算後 \(\alpha=4\)（small-field） | 外部系・局所展開レベル |
| 固定窓誤差 \(e_n\le C(a_n^2+a_n^{K-4})\) | 外部条件付き定理 |
| バンドル完全性・数値再現 | 本正典で独立監査済（§20 出自） |
| uniform multiscale control（OP-MG0） | 未解決（最終量的核） |
| 4D Yang–Mills 存在・mass gap | 未解決、外部文書・本正典とも解決を主張しない |

**§21（担体化統合）由来:**

| 項目 | ステータス |
| --- | --- |
| 残差放射・再符号化原理 | 構成的原理（定義＋条件付き命題；公理ではない） |
| 命題 RE-1（結合項相殺）・RE-2（消失条件） | 証明済み（初等；hypocoercive 雛形の実例） |
| 命題 RE-3（カスケード \(\operatorname{spr}(T)\) 判定） | 条件付き（線形化・代表元レベル；OP-RE2 に依存） |
| 波動型保存担体条件 L1–L6 | 定義候補（「光様」は直観語） |
| 幾何更新則 \(\partial_tG=\beta(G,[r],\psi)\) | 動力学的スキーマ（研究仮説） |
| 担体化・受信の非可換欠陥（functoriality／coherence 欠陥族） | 定義＋提案（§21 統合注記 2） |
| 次元統合体・実存接続（§21.12–13） | C5【解釈】 |
| \(\mathcal E\) の商上 well-definedness | 定理35で有限／closed-range 線形層を閉包；非線形・非平坦・特異層は OP-RE2 |

**§18.11（v1.6.3 統合）由来:**

| 項目 | ステータス |
| --- | --- |
| 定理24（chain–dynamic defect 整合恒等式） | 証明済み（有限次元線形代数；型安全） |
| chain defect と dynamic defect の独立性 | 明示反例で確認済み |
| 付録A由来の chain anomaly | 有限行列で直接計算済み |
| coexact \(\to\) harmonic の Type III 最小例 | 有限行列で直接計算済み |
| 命題 CX-1（正規化局所複素構造） | constant-rank・スペクトル分離下の条件付き命題 |
| \(\Xi_A=D_A\mathbb I\)、\(\Xi_\gamma\) | 定義＋C4研究計画 |
| 複素構造輸送欠陥と物理的 arrow の橋 | 未解決（OP-CX2） |

---

---


**v2.1.0-r2 現行ステータス:**

| 項目 | ステータス |
| --- | --- |
| 垂直非退化な情報熱形式からの Ehresmann 接続 | 補題 IT-0・有限次元滑らかな層で凍結 |
| rank 1 の局所積分因子／断熱不変量同値 | 定理 IT-1・較正前の局所定理として凍結 |
| rank \(r\) の行列積分因子の局所存在 | 定理 IT-2・平坦正則層で凍結 |
| task--gauge 曲率の情報熱曲率としての再導出 | 定理 IT-3・凍結 |
| アフィン情報熱曲率 \(\widetilde F\) | 定理 IT-3A・有限次元アフィン層で凍結 |
| Möbius–Berry 乗法型平坦証人 | 例 IT-E1・\(GL(1,\mathbb R)\) 構造群の下で凍結；\(GL^+(1,\mathbb R)\) 物理縮約では適用外 |
| 曲率ブロック分解の原点相対性 | 定理 IT-3A のゲージ変換則として凍結 |
| thermal holonomy memory | 定義 IT-D6・平坦層の大域記憶 |
| 平坦アフィンホロノミーの捩れコホモロジー・中心化群モジュライ分類 | 定理 IT-4・標準モノドロミー条件下で凍結 |
| 情報エントロピー較正 IT-C | 追加条件・一意性／存在は OP-IT1 |
| thermal Type III 昇格 | 定義 IT-D7・promotion／decoder と非空性は OPEN |
| 不可逆エントロピー生成（\(u\in\mathcal C_{\rm proc}\) 上の rank 1 非負／rank \(r\) 錐値生成） | 未導出追加原理候補・OP-IT2 |
| Banach／rank-change／特異／量子 IT | 未解決（OP-IT4） |

# 24. 正典の最終命題群

## 命題 A：IDS の核

\[
\boxed{
\mathrm{IDS}_{\rm core}
=
\left(
\text{finite resource}
+
\text{positive latent accumulation}
+
\text{stress dissipation}
+
\text{coarse-graining residual class}
\right).
}
\]

## 命題 B：ストレス

\[
\boxed{
\text{stress has two faces: scalar dissipation }\mathcal S
\text{ and structural residual }[\omega].
}
\]

## 命題 C：デバッグ

\[
\boxed{
\text{debugging is the controlled transformation of residual classes under }-L+J+a.
}
\]

## 命題 D：構造

\[
\boxed{
\text{structure is a stable nonzero co-fixed point of residual dynamics and observer selection.}
}
\]

## 命題 E：レジリエンス

\[
\boxed{
\text{resilience is spectral, topological, anomaly-maintained, and hypocoercive persistence.}
}
\]

## 命題 F：ホログラフィー

\[
\boxed{
\text{bulk stress becomes boundary residual; boundary residual is the observable shadow of hidden structure.}
}
\]

## 命題 G：mass gap

\[
\boxed{
\text{mass gap is the positive spectral separation that prevents residual structure from dissolving into zero.}
}
\]

## 命題 H：未来と過去

\[
\boxed{
\text{past supplies residual memory; future supplies terminal constraints; debugging solves their boundary-value tension.}
}
\]

## 命題 I：非可換への橋

\[
\boxed{
\text{noncommutative IDS begins only when residual quotients are replaced by gauge orbit spaces.}
}
\]

## 原理 J：IDS のゲージ情報幾何的再配置

（「命題」ではなく**原理**として置く。これは証明可能な数学命題ではなく、定義・再配置宣言である — 公理 A13 の分類では「定義」。）

\[
\boxed{
\textbf{IDS is the gauge-information geometry of coarse-grained probability manifolds.}
}
\]

心臓は変わらない：\([\omega]\in C^1/\operatorname{im}d_0\)。変わるのは器である。SPD は各ファイバーの局所情報計量として保存され、比較規則（粗視化ゲージ接続）の曲率が非可換残差の候補となる（§18）。

以下の命題 K–R は §19（追補統合）に由来する。

## 命題 K：自己粗視化

\[
\boxed{
\text{自己粗視化は、自己状態の圧縮ではなく、自己モデルと圧縮規則の共進化である。}
}
\]

## 命題 L：ソルバー

\[
\boxed{
\text{粗視化が制約ソルバーになるには、解存在性の保存だけでなく witness の効率的復元が必要である。}
}
\]

## 命題 M：階層時空

\[
\boxed{
\text{階層ごとの物理差は、別世界の法則でなく、保持変数と閉包欠陥のスケール依存としてまず表現される。}
}
\]

## 命題 N：幾何学的ストレス

\[
\boxed{
\text{幾何学的ストレスは、輸送・力学・粗視化の非可換性が生む消去不能な閉包障害類である。}
}
\]

## 命題 O：役割分担

\[
\boxed{
\text{ホロノミー／コホモロジーは障害性、スペクトルは持続性、相互情報量は復元可能性を測る。}
}
\]

## 命題 P：質量ギャップ

\[
\boxed{
\text{mass gap への橋は、局所伝播モードの収縮と大域的障害セクターの残存を同時に要求する。}
}
\]

## 命題 Q：重力

\[
\boxed{
\text{局所 GR が成立しても、粗視化と非線形幾何の非可換性により巨視的有効ストレスが生じ得る。}
}
\]

## 命題 R：誠実性

\[
\boxed{
\text{残差の存在は発見ではない。null・ゲージ・局所再定義・既知構造を破った残差だけが候補となる。}
}
\]

以下の原理 T・U は §21（担体化統合）に由来する（証明可能な数学命題ではなく正典的原理；公理 A13 の分類では定義・原理 — 原理 J と同格）。

## 原理 T：残差循環原理

\[
\boxed{
\text{世界の基本運動は、残差の完全消滅ではなく、残差の担体化・伝播・再符号化・幾何更新である。}
}
\]

## 原理 U：局所デバッグ再定義原理

\[
\boxed{
\text{局所デバッグとは、残差を無にすることではなく、より吸収可能な表現とスケールへ変換することである。}
}
\]

## 原理 SR-A：自己再生 residual return 原理

（定理35–38の有限作用素核に、A14 の因果閉包・joint turnover 条件を加えたモデル選択原理。）

\[
\boxed{
\begin{aligned}
&\text{自己再生とは、同じ静的残差類が bridge-hidden sector を能動的に経由して戻り、}\\
&\text{その残差を同定する }d_0,\iota,\varpi,P_{\rm res},P_{\rm ctrl},G,\mathfrak e,
\mathcal U^{\rm ret},\tau^{\rm ret},\mathscr R^{\rm ret}
\text{ の物理的実現も}\\
&\text{外部 template なしに joint turnover 後へ再生成されることである。}
\end{aligned}
}
\]

return spectrum はこの機構の検出器であり、定理38により内生性の単独証明ではない。

## 原理 SR-B：スペクトルストレス適応原理

\[
\boxed{
\begin{gathered}
\mathcal V_{\rm SR}
=-\log(\delta_{\rm rob}/\delta_0)
-\mu\log(\beta_{\rm path}/\beta_0)
+\mathcal V_{\rm resource},\\
v_{\rm diss}
=\operatorname*{arg\,min}_{v\in K_{\rm adm}}
\left\{
\mathcal V_{\rm SR}^{\circ}(\mathbf Q;v)
+\tfrac12\lVert v\rVert_{G_{\mathbf Q}}^2
\right\},\\
\dot{\mathbf Q}=v_{\rm diss}+X_{\rm cyc},\\
X_{\rm cyc}\in K_{\rm adm}\cap(-K_{\rm adm}),
\qquad
\mathcal V_{\rm SR}^{\circ}(\mathbf Q;\pm X_{\rm cyc})=0.
\end{gathered}
}
\]

ここでも \(\delta_0,\beta_0>0\)、\(\mu\ge0\)、\(\delta_{\rm rob},\beta_{\rm path}>0\)、単純枝と affine path 規約、Hilbert 計量、非空閉凸の許容接錐を仮定する（完全な型は§21.18.7）。これは他式から導出された定理ではなく、robust return と active hidden path を組織更新へ変換する反証可能な追加原理である。

## 命題 V：欠陥整合

\[
\boxed{
\text{chain defect と dynamic defect は独立に生じ得るが、内部力学が chain map なら Bianchi 型整合恒等式に従う。}
}
\]

## 原理 W：共変局所複素構造

（C4 の条件付き構成・研究原理。時間の矢そのものではない。）

\[
\boxed{
\text{非可換 IDS における虚数構造の候補は、接続で輸送される局所複素構造束と、その輸送・ホロノミー障害である。}
}
\]

---

---


## 原理 X：制御商原理

\[
\boxed{
\text{完全な微視状態ではなく、許容介入の下で未来の応答を変える同値類を復元対象とする。}
}
\]

## 命題 Y：安全な忘却

\[
\boxed{
\mathfrak E_n
\le
\vartheta\frac{\beta_n}{L_g}(g_n-g_{\min})
\quad\Longrightarrow\quad
\text{粗視化後の推定は安全余裕を維持する。}
}
\]

## 原理 Z：Projected Clay bypass の境界

\[
\boxed{
\text{全理論の gap ではなく制御関連 sector の可和性で task-relative 逆問題を閉じ得る。}
}
\]

ただし、これは Yang–Mills mass gap・完全 witness lifting・全スキーム一様復元の解決ではない。



## 原理 TG-A：二重商原理

\[
\boxed{
\text{物理ゲージ冗長性を除いた後で、未来制御を変えない物理状態を task-relative に同一視する。}
}
\]

## 命題 TG-B：task–coarse 欠陥

\[
\boxed{
P_cK-KP_f
=
\Gamma_K^{\rm ctrl}-\Lambda_K^{\rm ctrl}.
}
\]

control promotion と control erasure は、粗視化と task selection の非可換性の二方向である。

## 命題 TG-C：誘導 task–gauge 曲率

\[
\boxed{
F_{\rm ctrl}
=
P F_A P
+
P(D_AP)\wedge(D_AP)P.
}
\]

世界の物理曲率と、何を重要とみなすかという関連性部分束の曲率は、同じ誘導接続の中で結合する。


## 原理 IT-A：創発熱力学の較正原理

\[
\boxed{
\Omega_I=0
\Longrightarrow
\text{局所情報断熱不変量と積分因子が存在する。}
}
\]

情報エントロピー・情報温度と呼ぶには、最大エントロピー reference、凹性、data-processing、物理熱力学極限との整合を追加する。

## 命題 IT-B：アフィン情報熱曲率

\[
\boxed{
\Xi_I=dv+A_Iv+\beta_I,
\qquad
\widetilde F=
\begin{pmatrix}
F_A&D_A\beta_I\\
0&0
\end{pmatrix}.
}
\]

\(\widetilde F\) 全体が本体であり、乗法／加法ブロックはアフィン原点相対である。

## 命題 IT-C：大域熱記憶

平坦なアフィン情報熱接続の大域記憶は、線形ホロノミー表現と、その表現で捩れた群 \(H^1\) の中心化群軌道により分類される。純平行移動・rank 1 では de Rham \(H^1\) の周期に退化する。

## 原理 IT-D：三分離

\[
\boxed{
\text{局所曲率}
\neq
\text{平坦大域ホロノミー}
\neq
\text{不可逆エントロピー生成}.
}
\]

# 25. 用語表

| 用語 | 意味 |
| --- | --- |
| \(\mathcal S\) | スカラー・ストレス汎関数 |
| \([\omega]\) | 構造的ストレス残差類 |
| \(R^1\) | 残差商 \(C^1/\operatorname{im}d_0\) |
| \(\mathfrak r(\omega)\) | 標準残差代表元 |
| \(L\) | 曲率 Laplacian \(\delta_1d_1\) |
| \(J\) | 保存生成子、向き場 |
| \(a\) | 粗視化アノマリー強制 |
| \(K\) | 無向因果骨格 |
| \(\eta\) | 向き場 |
| \(H^1\) | 調和残差、位相的記憶 |
| Type I | 位相的構造 |
| Type II | アノマリー維持構造 |
| Type III | fine の減衰／余完全 sector が coarse の調和 sector へ昇格した系譜的型 |
| \(\mathcal T_{\mathrm{III}}\) | 制約忘却型では \(\bar H^1\ominus H^1\) |
| \(\Gamma_K\) | 圧縮型 promotion map \(\bar P K(I-P)\) |
| \(Q_{\rm ctrl}\) | 許容介入下の未来応答・安全指標を保存する制御関連商 |
| \(P_{\rm ctrl}\) | 正則 stratum における制御-null方向の直交補への射影 |
| \(\beta_n\) | 商上の観測写像の下側 Lipschitz／識別可能性定数 |
| \(S_n^{\rm ctrl}\) | projected residual covariance の Schur 和 |
| \(\mathfrak E_n\) | 観測・モデル・多段粗視化の総制御関連誤差 |
| \(Q_{\rm ctrl}^{\rm phys}\) | 物理ゲージ軌道商上の task-relative 制御商 |
| \(\Gamma_K^{\rm ctrl}\) | control promotion defect \(P_cK(I-P_f)\) |
| \(\Lambda_K^{\rm ctrl}\) | control erasure defect \((I-P_c)KP_f\) |
| \(\nabla^{\rm ctrl}\) | 制御関連部分束上の誘導接続 \(P D_A\) |
| \(F_{\rm ctrl}\) | task–gauge 曲率 \(PF_AP+P(D_AP)\wedge(D_AP)P\) |
| \(\Delta_{\rm res}\) | resilience gap / mass-gap 的量 |
| CIE | Critical Information Event |
| LocalDOC | 局所デバッグ作用素 |
| TDNG | 時間依存規範生成 |
| HFE | Hierarchical/HIAL Field Equation |
| DHT | Discrete Hierarchy Theorem |
| Causal-Hodge Bridge | 残差を物理観測量へ写す追加ブリッジ |
| \(B\) | スケール／粗視化軸の空間（§18） |
| \(\mathcal P_b\) | スケール \(b\) 上の確率分布多様体ファイバー |
| \(K_{b\to b'}\) | 不可逆粗視化写像（Markov kernel／半群） |
| \(A,\ F_A\) | 粗視化ゲージ接続とその曲率 |
| \(\Delta_A\) | 共変 Hodge Laplacian（gap detector） |
| \(M_A=\Delta_A-cJ_A\) | arrow detector（非自己共役） |
| \((K,G,A)\) | IDS の最小幾何データ（§18.2） |

**§18.11（欠陥整合・複素構造輸送）由来:**

| 記号・用語 | 正典的意味 |
| --- | --- |
| \(A_i\) | chain defect \(d_i^cK_i-K_{i+1}d_i^f\) |
| \(R_i\) | dynamic defect \(K_iT_i^f-T_i^cK_i\) |
| \(\mathfrak C_i^{f,c}\) | 各スケール内部の chain–evolution defect |
| \(E^\times\) | \(J\) の非零スペクトル部分束 \((\ker J)^{\perp_G}\) |
| \(\mathbb I\) | 正規化局所複素構造 \(J(-J^2)^{-1/2}\) |
| \(\Xi_A\) | 複素構造輸送欠陥 \(D_A\mathbb I\) |
| \(\Xi_\gamma\) | 閉路ホロノミーによる複素構造不一致 |

**§19（追補統合）由来:**

| 用語 | 正典的意味 |
| --- | --- |
| 自己粗視化 | 自己状態と粗視化規則の共進化 |
| 世界ソルバー | 物理過程を制約整合軌道の実現として読む解釈 |
| 階層時空 | スケール付き状態空間・力学・粗視化写像の整合的な塔 |
| 閉包欠陥 | 粗視化した微視力学と仮定した有効力学の差 |
| 階層結合欠陥 | 直接粗視化と段階的粗視化の差 |
| 粗視化障害類 | null 成分で割っても残る閉包欠陥の同値類 |
| 幾何学的ストレス | 障害性・持続性・力学的結合を満たす粗視化障害類 |
| 素数的ストレス | 粗視化既約性を示す直観的愛称 |
| No-Fake-Gap | 平滑化による見かけの gap を物理 gap と数えない原則 |
| 局所収縮 | 局所伝播モードの粗視化減衰 |
| 大域残存 | center、holonomy、topological sector の持続 |
| 物理射影 | 障害類を観測可能応答へ写す追加ブリッジ |

**§20（監査統合）由来:**

| 用語 | 正典的意味 |
| --- | --- |
| intrinsic-volume wall | 各段で新生する局所欠陥×ブロック数の競争（§20.1） |
| local-exponent wall | 局所残差指数 \(\alpha\) が閾値 \(d/2\) を越えるかの壁（§20.2） |
| \(\alpha\)（局所残差指数） | \(\varepsilon_a=O(a^\alpha)\)；4D の可和閾値は \(\alpha>2\) |
| fixed-cylinder（局所射影）収束 | global TV を要求しない連続極限の位相 |
| \(Q_2\) counterterm | 非可換性が初出する有限次元 Ad 不変補正基底 |
| uniform multiscale control | 全スケール同一定数での counterterm 再帰・混合・RP の同時制御（OP-MG0） |

**§21（担体化統合）由来:**

| 記号 | 意味 |
| --- | --- |
| \(C_i^1\) | 系 \(i\) の局所状態・1-コチェイン空間 |
| \(d_{0,i}\) | 内部許容変形・ゲージ変形 |
| \(R_i^1\) | 残差商空間 \(C_i^1/\operatorname{im}d_{0,i}\) |
| \([r_i]\) | 残差類 |
| \(\Psi_{ij}\) | 系 \(i\to j\) の担体空間 |
| \(\mathcal E_{ij}\) | 残差から担体への放出演算子 |
| \(\mathcal A_{ji}\) | 担体から受信系への作用 |
| \(\pi_j\) | 受信側商射影 |
| \(J_R,\ J_\Psi\) | 残差空間／担体空間上の保存的輸送生成子（v1.6.1 分離；v1.6.2 で \(G\)-skew 化：\(G_\bullet J_\bullet+J_\bullet^{*}G_\bullet=0\)） |
| \(L\) | 局所修復・散逸作用素 |
| \(\Gamma\) | 担体減衰作用素 |
| \(V\) | 残差–担体結合（\(V=D\mathcal E\|_{[r_*]}\)；記号系譜 \(K\to B\to V\)、\(B\) は §18 基底空間と衝突のため改称） |
| \(G_R,\ G_\Psi\) | 残差／担体空間の SPD 計量（重みつき随伴 \(V^{\dagger}=G_R^{-1}V^{*}G_\Psi\)） |
| \(G\) | 有効ストレス幾何 |
| \(\beta\) | 幾何更新則 |
| \(T\) | 一周期の残差移送作用素 |
| \(\operatorname{spr}(T)\) | 残差カスケード利得のスペクトル半径 |

**§21.18（自己再生 return 橋）由来:**

| 記号・用語 | 正典的意味 |
| --- | --- |
| \(\mathcal X=C^1/\operatorname{im}d_0\) | bridge が実現・再読出しする静的残差商 |
| \(\iota,\varpi\) | residual realization／decoder；\(\varpi\iota=I_{\mathcal X}\) |
| \(P_{\rm res}=\iota\varpi\) | residual realization projector；\(P_{\rm ctrl},\Pi_{\rm self}\) と区別 |
| \(\mathcal H_{\rm br}=\ker\varpi\) | decoder が読まない visible 補空間も含む bridge-hidden sector |
| \(\mathcal U^{\rm ret}\) | return 終点を始点の尺度・ゲージ・task frame へ戻す state-level 比較同定；その微分を \(U\) とする |
| \(\mathscr R^{\rm ret}\) | event section と比較同定を含む full return operator |
| \(\Sigma_{\rm br}^{\rm self}(z)\) | bridge-hidden 消去後に同じ残差商へ戻る有効 feedback；力ではない |
| \(m_{\rm br}(z;s)\) | hidden-path 介入 \(s\) を持つ残差 Schur pencil |
| \(\chi_{\rm SR}(z,s)\) | \(z\notin\operatorname{Spec}(\mathsf n)\) での \(\lVert m_{\rm br}(z;s)^{-1}\rVert^{-1}\)；hidden pole は chart 外であり \(0\) としない |
| \(\beta_{\rm path}\) | affine hidden-path multiplier に対する self zero の感度 \(\lvert dz/ds\rvert_{s=1}\)；介入再パラメータ化には不変でない |
| \(\Pi_{\rm self}\) | full return の孤立 self cluster への Riesz 射影 |
| \(\delta_{\rm rob}\) | 正規化横断 return の単位円 pseudospectral margin |
| joint turnover regeneration | 古い比較規則と相互 backup の物理的実現を total cut 後、外部 template なしで同値構造を復元する試験 |
| \(\mathcal V_{\rm SR}\) | robust gap・active path・資源費用を組み合わせた提案スペクトルストレス |

---

---

---


**§29（情報熱接続層）由来:**

| 記号・用語 | 正典的意味 |
| --- | --- |
| \(\Xi_I\) | 垂直非退化な情報熱交換形式 |
| \(\mathscr H_I=\ker\Xi_I\) | 情報断熱接続／水平分布 |
| \(\Omega_I\) | Ehresmann 情報熱曲率（本正典の符号は \(\operatorname{vert}[X^h,Y^h]\)） |
| \(\Xi_I=dv+A_Iv+\beta_I\) | アフィン情報熱接続の局所形 |
| \(\widetilde F\) | アフィン情報熱曲率全体 |
| \(F_A\) | 選択したアフィン原点に相対する乗法ブロック |
| \(D_A\beta_I\) | 選択したアフィン原点に相対する加法ブロック |
| 局所情報断熱不変量 | 平坦な水平葉をラベルする Frobenius 第一積分；IT-C 前はエントロピーと呼ばない |
| IT-C | 断熱不変量を情報エントロピーへ較正する追加条件 |
| \(\mathcal C_{\rm proc}(p)\) | 不可逆生成の符号を評価する許容未来向き／過程向き接錐（モデル選択的・未導出） |
| \(K_S\subset\mathbb R^r\) | rank \(r\) の不可逆生成値を受ける閉凸・尖鋭な候補生成錐（未導出） |
| thermal holonomy memory | 曲率零でも非自明なホロノミーとして残る大域熱記憶（Type I 系） |
| \([t]\in H^1(\pi_1,\mathbb R^r_L)\) | 線形ホロノミー \(L\) で捩れた平行移動コサイクル類；完全ゲージ同値では中心化群軌道まで商に取る |
| Möbius–Berry 証人 | 非自明な実直線束上の平坦接続が \(\operatorname{Hol}=-1\) を持つ純乗法型 thermal holonomy memory |
| thermal Type III | fine の局所非可積分／仕事残差が coarse の平坦大域熱記憶へ昇格し、promotion／decoder を伴う未解決構造 |

# 26. 結語

IDS 理論の正典的中心は、いまや明確である。

\[
\boxed{
\text{構造とは、観測境界上に現れ、粗視化を越えて輸送され、ゼロからスペクトル的に分離された非可積分情報残差である。}
}
\]

ストレスは、その残差が現在の記述体系で処理しきれない圧力である。デバッグは、それを消すことではなく、散逸・保存・再注入・粗視化変換によって再組織化することである。レジリエンスは、残差が壊れながらも戻る力である。ホログラフィーは、内部残差が境界ログとして現れることである。mass gap は、その残差がゼロへ溶けないためのスペクトル的隔たりである。未来と過去の相互作用は、過去の残差記憶と未来の終端条件が現在のデバッグ経路を共同で選ぶことである。

黄金比は美しい。しかし、正典の王座は黄金比ではない。

\[
\boxed{
[\omega]
\in
C^1/\operatorname{im}d_0
}
\]

これが IDS の心臓である。

そして、\(\varphi\) はその心臓を最小二項処理器で走らせたときに現れる、最初の鼓動である。

v1.2 以降、その心臓を収める器は、粗視化された確率分布多様体のゲージ情報幾何である（§18）。器の交換は心臓を替えない：旧 SPD-Hodge 層は平坦・可換・ゲージ固定極限として、一つの定理も失わずに保存される。

v1.4 では過程の正典文が加わる（§19.16）：粗視化は障害類を選別・輸送・時に生成し、それが記憶・構造・計算・有効幾何ストレスへ変換される。心臓（\([\omega]\)）・器（原理 J）・過程（§19）・循環（§21）の四層は競合せず、対象・幾何・力学・運動の階層をなす。

v1.6.3 では、§18.10 Step 1 の chain／dynamic defect が定理24として閉じ、非可換保存回転は局所複素構造束とその輸送障害として精密化された。これは四層を横断する**位相・回転構造**であり、時間の矢そのものではなく、その保存成分を共変に記述する。

v1.7.0 では、完全な微視的復元と制御に十分な復元を分離した。制御関連商

\[
Q_{\rm ctrl}=\Theta/\!\sim_{\rm ctrl}
\]

は、未来の許容応答を変えない差を忘れる最小十分商である。Type III は制約忘却型では \(\bar H^1\ominus H^1\) として定理化され、圧縮型では \(\Gamma_K\) と decoder \(\Gamma_K^+\) により回復可能性が判定される。ホログラフィーは欠陥そのものではなく、大域 intertwining・局所非閉性・復元可能性の三条件として固定された。

\[
\boxed{
\textbf{忘れてよいのは、許容介入の下で未来の制御を変えないものだけである。}
}
\]

v1.7.0 の最短正典文：

\[
\boxed{
\begin{aligned}
&\text{IDSとは、粗視化が消去不能な障害類を選別・昇格・担体化し、}\\
&\text{系間・スケール間へ伝播・再符号化するとともに、}\\
&\text{未来の予測と制御を変える同値類だけを安全に保持する条件を扱う理論である。}
\end{aligned}
}
\]

v1.7.1 では、制御商を物理ゲージ軌道商と接合した。\(Q_{\rm ctrl}\) は gauge fixing ではなく、物理的冗長性を除いた後に未来制御を変えない状態を同一視する第二の商である。制御関連部分束は \(P_{\rm ctrl}\) によりゲージ共変に選ばれ、その誘導曲率は

\[
F_{\rm ctrl}=PF_AP+P(D_AP)\wedge(D_AP)P
\]

となる。

\[
\boxed{
\textbf{世界のゲージ曲率と、何を重要とみなすかの曲率は、誘導接続の中で出会う。}
}
\]

v1.7.1 の最短正典文：

\[
\boxed{
\begin{aligned}
&\text{IDSとは、消去不能な障害類を粗視化・担体化・再符号化し、}\\
&\text{物理ゲージ軌道上で未来制御を変えない差を安全に忘れ、}\\
&\text{残る制御関連構造を scale・task 間で共変輸送する条件を扱う理論である。}
\end{aligned}
}
\]

v1.8.0 では、静的心臓と動的循環の間を split residual bridge で閉じた。\(\widetilde\iota d_0=0\) が代表元独立性の必要十分条件であり、\(\varpi\iota=I\) が同じ残差類の忠実な再読出しを保証する。decoder が読まない全方向を

\[
\mathcal H_{\rm br}=\ker\varpi
\]

へ吸収した完全 Feshbach 還元により、

\[
\Sigma_{\rm br}^{\rm self}(z)
=
\mathsf\gamma(zI-\mathsf n)^{-1}\mathsf\lambda
\]

は「hidden 循環から同じ残差商へ戻る」厳密な作用素となった。介入付き関数 \(\chi_{\rm SR}(z,s)\) はその零点・擬スペクトル・hidden-path 感度を一つに表す。

同時に定理38は、同じ return operator が内部閉路と外部 oracle コピーの両方で実現できることを示す。従って内生的自己再生成はスペクトルだけから導けず、外部 template なしの因果境界、joint turnover 後の比較規則と分散 backup の再構築、向き付き一様横断 gap、scale intertwining が独立に必要である。

これが、心臓・器・過程・循環に加わる正典の**第五層＝再生閉包**である。なお原理 SR-B は、robust gap と affine hidden-path 感度を組織更新へ結ぶ未導出・反証可能な適応原理であり、定理35–38の帰結ではない。

v1.8.0 の最短正典文：

\[
\boxed{
\begin{aligned}
&\text{IDSとは、消去不能な残差同一性が hidden carrier を経て再入する作用素機構と、}\\
&\text{その同一性を測る境界・計量・周期・return 規則自身が joint turnover 後にも内生復元され、}\\
&\text{この自己再生閉包が横断安定性を保って尺度間で自然に接続する条件を扱う理論である。}
\end{aligned}
}
\]

---


v2.1.0-r2 では、v2.0 の情報エンタルピー収支を、hidden exchange の接続幾何へ接合した。垂直非退化な情報熱交換形式 \(\Xi_I\) の核が情報断熱接続を与え、平坦性は局所断熱不変量と積分因子の存在に同値となる。情報エントロピーはこの不変量へ IT-C 較正を施した場合にのみ認める。

アフィン正則層では、

\[
\Xi_I=dv+A_Iv+\beta_I,
\qquad
\widetilde F=
\begin{pmatrix}
F_A&D_A\beta_I\\
0&0
\end{pmatrix}
\]

により、task--gauge 曲率と仕事／hidden-exchange 曲率が単一のアフィン曲率へ統合された。曲率零でも大域ホロノミーは残り得て、その平坦アフィン記憶は線形ホロノミー表現で捩れたコホモロジー類と中心化群作用により分類される。Wankel 型は粗視化昇格ではなく、純平行移動の Type I 系熱記憶である。thermal Type III の名は、fine の局所非可積分性が coarse の平坦大域記憶へ promotion され、decoder で復元可能な場合にのみ留保する。

v2.1.0-r2 の最短正典文：

\[
\boxed{
\begin{aligned}
&\textbf{IDSとは、消去不能な残差と hidden 情報エンタルピーの交換を接続として比較し、}\\
&\textbf{その局所曲率、平坦大域ホロノミー、不可逆生成を分離し、}\\
&\textbf{局所断熱不変量を較正された情報エントロピーへ、}\\
&\textbf{大域熱記憶を捩れコホモロジー類へ整理する理論である。}
\end{aligned}
}
\]

---

# 27. v2.0 定量的物理閉包・Yang–Mills direct multiscale layer


**作成日:** 2026-07-14  
**本章の位置:** v1.8.0 以後の定量的物理閉包を master canon に統合する。  
**停止線:** 本書は 4D pure Yang–Mills の質量ギャップ証明を宣言しない。finite-star の exact closure、抽象 gap theorem、局所 SU(2) tariff seed、および volume/scale transfer machinery と、actual 4D physical transfer form の一様比較を分離する。

---

### 状態記号

- **【A】** 抽象 Hilbert／Banach／確率空間上で証明済み。
- **【F】** exact finite-block／finite-graph SU(2) で証明・区間認証済み。
- **【C】** 明示仮定つき条件付き定理。
- **【U】** actual 4D Yang–Mills で未証明の load-bearing 入力。
- **【NG】** no-go／型誤り／certificate failure の厳密な分離。
- **【AUDIT】** 外部系列の主張で、proof artifact・規約・単位の監査が必要。

## 27.0. 今回の正典的判定

これまでの議論を一行で再評価すると、次である。

\[
\boxed{
\begin{aligned}
&\textbf{体積・尺度・tail・hidden sector を一様に束ねる道具は、かなり完成している。}\\
&\textbf{SU(2) 固有の正値 seed・color observability・block action channel も、かなり構成済みである。}\\
&\textbf{残る load-bearing theorem は、それらを actual physical transfer energy へ同一 law 上で降下させること。}
\end{aligned}
}
\]

したがって、古い表現

\[
\text{「uniformity を作る」},\qquad
\text{「non-Abelian tariff を初めて生成する」}
\]

は広すぎる。現在の正確な未閉点は、

\[
\boxed{
\textbf{Physical Non-Abelian Tariff Descent}
}
\]

である。

RG はこの定理を得る一つの経路だが、正典上の主経路ではない。主経路は、全尺度の analysis／decoder／enthalpy form を直接比較する **IDS direct multiscale route** とする。

---

## 27.1. v2.0 共通核：Promotion–Tail–Decoder–Defect Transport

v1.8.0 以後に別名で現れた機構を、次の一つの核へ統一する。

\[
\boxed{
\text{局所 parametrix／decoder}
+\text{大きい欠陥の promotion}
+\text{無限 tail の weighted control}
+\text{defect の Carleman–Green 輸送}
+\text{defect}<1\text{ 後の exact 化}
}
\]

### 27.1.1 同じ核の特殊化

| 表面的名称 | 近似逆／観測 | 欠陥 | exact 化条件 |
|---|---|---|---|
| bounded decoder | \(\mathbb D\mathbb TQ\) | \(Q-\mathbb D\mathbb TQ\) | norm \(<1\) |
| inverse parametrix | \(GL\) | \(I-GL\) | norm \(<1\) |
| Feshbach | hidden inverse \(D^{-1}\) | \(BD^{-1}B^*\) | relative defect \(<1\) |
| coarse closure | \(U_{\rm eff}\mathcal R\) | \(\mathcal RU-U_{\rm eff}\mathcal R\) | transported budget |
| chart correction | reference law | same-law mismatch | relative residual \(<1\) |
| Type III | promotion + decoder | reconstruction leakage | singular floor \(>0\) |

この表に還元できる新名称を、独立の新原理として数えない。

### 27.1.2 Anchored Defect Transport【A】

対象 \(L_n\) と parametrix \(G_n\) に対し、

\[
R_n=I-G_nL_n
\]

と置く。first-order transport

\[
G_{n+1}=G_n-G_n\Delta L_nG_n+E_n
\]

から exact に、

\[
\boxed{
R_{n+1}
=(I-G_n\Delta L_n)R_n
+G_n\Delta L_nG_n\Delta L_n
-E_nL_{n+1}.
}
\]

従って \(R_{n+1}=A_nR_n+s_n\) であり、既存 Carleman–Green kernel をそのまま使える。Carleman は invertibility を生成せず、anchor residual と source を全区間へ輸送する。

---

## 27.2. 情報熱力学の正典整理

### 27.2.1 四量を混同しない

- **内部情報エネルギー**：現在 state 内部に蓄えられた cost／curvature／stress。
- **情報エントロピー**：同じ保存制約下の表現可能性・分布幅。
- **情報エンタルピー**：内部量に、boundary・hidden return・scale exchange の課金を加えた open-system form。
- **情報自由エネルギー**：energy／enthalpy と entropy の競合を表す変分量。

IDS の \(PV\) 対応は通常の体積仕事を直輸入することではない。正典的には、

\[
\boxed{
\text{情報エンタルピー}
=\text{内部情報エネルギー}
+\text{boundary／reentry／representation-expansion cost}
}
\]

である。

### 27.2.2 Feshbach = enthalpy reduction【A】

visible／hidden block

\[
H=\begin{pmatrix}A&B\\B^*&D\end{pmatrix}
\]

に対し、effective visible form は

\[
A_{\rm eff}(z)=A-B(D-z)^{-1}B^*.
\]

hidden sector を消去した価格が self-energy であり、これが情報エンタルピーの boundary/reentry 項である。

### 27.2.3 最大エントロピー reference と Pythagorean chain【A】

保存する charge／enthalpy moment を一致させる最大エントロピー state を reference とする。このとき relative entropy は「保存量は同じだが、actual law が reference からどれだけ余分な構造を持つか」を測る。

moment matching により一次 score defect が消え、KL chain rule により block／scale 間の entropy defect を複式簿記できる。これが non-Abelian entropic broadening の defect budget を供給する。

### 27.2.4 保存則の正確な役割【A／NG】

エネルギー・情報エンタルピー保存則は、

- scale 間の漏れを除く、
- terminal anchor を multiplicative loss なしで輸送する、
- Feshbach 課金を exact balance にする、

ことができる。しかし、mass scale を無から生成しない。

\[
\boxed{
\text{保存則は tariff を運ぶ。正の physical tariff の存在は別の coercivity theorem である。}
}
\]

---


### 27.2.5 収支層と接続層の役割分担（v2.1）

v2.0 の情報熱力学は、内部エネルギー、最大エントロピー reference、Feshbach self-energy、boundary／reentry／tail 課金を同一の収支へ載せる**帳簿層**である。v2.1 の IT 層は、この収支を変数変更・task・scale・boundary の間で比較するとき、何を情報断熱輸送とみなし、いつ局所状態量へ積分でき、どの大域記憶が残るかを決める**接続層**である。

\[
\boxed{
\text{v2.0: 何を課金するか}
\qquad+
\qquad
\text{v2.1: その課金をどう比較・積分・周回するか}
}
\]

保存則は tariff を輸送し、IT 平坦性は局所断熱不変量を与える。しかし、いずれも単独で正の physical tariff、不可逆エントロピー生成、または mass gap を生成しない。

## 27.3. 定量的完全性と bounded decoder

### 27.3.1 Robust approximate reconstruction【A】

analysis operator \(\mathbb T:Q\mathcal H\to\mathcal Y\) と bounded decoder \(\mathbb D\) が

\[
\|Q-\mathbb D\mathbb TQ\|\le\varepsilon<1
\]

を満たせば、

\[
\boxed{
\|\mathbb TQx\|
\ge
\frac{1-\varepsilon}{\|\mathbb D\|}\|Qx\|.
}
\]

これは「想定外 mode」が analysis family 全体から消える余地を operator norm で閉じる。

### 27.3.2 Schur–Cotlar volume-free gluing【A】

局所 decoder \(D_\alpha\) について、

\[
\|D_\alpha^*D_\beta\|\le a_{\alpha\beta},\qquad
R_*:=\sup_\alpha\sum_\beta a_{\alpha\beta}<\infty,\quad
C_*:=\sup_\beta\sum_\alpha a_{\alpha\beta}<\infty
\]

なら、global decoder は volume-free に bounded で、

\[
\|\mathbb D\|^2\le\sqrt{R_*C_*}.
\]

したがって、体積一様化の「足し方」は既に正典化されている。

### 27.3.3 Failure-Mode Completeness【A】

physical gap が失敗するなら、必ず次のいずれかの witness が出る。

1. nonpositive invariant measure／cycle、
2. decoder singularity／reconstruction defect、
3. visible coercivity collapse、
4. hidden floor／Feshbach relative-bound collapse、
5. representation・locality tail collapse、
6. global／topological sector incompleteness、
7. continuum promotion collapse。

これは思いつきの failure list ではなく、invariant measure completeness、bounded decoder、Mosco／OS promotion の対偶である。

---

## 27.4. Scale-unitary IDS gap theorem

### 27.4.1 Metric と energy の同型再帰

各尺度 \(n\) で、physical detail analysis \(A_n\)、coarse transport \(C_n\)、metric \(G_n\)、physical energy form \(K_n\) を取る。

\[
\boxed{
G_n=A_n^*A_n+C_n^*G_{n+1}C_n.
}
\tag{4.1}
\]

energy 側で、

\[
\boxed{
K_n
\succeq
\tau_*A_n^*A_n
+C_n^*K_{n+1}C_n
-\mathcal E_n
}
\tag{4.2}
\]

とする。\(\mathcal E_n\) は enthalpy、chart、tail、Feshbach、boundary、gluing の net negative defect である。

terminal scaleで、

\[
K_N\succeq\tau_*G_N
\tag{4.3}
\]

を仮定する。

### 定理 DIDS-1（Scale-Unitary Direct Gap Theorem）【A】

transported defect を、

\[
\mathfrak E_N
=
\sum_{n<N}C_{0:n}^*\mathcal E_nC_{0:n}
\]

とする。もし

\[
\boxed{
\mathfrak E_N\preceq\theta\tau_*G_0,
\qquad 0\le\theta<1,
}
\tag{4.4}
\]

かつ physical decoder が

\[
\boxed{Q\preceq C_DG_0}
\tag{4.5}
\]

を満たすなら、

\[
\boxed{
K_0
\succeq
\frac{(1-\theta)\tau_*}{C_D}Q.
}
\tag{4.6}
\]

#### 証明

(4.2)を後ろ向きに展開し、(4.1)、(4.3)を用いると、

\[
K_0\succeq\tau_*G_0-\mathfrak E_N.
\]

(4.4)、(4.5)を代入する。∎

#### 正典的意味

- scale 数による積型目減りはない。
- 各 scale で pointwise positive drift を要求しない。
- volume／scale の足し上げは decoder と Carleman–Green が担う。
- actual 物理内容は \(\tau_*>0\) と \(\theta<1\) を同じ law 上で出すことに集中する。

### 27.4.2 Continuous form【A】

continuous scale transport \(U(t)\) では、terminal term と anomaly Gramian を合わせ、

\[
\inf_{x\perp\Omega,\|x\|=1}
\left[
\langle U(T)x,K(T)U(T)x\rangle
+
\int_0^T\|\mathcal A(t)^{1/2}U(t)x\|^2dt
\right]>0
\]

が direct gap condition である。これは strong-entry を仮定しない Form B であり、IDS direct route の連続版である。

---

## 27.5. 非可換 tariff の構成鎖

「actual SU(2) で正値が何もない」は誤りである。次の部分は既に閉じている。

### 27.5.1 Casimir commutator seed【A】

curvature covariance \(\Sigma_F\succeq\sigma^2I\) なら、

\[
\boxed{
\mathbb E\|[F,x]\|^2
\ge
C_A\sigma^2\|x\|^2.
}
\]

SU(2) では \(C_A>0\)、U(1) では \(C_A=0\)。これは non-Abelian discriminator の最小 seed である。

### 27.5.2 Conditional SU(2) twirl【A／F】

one-link Wilson conditional lawを中心化すると、adjoint twirl は色方向へ exact floor を持つ。KL defect に対しても安定で、renormalized color observability を与える。

### 27.5.3 Physical quotient descent と no-go【A／NG】

色 twirl の下界は gauge tangent の直交補空間へ降下する。しかし periodic long-wave transverse modeに対する physical curl energy は \(O(L^{-2})\) で消える。

\[
\boxed{
\text{local color observability}\neq\text{physical infrared coercivity}.
}
\]

従って twirl は tariff の色方向を非退化化するが、scalar mass tariff を生成しない。

### 27.5.4 Gauge-invariant block-holonomy frame【A／C】

flat-background Coulomb sliceでは dyadic curvature／block-holonomy shell が Parseval 型 physical frame を持ち、rescaled sensor \(\mathcal B_n\) は shell norm と一様同値である。非線形・全boundary sectorへの昇格が actual 入力として残る。

### 27.5.5 Entropy-protected non-Abelian drift【A／C】

max-entropy reference、Casimir positivity、KL transportにより、

\[
\kappa_{\rm eff}
=
\kappa_{\rm ref}-L_R\sqrt{2c_Vc_D}>0
\]

なら reference broadening の二次 drift が actual lawでも正に残る。実模型の load-bearing input は、block conditional KL defect と reference drift margin の same-law control である。

### 27.5.6 Finite-star action tariff【F／AUDIT】

three-plaquette SU(2) starでは mixed trivalent channel \((\tfrac12,\tfrac12,1)\) が exact に生成される。channel-specific \(9j\) log algebraの付属verifierは、point values \(\beta\in\{0.1,0.2,0.3,0.4\}\) で mixed action coefficient の正符号certificateを報告する。ただしこれは連続\(\beta\)-interval定理ではなく、独立interval監査前の【F／AUDIT】証拠として扱う。

これは非可換networkが density だけでなく action に現れる具体的証拠である。ただし finite-star action coefficient は physical transfer gapそのものではない。

### 27.5.7 High-tail／hidden reentry control【A／F】

Casimir denominator splitting により、

\[
B(D-m)^{-1}B^*
\]

を volume factorなしで局所 self-energy 密度の和へ押し込める。scale-adaptive representation cutoffで relative loss \(\Theta_{J,m}<\theta_*<1\) を作れる。従って high-representation tail を volume factorなしのrelative form budgetへ還元する制御定理は利用可能である。ただし actual \(2^4\) block／exact physical transfer form上の \(\Theta_{J,m}\) 係数は未評価であり、actual PNATD budgetが認証済みという意味ではない。

### 27.5.8 No-Free-Path【A／C】

現在 scaleで直接課金されないmodeも、recoverable promotion、no-cancellation angle、twist/hypocoercivity、terminal anchorのいずれかで必ず課金される条件を定理化した。実YMで必要なのは各 singular floor と angle の同一physical quotient上の評価である。

---

## 27.6. Finite-Star Coordinate Closure Theorem

### 27.6.1 Exact finite-star library【F】

次を exact／rigorous tailつきで構成した。

1. planar \(2\times2\) boundary density、
2. density-to-action log-tail、
3. rectangle／chair geometry channel、
4. three-plaquette trivalent projector、
5. exact \(9j\) product algebra、
6. infinite highest-spin tower、
7. weighted Banach algebra、
8. same-law character／corrected heat-kernel action atlas、
9. low-mode promotionと ADT inverse transport。

### 27.6.2 Hypergroup と weighted tail【F】

raw normalized networks \(\Psi_\alpha\) は、

\[
\Psi_\alpha\Psi_\beta
=
\sum_\gamma
D_\gamma\{9j\}^2\Psi_\gamma,
\qquad
N_{\alpha\beta}^{\ \gamma}\ge0,
\quad
\sum_\gamma N_{\alpha\beta}^{\ \gamma}=1.
\]

size weight \(|\alpha|\) に対し、

\[
\|FG\|_\sigma\le\|F\|_\sigma\|G\|_\sigma.
\]

従って finite exact closureを要求せず、

\[
\|P_{>R}S\|_0
\le
 e^{-\sigma R}[-\log(1-q_\sigma)]
\]

で無限towerを一つのtail channelへ収納できる。

### 27.6.3 Same-law action atlas【F】

local \(\beta\) 規約において、

- weighted-character chart：およそ \([0.1,0.9375]\)、
- low-mode-corrected weak action chart：\([0.4,1.075]\)、
- same-law overlap：少なくとも \([0.4,0.9375]\)

を認証した。

最終cell \([1.05,1.075]\) では、

\[
\|\rho_H^{-1}P_{\le2}(\rho_W-\rho_H)\|\le0.88011,
\]

\[
\|I-G_M\rho_M\|\le0.30313,
\]

\[
\|\rho_M^{-1}(I-P_{\le2})(\rho_W-\rho_H)\|\le0.04831.
\]

これらは finite-star same-law identityであり、actual 4D crossoverの証明ではない。

### 定理 FSCC-1（Finite-Star Coordinate Closure）【F】

compact \(\beta\)-interval上の exact star lawについて、weighted chartが成立し、positive floor \(m_B>0\) を持つとする。size cutoff \(R\) 内の全ordered admissible networksを保持する。

1. retained Fisher matrixは
   \[
   F_\beta\succeq m_BI;
   \]
2. \(0<\sigma'<\sigma\) に対し、coefficient analysis \(P_R\) と inclusion decoderは
   \[
   \|I-D_RP_R\|_{\mathcal A_\sigma\to\mathcal A_{\sigma'}}
   \le e^{-(\sigma-\sigma')R}<1;
   \]
3. action tailは weighted Banach boundで一様制御される。

従って finite-star coordinate／action layerは complete retained state、bounded two-norm decoder、positive Fisher frame、same-law atlasを持つ。∎

#### 射程

FSCC-1 は actual 4D Markov closure、physical transfer tariff、volume-uniform continuum gapを意味しない。

---

## 27.7. Physical Non-Abelian Tariff Descent

ここが現在の load-bearing actual theorem である。

### 27.7.1 Block conditional setting

physical transfer Hilbert space上で、block／scale／boundary sector \((n,B,\partial)\) ごとに、gauge-invariant sensor

\[
\mathcal B_{n,B,\partial}
\]

と conditional physical form

\[
K^{\rm act}_{n,B\mid\partial}
\]

を取る。

reference conditional law／formを \(K^{\rm ref}\) とし、

\[
\boxed{
K^{\rm ref}_{n,B\mid\partial}
\succeq
\tau^{\rm ref}_{n,B,\partial}
\mathcal B^*\mathcal B
}
\tag{7.1}
\]

を仮定する。

### 27.7.2 Same-law defect decomposition

actual-reference差を、共通の稠密form domain

\[
\mathcal D
=
\mathcal D(K^{\rm act})
\cap
\mathcal D(K^{\rm ref})
\cap
\mathcal D(\mathcal B)
\]

上の対称sesquilinear formsとして、

\[
K^{\rm act}-K^{\rm ref}
=
\Delta_{\rm ent}
+\Delta_{\rm chart}
+\Delta_{\rm Fesh}
+\Delta_{\rm tail}
+\Delta_{\rm bdry}
+\Delta_{\rm glue}
\]

と分ける。各 \(\Delta_i\) はsensor kernelと両立し、

\[
\ker\mathcal B\cap\mathcal D
\subseteq
\ker_{\rm form}\Delta_i,
\qquad
\Delta_i[\psi,\varphi]=0
\quad
(\psi\in\ker\mathcal B\cap\mathcal D,\ \varphi\in\mathcal D),
\]

かつ共通form domain上で二側相対不等式

\[
-\varepsilon_i\,\mathcal B^*\mathcal B
\preceq_{\mathcal D}
\Delta_i
\preceq_{\mathcal D}
\varepsilon_i\,\mathcal B^*\mathcal B
\]

を満たすとする。このとき、

\[
\boxed{
K^{\rm act}
\succeq_{\mathcal D}
\tau_{\rm net}\mathcal B^*\mathcal B,
\qquad
\tau_{\rm net}
=
\tau_{\rm ref}-\sum_i\varepsilon_i.
}
\tag{7.2}
\]

### 定理スキーマ PNATD-YM【C／U】

次を actual 4D SU(2) transfer theoryで一様に示せ。

\[
\boxed{
\inf_{a,L,n,B,\partial}\\tau_{\rm net}>0.
}
\tag{7.3}
\]

さらにsensor familyが bounded decoderを持ち、transported defect budgetが DIDS-1 の \(\theta<1\) を満たすなら、physical gapが従う。

#### 制御定理が利用可能な sub-budget（actual PNATD係数は未認証）

- \(\varepsilon_{\rm Fesh}\)：LSD／Casimir denominator splitting によるrelative-form制御機構、
- \(\varepsilon_{\rm tail}\)：weighted representation／network algebraによる無限tail制御機構、
- \(\varepsilon_{\rm chart}\)：same-law atlas／corrected referenceによるchart差制御機構、
- color kernel：conditional twirl＋gauge quotientによる局所kernel排除機構、
- volume gluing：Schur–Cotlar decoderによるvolume-free結合機構、
- scale source：Carleman–Green／ADTによるsource輸送機構、
- failure completeness：FMCによるwitness分類。

\[
\boxed{
\text{control theorem available}
\neq
\text{actual }2^4\text{ block／physical transfer form上のPNATD係数認証済み}.
}
\]

各 \(\varepsilon_i\) のactual値、共通form domain、kernel compatibility、sector一様性は
PTD-0以後の実装義務である。

#### 主に残る sub-budget【U】

1. reference physical form tariff \(\tau_{\rm ref}\) の actual transfer-Hamiltonian同定、
2. conditional enthalpy／boundary defect \(\varepsilon_{\rm ent}+\varepsilon_{\rm bdry}\)、
3. nonlinear global sectorを含む physical sensor completeness、
4. physical-time normalizationでの \(a\)-一様正値。

したがって現在の核心は「non-Abelian seedの発見」ではなく、

\[
\boxed{
\text{生成済みseed／action tariffをphysical infrared energyへ同一law上で降下させること。}
}
\]

---

## 27.8. IDS direct multiscale route

RG trajectoryを主定理に置かず、physical nonvacuum spaceを全scaleで直接測る。

### 27.8.1 Analysis family

\[
T_j=
\bigl(
T_j^{\rm curv},
T_j^{\rm loop},
T_j^{\rm tri},
T_j^{\rm electric},
T_j^{\rm flux},
T_j^{\rm hidden}
\bigr).
\]

finite-star libraryは各block sensorのlocal basisとして使う。

### 27.8.2 Decoder

\[
\|Q\psi\|^2
\le
C_D\sum_jw_j^2\|T_j\psi\|^2.
\]

martingale filtration、weighted coefficient projection、Type III promotion、global sector channelを組み合わせる。

### 27.8.3 Tariff

\[
\langle\psi,H_{a,L}\psi\rangle
\ge
\sum_j\mu_j\|T_j\psi\|^2
-\mathcal R[\psi].
\]

既存 machineryで

\[
\mathcal R\le\theta\sum_j\mu_j\|T_j\psi\|^2,
\qquad\theta<1
\]

を作り、

\[
\mu_j\ge m_*C_Dw_j^2
\]

を physical units で示せば DIDS-1 が閉じる。

### 27.8.4 RG routeとの関係

RG finite entryは、\(\mu_j\) の正値を flow／strong anchor経由で示す代替法である。direct routeは、coercive anomaly Gramian／conditional tariffとして同じ物理内容を直接証明する。正典上、両routeは競合せず、同じ PNATD-YM を異なる方法で閉じる。

---

## 27.9. 体積・尺度・格子幅の一様性

### 27.9.1 体積【A】

局所decoder／channel kernelsのSchur row・column sumsを一様にすれば、global normはvolume-free。

### 27.9.2 全尺度【A／C】

source recursion

\[
R_{n+1}=A_nR_n+s_n
\]

をCarleman–Greenで制御する。有限個のbad scale、local backflow、\(\|A_n\|>1\) を即失敗にしない。必要なのはsource convolutionと長距離average contraction／anchorの一様budgetである。

### 27.9.3 Tail【A／F】

representation、intertwiner、network-size、log-order tailを別台帳で管理する。有限cutoff外を0としない。

### 27.9.4 格子幅・物理単位【C／U】

裸のdimensionless transfer gapを一様正と要求しない。

\[
H_a=-a^{-1}\log T_a
\]

に対して、physical tariff \(\tau_*\) とdecoder metricを定義する。continuumではMosco／strong-resolvent、vacuum projector、bottom completeness、OS/GNS time identificationが必要である。

---

## 27.10. PURE_YM系列との正典crosswalk

参照ファイル：`PURE_YM_UNIFORM_RG_AND_MASS_GAP(5).md`。

### 27.10.1 輸入できる構造

1. **D-20 sector split**：低mode相対比較＋高mode絶対支配は、low-mode corrected referenceと同じpromotion原理。
2. **strong fixed-a anchor候補**：proof artifact／規約／volume uniformity監査後、terminal anchor入力として利用可能。
3. **hierarchical flow**：actual \(\mathbb Z^4\) theoremではなくreference flow。
4. **SU(2)–U(1) discriminator**：positive tariffが \(C_A>0\)／non-Abelian intertwinerを本質使用するかのacceptance gate。
5. **H-cross**：direct routeでは physical non-Abelian tariff descent／coercive anomaly Gramianに翻訳される。

### 27.10.2 輸入しない短絡

- no phase transition \(\Rightarrow\) spectral gap、
- area law \(\Rightarrow\) mass gap、
- hierarchical／MK \(\Rightarrow\mathbb Z^4\)、
- free-energy Jensen bound \(\Rightarrow\) transfer gap、
- proof artifactなしの数値定数。

---

## 27.11. 更新後のload-bearing obligations

### OP-DIDS1【U】 Actual transfer Hilbert and sensor family

finite-volume physical Hilbert space上で、curvature／loop／trivalent／electric／flux／hidden channelsを定義し、domain・gauge quotient・global sectorを固定する。

### OP-DIDS2【U】 Physical non-Abelian tariff descent

(7.3)を証明する。現在の最重要義務。

### OP-DIDS3【U】 Conditional enthalpy and boundary stability

actual block conditional lawとmax-entropy／heat-kernel referenceのsame-law form差を、全boundary条件で一様に囲う。

### OP-DIDS4【U】 Nonlinear physical decoder

actual nonflat gauge orbit・center／flux sectorを含むbounded decoderを構成する。

### OP-DIDS5【U】 Carleman source coefficients

Feshbach、tail、chart、boundary、global mixingをactual coefficientsでsource budgetへ入れ、\(\theta<1\) を認証する。

### OP-DIDS6【U】 Physical-unit continuum promotion

lattice lower formを \(a,L\) 一様にし、Mosco／OS/GNSへ送る。

### OP-DIDS7【U】 Non-Abelian discriminator

同じsensor／reference constructionをU(1)へ適用し、SU(2)のpositive tariffを作る項がU(1)で消えることを示す。

---

## 27.12. 次の実作業

新しい抽象理論を増やさず、PNATD-YMを有限blockで直接測る。

### Experiment PTD-0

同じfinite conditional SU(2) block上に、

- corrected reference law、
- physical transfer／Dirichlet form、
- block holonomy／trivalent sensor、
- electric Casimir、
- Feshbach low/high split

を置く。

### Experiment PTD-1

一般化固有値

\[
\tau_{B,\partial}
=
\inf_{\psi\perp\ker\mathcal B}
\frac{\langle\psi,K^{\rm phys}_{B\mid\partial}\psi\rangle}
{\|\mathcal B_{B\mid\partial}\psi\|^2}
\]

をinterval評価する。

### Experiment PTD-2

\[
\tau_{\rm net}
=
\tau_{B,\partial}
-\varepsilon_{\rm ent}
-\varepsilon_{\rm Fesh}
-\varepsilon_{\rm tail}
-\varepsilon_{\rm glue}
\]

を同じnormalizationで計算し、正ならblock-size／boundary ladderへ進む。

### Failure outputs

- `REFERENCE-PHYSICAL-FORM-MISMATCH`
- `BOUNDARY-ENTHALPY-DEFECT`
- `FESHBACH-BUDGET-COLLAPSE`
- `SENSOR-KERNEL-WITNESS`
- `GLOBAL-SECTOR-INCOMPLETENESS`
- `PHYSICAL-UNIT-SCALING-FAILURE`

---

## 27.13. No-go・禁止事項

1. color twirl \(\Rightarrow\) physical mass gap としない。
2. finite-star positive action coefficient \(\Rightarrow\) transfer gap としない。
3. energy conservation \(\Rightarrow\) mass generation としない。
4. density coefficientとaction coefficientを混同しない。
5. projected overlapをsame-law overlapと呼ばない。
6. certificate failureをphysical failureと呼ばない。
7. finite volumeの正gapをthermodynamic gapへ昇格しない。
8. dimensionless lattice gapをphysical massへ直結しない。
9. no transition／analyticity／area lawをgapと同値視しない。
10. RG routeの停止をdirect IDS routeの停止とみなさない。

---

## 27.14. v2.0 最短正典文

\[
\boxed{
\begin{aligned}
&\textbf{IDSとは、消去不能な残差同一性を quotient・promotion・carrier・decoder で保持し、}\\
&\textbf{局所の正値 tariff と hidden／tail／boundary defect を同一のエンタルピー収支へ課金し、}\\
&\textbf{その defect を Carleman–Green で尺度・体積を越えて輸送する理論である。}\\
&\textbf{物理gapは、non-Abelian tariff が physical transfer formへ同一law上で降下し、}\\
&\textbf{bounded decoderと全defect budgetの下で真空補空間を漏れなく課金するときに生じる。}
\end{aligned}
}
\]

現在の4D Yang–Millsに関する正確な停止点は、

\[
\boxed{
\inf_{a,L,n,B,\partial}
\left(
\tau_{\rm ref}
-\varepsilon_{\rm ent}
-\varepsilon_{\rm bdry}
-\varepsilon_{\rm Fesh}
-\varepsilon_{\rm tail}
-\varepsilon_{\rm glue}
\right)>0
}
\]

を actual physical transfer theoryで証明することである。

---

## 27.15. Provenance index

本書は、以下の正本を統合した companion canon である。

- `IDS_Canonical_Theory_v1_8_0_JA.md`
- `IDS_NonAbelian_CoarseGraining_Canonical_v1_10_JA.md`
- `IDS_SCALE_UNITARY_ENTHALPY_ANOMALY_v1_1_JA.md`
- `IDS_RENORMALIZED_INFORMATION_ENTHALPY_GAP_TRANSFER_v0_9_JA.md`
- `IDS_QUANTITATIVE_EXACTNESS_BOUNDED_DECODER_v1_2_JA.md`
- `IDS_FAILURE_MODE_COMPLETENESS_v2_9_JA.md`
- `IDS_NO_FREE_PATH_GAP_TRANSFER_v1_0_JA.md`
- `IDS_NONABELIAN_ENTROPIC_BROADENING_v1_3_JA.md`
- `IDS_SU2_CONDITIONAL_TWIRL_DECODER_v1_5_JA.md`
- `IDS_PHYSICAL_DESCENT_AUDIT_v1_6_JA.md`
- `IDS_MULTISCALE_BLOCK_HOLONOMY_COMPLETION_v1_7_JA.md`
- `IDS_YM_LOCAL_SELF_ENERGY_DENSITY_v0_5_JA.md`
- `IDS_ENTHALPY_ENTROPY_PYTHAGOREAN_RG_v1_4_JA.md`
- finite-star v3.0–v4.1 series
- `PURE_YM_UNIFORM_RG_AND_MASS_GAP(5).md`（crosswalk／監査対象）
- `IDS_Addendum_IT_v2_1_draft_JA(2).md`（r2 を監査精密化し §29 へ統合）

# 28. v2.0 Freeze Record

1. v1.8.0 の定理1–38は変更せず継承する。
2. v2.0 は DIDS-1、ADT、FMC、FSCC-1、PNATD-YM schemaを追加する。
3. finite-star exact結果をactual 4Dへ昇格しない。
4. Physical Non-Abelian Tariff Descentを現在のload-bearing open theoremとして凍結する。
5. RG routeとdirect IDS routeを同じphysical tariff theoremの代替経路として保持する。
6. mass gap未証明の停止線を変更しない。

# 29. 情報熱接続層（IT層）

**統合日:** 2026-07-16  
**出自:** `IDS_Addendum_IT_v2_1_draft_JA(2).md` r2 を独立監査し、定理 IT-4 のモジュライ分類を中心化群商まで精密化して統合。  
**位置づけ:** v2.0 の情報エンタルピー収支を置換せず、hidden exchange の断熱比較、局所可積分性、大域ホロノミーを接続論として統一する横断層。有限次元・滑らかな古典層を本版で凍結し、無限次元・特異・量子・thermal Type III 昇格は未解決として分離する。

## 29.0 輸入元と依存関係の宣言

本層の数学的内容は次の三種に峻別される。

| 種別 | 内容 | 出典 |
| --- | --- | --- |
| 古典 | Frobenius 定理、Ehresmann 接続、線形接続の曲率、Carathéodory 型可積分性 | Kobayashi–Nomizu, Hermann ほか標準文献 |
| 輸入 | 1次元ファイバー上で「熱形式の核＝接続」「曲率消滅 ⟺ 局所 \(TdS\) 表示 ⟺ 局所自明ホロノミー ⟺ 閉断熱リフトの閉性 ⟺ Jauch 保存則」の同値パッケージ | Roberts, arXiv:2503.08753（Theorem 1, Corollary 1, §VI–VII） |
| 本層の新規 | 多次元ファイバーへの垂直非退化拡張（補題 IT-0）、行列積分因子の自動性（定理 IT-2）、\(F_{\rm ctrl}\) の再導出（定理 IT-3）、\(\Xi_A,\Xi_\gamma\) の断熱的再解釈（系 IT-3.1）、thermal holonomy memory と捩れコホモロジー分類（定理 IT-4）、thermal Type III 昇格構造（IT-D7） | 本文 |

Roberts の定理自体は Carathéodory＋Frobenius＋ホロノミーの古典的事実の組み合わせであり、本層の価値は新しい数学的火力ではなく、**既存の IDS 対象群を単一の定義原理へ束ねる正典的整理**にある。この評価を正典文に含める。

---

## 29.1 公理 A15. 情報熱束公理（モデル選択的）

IDS モデルは、次を備えるとき **IT 構造を持つ**という。

1. 操作可能変数の滑らかな有限次元多様体 \(B_I\)（control, task, scale, boundary, observable configuration の正則層）。
2. 滑らかな沈め込み \(\pi_I:\mathcal E_I\to B_I\)。ファイバーは hidden 情報エンタルピー座標（残差予算、carrier 収支、bridge-hidden 収支等）を表し、次元 \(r\ge1\)。
3. ファイバー方向を座標付けする垂直座標写像 \(\mathcal H_I:\mathcal E_I\to\mathbb R^r\)、すなわち各点で \(d\mathcal H_I|_{\ker(\pi_I)_*}\) が線形同型。
4. hidden 方向を消す操作的仕事形式、すなわち \(\mathbb R^r\) 値 1 形式 \(W_I\) で

\[
\ker(\pi_I)_*\subseteq\ker W_I.
\]

A14（自己再生構成公理）と同様、A15 は普遍主張ではない。IT 構造を持たない IDS モデルは正典に反しない。無限次元（Banach）ファイバー、rank-change、特異層は本層の射程外であり OP-IT4 に隔離する。

**射程の明示（r2）。** A15 条件 3 の大域的垂直座標 \(\mathcal H_I:\mathcal E_I\to\mathbb R^r\) は、**大域的に座標化可能なファイバーを持つ模型**への限定である。非自明なアフィン束一般では単一の大域座標 \(v\) は存在しない。一般形は次とする。

**A15′（局所アトラス版・一般形）。** 開被覆 \(\{U_\alpha\}\) と局所自明化ごとの \((v_\alpha,\Xi_\alpha)\) を持ち、重なり上で

\[
v_\beta=g_{\beta\alpha}v_\alpha+c_{\beta\alpha},
\qquad
\Xi_\beta=g_{\beta\alpha}\,\Xi_\alpha
\]

を満たす（\(g_{\beta\alpha},c_{\beta\alpha}\) はコサイクル条件を満たす \(\operatorname{Aff}(r)\) 遷移関数）。座標不変には、モデルベクトル束 \(\mathcal V\to B_I\) に対し \(\Xi_I\in\Omega^1(\mathcal E_I;\pi_I^*\mathcal V)\) で垂直制限が各点同型となる solder 型形式として定義できる。本層の定理 IT-0〜IT-3A の局所的主張は A15′ 下でもチャートごとに成立し、定理 IT-4 は局所自明化可能性のみを要する。大域的主張（貼り合わせ障害）は OP-IT1(c) に属する。

**ゲージ規約。** ファイバーの再座標付け \(v'=g(b)\,v+c(b)\)（\(g:B_I\to GL(r,\mathbb R)\)、\(c:B_I\to\mathbb R^r\) 滑らか、構造群 \(\operatorname{Aff}(r)=GL(r)\ltimes\mathbb R^r\)）を情報エンタルピー・ゲージと呼ぶ。\(r=1\) では Roberts の gauge symmetry \(U\mapsto aU+b\) に一致する。情報熱形式には等変性

\[
\boxed{
\Xi_I'=g\,\Xi_I
}
\]

を要求する。これは水平分布 \(\mathscr H_I=\ker\Xi_I\)（したがって情報断熱過程の概念）がゲージ不変であることと同値。アフィン形 \(\Xi_I=dv+A_Iv+\beta_I\)（§29.6A）に対しては、この要求から変換則

\[
A_I'=gA_Ig^{-1}-dg\,g^{-1},
\qquad
\beta_I'=g\beta_I-dc-A_I'c
\]

が一意に従う。

---

## 29.2 基本定義

**定義 IT-D1（情報熱交換形式）。**

\[
\boxed{
\Xi_I:=d\mathcal H_I+W_I
}
\qquad(\mathbb R^r\text{ 値 }1\text{ 形式}).
\]

**定義 IT-D2（垂直非退化性）。** \(\Xi_I\) が**垂直非退化**であるとは、各点 \(p\in\mathcal E_I\) で制限

\[
\Xi_I|_{V_p}:V_p\to\mathbb R^r,
\qquad V_p:=\ker(\pi_I)_*|_p
\]

が線形同型であること。A15 の条件 3–4 のもとで \(\Xi_I|_{V}=d\mathcal H_I|_{V}\) だから、A15 は垂直非退化性を含意する。\(r=1\) では Roberts の「\(\xi\) nowhere-vanishing かつ縦方向で 1」に対応する。

**定義 IT-D3（情報断熱接続）。**

\[
\boxed{
\mathscr H_I:=\ker\Xi_I.
}
\]

\(\mathscr H_I\) に接する曲線を**情報断熱過程**（information adiabat）と呼ぶ。意味は、操作可能状態を変化させながら hidden sector との正味エンタルピー交換を発生させない更新である。

**定義 IT-D4（情報熱曲率）。** Hermann–Roberts 流に、

\[
\Omega_I(X,Y):=\operatorname{vert}[X,Y]
\qquad(X,Y\in\mathscr H_I).
\]

**定義 IT-D5（情報熱ホロノミー）。** 閉曲線 \(\gamma_B\subset B_I\) の水平リフトが誘導するファイバー自己写像を \(\operatorname{Hol}_I(\gamma_B)\) とする。

---

## 29.3 補題 IT-0. 垂直非退化性は接続を与える（rank \(r\) 一般）

**補題。** \(\pi_I:\mathcal E_I\to B_I\) を沈め込み（\(\dim B_I=n\)、ファイバー次元 \(r\)）、\(\Xi_I\) を垂直非退化な \(\mathbb R^r\) 値 1 形式とする。このとき \(\mathscr H_I=\ker\Xi_I\) は Ehresmann 接続である。すなわち各点で

\[
T_p\mathcal E_I=\mathscr H_{I,p}\oplus V_p,
\]

かつ \((\pi_I)_*\) は \(\mathscr H_{I,p}\) を \(T_{\pi_I(p)}B_I\) へ同型に写す。

**証明。** \(\Xi_I|_{V_p}\) が単射だから \(\mathscr H_{I,p}\cap V_p=\{0\}\)。\(\Xi_I|_{V_p}\) が全射だから点ごとの線形写像 \(\Xi_{I,p}:T_p\mathcal E_I\to\mathbb R^r\) も全射であり、\(\dim\mathscr H_{I,p}=\dim\ker\Xi_{I,p}=(n+r)-r=n\)。次元勘定により \(T_p\mathcal E_I=\mathscr H_{I,p}\oplus V_p\)。直和分解と \(\ker(\pi_I)_*=V_p\) から \((\pi_I)_*|_{\mathscr H_{I,p}}\) は単射、次元一致により同型。\(\square\)

**注意（本補題の意義）。** Roberts の Lemma 1 は「非零 1 形式の核は余次元 1」という rank-1 特有の勘定に依存する。多次元 hidden sector では核が補空間になること自体が自動でなく、垂直非退化性 IT-D2 が**追加の実質条件**である。元提案はこの点を明示していなかったため、ここで条件化する。垂直非退化性が退化する点（hidden 収支のヤコビアン退化）は rank-change 特異点であり OP-IT4 へ送る。

---

## 29.4 定理 IT-1. IDS–Carathéodory–Roberts 定理（rank 1）

**定理。** \(r=1\)、A15 と IT-D2 を満たすとする。\(\mathscr H_I=\ker\Xi_I\) は接続であり、次は同値。

- (A) 各点の近傍で滑らかな \(T_I\)（非零）と \(S_I\) が存在して \(\Xi_I=T_I\,dS_I\)。
- (B) \(\Omega_I\) が恒等的に消える。
- (C) 各点の近傍で \(\operatorname{Hol}_I\) が自明。
- (D) 各点の近傍で、すべての閉曲線の情報断熱リフトが閉じる。
- (E) （Jauch 型保存則）閉じた情報断熱過程が基底変数を復元するならば、その過程に沿う操作的仕事の総和 \(\int_\gamma W_I\) は零。

**条件注記（r1）。** (D)⟺(E) のうち「\(\int_\gamma W_I=0\) からファイバー点の復元」を結論する向きには、\(\mathcal H_I\) が当該ファイバー領域上で**単射**であることを要する。A15 条件 3 は微分の同型（局所単射）を与えるのみで大域単射を含意しない（ファイバーが \(S^1\) 型なら反例が作れる）。以下では各ファイバーが \(\mathbb R^r\) の凸領域に \(\mathcal H_I\) で埋め込まれる場合に (E) を含めた五者同値とし、一般には (A)–(D) の四者同値を主張する。

**証明。** 接続性は補題 IT-0（\(r=1\)）。(A)⟺(B) は Frobenius（\(\ker\Xi_I\) の可積分性 ⟺ 対合性 ⟺ 曲率消滅）と、可積分 1 形式の局所積分因子表示による。(B)⟺(C)⟺(D)⟺(E) は Roberts, Corollary 1 および §VI の議論をそのまま \( (U,\omega,\xi)\mapsto(\mathcal H_I,W_I,\Xi_I)\) と読み替えて適用する。(E) の同値変形は、断熱条件 \(\Xi_I(\bar\gamma)=0\) のもとで \(\int_\gamma W_I=-\int_\gamma d\mathcal H_I\) が成り立つことから、「リフトが閉じる ⟺ \(\mathcal H_I\) が復元される ⟺ 仕事総和零」による。\(\square\)

**正典的帰結。**

\[
\boxed{
\text{情報温度と情報エントロピーは公理ではなく、}
\Xi_I\text{ が可積分な層でのみ創発する状態量である。}
}
\]

**名称注記（r2）。** 正確には、平坦性から直接従うのは積分因子 \(T_I\) と局所情報断熱不変量 \(S_I\) の存在までである。「情報温度・情報エントロピー」の名称は較正条件 IT-C（§29.9）の充足を前提とする。

これは正典方針 1.2「\(\varphi\) を公理に入れない」と同型の規律——**創発量を公理に入れない**——の熱力学版である。

---

## 29.5 定理 IT-2. 行列積分因子の局所自動性（rank \(r\)）

**定理。** A15・IT-D2 を満たす rank \(r\) の IT 構造で、次は同値。

- (B\(_r\)) \(\Omega_I\) が恒等的に消える。
- (A\(_r\)) 各点の近傍で、滑らかな可逆行列場 \(M_I:U\to GL(r,\mathbb R)\) と滑らかな \(\mathbf S_I=(S_I^1,\dots,S_I^r)\)（\(dS_I^1,\dots,dS_I^r\) が各点で一次独立）が存在して

\[
\Xi_I=M_I\,d\mathbf S_I.
\]

**名称規約（r1）。** 本定理が与える \(\mathbf S_I\) は、数学的には水平葉層をラベルする局所第一積分であり、以後**局所情報断熱不変量**と呼ぶ。「情報エントロピー」の名称は較正条件 IT-C（§29.9）を満たす場合にのみ用いる。Frobenius は葉の存在を与えるが、その熱力学的地位（凹性・単調性・最大化特性）は与えない。

**証明。** (A\(_r\))⇒(B\(_r\))：\(\ker\Xi_I=\bigcap_a\ker dS_I^a\) は \(\mathbf S_I\) の等位集合の葉層に接するから可積分、Frobenius により対合的、よって \(\Omega_I=0\)。

(B\(_r\))⇒(A\(_r\))：\(\Omega_I=0\) より \(\mathscr H_I\) は対合的、Frobenius により各点の近傍に平坦チャート \((x^1,\dots,x^n,w^1,\dots,w^r)\) が存在して \(\mathscr H_I=\operatorname{span}\{\partial_{x^i}\}\)。\(S_I^a:=w^a\) と置くと \(\ker\Xi_I=\bigcap_a\ker dS_I^a\)。各点で余分布 \(\operatorname{Ann}(\mathscr H_I)\subset T^*\mathcal E_I\) は \(r\) 次元であり、\(\{\Xi_I^a\}\) と \(\{dS_I^a\}\) はいずれもその基底（前者は垂直非退化性、後者はチャート構成による）。したがって一意な滑らかな行列場 \(M_I\) が存在して \(\Xi_I^a=(M_I)^a{}_b\,dS_I^b\)、基底同士の変換だから \(M_I\) は各点で可逆。\(\square\)

**注意（元提案の較正修正）。** 元提案は「行列積分因子 \(M_I\) と複数エントロピー座標の存在条件」を OP-IT1 として未解決に置いた。定理 IT-2 により、**平坦性のもとでの局所存在は自動**である。真に未解決なのは存在ではなく次の三つであり、OP-IT1 をそのように改稿する。

1. **スカラー圧縮**：\(M_I\) がゲージ変換で \(T_I\cdot\mathrm{Id}\) またはブロック対角（チャネル別温度）へ正規化できる条件。これは多チャネル hidden exchange の低次元熱力学的圧縮可能性であり、IDS の自己粗視化問題（§19）に接続する。
2. **非平坦分解**：\(\Omega_I\neq0\) のときの \(\Xi_I=M_I\,d\mathbf S_I+\Xi_I^{\rm anh}\) 型の正準分解と、非可積分残部 \(\Xi_I^{\rm anh}\) の障害類としての同定。これは残差類 \([\omega]\) の熱力学的対応物候補である。
3. **大域化**：局所 \(\mathbf S_I\) の貼り合わせ障害と \(\operatorname{Hol}_I\) の関係（thermal holonomy memory、§29.8）。

---

## 29.6 定理 IT-3. 受理テスト：\(F_{\rm ctrl}\) の情報熱接続としての再導出

正典定理 34 の設定を採る。計量付き物理ゲージベクトル束 \(V\to S\)、接続 \(D_A\)、滑らかな一定 rank のゲージ共変直交射影 \(P=P_{\rm ctrl}\)、制御関連部分束 \(E_{\rm ctrl}=\operatorname{Ran}P\)、誘導接続 \(\nabla^{\rm ctrl}=PD_A\)。

**構成。** 基底を \(B_I:=S\)、全空間を \(\mathcal E_I:=E_{\rm ctrl}\)（rank \(r=\operatorname{rank}P\) のベクトル束の全空間）、垂直座標を局所平行化枠 \(\{e_\alpha\}\subset\Gamma(E_{\rm ctrl})\) に関するファイバー座標 \(v=(v^\alpha)\) とする。局所接続形式を \(A_{\rm ctrl}\)（\(\nabla^{\rm ctrl}e_\beta=(A_{\rm ctrl})^\alpha{}_\beta e_\alpha\)）とし、**制御情報熱形式**を

\[
\boxed{
\Xi_{\rm ctrl}:=dv+A_{\rm ctrl}\,v
}
\]

と定める。これは A15 の型に適合する：\(\mathcal H_I=v\)（hidden＝task 関連予算座標）、\(W_I=A_{\rm ctrl}v\) は垂直ベクトルを消し（\(A_{\rm ctrl}\) は基底 1 形式）、\(\Xi_{\rm ctrl}|_V=dv|_V\) は同型なので垂直非退化。補題 IT-0 により \(\mathscr H_{\rm ctrl}=\ker\Xi_{\rm ctrl}\) は Ehresmann 接続であり、これは線形接続 \(\nabla^{\rm ctrl}\) の水平分布に他ならない（\(\ker\Xi_{\rm ctrl}\) に沿う移動 ⟺ \(\nabla^{\rm ctrl}\)-平行移動）。

**定理。** 上の構成で、情報熱曲率 \(\Omega_{\rm ctrl}=\operatorname{vert}[\,\cdot\,,\cdot\,]\) は、垂直空間とファイバーの自然な同一視のもとで

\[
\boxed{
\Omega_{\rm ctrl}(X,Y)\big|_v
=-\,F_{\rm ctrl}(X,Y)\,v
=-\bigl(PF_AP+P(D_AP)\wedge(D_AP)P\bigr)(X,Y)\,v.
}
\]

特に \(\Omega_{\rm ctrl}\equiv0\iff F_{\rm ctrl}\equiv0\) であり、定理 34 の task–gauge 曲率は rank \(r\)・線形ゲージ群 \(GL(r)\) における情報熱曲率の特殊化である。

**訂正（r1）。** r0 では「Roberts の設定は本定理の rank-1 可換極限」と述べたが、これは不正確であった。Roberts の \(\xi=dU+\omega\) の仕事項 \(\omega\) はファイバー座標に比例しない加法項であり、線形形 \(dv+Av\) には含まれない。正確な包含関係は §29.6A の三層階層による：Roberts と定理 34 が同一の構造化された図式に入る最小の場所は、線形接続ではなく**アフィン情報熱接続**である。

**証明。** 二段に分ける。

*(i) Ehresmann 曲率と線形曲率の一致（符号規約込み）。* 局所座標 \((x^i,v^\alpha)\) で \(X=\partial_i\) の水平リフトは

\[
X^h=\partial_i-(A_iv)^\alpha\partial_{v^\alpha},
\qquad A_i:=A_{\rm ctrl}(\partial_i).
\]

座標場 \(\partial_i,\partial_j\) に対し

\[
[X^h,Y^h]
=\Bigl[-(\partial_iA_j)v+(\partial_jA_i)v+A_jA_iv-A_iA_jv\Bigr]^\alpha\partial_{v^\alpha}
=-\bigl(F_{ij}\,v\bigr)^\alpha\partial_{v^\alpha},
\]

ここで \(F_{ij}=\partial_iA_j-\partial_jA_i+[A_i,A_j]\) は \(\nabla^{\rm ctrl}\) の曲率の局所成分。基底成分は消えるので \(\operatorname{vert}[X^h,Y^h]=[X^h,Y^h]\)、よって \(\Omega_{\rm ctrl}(X,Y)|_v=-F^{\nabla^{\rm ctrl}}(X,Y)v\)。符号は本規約（\(\Omega=\operatorname{vert}[\,\cdot\,,\cdot\,]\)、\(\Xi=dv+Av\)）に固有であり、以後この規約で固定する。

*(ii) \(F^{\nabla^{\rm ctrl}}=F_{\rm ctrl}\)。* 正典定理 34 の証明を再掲・補完する。\(s\in\Gamma(E_{\rm ctrl})\)、\(Ps=s\) とし、\(X,Y\) を可換な座標ベクトル場とする。

\[
\nabla^{\rm ctrl}_X\nabla^{\rm ctrl}_Ys
=PD_X(PD_Ys)
=P(D_XP)D_Ys+PD_XD_Ys,
\]

（\(P^2=P\)、\(PP=P\) を使用）。反対称化して

\[
F^{\nabla^{\rm ctrl}}(X,Y)s
=PF_A(X,Y)s
+P\bigl[(D_XP)D_Y-(D_YP)D_X\bigr]s.
\]

\(D_Ys=(D_YP)s+PD_Ys\) を代入する。\(D_A(P^2)=D_AP\) から \((D_AP)P+P(D_AP)=D_AP\)、左から \(P\) を掛けて

\[
P(D_AP)P=0.
\]

よって \(P(D_XP)D_Ys=P(D_XP)(D_YP)s+P(D_XP)P\,D_Ys=P(D_XP)(D_YP)s\)。反対称項と合わせて

\[
F^{\nabla^{\rm ctrl}}(X,Y)s
=\bigl(PF_AP+P(D_AP)\wedge(D_AP)P\bigr)(X,Y)s
=F_{\rm ctrl}(X,Y)s.
\]

(i)(ii) を合成して主張を得る。\(\square\)

**正典的読み替え。** 定理 34 の分解

\[
\text{task–gauge curvature}=\text{task が見る物理曲率}+\text{関連性の選び方自体の捩れ}
\]

は、IT 層では次と同値になる：**task 関連 hidden 予算の断熱輸送が操作順序に依存する度合い**は、物理曲率成分と task 族自身の変形成分（\(D_AP\neq0\)）の和である。定理 34 の系「\(F_A=0\) でも \(D_AP\neq0\) なら operational holonomy が生じ得る」は、IT 語彙では「物理的に平坦でも、何を関連とみなすかの変更履歴だけで情報熱ホロノミー（task 記憶）が生じ得る」となる。**rc2 訂正:** ただしこのホロノミーは一般に \(F_{\rm ctrl}=P(D_AP)\wedge(D_AP)P\neq0\) の**曲率由来**であり、平坦性（\(\Omega_I=0\)）を要する thermal holonomy memory の証人ではない。平坦な正典内証人は、基底を1次元に取った例 IT-E1（§29.8.1）で与える。

---

## 29.6A 定理 IT-3A. アフィン情報熱接続と曲率の二成分分解（上位本体）

**三層階層。** IT 層の接続は次の三層をなす。

| 層 | 形 | 構造群 | 含まれるもの |
| --- | --- | --- | --- |
| 一般 | \(\Xi_I=d\mathcal H_I+W_I\)（\(W_I\) の係数はファイバー依存可） | 擬群 \(\operatorname{Diff}(F)\)（構造の縮約なし） | Roberts 一般形（理想気体等、\(P_i\) が \(U\) 依存） |
| **アフィン** | \(\Xi_I=dv+A_Iv+\beta_I\)（\(A_I,\beta_I\) は基底から引き戻し） | \(\operatorname{Aff}(r)=GL(r)\ltimes\mathbb R^r\) | **統一定理の場所**：定理 34 と Roberts の係数ファイバー非依存例（Wankel 等） |
| 線形 | \(\Xi_I=dv+A_Iv\)（\(\beta_I=0\)） | \(GL(r)\) | 定理 34（定理 IT-3） |

補題 IT-0・定理 IT-1・定理 IT-2 は一般層で成立する。ゲージ共変な構造定理が書ける最小の構造化層がアフィン層であり、以後これを IT 層の**上位本体**とする。定理 IT-3 は \(\beta_I=0\) の線形部分定理へ再配置する。

**定理 IT-3A。** \(A_I\) を \(\mathfrak{gl}(r)\) 値、\(\beta_I\) を \(\mathbb R^r\) 値の基底 1 形式（いずれも \(B_I\) から引き戻し）とし、

\[
\boxed{
\Xi_I=dv+A_Iv+\beta_I
}
\]

と置く。\(\Xi_I\) は垂直非退化であり（\(\Xi_I|_V=dv|_V\)）、補題 IT-0 により \(\mathscr H_I=\ker\Xi_I\) は Ehresmann 接続。その曲率は、垂直空間とファイバーの自然な同一視のもとで

\[
\boxed{
\Omega_I(X,Y)\big|_v
=-\Bigl(F_{A}(X,Y)\,v+(D_{A}\beta_I)(X,Y)\Bigr),
\qquad
F_A=dA_I+A_I\wedge A_I,\quad
D_A\beta_I=d\beta_I+A_I\wedge\beta_I.
}
\]

すなわち情報熱曲率は

\[
\boxed{
\text{情報熱曲率}
=
\underbrace{F_A\,v}_{\text{乗法的（表現・task–gauge）成分}}
+
\underbrace{D_A\beta_I}_{\text{加法的（仕事・hidden-exchange）成分}}
}
\]

と二成分に分解する。

**不変性警告（r2）。** 幾何学的本体は拡大曲率 \(\widetilde F\) 全体であり、\((F_A\,v,\ D_A\beta_I)\) への分解は**選択したアフィン原点（零セクション）に相対的**である。ゲージ変換則（証明末尾）が示す通り、\(F_A\) は共役でのみ変換する（下部線形化の曲率として内在的）が、\(D_A\beta_I\) は原点移動 \(c\) に対して \(-(gF_Ag^{-1})c\) だけ混合する。したがって \(F_A\neq0\) の一般領域では「加法的曲率」は独立のゲージ不変量ではない。例外として \(F_A=0\) の層では \((D_A\beta_I)'=g\,D_A\beta_I\) と線形共変になり、加法成分が単独で意味を持つ。正典文は次の形で凍結する：

\[
\boxed{
\text{情報熱曲率はアフィン曲率 }\widetilde F\text{ であり、}
(F_A,\,D_A\beta_I)
\text{ は選択したアフィン原点に相対的な分解である。}
}
\]

同値な行列表示として、拡大変数 \(\widetilde v=(v,1)^{\!\top}\)、拡大接続 \(\widetilde A=\begin{pmatrix}A_I&\beta_I\\0&0\end{pmatrix}\) により \(\Xi_I=d\widetilde v+\widetilde A\,\widetilde v\)、曲率は

\[
\widetilde F=d\widetilde A+\widetilde A\wedge\widetilde A
=\begin{pmatrix}F_A&D_A\beta_I\\0&0\end{pmatrix}.
\]

**証明。** 水平リフトは \(X_i^h=\partial_i-(A_iv+\beta_i)^\alpha\partial_{v^\alpha}\)。\(A_i,\beta_i\) が基底のみに依存することを用いて交換子を展開すると

\[
[X_i^h,X_j^h]
=-\Bigl[(\partial_iA_j-\partial_jA_i+[A_i,A_j])v
+(\partial_i\beta_j-\partial_j\beta_i+A_i\beta_j-A_j\beta_i)\Bigr]^\alpha\partial_{v^\alpha}
=-\bigl(F_{ij}v+(D_A\beta)_{ij}\bigr)^\alpha\partial_{v^\alpha}.
\]

基底成分は消えるので \(\operatorname{vert}[X_i^h,X_j^h]=[X_i^h,X_j^h]\)。拡大行列表示は成分計算 \(d\widetilde v+\widetilde A\widetilde v=(dv+A_Iv+\beta_I,\,0)^{\!\top}\) と \(\widetilde A\wedge\widetilde A=\begin{pmatrix}A\wedge A&A\wedge\beta\\0&0\end{pmatrix}\) による。ゲージ変換則（§29.1）のもとで \(F_A\mapsto gF_Ag^{-1}\)、\(D_A\beta\mapsto g\,D_A\beta-(gF_Ag^{-1})c\) 型に共変であることは \(\widetilde F\mapsto\widetilde g\widetilde F\widetilde g^{-1}\)（\(\widetilde g=\begin{pmatrix}g&c\\0&1\end{pmatrix}\)）から従う。\(\square\)

**系 IT-3A.1（較正零予算からの生成・rc2 改称）。** アフィン束には標準的な零セクションが存在しないため、本系は物理的に較正されたエンタルピー原点（較正済み零予算セクション）の選択に相対的である。その選択のもとで、零予算セクション \(v=0\) 上でも

\[
\Omega_I(X,Y)\big|_{v=0}=-\,D_A\beta_I(X,Y)
\]

が残る。正典的読み替え：

\[
\boxed{
\text{較正零予算にある系でも、操作順序そのものが正味のエンタルピー変位を生成し得る。}
}
\]

線形層（定理 IT-3）はこの現象を表せない（線形ホロノミーは \(v=0\) を固定する）。これが線形層をアフィン層へ拡張する物理的必然であり、消去的粗視化アノマリー（A8）の熱力学的対応物の候補を与える。

**系 IT-3A.2（Wankel＝平行移動ホロノミー・r2 符号修正）。** Roberts §VII の回転仕事系は \(r=1\)、\(A_I=0\)、\(\beta_I=-\tau(\theta)\,d\theta\)、\(B_I=S^1\) の場合である。基底が 1 次元なので \(F_A=D_A\beta_I=0\) が自明に成立（局所平衡）する一方、水平条件 \(\Xi_I=0\) は \(dv=\tau\,d\theta\) を与え、ホロノミーは純粋な平行移動

\[
\operatorname{Hol}_I(S^1):\ v\mapsto v+\oint\tau\,d\theta\neq v,
\qquad
t_{S^1}=-\oint_{S^1}\beta_I=+\oint\tau\,d\theta
\]

として残る（Roberts の「一周で全エネルギーが増加する」記述と符号整合。r1 の \(-\oint\tau\,d\theta\) は誤りであった）。したがって thermal holonomy memory（§29.8）はアフィン描像では**曲率零の平行移動ホロノミー**、すなわち \(\operatorname{Aff}(r)\) の平行移動部分群に値を取る大域記憶として正確に特徴づけられる。

**正典的成果の再定式化（r1）。** v2.1 の成果は「Roberts を IDS へ追加したこと」ではなく、

\[
\boxed{
\text{IDS の task–gauge 曲率（乗法成分）と熱力学的仕事曲率（加法成分）を、}
\operatorname{Aff}(r)
\text{ アフィン情報熱接続の単一の曲率 }\widetilde F\text{ の二つのブロックとして統一したこと}
}
\]

である。

---

## 29.7 系 IT-3.1. \(\Xi_A=D_A\mathbb I\)・\(\Xi_\gamma\) の断熱的再解釈

§18.11 の正規化局所複素構造 \(\mathbb I=J(-J^2)^{-1/2}\) を、\(\operatorname{End}\)-束（誘導接続 \(D_A^{\rm End}\) 付き）の section とみなす。§29.6 の構成をファイバー \(=\operatorname{End}\)-束へ適用すると：

1. **輸送欠陥＝非断熱性。** \(\mathbb I\) のグラフが情報断熱接続 \(\mathscr H_I\) に沿う（＝水平 section である）こととは \(D_A^{\rm End}\mathbb I=0\) に他ならず、したがって

\[
\Xi_A=D_A\mathbb I
\]

は「保存回転構造の輸送が情報断熱でない度合い」を測る。\(\Xi_A\) は曲率ではなく **section の非水平性**であり、この型区別を正典に明記する。

2. **ホロノミー欠陥＝情報熱ホロノミーの作用。** §18.11 の

\[
\Xi_\gamma=\operatorname{Hol}_A(\gamma)\,\mathbb I_x\operatorname{Hol}_A(\gamma)^{-1}-\mathbb I_x
\]

は、\(\operatorname{End}\)-束上の情報熱ホロノミー \(\operatorname{Hol}_I(\gamma)\)（随伴作用）が \(\mathbb I_x\) を動かす量である。定理 IT-1(C)(D) の語彙で、\(\Xi_\gamma\neq0\) は「閉じた操作サイクルの断熱リフトが \(\mathbb I\) を復元しない」ことを意味する。

証明はいずれも定義の書き換えであり、新規の解析を要しない。\(\square\)

これにより OP-CX2（\(\Xi_A,\Xi_\gamma\) と曲率・欠陥族の統一障害理論）の**語彙側**は IT 層へ吸収される。定理化（欠陥族との定量関係）は依然 OP-CX2 に残る。

---

## 29.8 大域熱記憶の分類（r2 全面改稿）

### 29.8.1 定義 IT-D6（改称）. thermal holonomy memory

IT 構造を持つ IDS モデルにおいて、連結開集合 \(U\subseteq B_I\) 上で

\[
\boxed{
\Omega_I\big|_{\pi_I^{-1}(U)}=0
\quad\text{かつ}\quad
\exists\,\gamma\subset U:\ \operatorname{Hol}_I(\gamma)\neq\mathrm{id}
}
\]

が成り立つとき、\(\gamma\) の類を **thermal holonomy memory**（大域熱記憶）と呼ぶ。局所的にはあらゆる点で積分因子と局所情報断熱不変量が存在する（定理 IT-1/IT-2。エントロピーの名称は IT-C 較正後）にもかかわらず、サイクル後に消えない大域記憶が残る状態である。

**再分類注記（r2・重要）。** r0–r1 ではこれを thermal Type III と呼んだが、これは正典分類との不整合であった。既存 IDS の Type III は「fine の coexact sector → coarse の harmonic sector」という**粗視化による系譜的昇格**を本質とする（定理 25–26、\(\bar H^1\ominus H^1\)）。一方、本定義の現象は粗視化昇格を含まない。特に Wankel 型（\(A_I=0\)、\(d\beta_I=0\)、\(\oint\beta_I\neq0\)）では \(\beta_I\) は閉だが exact でない 1 形式であり、計量を選べば調和代表を持つ——すなわち正典語彙では **Type I（調和・位相的記憶）系**の対象である。よって本定義は thermal holonomy memory と改称し、Type I 系対応を定理 IT-4(5) の範囲で明示する。thermal Type III の名称は IT-D7 の昇格構造にのみ用いる。

**非空性の証拠（r2 凍結）。** 加法型（平行移動型）は Roberts §VII の回転仕事系（系 IT-3A.2、符号修正済み）。乗法型については、r2 までの「\(F_A=0,D_AP\neq0\) が rank \(r\) の実例族」という主張は誤りであった：その族は一般に \(F_{\rm ctrl}=P(D_AP)\wedge(D_AP)P\neq0\) の曲率由来ホロノミーであり、本定義（\(\Omega_I=0\)）を満たさない。正しい乗法型証人を次で与える。

**例 IT-E1（Möbius–Berry 証人・乗法型）。** \(B_I=S^1\)（task ループ座標 \(\theta\)）、\(V=S^1\times\mathbb R^2\)、\(D_A=d\)（\(F_A=0\)）とする。普遍被覆 \(\mathbb R\to S^1\) 上、または切断区間 \([0,2\pi]\) 上の局所単位フレームとして

\[
e(\theta)=\bigl(\cos\tfrac\theta2,\ \sin\tfrac\theta2\bigr),
\qquad
P(\theta)=e(\theta)e(\theta)^{\!\top}
\]

を置く。\(e(\theta+2\pi)=-e(\theta)\) であるため \(e\) 自身は \(S^1\) 上の大域 section ではないが、\(P\) の成分は \(\tfrac{1+\cos\theta}2,\ \tfrac{\sin\theta}2,\ \tfrac{1-\cos\theta}2\) で \(2\pi\) 周期・滑らかであり、\(S^1\) 上の rank 1 射影へ降下する。\(E_{\rm ctrl}=\operatorname{Ran}P\) は写像 \(\theta\mapsto[e(\theta)]\in\mathbb{RP}^1\) によるトートロジカル実直線束の引き戻し、すなわち Möbius 直線束であり**非自明**である。従って単一の大域ファイバー座標 \(v\) は存在せず、A15′ が実際に必要となる最初の正典内実例でもある。

基底が1次元なので \(F_{\rm ctrl}\equiv0\)、すなわち \(\Omega_I\equiv0\)（平坦）。普遍被覆上の局所表示で平行 section を \(s=f\,e\) と書くと、\(e^{\top}e'=0\) より

\[
P\,ds=f'e\,d\theta=0,
\]

したがって \(f\) は定数である。一周後には \(e(2\pi)=-e(0)\) なので

\[
s(2\pi)=-s(0),
\qquad
\operatorname{Hol}_I(S^1)=-1\in GL(1,\mathbb R),
\qquad L=-1,\quad t=0.
\]

これは純乗法型の thermal holonomy memory である。さらに \(H^1(\mathbb Z,\mathbb R_{-1})=0\)（\(B^1=(1-(-1))\mathbb R=\mathbb R\)）なので、この線形ホロノミー上の加法型記憶は原点変更で消去できる。すなわち、乗法型と加法型は独立に選べるだけでなく、係数の捩れによって相互に制約される。

**構造群注記。** 本例は \(GL(1,\mathbb R)=\mathbb R^\times\) を許す signed task／residual-budget 層の証人である。物理的エンタルピーの向きと単位を固定して構造群を \(GL^+(1,\mathbb R)=\mathbb R_{>0}\) に縮約する模型では、向きを反転する \(-1\) ホロノミーは許容ゲージから外れる。その場合、本例は抽象 task–gauge 層の証人ではあるが、正向き物理エネルギー単位だけを許す熱力学模型の証人とは数えない。

### 29.8.2 定理 IT-4. 平坦アフィンホロノミーの捩れコホモロジー分類

**定理。** \(U\subseteq B_I\) を連結開集合、その上のアフィン情報熱接続（A15 または A15′ の局所自明化可能アフィン束上、§29.6A）が平坦（\(\widetilde F=0\)、すなわち \(F_A=0\) かつ \(D_A\beta_I=0\)）とし、基点 \(b_0\in U\) を固定する。

**射程注記。** 本定理は、与えられた平坦接続のホロノミー表現を分類する。非自明アフィン束を含む全ての平坦接続の大域ゲージ同値類を接続データだけから分類するという、より強い主張はしない。標準的な普遍被覆・モノドロミー対応が使える連結滑らかな基底を仮定する。

1. **（ホモトピー不変性）** 平行移動は道の端点固定ホモトピー類にのみ依存し、ホロノミーは表現

\[
\rho=(L,t):\pi_1(U,b_0)\longrightarrow\operatorname{Aff}(r)=GL(r)\ltimes\mathbb R^r
\]

を定める。

2. **（コサイクル則）** 合成則は

\[
L_{\gamma\delta}=L_\gamma L_\delta,
\qquad
t_{\gamma\delta}=t_\gamma+L_\gamma t_\delta,
\]

すなわち \(t\in Z^1\bigl(\pi_1(U),\mathbb R^r_L\bigr)\)（線形ホロノミー表現 \(L\) で捩れた係数の群 1-コサイクル）。

3. **（ゲージ依存性）** ファイバー枠と原点の変更 \((g,c)\in\operatorname{Aff}(r)\) は \(\rho\) の共役に対応し、

\[
L_\gamma\mapsto gL_\gamma g^{-1},
\qquad
t_\gamma\mapsto g\,t_\gamma+\bigl(I-gL_\gamma g^{-1}\bigr)c.
\]

純原点移動（\(g=I\)）では \(t\) は coboundary \((I-L_\gamma)c\) だけ変化する。

4. **（モジュライ分類）** 純原点移動により、固定した線形表現 \(L\) に対する平行移動成分は捩れコホモロジー類

\[
[t]\in H^1\bigl(\pi_1(U),\mathbb R^r_L\bigr)
\]

へ降下する。ただし線形枠の変更も許す完全なアフィンゲージ同値では、\([t]\) は生の単独不変量ではない。\(L\) の代表元を固定した後にも中心化群

\[
Z_{GL(r)}(L)
=
\{g\in GL(r):gL_\gamma=L_\gamma g\ \forall\gamma\}
\]

が \(H^1(\pi_1(U),\mathbb R^r_L)\) に作用する。従ってアフィンホロノミー表現の共役モジュライは、集合論的に

\[
\boxed{
\frac{\operatorname{Hom}(\pi_1(U),\operatorname{Aff}(r))}{\operatorname{Aff}(r)}
\cong
\bigsqcup_{[L]\in\operatorname{Hom}(\pi_1(U),GL(r))/GL(r)}
\frac{H^1(\pi_1(U),\mathbb R^r_L)}{Z_{GL(r)}(L)}
}
\]

と整理される（異なる代表元間の同定は共役が誘導する係数加群同型による）。したがって幾何学的本体は、生の対 \(([L],[t])\) ではなく、**線形ホロノミー表現と捩れコホモロジー類からなる対の同型類**である。**乗法型記憶**と**加法型記憶**は独立に非自明になり得るが、完全分類では中心化群作用まで商に取る。

5. **（純平行移動型・de Rham 対応・r2 最終精密化）** \(L\equiv I\) のとき \(H^1(\pi_1(U),\mathbb R^r)=\operatorname{Hom}(\pi_1(U),\mathbb R^r)\) であり、coboundary \((I-L)c=0\) が消えるので \(t\) は**原点変更に対して**厳密な不変量。ただし \(Z_{GL(r)}(I)=GL(r)\) が \(t\mapsto gt\) と作用するため、完全な情報エンタルピー・ゲージ下の不変量は第4項の通り \(t\) の \(GL(r)\) 軌道（同値に、de Rham 類のフレーム共変な同型類）である。ファイバー rank が \(r=1\) でも \(H^1(\pi_1(U),\mathbb R)\) は一般に多次元であり、完全ゲージ下の非零不変量はその実射影類

\[
[t]\in\mathbb P\!\left(H^1(\pi_1(U),\mathbb R)\right)
\]

である（向き保存ゲージ \(\mathbb R_{>0}\) に制限すれば正の ray 類）。\(b_1(U)=1\) の場合に限って、全 \(GL(1,\mathbb R)\) ゲージ下では零／非零へ、向き保存ゲージ下ではさらに符号つき ray へ縮約する。Wankel は \(U=S^1\) なのでこの一次元の場合に属し、\(\oint\tau\,d\theta\) の数値自体はエネルギー単位の取り替えでスケールする。さらに \(A_I=0\) の場合、平坦性は \(d\beta_I=0\) となり、

\[
t_\gamma=-\oint_\gamma\beta_I,
\]

すなわち \([t]\) は de Rham 類 \(-[\beta_I]\in H^1_{\rm dR}(U)\otimes\mathbb R^r\) の周期準同型に一致する。Wankel（\(\beta_I=-\tau\,d\theta\)、\(U=S^1\)）では \(t_{S^1}=\oint\tau\,d\theta\)。

**証明。** (1) 平行移動はアフィン線形 ODE \(\dot v=-A_I(\dot\gamma)v-\beta_I(\dot\gamma)\) の解として存在・一意・完備（線形成長評価による）。拡大表示 \(\Xi_I=d\widetilde v+\widetilde A\,\widetilde v\) により、平坦線形接続 \(\widetilde A\)（\(\widetilde F=0\)）の平行移動のホモトピー不変性という標準事実に帰着する。(2) 道の連結に対する transport の合成が \(\operatorname{Aff}(r)\) の積 \((g_1,c_1)(g_2,c_2)=(g_1g_2,\,g_1c_2+c_1)\) に従うことから直ちに従う。(3) \(\widetilde g=\begin{pmatrix}g&c\\0&1\end{pmatrix}\) による共役の直接計算：

\[
(g,c)(L_\gamma,t_\gamma)(g,c)^{-1}
=\bigl(gL_\gamma g^{-1},\ g\,t_\gamma+(I-gL_\gamma g^{-1})c\bigr).
\]

(4) 固定した \(L\) のもとで純原点移動は coboundary を加えるため \(H^1\) へ降下する。さらに同じ \(L\) を保つ線形枠変更は中心化群 \(Z_{GL(r)}(L)\) をなし、これがコホモロジー類へ作用する。線形表現の共役類ごとにこの商を取り、異なる代表元を共役誘導同型で同定すれば表示された非交和を得る。(5) \(L=I\) では係数の作用が自明なので \(Z^1=\operatorname{Hom}\)、\(B^1=0\)。\(A_I=0\) では transport が \(\dot v=-\beta_I(\dot\gamma)\) の線積分となり主張の式を得る。\(\square\)

**系 IT-4.1（OP-IT3 分類部分の閉包）。** r1 で OP-IT3 に送った「thermal 大域記憶の二型分類の定理化」は、平坦・局所自明化可能・有限次元層において定理 IT-4 で閉包された。

**正典的接続（構造対応・限定つき）。** 既存 IDS 可換核の残差類 \([\omega]\in C^1/\operatorname{im}d_0\) は鎖複体上の \(H^1\) 型対象であり、定理 IT-4 の \([t]\in H^1(\pi_1,\mathbb R^r_L)\) はその**線形ホロノミー表現で捩られた非可換一般化**の位置に立つ。純平行移動・rank 1 では (5) の de Rham 対応により文字通り \(H^1\) 類に一致する。ただし複体が異なる（グラフ複体 vs 基本群コホモロジー）ため、一般階数での同型主張はせず、対応の定理化は OP-IT3 の残余に含める。

### 29.8.3 定義 IT-D7. thermal Type III（昇格構造・再定義）

fine 側と coarse 側の IT 構造の間に許容粗視化に対応するスケール写像が与えられているとする。**thermal Type III 構造**とは、

\[
\boxed{
\text{fine 側の局所非可積分性（}\Omega_I^{\rm fine}\neq0\text{）または仕事残差}
\ \longrightarrow\
\text{coarse 側の平坦かつ非自明な thermal holonomy memory}
}
\]

という**昇格**であって、promotion map と decoder（定理 25–26 の thermal 版）を伴うものをいう。定義 IT-D6 の thermal holonomy memory は coarse 側の到達状態であり、それ自体は Type III ではない。IT-D7 の非空性・構成・既存 Type III（\(\bar H^1\ominus H^1\)）との対応はすべて未確立であり、OP-IT3（残余）とする。

---

## 29.9 原理と較正条件

**較正条件 IT-C（エントロピー較正・r1）。** 定理 IT-2 の局所情報断熱不変量 \(\mathbf S_I\) を**情報エントロピー**と呼ぶための追加条件を次とする。

1. **reference 整合**：保存 moment 固定下で、v2.0 の最大エントロピー reference の最大化量と（単調再パラメータ化を除いて）一致する。
2. **凹性**：適切なチャネル分解のもとで凹。
3. **data-processing 整合**：対象とするエントロピー／ダイバージェンスの規約で単調方向を明示し、その方向で許容粗視化（A7）に対して単調。
4. **退化整合**：\(r=1\)・物理熱力学模型への制限で通常のエントロピー規約へ退化する。

IT-C を満たさない \(\mathbf S_I\) は局所情報断熱不変量のままであり、エントロピーの名を与えない。Carathéodory 型構成では \(\mathbf S_I\) は葉の単調再ラベルの自由度を持つため、IT-C は名称の較正であると同時にこの自由度の部分的固定でもある。IT-C の充足可能性・一意性は OP-IT1(a) と結合した未解決問題である。

**原理 IT-A（創発熱力学原理・条件付き・r2 精密化）。** 平坦性（\(\Omega_I=0\)）は局所情報断熱不変量と積分因子の存在条件であり（定理 IT-1/IT-2）、情報エントロピー・情報温度への昇格には較正条件 IT-C を追加する。いずれも公理として仮定しない。（無限次元・特異層では未証明：OP-IT4。）

**原理 IT-B（三分離原理・一部未導出）。** 次の三者を同一視しない。

- \(\Omega_I\neq0\)：局所非可積分性・操作順序依存（定理化済み）。
- \(\operatorname{Hol}_I\neq\mathrm{id}\)（\(\Omega_I=0\) 下）：大域的熱記憶・thermal holonomy memory（定理 IT-4 で分類済み）。
- 許容な未来向き過程 \(u\) に対する \(d_iS_I(u)\ge0\)：実際の不可逆エントロピー生成。

**監査注記（必須）:** 第三項は Roberts から従わない。Roberts の枠組みは熱静力学であり散逸を含まない。また、1 形式の正値性を全接ベクトルに要求すると \(u\) と \(-u\) の双方が許されるため、尖鋭な正錐では生成項が自動的に零となる。そこで各点 \(p\in\mathcal E_I\) に、物理的に許容された未来向き過程の非空な閉凸接錐

\[
\mathcal C_{\rm proc}(p)\subseteq T_p\mathcal E_I
\]

を追加データとして指定し、生成不等式はこの錐上でのみ課す。候補分解は、rank 1 では

\[
\boxed{
\forall u\in\mathcal C_{\rm proc}(p):\quad
 dS_I(u)=T_I^{-1}\Xi_I(u)+d_iS_I(u),
 \quad d_iS_I(u)\ge0,
}
\]

rank \(r>1\) では閉凸・尖鋭な生成錐 \(K_S\subset\mathbb R^r\) を指定して

\[
\boxed{
\forall u\in\mathcal C_{\rm proc}(p):\quad
 d\mathbf S_I(u)=M_I^{-1}\boldsymbol\Xi_I(u)+d_i\mathbf S_I(u),
 \quad d_i\mathbf S_I(u)\in K_S.
}
\]

正の共役ベクトル \(\lambda\in\operatorname{int}K_S^*\) を選べば、スカラー生成率

\[
\sigma_I(u):=\langle\lambda,d_i\mathbf S_I(u)\rangle\ge0
\qquad
(u\in\mathcal C_{\rm proc}(p))
\]

を得る。\(\mathcal C_{\rm proc}\)、\(K_S\)、\(\lambda\) の正典的選択、ゲージ共変性、粗視化整合性、残差力学からの導出は OP-IT2 に含める。

これは IDS 側の**追加構成原理の候補**であり、既存 IDS 方程式（\(\dot\rho=-L\rho+J\rho+a\)、拡張二次収支汎関数）からの導出は未完である。この地位は正典 C.3 の「スペクトルストレス適応則は未導出」と同格に扱う。

---

## 29.10 未解決問題

**OP-IT1（改稿）。** (a) 行列積分因子 \(M_I\) のスカラー圧縮・ブロック対角化のゲージ不変条件。(b) 非平坦時の正準分解 \(\Xi_I=M_I\,d\mathbf S_I+\Xi_I^{\rm anh}\) と非可積分残部の障害類同定、残差類 \([\omega]\) との関係。(c) 局所エントロピー座標の大域貼り合わせ障害と \(\operatorname{Hol}_I\) の分類。（存在問題は定理 IT-2 で局所閉包済み。）

**OP-IT2。** Feshbach self-energy \(\Sigma_{\rm br}^{\rm self}(z)\) からの情報熱接続の正準構成：hidden 有効状態 \(h_*(b)\) の垂直補正から \(W_I\) を構成し、OP-13（\(K\to A\) 橋）の候補構成として評価する。あわせて原理 IT-B 第三項の残差力学からの導出、および許容過程接錐 \(\mathcal C_{\rm proc}\)、生成錐 \(K_S\)、正の共役 \(\lambda\in K_S^*\) の正準構成・ゲージ共変性・粗視化整合性を定理化する。

**OP-IT3（r2 改稿・残余）。** 平坦層の分類は定理 IT-4 で閉包済み。残余：(a) thermal Type III（IT-D7、昇格構造）の promotion map・decoder の構成と非空性、(b) 既存 Type III（\(\bar H^1\ominus H^1\)、定理 25–26）との対応の定理化または反例、(c) \([t]\in H^1(\pi_1,\mathbb R^r_L)\) と可換核 \([\omega]\in C^1/\operatorname{im}d_0\) の一般階数での関係（グラフ複体と基本群コホモロジーの橋）、(d) 非平坦（\(\widetilde F\neq0\)）での大域記憶の分類。

**OP-IT4。** Banach ファイバー・rank-change・垂直退化点・非可換（Lie 代数値）\(\Xi_I\) への拡張。特に quantum 層での取り扱い。

---

## 29.11 受理判定

受理条件は「既存正典対象の少なくとも一つを \(F_I\) の特殊化として証明付きで再導出すること」であった。判定：

1. **合格（主）:** 定理 IT-3 により、定理 34 の \(F_{\rm ctrl}=PF_AP+P(D_AP)\wedge(D_AP)P\) は、制御情報熱形式 \(\Xi_{\rm ctrl}=dv+A_{\rm ctrl}v\) の Ehresmann 曲率として（符号規約 \(\Omega=-F\,v\) のもと）再導出された。
2. **合格（副）:** 系 IT-3.1 により、§18.11 の \(\Xi_A,\Xi_\gamma\) はそれぞれ「section の非断熱性」「情報熱ホロノミーの作用」として同じ図式に位置づけられた。
3. **較正修正:** 元提案の OP-IT1（行列積分因子の存在）は、平坦局所層では未解決問題ではなく定理（IT-2）であることが判明し、未解決部分を (a)–(c) へ再定義した。
4. **r1 追加（外部講評反映）:** 定理 IT-3A により、統一の正しい場所が線形接続ではなくアフィン情報熱接続であることが確定した。定理 34（乗法成分）と Roberts 型仕事ホロノミー（加法成分）は単一の拡大曲率 \(\widetilde F\) の二ブロックであり、r0 の統合主張はこの形でより強く成立する。同時に、r0 の「Roberts＝線形図式の rank-1 極限」という包含主張は訂正され、一般 Roberts は IT-0 の一般層、係数ファイバー非依存例のみがアフィン層に属することを明記した。
5. **r2 追加（第二次講評反映）:** (a) 系 IT-3A.2 の符号誤りを修正。(b) \(\widetilde F\) 全体のみが幾何学的本体であり二成分分解は原点相対であることを凍結。(c) 旧 thermal Type III を thermal holonomy memory（Type I 系）へ再分類し、定理 IT-4 により平坦アフィンホロノミーを、線形表現の共役類ごとの \(H^1(\pi_1(U),\mathbb R^r_L)/Z_{GL(r)}(L)\) としてモジュライ分類した（OP-IT3 の平坦分類部分を閉包）。これにより本層は曲率統合に加え、**情報熱の大域記憶を線形ホロノミー表現で捩られたコホモロジー類として分類する**層を獲得し、可換核の \(H^1\) 構造との接続が明示化された。

以上により IT 層は**統合**（原始概念の削減）であって並列語彙の追加ではなく、受理条件を満たす。本 v2.1.0-r2 では独立講評三巡、中心化群モジュライ監査、IT-E1 の束論的再検算、不可逆生成の接錐型監査を反映し、§23 のステータス台帳・§30 の Freeze Record・非主張リストを更新した上で public-r6.2 として正式凍結した。

---

## 29.12 凍結しないもの（本層が主張しないこと）

1. 質量ギャップ、OP-13 の閉包、PNATD への寄与。OP-IT2 は候補構成の提示にとどまる。
2. 許容過程接錐 \(\mathcal C_{\rm proc}\) 上の rank 1 非負生成、または rank \(r\) の \(K_S\)-錐値生成を含む非平衡分解が既存 IDS 方程式から従うこと。
3. thermal Type III（IT-D7）の非空性、および既存 Type III（\(\bar H^1\ominus H^1\)）との同一視。thermal holonomy memory の Type I 系対応も、定理 IT-4(5) の de Rham 対応（純平行移動・\(A_I=0\)）を超える一般階数では主張しない。
4. 無限次元・特異・量子層での定理 IT-0〜IT-4 の成立。
5. Roberts の枠組みが熱力学と IDS の関係を「類比以上のもの」として確立すること（Roberts 自身が原論文結論部で保留している論点であり、本層も保留を継承する）。
6. あらゆる IDS モデルが IT 構造を持つという普遍存在主張。

---

## 29.13 監査注記・出典

- 輸入定理の原典: B. W. Roberts, "Heat as a gauge connection," arXiv:2503.08753（v2, 2026-01-11 生成版を参照）。Theorem 1・Corollary 1（同値 (A)–(D)）、§VI（Jauch 保存則の (D)⇒(A) としての証明）、§VII（flat かつ非自明ホロノミーの回転仕事系実例）。
- 定理 IT-0/IT-2 は古典的（Frobenius・Ehresmann）だが、IDS 文脈での条件化（垂直非退化性の明示、較正修正）は本層で行った。独立検証を推奨する。
- 定理 IT-3(ii) は正典定理 34 の証明の再掲・補完であり、(i) の符号計算は本層で固定した規約に依存する。他文献と符号が異なり得る点に注意。
- **r1 外部講評記録:** 独立講評（2026-07-16）が IT-0/IT-2/IT-3 の中心計算を追認した上で、(i) 線形からアフィンへの本体昇格、(ii) ゲージ変換則の明示、(iii) エントロピー較正の分離、(iv) Jauch のファイバー単射性、を指摘。(i) の曲率公式 \(\operatorname{vert}[X^h,Y^h]|_v=-(F_Av+D_A\beta)\)、拡大行列曲率 \(\widetilde F\)、ゲージ変換則は本層側で独立に検算し一致を確認した。講評の「アフィンが最小共通形」という表現のみ較正した：一般 Roberts（係数ファイバー依存）は IT-0 の一般層に属し、アフィン層は「構造群を持ちゲージ共変定理が書ける最小の構造化層」である。
- **r2 外部講評記録:** 第二次独立講評（2026-07-16）が r1 に対し四点を指摘。(1) 系 IT-3A.2 の符号誤り——本層側の水平条件 \(dv=\tau\,d\theta\) の再計算により**誤りを確認し修正した**。(2) 二成分分解の原点相対性——r1 で導出済みの変換則 \((D_A\beta)'=gD_A\beta-(gF_Ag^{-1})c\) の直接の帰結であり、不変性警告として凍結した。(3) 旧 thermal Type III の再分類——Wankel 型が \(\beta_I\) の de Rham 類（調和代表を持つ位相記憶）である以上、正典分類では Type I 系が正しいという指摘を受理し、改称・再定義した。(4) コサイクル分類——\(\operatorname{Aff}(r)\) の積・共役計算を本層側で独立に検算し（\(t_{\gamma\delta}=t_\gamma+L_\gamma t_\delta\)、\(t\mapsto gt+(I-gLg^{-1})c\)）、定理 IT-4 として証明付きで採録した。講評者の提案が定理として成立することを確認済み。
- 本節は正典 §29 として統合済みである。以後の改訂は改訂履歴・§30・付録 B.2 の同時更新を要する。
- **第三次外部講評記録（rc2）:** 第三次独立講評（2026-07-16）が (1) IT-4(5) の過大不変性、(2) 曲率由来ホロノミーと平坦記憶の混同（本層側の誤り、三巡の監査を通過していた）、(3) 零予算の原点相対性、(4) rank \(r>1\) 生成式の型不備、を指摘。(2) は本層側で \(F_{\rm ctrl}\) の直接評価により誤りを確認し、例 IT-E1（Möbius–Berry、\(\operatorname{Hol}=-1\)・\(H^1(\mathbb Z,\mathbb R_{-1})=0\) まで検算済み）で置換した。なお同講評の指摘1（中心化群商）は先行監査で反映済みであった。
- **r2 最終凍結監査記録:** rc2 の残条件を独立に再検算した。(1) IT-E1 では \(e\) を普遍被覆上の局所フレームとして扱い、\(P\) の周期性、Möbius 束の非自明性、平坦性、\(\operatorname{Hol}=-1\)、\(H^1(\mathbb Z,\mathbb R_{-1})=0\) を確認。(2) rank 1 の完全ゲージ不変量は一般に \(H^1\) の射影類であり、零／非零への縮約は \(b_1(U)=1\) に限定した。(3) 不可逆生成は許容過程接錐 \(\mathcal C_{\rm proc}\) 上の評価として型安全化した。(4) 現行正本を v2.1.0-r2／public-r6.2 とし、detached checksum・r1差分・rc2差分を同梱した。

---


# 30. v2.1.0-r2 Freeze Record

1. v2.0.0-r1 の全定理・停止線を変更せず継承する。
2. A15／A15′、補題 IT-0、定理 IT-1〜IT-4、定理 IT-3A、系 IT-3.1、例 IT-E1 を有限次元・滑らかな古典正則層で凍結する。IT-E1 は全構造群 \(GL(1,\mathbb R)\) の証人であり、正向き部分群 \(GL^+(1,\mathbb R)\) に制限した物理的部分圏の証人とは数えない。
3. 定理 IT-2 が与えるものを「局所情報断熱不変量」とし、IT-C なしに情報エントロピーと呼ばない。
4. 情報熱曲率の本体を \(\widetilde F\) 全体とし、\((F_A,D_A\beta_I)\) の二成分をアフィン原点相対とする。
5. Wankel 型を thermal holonomy memory（Type I 系）へ分類し、符号を \(v\mapsto v+\oint\tau d\theta\) と凍結する。IT-E1 は純乗法型、Wankel は純加法型の有限証人として区別する。
6. 平坦アフィンホロノミーの分類は、生の対 \(([L],[t])\) ではなく、線形表現共役類ごとの \(H^1(\pi_1,\mathbb R^r_L)/Z_{GL(r)}(L)\) として凍結する。\(L=I,r=1\) の完全ゲージ商は一般に \(\{0\}\sqcup\mathbb P(H^1(U;\mathbb R))\) であり、零／非零へ縮約するのは \(b_1(U)=1\) の場合に限る。
7. thermal Type III は promotion map・decoder を伴う coarse-graining 昇格構造として定義のみを置き、非空性と既存 Type III との同一視を主張しない。
8. 不可逆エントロピー生成は、許容過程接錐 \(\mathcal C_{\rm proc}\) 上の rank 1 非負生成または rank \(r\) の \(K_S\)-錐値生成という**型規約のみ**を置く。\(\mathcal C_{\rm proc}\)、\(K_S\)、\(\lambda\) の正準性と力学的導出は未解決のまま保持する。
9. Feshbach self-energy からの正準 IT 接続、Banach／rank-change／特異／量子拡張は未解決のまま保持する。
10. IT 層から mass gap、PNATD、OP-13 の閉包を導かない。
11. 4D Yang--Mills の load-bearing 停止点を Physical Non-Abelian Tariff Descent のまま変更しない。
12. **正式凍結完了:** IT-E1 の周期性・Möbius 束の非自明性・平坦性・\(\operatorname{Hol}=-1\)・\(H^1(\mathbb Z,\mathbb R_{-1})=0\) を再検算し、局所フレームと構造群射程を修正した。IT-4(5) を rank 1 一般の射影類へ修正し、零／非零縮約を \(b_1(U)=1\) に限定した。rank \(r>1\) の不可逆生成を許容過程接錐上の錐値 1 形式として型安全化した。
13. detached checksum は `IDS_Canonical_Theory_v2_1_0_r2_JA.sha256` として別ファイルで発行し、その外部ファイルを正本照合値とする。
14. `IDS_Canonical_Theory_v2_1_0_r1_JA.md` と `IDS_Canonical_Theory_v2_1_0_rc2_JA.md` は監査・差分追跡用の superseded historical release として保持し、異なる内容へ既存版番号を再利用しない。現行正本は v2.1.0-r2／public-r6.2 とする。

---

# 付録 A. 最小 2-複体の雛形

頂点 \(\{0,1,2,3\}\)、辺

\[
e_0=(0,1),
e_1=(1,2),
e_2=(2,3),
e_3=(3,0),
e_4=(0,2)
\]

三角 2-cell

\[
T_1=(0,1,2),
\qquad
T_2=(0,2,3)
\]

を持つ複体を考える。

このとき、標準向きで

\[
d_0=
\begin{pmatrix}
-1&1&0&0\\
0&-1&1&0\\
0&0&-1&1\\
1&0&0&-1\\
-1&0&1&0
\end{pmatrix}
\]

\[
d_1=
\begin{pmatrix}
1&1&0&0&-1\\
0&0&1&1&1
\end{pmatrix}.
\]

\[
d_1d_0=0.
\]

曲率 Laplacian は

\[
L=\delta_1d_1=d_1^Td_1.
\]

この複体では \(H^1=0\) で、Type I 構造は存在せず、Type II 構造の最小実験場になる。2-cell を一つ除去すると \(H^1\ne0\) となり、Type I + Type II の混合を観察できる。

---

# 付録 B. One-page English Abstract

IDS is a principle theory of open hierarchical systems under finite observable resources. Its core architecture separates latent positive accumulation from observable finite allocation, equips the observable manifold with a scalar stress functional dissipated by natural gradient flow, and identifies the cross-scale invariant not with raw information or scalar stress but with the non-integrable Hodge residual class

\[
[\omega]\in C^1/\operatorname{im}d_0.
\]

Admissible coarse-graining preserves gradients and therefore descends to the residual quotient; eliminative coarse-graining violates this condition and generates an anomaly. Promoting the residual class to a dynamical variable yields the minimal abelian debug equation

\[
\dot\rho=-\delta_1d_1\rho+a,
\]

with causal orientation represented by an admissible conservative generator \(J\), giving

\[
\dot\rho=-L\rho+J\rho+a.
\]

Structures are stable nonzero co-fixed points of residual dynamics and observer selection. Resilience is persistence of residual classes under perturbation, observation, and coarse-graining; its simplest quantitative measure is the positive spectral gap of the curvature Laplacian. Holography, mass gap, cosmology, galaxy dynamics, AI self-debugging, and future/past interaction are treated as modular extensions. The golden ratio is not a fundamental axiom; it is the Perron/minimax signature of the minimal binary swap–aggregation architecture and of a self-dual additive residual balance on SPD observables.

From v1.2 the geometric vessel is reorganized as gauge-information geometry: a hierarchical bundle of probability manifolds over scale space, Fisher/SPD metrics on fibers (canonical by Chentsov monotonicity), irreversible coarse-graining maps between fibers, and a gauge connection comparing surviving degrees of freedom across scales. The proven abelian core is preserved as the flat, abelian, gauge-fixed limit. Finite flat noncommutative deformation, gauge-quotient local structure, and Type III promotion are established as finite theorem layers; continuum nonflat, global gauge, and quantum completion remain open.

Later revisions extend the canon in three directions. v1.4 integrates self-coarse-graining (co-evolution of effective states and compression rules), dynamical closure defects, and geometric stress as obstruction classes surviving gauge, exact, local-redefinition, and null quotients. v1.5 integrates an independently audited advance on the non-abelian program: centered connected defects accumulate quadratically in amplitude and only linearly in volume, giving the four-dimensional threshold alpha > 2; the compact-Lie small-field sector, after a finite order-epsilon^2 counterterm, leaves an order-epsilon^4 residual (alpha = 4), so the remaining wall is uniform multiscale control, not volume. v1.6 adds the residual emission-carrierization-re-encoding principle: residuals coupled to transport can be externalized as carrier states and re-encoded as new residual classes in receiving systems, closing the dynamic cycle residual -> carrier -> new residual -> geometry update. v1.6.3 closes the typed chain–dynamic defect calculation by an exact compatibility identity, separates a chain-anomaly example from a genuine coexact-to-harmonic Type III example, and introduces a conditional bundle of normalized local complex structures \(\mathbb I=J(-J^2)^{-1/2}\). Its transport and holonomy defects, \(\Xi_A=D_A\mathbb I\) and \(\Xi_\gamma\), measure failure to preserve conservative rotation structures across scales; they do not by themselves constitute an arrow of time. The four canonical layers remain: the heart (the residual class), the vessel (gauge-information geometry), the process (selection and generation of obstruction classes under coarse-graining), and the motion (carrierization, propagation, and re-encoding of residuals across systems and scales), now crossed by a covariant phase/rotation structure. v1.7.0 rigorously identifies constraint-forgetting Type III as the promoted subspace \(\bar H^1\ominus H^1\), extends finite compression by the promotion map \(\Gamma_K=\bar P K(I-P)\) and its Moore--Penrose decoder, redefines IDS holography as global intertwining plus subregion nonclosure plus recoverability, and introduces the control-relevant quotient \(Q_{\mathrm{ctrl}}\) with projected-mixing and resilience-budget theorems. The latter closes only task-relative inverse problems; it does not solve the full Yang--Mills mass-gap or universal microscopic witness-lifting problems. v1.7.1 places this quotient after the physical gauge-orbit quotient, proves gauge covariance of the control-relevant projector on regular strata, splits task--coarse incompatibility into promotion and erasure defects, and equips the control-relevant subbundle with the induced connection whose curvature is \(F_{\mathrm{ctrl}}=PF_AP+P(D_AP)\wedge(D_AP)P\). Singular strata, non-invariant and dynamic tasks, and global nonlinear descent remain open.

v1.8.0 closes the finite linear bridge between the static residual quotient and a full return cycle. A split residual realization \(\iota:\mathcal X\to V\), \(\varpi:V\to\mathcal X\), \(\varpi\iota=I\), yields the exact decomposition \(V=\iota\mathcal X\oplus\ker\varpi\). Absorbing every decoder-invisible direction into the bridge-hidden sector gives an exact Feshbach self-energy \(\Sigma_{\rm br}^{\rm self}(z)\) and intervention-dependent spectral function \(\chi_{\rm SR}(z,s)\) directly on \(\mathcal X=C^1/\operatorname{im}d_0\), with no projection-induced false positives. Gauge and scale naturality follow from chain and return intertwiners. A complementary no-go theorem proves that no spectrum or resolvent of the observed return operator alone can distinguish endogenous renewal from an external oracle implementing the same map. Causal closure without external templates, joint turnover reconstruction of the residual comparison rules and distributed backups, bounded normalized self dynamics, transverse contraction uniform relative to the self mode, and the proposed spectral-stress adaptation law therefore remain explicit, falsifiable constitutive conditions rather than consequences of operator theory. This regeneration closure is the fifth canonical layer added to the heart, vessel, process, and motion layers.


## B.1 v2.0 English Update

Version 2.0 adds a quantitative physical-closure layer. The common mechanism is promotion of large omitted channels, weighted control of the infinite tail, bounded decoding or parametrices, and Carleman--Green transport of the remaining defect. A direct multiscale gap theorem shows that a scale-unitary metric decomposition, a same-law positive tariff on every detail channel, a terminal anchor, a bounded decoder, and a transported defect budget strictly below one imply a physical vacuum-complement lower bound without requiring an autonomous finite-dimensional RG trajectory.

For four-dimensional Yang--Mills, the remaining load-bearing statement is sharpened to Physical Non-Abelian Tariff Descent: non-Abelian Casimir seeds, conditional twirl observability, finite-star action channels, same-law atlases, and volume-uniform Feshbach/tail bounds must be compared on the actual transfer-Hamiltonian form, uniformly in volume, lattice spacing, scale, boundary condition, and global sector. This statement remains open; the mass gap is not claimed.


## B.2 v2.1 English Update

Version 2.1 adds an information-thermal connection layer without replacing the version 2.0 enthalpy ledger. A vertically nondegenerate, vector-valued exchange form defines an Ehresmann horizontal distribution for information-adiabatic comparison. Vanishing curvature is locally equivalent to the existence of a matrix integrating factor and independent adiabatic first integrals; these first integrals are called information entropy only after additional calibration against maximum-entropy references, concavity, data-processing behavior, and the ordinary thermodynamic limit.

On the structured affine layer,

\[
\Xi_I=dv+A_Iv+\beta_I,
\qquad
\widetilde F=
\begin{pmatrix}
F_A&D_A\beta_I\\
0&0
\end{pmatrix},
\]

so the previously derived task--gauge curvature is the homogeneous linear sector, while additive work or hidden-exchange curvature is the translational sector. Only the full affine curvature is intrinsic; the two-block split depends on the chosen affine origin. Flat connections can nevertheless retain global information-thermal memory. Their affine holonomy is classified, for each linear holonomy conjugacy class, by twisted group cohomology modulo the centralizer action. A Möbius real line bundle gives a flat purely multiplicative witness with holonomy \(-1\) when the full structure group \(GL(1,\mathbb R)\) is allowed; it is not a witness in a positively oriented \(GL^+(1,\mathbb R)\) subcategory. For pure translational rank-one memory, the full gauge invariant is generally the projective class of the de Rham first-cohomology element, reducing to a zero/nonzero distinction only when the first Betti number is one. This global memory is Type-I-like; the name thermal Type III is reserved for a still-open coarse-graining promotion equipped with a decoder. Any irreversible entropy-production ansatz is evaluated only on an admissible process cone and remains an additional, underived principle. No quantum extension or Yang--Mills gap consequence is claimed.

# 付録 C. v1.8.0 Freeze Record・監査境界

**Freeze metadata:** public-r4、2026-07-13。文書 hash は自己参照を避け、同名の detached checksum ファイル `IDS_Canonical_Theory_v1_8_0_JA.sha256` に記録する。

## C.1 v1.7.0–v1.7.1 の追加差分として凍結済みのもの

定理1–24を含む v1.6.3 以前の核は本文どおり継承するが、ここでは v1.7 系の追加差分だけを列挙する。

1. 計量複体対の Type III 直交同定・階数公式・半群検出器（定理25）。
2. 有限圧縮型 promotion、recoverable source / target、Moore–Penrose decoder（定理26）。
3. 制御関連商 \(Q_{\rm ctrl}\) の普遍性（定理27）。
4. projected mixing の閾値 \(\Delta_{\rm ctrl}>d/2\)（定理28）。
5. quotient observability に基づく安全予算（定理29）。
6. 多段誤差再帰（定理30）。
7. IDS holography の三条件。
8. OP-MG0 における「条件付き theorem schema」と「実模型停止線」の分離。
9. 物理ゲージ軌道上の制御商（定理31）。
10. 制御関連射影のゲージ共変性（定理32）。
11. control promotion／erasure defect の二分解（定理33）。
12. 誘導 task–gauge connection と曲率公式（定理34）。
13. 安全予算の物理ゲージ不変性（系34.1）。

## C.2 v1.8.0 で新たに凍結したもの

1. 代表元上の線形写像が残差商へ降下する必要十分条件 \(\widetilde\iota d_0=0\)（定理35）。
2. bounded split decoder／left inverse \(\varpi\) の存在仮定下での split residual bridge \(\varpi\iota=I\) と topological 分解 \(V=\operatorname{Ran}\iota\mathbin{\widehat\oplus}\ker\varpi\)（定理35）。decoder 存在は Banach 一般で自動としない。
3. 複素 Banach 層（実模型は複素化）での、decoder-invisible visible 補空間を含む bridge-hidden sector と残差商上の完全 Schur–Feshbach 同値（定理36）。
4. \(z\notin\operatorname{Spec}(\mathsf n)\) のもとでの \(z\notin\operatorname{Spec}(\mathscr R^{\rm ret})\iff m_{\rm br}(z)\) 可逆、およびその共通 resolvent chart における圧縮公式 \(\varpi(zI-\mathscr R^{\rm ret})^{-1}\iota=m_{\rm br}(z)^{-1}\)（定理36）。
5. 能動的再入の modewise 定義、\(P_{\rm res}\ne\Pi_{\rm self}\) が非自明再入から従うこと（系36.1）。
6. \(C^1\) 単純零点枝と無次元 affine hidden-path multiplier 規約下の感度公式（系36.2）。
7. bounded exact chain／return intertwiners と共通 Feshbach chart 下の self-energy・Schur pencil 自然性（定理37）。
8. \(z\notin\operatorname{Spec}(\mathsf n)\) での \(\chi_{\rm SR}(z,s)\) の resolvent-norm 定義。hidden pole は chart 外であり \(0\) としない。
9. \(C^1\) Banach return map と bounded linearization に対し、return operator 単独では内生生成と外部 oracle 再生を識別できない no-go（定理38）。
10. OP-RE2 の有限可換線形／closed-range 層の代数的閉包。
11. 有限 \(2\times2\) 模型による代数的 bridge 条件の非空性。

## C.3 凍結しないもの

1. H-Δ と 4D Yang–Mills mass gap の同値。
2. fixed-window G2''、E1*、STEP-PINCER の閉包。
3. UV-ITER、OS-REST、連続 full vacuum-complement gap。
4. 非平坦 continuum BRST/BV・Gribov 大域理論。
5. \(Q_{\rm ctrl}\) の有限次元・計算可能な実現が常に存在するという主張。
6. \(\Delta_{\rm ctrl}\le d/2\) なら全ての task-relative 逆問題が不可能という主張。
7. rank-change／特異 orbit-type における単一の滑らかな \(P_{\rm ctrl}\)。
8. 非不変 task、時間依存 task、大域非線形 task–coarse 降下。
9. task–gauge 曲率が特定の物理相互作用や時間の矢を自動的に意味するという主張。
10. 任意の物理・生命・意識・情報系が能動的再入を持つという普遍存在主張。
11. 外部 template なしの joint turnover regeneration が spectrum だけで判定できるという主張。
12. normalized self boundedness、self-relative 横断 power gap、path sensitivity の全尺度一様な正下界の一般存在。
13. スペクトルストレス適応則が既存 IDS 方程式から導出済みであるという主張。
14. 非平坦非線形ゲージ軌道、特異 task、unbounded／non-Fredholm return、random cocycle への一般拡張。
15. fixed point 条件だけから線形化の固有値 \(1\) が従うという主張。

## C.4 情報源の優先規則

- 本正典の有限線形定理は本文の証明を優先する。
- 非可換有限層の詳細証明が必要な場合は外部監査資料 `IDS_NonAbelian_CoarseGraining_Canonical_v2_0_JA.md` を現行正本とし、v1.10 はその基底版として保持する。§20 の再現スクリプト名も同じ外部 bundle の provenance 記録である。
- MG0 条件付きパッケージと SU(2) 実模型再構成が緊張する場合、**条件付き implication と実模型の未閉ゲートを分離して両方を保持する**。
- 自己再生について、Schur–Feshbach 同値は定理35–37、内生性判定は A14・joint turnover intervention、駆動則は原理 SR-B を優先し、三層を混同しない。
- mass gap 未証明という停止線を変更しない。
