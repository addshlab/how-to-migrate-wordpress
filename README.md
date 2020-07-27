# WordPressのサーバー移行に必要なこと

## あると便利な知識

* MySQL/MariaDB
  * SELECT
  * WHERE 
* Linux コマンド
  * cd (移動)
  * ls (一覧)
  * mv (変更)
  * cp (複製)
  * rm (削除)
  * su (ユーザー切り替え)
  * sudo (別ユーザーで実行。殆どの場合は管理者権限で実行)
  * chown (所有件の変更)
  * chmod (パーミッションの変更)
  * tar (ファイルをまとめる/展開する)
  * mysql (MySQLの機能を使う
  * mysqldump (データベースのファイルダンプを行う)
* WP-CLI
  * wp db cli
  * wp db export PATH/NAME.sql
  * wp db import PATH/NAME.sql
  * wp search-replace 'BEFORE' 'AFTER'
  * wp search-replace 'BEFORE' 'AFTER' --dry-run

## 文字列の置換に関すること

### 置換が必要になるパターン

1. 接続が http から https になる時
1. ドメイン名が変更になるとき
    1. 本番環境の URL 変更に伴う移設
    1. 検証環境から本番環境 への移設  



