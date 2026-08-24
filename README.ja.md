<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 005 プロジェクトバナー" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 005

### 写真を、暗い構造と小さな鮮色が物語る童話版画へ

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#4つの出力を支えるひとつの版画ロジック)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#境界と信頼性)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 鈍い大形 · 暗い構造場 · 部分的な露出 · 三層の色秩序 · シルクスクリーン × パステル

XXD Panel 005 は、Codex と互換 Agent のための画像生成 Skill です。写真にある本当の身元、動き、機能、感情を保ち、主体を一つか二つの鈍い大形へ圧縮します。さらに元写真の空間と意味から暗い構造場を育て、隠す、切る、包み込む、部分的に見せるという操作で童話版画の物語を組み立てます。

色は暗い構造、淡い余白、ごく小さな高彩度の合図という三層を守ります。平面的なシルクスクリーンと粉っぽいパステルが、かすれ、粒子、紙目、飛沫、白抜け、わずかな見当ずれを残します。文字は小さな標識、物体パネル、または端の注記としてのみ構造に組み込みます。

## なぜ 005 が必要なのか

一般的な「童話風」は、暗い背景に明るい色を均等に散らし、城、星、笑顔を足すだけの汎用的な可愛い漫画へ崩れがちです。

005 は順序を逆にします。

```text
元写真の事実を固定 → 一つか二つの鈍い大形へ圧縮 → 元写真から暗い構造場を育てる → 遮蔽と部分露出で語る → 暗／淡／鮮の三層を固定 → シルクスクリーンと粉状パステルで仕上げる
```

無関係な写真に替えても大形、暗場の役割、遮蔽、鮮色の合図、文字がほぼ成立するなら、それは 005 ではありません。

## 005 のビジュアル契約

- **一つか二つの鈍い大形：** 少なくとも三つの写真固有の手掛かりで身元、動き、機能、感情を保ちます。
- **写真から育つ暗場：** 大きな低明度の場が、容器、道、枠、または密度の殻として明確に働きます。
- **構造による物語：** 遮蔽、切り取り、包み込み、部分露出が情報の順序を作ります。
- **平面的な絵本視点：** 俯瞰圧縮、横移動、正面枠、道の誘導、尺度跳躍、端の切り取りから一つを選びます。
- **三層の色秩序：** 暗い構造が重さ、淡い場が呼吸、小さな高彩度色が読解の合図を担います。
- **疎な機能線：** 線は機能、道、境界、質感、識別にだけ使います。
- **シルクスクリーン × パステル：** 平面色にかすれ、粒子、紙目、飛沫、白抜け、わずかな見当ずれを残します。
- **構造内の文字：** 丸く鈍い低密度の小標識、物体パネル、端の注記として扱います。

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2089987808664719723) · 2026-08-19<br>
> GPT2 x 格林童话 x 转绘 x 童趣 x 美学提示词 x VOL.005

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089987808664719723"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 005 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089987808664719723"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 005 作例 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089987808664719723"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 005 作例 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089987808664719723"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 005 作例 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2089987808664719723">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 005 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元画像ごとに7点の独立PNGを出力します。モード選択後、生成前に完成画像全体の画角を必ず確認します：元プロンプトの `3:4`、明示的な元画像比率、一般的な比率、またはカスタム比率／正確なピクセルです。元画像寸法を暗黙には適用しません。

| モード | 画角ルール | 成果物 |
| --- | --- | --- |
| `top-bottom` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：上に高忠実度の元画像、下に 005 デザイン、約50/50 |
| `left-right` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：左に高忠実度の元画像、右に 005 デザイン、約50/50 |
| `design-only` | ユーザー確認済みの完成画角 | 005 デザインが全画面を満たし、元画像は表示しない |
| `wallpaper-pack` | 端末ごとに確認 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

二連モードは元画像を高忠実度の編集／参照入力として使い、完全なスタイルプロンプト一式で完成画面を直接生成します。写真、デザイン、色、光、文字、意味を一体化するためです。決定論的な合成は、完成画面の再試行後も失敗した場合、原画像のピクセル完全保持を明示された場合、生成経路が指定画角に対応しない場合、または無劣化の最終ピクセル調整が必要な場合だけ使います。

壁紙は連動または独立を選べます。連動はiPad基準作を一つ承認し、他の端末を元画像＋同じ基準作から個別に再構成します。独立は各端末が元画像だけを参照します。どちらも他端末の成果を切り抜かず、派生を連鎖しません。

## 文字は版画構造の一部になる

生成前に、自動文案、カスタム文案、文字なしを選びます。文字を入れる場合は対象言語または地域も指定します。

自動文案は、主体の身元、見える動き、機能、関係、既知の場所、または暗場が担う構造的な物語から短い語句を抽出します。現在の画像と強く結びつけますが、童話を創作したり語呂合わせや反転を強制したりしません。

既定はタイトル1本です。実際に情報価値がある場合だけ0〜2本の短い注記を追加し、洗練されて見せるためだけに番号、年、座標、アーカイブラベルを創作しません。

ユーザーが完成稿を渡した場合は一字一句保ちます。方向や編集可能な草稿の場合だけ、対象、目的、必須語、語調、含意を守りながら磨きます。

