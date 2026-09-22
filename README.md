# TM Tools for Maya

Maya用TM Toolsの公式配布ページです。Google Drive、Dropbox、フォルダ選択設定は使いません。

## 最初の1回（新規・旧版）

1. [Update_TM_Tools.py](https://github.com/KarakuriKissa/TM-Tools-Releases/releases/latest/download/Update_TM_Tools.py) をダウンロードする。Mayaの新規導入と旧版の復旧で同じファイルを使う。
2. `Update_TM_Tools.py` をMayaの3D画面へドラッグ＆ドロップする。
3. 完了表示後にMayaを再起動する。

## 通常の更新

1. Mayaのメニューバーで `TM Tools → TM Toolsを更新...` を押す。
2. 「今すぐ更新」を押す。
3. 完了表示後にMayaを再起動する。

更新時はGitHub Releasesから最新版を取得し、バージョン、SHA256、ZIP内容を検証します。現在のツールは `tm_tools_backup` に退避され、置き換えに失敗した場合は元へ戻ります。
