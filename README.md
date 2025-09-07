# sample

＜流れ＞
１．GitHub(web)でリポジトリを作成
２．作業フォルダに移動
	「cd ○○」
３．ローカルリポジトリ作成
	「git init」
４．ステージング環境にファイル、フォルダ登録
	「git add ○○」(*で全て)
５．初回コミット
	「git commit -m "master:initialize commit"」
----------
６．作業用ブランチ(feature)作成
	「git branch feature」
６．作業用ブランチに移動
	「git checkout feature」
７．ステージング環境に編集情報を反映
	「git add ○○」
８．作業用ブランチ側コミット
	「git commit -m "feature:[add]○○"」
-----
９．リモートリポジトリを登録
	「git remote add origin <URL>.git」
10.リモートリポジトリに反映
	「git push origin main」

＜コマンド＞
・git init：ローカルリポジトリ作成
・git status：
・git add ○○：ステージング環境へ反映
・git commit -m "メッセージ"：ローカルリポジトリにコミット
・git reset ○○：取消、直近コミット状態に戻す
・git checkout ○○：ブランチ切り替え
・git branch ○○：ブランチ作成
・git clone <URL>：リモートリポジトリをローカルリポジトリにコピー
・git push origin ブランチ：リモートリポジトリに反映
・git pull origin ブランチ：ローカルリポジトリに反映