言語は命令文ではなく、想定する読者に従います。

```text
対象市場・読者 > 指定された成果物言語 > 方向指示の言語；不明なら生成前に確認
```

日本版は自然な現代日本語、韓国向けは自然な韓国語と正しい分かち書き、英国版は英国英語、アラビア語版は原則として自然な現代標準アラビア語と正しい右から左の組版を使います。外見、服装、風景、看板から国籍を推測せず、雰囲気づくりの偽外国語も使いません。

## 完成キャンバス優先とラスター境界

画像モデルが完成画面全体の美的再構成を担当し、二連レイアウトも完成キャンバス一枚の直接生成を既定とします。`scripts/compose_panel.py` は条件付きの復旧、無劣化ピクセル調整、読み取り専用監査にだけ残し、毎回の事前計画や美的評価には使いません。

納品物はすべてPNGラスターで、呼び出しごとに `~/Desktop/xxd/` に新規タスクを作ります。設定済み画像経路は匿名化された状態だけを返し、提供元、接続先、認証情報、ヘッダー、プロンプト、応答、アカウント情報を公開しません。SVG、HTML、Canvas、図解、プログラム描画は最終作品の代替になりません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-005.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-005" ~/.codex/skills/xxd-panel-005
```

Claude Code では同じフォルダを `~/.claude/skills/xxd-panel-005` にリンクできます。インストール後に Agent セッションを再起動してください。

```text
$xxd-panel-005
この写真を左右二連にしてください。文案は写真の意味から作り、自然な韓国語を使ってください。
```

写真だけでも呼び出せます。番号付きの複数行メニューでモードと文字設定を確認し、壁紙では連動／独立と端末サイズも確認します。

詳細仕様：

- [Skill ワークフロー](SKILL.md)
- [中国語の完全プロンプト](references/xxd-panel-005-prompt.zh-CN.md)
- [英語の完全プロンプト](references/xxd-panel-005-prompt.en.md)
- [元のスタイル指示](references/005-source.md)

## 境界と信頼性

- 各写真は独立したタスク内だけで使い、他の入力、旧成果物、作例の主題、色、文案、構図を借りません。
- 呼び出すたびに新しいタスクフォルダを作り、同じ原画像と条件でも新たに生成します。
- 成果物は PNG ビットマップであり、SVG、HTML、Canvas、プログラム描画の代替物ではありません。
- 設定済みビットマップブリッジは匿名化した状態だけを返し、プロバイダー、エンドポイント、ヘッダー、認証情報、プロンプト、応答本文を表示しません。
- 選択した通常モードごとに1点を返し、`wallpaper-pack` を選ぶと独立壁紙4点を追加します。`全部` は元写真1枚につき7点を4つの同階層モードフォルダへ出力し、一覧コラージュにはまとめません。

ローカル合成には Python 3 と Pillow が必要です。安全なビットマップブリッジは Python 3.11+ の `tomllib` を使用します。画像生成には、ホスト Agent の内蔵ラスター生成機能または設定済みの互換ルートが必要です。

## リポジトリ

```text
xxd-panel-005/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/banner.svg + examples/（今後のローカル作例用）
├── scripts/compose_panel.py + configured_imagegen.py
└── references/xxd-panel-005-prompt.zh-CN.md + xxd-panel-005-prompt.en.md + 005-source.md
```

## XXD について

XXD は小小東（Xiaoxiaodong）のブランド名の略称です。このプロジェクトは [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) が制作・管理しています。

## サポートと会員制度

### 個別深度相談 · 1時間 CNY 299

Skills 利用に関する一対一相談は1時間 CNY 299です。下の WeChat QR コードから予約してください。

### Xiaoxiaodong Skills ユーザー交流グループ · CNY 99

一度 CNY 99 を支払うと、ワークフロー共有、作品相談、ユーザー同士の支援を行う交流グループに参加できます。時間制の個別相談は含まれません。

### 知識星球＋会員プロンプトライブラリ · 年額 CNY 699

[知識星球](https://wx.zsxq.com/group/15554814142882)と[XXD 会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)は同じ会員権です。**一度の年額決済で両方を利用でき、二重の購入は不要です。**

1. 知識星球で加入後、WeChat でプロンプトライブラリの交換コードを受け取る。
2. プロンプトライブラリで加入後、WeChat で知識星球への招待を受け取る。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD 有料サービス WeChat QR コード" width="320"></a>
</p>

<div align="center">

**暗い場が雑音を隠し、本当に大切な一点だけが物語を照らす。**

</div>

---

<div align="center">
  <h2>☕ オープンソースプロジェクトを支援</h2>
  <p>このプロジェクトが時間の節約になったなら、Star、共有、コーヒー一杯で継続を支援できます。</p>
  <table><tr><td align="center" width="240">
    <a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee で Xiaoxiaodong を支援" width="180"></a><br>
    <strong>Buy me a coffee</strong><br><sub>QR コードを読み取るか開いて支援できます</sub>
  </td></tr></table>
  <p><sub>支援は任意であり、このオープンソースプロジェクトの利用権には影響しません。</sub></p>
</div>
