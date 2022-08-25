# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
リモートリポジトリ：インターネット上でソースコードを管理する場所  
ローカルリポジトリ：自分のPC上でソースコードを管理する場所


## プッシュとマージの違いは何でしょうか？
プッシュ：ローカルリポジトリの変更内容をリモートリポジトリに反映させる処理  
マージ：元のブランチからブランチを切りそれぞれのブランチで行った変更内容を元のブランチに反映させること


## コミットとプッシュの違い
コミット：ローカルリポジトリに変更内容を登録すること  
プッシュ：コミットされた変更内容をリモートリポジトリに反映させること


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
編集内容を正確に表すように書く  
※最初のみ'first commit'と記述することが多い


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
前者では変更担当者がマージするのに対して、後者ではリモート上でレビュー担当者がコードのレビューをした後にマージできるためバグや、コードの記述ミスなどを防止するメリットがある。
ただし、後者ではローカルでの元のブランチに変更内容が反映されていないため、プルする必要がある。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
場合によって異なり、3つの方法がある  
1.先にマージされた変更内容を取り込む
2.後にマージしようとしている変更内容を取り込む
3.どちらの変更内容も取り込む