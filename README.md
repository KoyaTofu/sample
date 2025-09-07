# sample

# ＜流れ＞
1. GitHub(web)でリポジトリを作成
2. 作業フォルダに移動
	「cd ○○」
3. ローカルリポジトリ作成
	「git init」
4. ステージング環境にファイル、フォルダ登録
	「git add ○○」(*で全て)
5. 初回コミット
	「git commit -m "master:initialize commit"」
----------
6. 作業用ブランチ(feature)作成
	「git branch feature」
7. 作業用ブランチに移動
	「git checkout feature」
8. ステージング環境に編集情報を反映
	「git add ○○」
9. 作業用ブランチ側コミット
	「git commit -m "feature:[add] ○○"」
-----
10. リモートリポジトリを登録
	「git remote add origin URL.git」
11. リモートリポジトリに反映
	「git push origin main」

＜コマンド＞
- 「git init」	ローカルリポジトリ作成
- 「git status」
- 「git add ○○」ステージング環境へ反映
- 「git commit -m "メッセージ"」	ローカルリポジトリにコミット
- 「git reset ○○」	取消、直近コミット状態に戻す
- 「git checkout ブランチ」	ブランチ切り替え
- 「git branch ブランチ」	ブランチ作成
- 「git clone URL」		リモートリポジトリをローカルリポジトリにコピー
- 「git push origin ブランチ」リモートリポジトリに反映
- 「git pull origin ブランチ」ローカルリポジトリに反映



