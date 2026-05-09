# ps120-final-project

地球科学クラス課題のサイト（公開用）はリポジトリ直下の **`index.html` / `css` / `js` / `assets`** です。週次メモは **`notes/`** にあります。

GitHub で **Actions** を使って Pages を出している場合、このリポジトリのワークフローはサイト用ファイルだけを **`_site`** に集めてアップロードします（`notes/` などはサイトには載りません）。

**Settings → Pages** で **Deploy from a branch** のときは、Folder を **`/` (root)** にすると `README.md` ではなく **`index.html`** がトップになります。**GitHub Actions** を選んだ場合も、トップ URL はサイトのホームになります。
