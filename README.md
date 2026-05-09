# PS120 Final Project — Japan Earth Science

静的サイト（公開用）は **[`docs/`](docs/)** にあります。授業の週次メモは **[`notes/`](notes/)** にあり、GitHub Pages のアップロード対象には含まれません。

## GitHub Pages で公開する手順（推奨: GitHub Actions）

1. リポジトリの **Settings → Pages** を開く。
2. **Build and deployment** の **Source** で **GitHub Actions** を選ぶ（**Deploy from a branch** で **main / root** になっていると README が表示されることがあります）。
3. `main` にプッシュすると [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml) が走り、`docs/` の内容のみが公開される。

ユーザー／組織のプロジェクトサイトの URL は通常 `https://<ユーザー名>.github.io/<リポジトリ名>/` で、`docs/index.html` がトップページになります。

### ブランチで `/docs` だけを載せたい場合

**Source を「Deploy from a branch」** にするときは Branch **main**、Folder **`/docs`** を選んでください。その場合は Actions は不要でも構いません（ただし重複しないよう Actions はオフまたはワークフロー削除）。
