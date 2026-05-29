# キュン旅ポータル｜コンテンツ＆参加方法 セクション サンプル

京急「キュン旅」ポータルサイト IP個別CPページの「コンテンツ＆参加方法」セクションのUIサンプルです。

## 概要

音声コンテンツの3つの参加パターンをアコーディオン形式で表示するコンポーネントです。

| パターン | 内容 |
|---|---|
| ① 無償版 | 対象スポットへ行くだけで無料参加 |
| ② 有償版 | 記念きっぷ購入で限定コンテンツ解放 |
| ③ ウィング号版 | 乗車キャンペーン連動コンテンツ |

各パネルを開くと「コンテンツ内容」「対象スポット」「ご利用の流れ」が表示されます。

## デモ

`index.html` をブラウザで開くか、GitHub Pages で公開してご確認ください。

## 使い方

```bash
git clone https://github.com/YOUR_USERNAME/kyunkyo-accordion-sample.git
cd kyunkyo-accordion-sample
# index.html をブラウザで開く
```

## 構成

```
/
├── index.html   # コンポーネント本体（CSS・JS含む）
└── README.md
```

## 備考

- テキストはすべてダミーです
- 実装時はマップ枠にGoogle Maps等を埋め込む想定
- IP②（セーラームーン）ページでは「② 有償版」パネルを非表示にして流用可能
- アイコンは [Tabler Icons](https://tabler.io/icons) を使用

## 技術スタック

- HTML / CSS / Vanilla JS
- [Tabler Icons](https://tabler.io/icons)（CDN）
