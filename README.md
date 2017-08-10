# Azure で Wordpress 構築ハンズオンラボ

## 概要
このコンテンツは Microsoft Azure の Platform as a Service (PaaS) を使用してオープンソースの Wordpress を構築するための手順について記載したものです。
お手元の環境に合わせて適時タスクやステップをカスタマイズして実施してください。

## 前提条件
この演習を完了するためには、以下のソフトウェア（もしくは互換機能のあるツール）が必要です。

### Azure Database for PostgreSQL を使用する場合
* [最新の pgAdmin](https://www.pgadmin.org/download/)

### Azure Database for MySQL を使用する場合
* [最新の MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

### 共通で必要なもの
* [WordPress](https://wordpress.org/download/)
* Microsoft Azure にインスタンス作成可能なサブスクリプション及びユーザーアカウント。
* Web ブラウザ
* [Cyberduck](https://cyberduck.io/)

### 本手順の動作確認モジュールバージョン
* Windows 10 build 15063
* Google Chrome Version 60.0.3112.90 (Official Build) (64-bit)
* [pgAdmin 4 v1.6](https://www.postgresql.org/ftp/pgadmin/pgadmin4/v1.6/windows/)
* [MySQL Workbench 6.3.9 build 10690321](https://dev.mysql.com/downloads/workbench/)
* [WordPress 4.8.1](https://wordpress.org/download/)
* [Cyberduck Version 6.1.0 25371](https://cyberduck.io/)

__Microsoft Azure が利用可能で、インスタンス作成できることが前提となります。__

__本情報の内容（添付文書、リンク先などを含む）は、作成日時点でのものであり、予告なく変更される場合があります。__
