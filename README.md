# gitコマンド一覧
ファイル取り消し：git checkout -- fileName

ステージング取り消し：git reset HEAD -- fileName or directoryName
    ※ワークツリーのファイルには影響しない！

コミットの取り消し：git commit --amend
    ※但し、pushする前のコミットに限る

remoteへの接続：git remote add [追加するリモートリポジトリ名] [追加したいリポジトリ]
remoteリポジトリ確認：git remote / git remote -v
