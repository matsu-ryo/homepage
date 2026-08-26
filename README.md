# homepage

R.Matsushita homepage. GitHub PagesのJekyllビルドを利用した静的サイトです。

## 更新する場所

- News: `_data/news.yml`
- プロフィール: `_data/profile.yml`
- CV: `_data/cv.yml`
- 論文・発表: `_data/publications.yml`
- Travelの写真一覧: `_data/travel.yml`
- ナビゲーション: `_data/navigation.yml`
- コピーライト年などの共通設定: `_config.yml`
- 共通ヘッダー・フッター: `_includes/`
- 全ページ共通のHTML: `_layouts/default.html`
- 見た目: `styles/style.css`

各ページの`index.html`には、そのページ固有の本文だけを置きます。公開時にJekyllが共通レイアウトとデータを組み合わせます。

## 更新例

Newsを追加するときは、`_data/news.yml`の先頭へ次の形式で追加します。

```yaml
- date: "2026-08-26"
  display_date: "2026/08/26"
  text: 更新内容
```

## ローカルプレビュー

Jekyllをインストールした環境で、リポジトリのルートから次を実行します。

```shell
jekyll serve
```

表示されたローカルURLをブラウザで開いて確認します。生成物は`_site/`に出力され、Gitでは管理しません。
