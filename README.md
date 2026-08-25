# homepage

R.Matsushita homepage. GitHub PagesのJekyllビルドを利用した静的サイトです。

## 更新する場所

- News: `_data/news.yml`
- プロフィール: `_data/profile.yml`
- CV: `_data/cv.yml`
- 論文・発表: `_data/publications.yml`
- Travelの写真一覧: `_data/travel.yml`
- ナビゲーション: `_data/navigation.yml`
- 共通ヘッダー・フッター: `_includes/`
- 全ページ共通のHTML: `_layouts/default.html`
- 見た目とレスポンシブ設定: `styles/style.css`

各ページの`index.html`には、そのページ固有の本文だけを置きます。GitHub Pagesへの公開時に、共通レイアウトとデータが自動的に組み合わされます。

## ローカルプレビュー

Jekyllをインストールした環境で、リポジトリのルートから次を実行します。

```shell
jekyll serve
```

表示されたローカルURLをブラウザで開いて確認します。生成物は`_site/`に出力され、Gitでは管理しません。
