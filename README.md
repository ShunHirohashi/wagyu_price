# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
リポジトリはファイルやディレクトリの状況を記録する場所
リモートポジトリは複数人で共有が出来るリポジトリでローカルリポジトリは開発者が一人が使用する為に自分のPCに配置する為のリポジトリ


## プッシュとマージの違いは何でしょうか？
プッシュはローカルリポジトリで作成した変更履歴をリモートリポジトリにアップする事でまだリモートリポジトリに反映はされていないが、マージは別のブランチの作業内容をブランチに取り込みこと


## コミットとプッシュの違い
コミットは変更履歴を残す事で仮にミスしてもコミットしていればそこからやり直せる。
プッシュはローカルリポジトリで作成した変更履歴をリモートリポジトリにアップする事


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
どんな編集を行ったか分かり易い内容を書くこと


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
ローカルの場合、マージは自分自身で行えるため時間がリモートに反映まで時間が掛からないが、確認者がいない為ミスが起こりやすい
プルリクエストの場合は一旦マージ権限が有る人に確認が入るため、ミスが起こり辛いが他者に確認してもらう為、反映するまでに時間が掛かる

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
方法は３つあり
先にマージされた内容を取り込む
後にマージしようとした内容を取り込む
どちらの内容も取り込むです

プレフィックスはgitのコミットメッセージの先頭につける文字列のこと
コミットログがどんな変更したかざっくり理解できる
例は新しい機能の追加、テストの追加や修正、スタイルの変更など