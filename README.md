# Gitの使い方

## git add  <ファイルパス>
対象のファイルをステージングエリアに追加する

## git commit
ステージングエリアに上がっている対象をコミットする  
「-m」オプションをつけると、コミットメッセージを指定してコミットも可能

## git pull
最新のリポジトリを取得し、ローカルリポジトリを更新する。
git fetch + git mergeの動作をしている。

## git clone <リモートリポジトリURL>  
リモートリポジトリより、ローカルリポジトリを作成する

## git checkout -b <ブランチ名>
ブランチを新規作成し、新たに作成されたブランチに移動する

## git push <リモートリポジトリ名> <ブランチ名>
リモートリポジトリに指定したブランチを送信する  
「-f」オプションをつけると、他の人の更新を上書きすることも可能

## git stash
作業中の内容を退避させる
あまりお勧めできないらしい(追記)

## git fetch --all
すべてのリモートブランチをfetchする

## git commit -amend
コミットをやり直すことができる。
コミットメッセージを修正するのに利用できる。

## git commit
ステージングエリアに追加された対象ファイルがコミットされる

## git gc
ガーベージコレクションを実行する

## git bundle
リポジトリの内容をバイナリファイルにまとめる  
相手に送付する際に使用したりする

## git init
gitでバージョン管理を開始する

<<<<<<< HEAD
## git log
そのリポジトリでのコミットを新しい順に表示する
=======
## git cherry pick
他ブランチの特定のコミットを取り込む

>>>>>>> d6d0cd889073c38700925d59d0b5363d9ffb2bee
