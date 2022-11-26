メモ（とにかく必要な事をメモする）

git メモ

git status ：編集中のファイルが赤色で表示される
            ステージングされたファイルは緑で表示される

git add　：gitにcommitするために、addでgitにステージングする

git commit -m "(コミットメッセージ)"　：gitに対して保存する

git log　：gitのcommit履歴を確認できる

git push ：ローカル作業内容がリモート側にアップロードされる

git clone　：新規にローカル側にコピー
            最新のリポジトリがcloneされる

git pull　：最新のリポジトリ情報がダウンロードされる

git checkout -b hoge master　：masterからhogeというbranchを作る

git branch　：branchの一覧を見れる
            緑が現在のbranch

git merge hoge　：hogeをmasterに合流させる