# Webページ作成手順

卒業制作用のページをチームごとにフォークして、スクリーンショットや文言、必要なZipファイルを追加したものをプルリクエストして講師が組み込む。

## 準備
チームで作業担当者を一人決めて、以下を準備。

1. GitHubにサインイン
2. https://github.com/datgm21/works を開く
3. 右上の Fork をクリックしてフォークを実行
4. フォークしたリポジトリをGitHub Desktopでドキュメントフォルダーの自分の名前のフォルダー下の任意の場所にクローンする

以上。

## チームページの作成
クローンしたフォルダーをAtomかVisual Studioで開く。１年次のものも含めた作品フォルダーがあるので、卒業制作の作品名のフォルダーを開いて、以下を作成する。

### index.html
ドキュメント内の以下を書き換えたり、追記する。

- `*ゲーム概要*`の部分を消して、1～2行で作品のコアステートメントを書く
- 操作方法、ルール、使用アセットを書く。書き方は1年次の作品を参考にする
- コピーライトの行にある`*チーム名*`の部分を返して、チーム名に書き換える

その他、気づいた部分があれば書き換え、書き加える。

### ゲーム画面のスクリーンショット
ゲーム内容が分かるスクリーンショット(Win+Shift+Sキー)を作成して`game-image.png`を上書きする。jpgにした場合は、index.html内の該当箇所の拡張子もjpgに変更する。

スクリーンショットに手を加えてもよい。

### インストカードの画像
インストカードをjpg画像にして`inst.jpg`を上書きする。

### 実行データ
index.html内のダウンロードのパートにダウンロードするzipファイル名が書かれている。Unityでビルドしたフォルダー名をZipファイル名と同じにして、中にREADME.txtを追加したらzip圧縮する。
作成したzipフィルを作品名フォルダーにコピーする。
