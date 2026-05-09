# PS120 Final Project — Japan Earth Science

静的サイト本体は **[`site/`](site/)** にあります。授業メモなどは **`docs/`**（GitHub Pages の公開ディレクトリとは別）。

## GitHub Pages で公開する手順

1. リポジトリの **Settings → Pages** を開く。
2. **Build and deployment** の **Source** で **GitHub Actions** を選ぶ。
3. `main` にプッシュすると [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml) が走り、`site/` の内容が公開される。

ユーザー／組織のプロジェクトサイトの URL は通常 `https://<ユーザー名>.github.io/<リポジトリ名>/` です。サイト内のリンクは相対パスなので、そのままで動きます。
