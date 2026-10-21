# いろさし

写真から、色番号付きの図案と印刷用PDFを作るブラウザアプリです。

**使う:** https://higomon.github.io/irosashi/

写真を選び、仕上がりを調整して、印刷用PDFを保存します。
写真の処理はブラウザ内で行います。

## 編集・更新

`いろさし - 図案を作る.html` が唯一の編集元です。
ダウンロードしてブラウザで開いても使えます。

`main` ブランチへのpushでGitHub ActionsがこのHTMLを一時的に
`index.html` として配置し、GitHub Pagesへ公開します。
公開用の別HTMLを管理する必要はありません。
