# LIFE × TORCH — Dinner in Camp Night 2026

日光のキャンプ場 **TORCH Camping & Coworking Space** と、代々木八幡のイタリアンレストラン **LIFE**（オーナーシェフ 相場正一郎）による、一夜限りのコラボイベント特設サイト。

- 開催：**2026年7月4日(土) Dinner — 7月5日(日) Morning**
- 会場：栃木県日光市久次良町242 TORCH Camping & Coworking Space

## 構成

```
index.html        ← 1ページ完結の特設サイト本体
styles/           ← セクション別 CSS（main.css = 共通トークン）
assets/           ← ロゴ・写真
```

セクション順：Hero → 01 Story → 02 Talk Show → 03 Menu → 04 Plans → 05 Schedule → 06 Rental → 07 Shop → 08 Information。

欧文 Bricolage Grotesque / 和文 Noto Sans JP（Google Fonts を `styles/main.css` で読み込み）。

## ローカルで開く

外部リンク（フォント）以外はすべて相対パスのため、静的サーバーで配信すればそのまま表示できます。

```bash
cd life-x-torch
python3 -m http.server 8000   # → http://localhost:8000
```

## 未確定事項（要差し替え）

- **予約ボタン**：プラン A / プラン B / 食事のみ の 3つの予約 CTA は現在 `href="#"`（プレースホルダー）。確定した予約フォームの URL に差し替えてください。ユーザー向け表記は「オンラインで予約する / Reserve」のままとし、予約システム名は表に出さない方針です。
