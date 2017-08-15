# Excersise.3 Wordpress を設定する

## 概要
この演習では、Wordpress の基本的な設定を行います。サイトに応じた詳細な設定は別途行ってください。
[次の演習　Excercise.2 DB を作成する](./Excercise2-CreateDB.md)

## 前提条件
この演習を完了するためには、以下のソフトウェア（もしくは互換機能のあるツール）が必要です。

### Azure Database for MySQL を使用する場合
* [最新の MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

### 共通で必要なもの
* [WordPress](https://wordpress.org/download/)
* Microsoft Azure にインスタンス作成可能なサブスクリプション及びユーザーアカウント。
* Web ブラウザ
* [Cyberduck](https://cyberduck.io/)
* [Azure Cloud Shell](https://docs.microsoft.com/ja-jp/azure/cloud-shell/overview)

### 本手順の動作確認モジュールバージョン
* Windows 10 build 15063
* Google Chrome Version 60.0.3112.90 (Official Build) (64-bit)
* [pgAdmin 4 v1.6](https://www.postgresql.org/ftp/pgadmin/pgadmin4/v1.6/windows/)
* [MySQL Workbench 6.3.9 build 10690321](https://dev.mysql.com/downloads/workbench/)
* [WordPress 4.8.1](https://wordpress.org/download/)
* [Cyberduck Version 6.1.0 25371](https://cyberduck.io/)


## Task.1 Wordpress のファイルをアップロード作成する
- ブラウザで [Azure Portal](http://portal.azure.com/)にアクセスします。

- ポータルの上部の __リソースの検索__ メニューで Excercise1 で作成した Azure App Service を入力します。

![Ex2-5](./Picture/Ex2-5.png)





おつかれさまでした。以上で _Exercise.3_ は完了となります。


## 参考資料 

[Azure Database for MySQL](https://azure.microsoft.com/ja-jp/services/mysql/)

[最初の MySQL アカウントのセキュリティー設定](https://dev.mysql.com/doc/refman/5.6/ja/default-privileges.html)

[Azure Portal を使用した Azure Database for MySQL サーバーの作成](https://docs.microsoft.com/ja-jp/azure/mysql/quickstart-create-mysql-server-database-using-azure-portal)


__本情報の内容（添付文書、リンク先などを含む）は、作成日時点でのものであり、予告なく変更される場合があります。__