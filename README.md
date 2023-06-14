# tmp

## todo

* php.iniの導入
* phpMyAdminの導入
* アカウント作成のphpに取り組む

## 起動の注意点

* 実行環境で初めてdocker-composeを行う場合は，./bin/set-env-ugid.shを実行し，.devcontainer/.envに情報を記入する
* データベースを削除するとき（docker-compose.ymlを変更したときなどを含む）は，./bin/reset-container.shを実行する
