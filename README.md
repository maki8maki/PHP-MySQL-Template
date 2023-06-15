# tmp

## todo

* デフォルトphpファイルの変更について調べる
* phpMyAdminの導入
* アカウント作成のphpに取り組む

## 使い方

* コンテナの起動（vscodeのdevcontainerやターミナル）を行い，[http://localhost:80](http://localhost:80)にアクセスする

## 起動の注意点

* 実行環境で初めてdocker-composeを行う場合は，./bin/set-env-ugid.shを実行し，.devcontainer/.envに情報を記入する
* データベースを削除したいとき（docker-compose.ymlを変更したときなどを含む）は，./bin/reset-container.shを実行する
  * ターミナルから行うとき
