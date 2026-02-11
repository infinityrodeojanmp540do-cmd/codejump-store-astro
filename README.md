# astro-base-template

Astro + FLOCSS をベースにしたフロントエンド用テンプレートです。

---

## 📁 Directory Structure

```text
src/
├ components/
│ ├ layout/
│ │ ├ Header.astro
│ │ └ Footer.astro
│
├ layouts/
│ └ Layout.astro
│
├ pages/
│ └ index.astro
│
├ scripts/
│ └ header-menu.js
│
└ styles/
  ├ foundation/
  │ ├ _index.scss
  │ ├ _reset.scss
  │ └ _element.scss
  │
  ├ layout/
  │ ├ _header.scss
  │ ├ _footer.scss
  │ └ _index.scss
  │
  ├ object/
  │ ├ component/
  │ ├ project/
  │ └ utility/
  │
  └ style.scss

  🧱 CSS Architecture (FLOCSS)
	•	foundation/
リセット・要素レベルのベーススタイル
	•	layout/
ヘッダー・フッターなどページ構造
	•	object/
	•	component: 再利用可能な小パーツ
	•	project: ページ固有のUI
	•	utility: 余白・表示制御など補助クラス

  🧠 Rules
	•	JS用クラス → .js-*
	•	見た目用クラス → .l-, .c-
	•	状態 → .is-*