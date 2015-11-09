SASO - README

インストール方法

ステップ１：SASOが使用するデータベースを作成
　ご自身のサーバのデータベースシステムに空のデータベースを作成して下さい。

ステップ２：SASOフォルダの中にある「config.php」を編集
　DOCUMENT_ROOTにSASOフォルダの置き場所を入力て下さい。最後が「/」（スラッシュ）で終わるようにして下さい。
　PROGRAM_DIRにSASOフォルダの名称を入力して下さい。「/」（スラッシュ）は不要です。
　DSNを適切に入力して下さい。当アプリケーションはデータベース接続にPDOを使用しています。デフォルトではMYSQLの設定が入っています。
　USERにはデータベースのユーザ名を、PASSWORDにはデータベースのパスワードを入れて下さい。

ステップ３：installer/installer.phpにアクセス
　SASOフォルダ以下の「installer/installer.php」にアクセスします。
　お名前とログインID、パスワードを入力しインストールします。
　ログインIDとパスワードはどこかに書き留めておいて下さい。忘れると、復元できません。

インストール方法は以上です。

ソフトウエア名：SASO
バージョン：2.3.1
リリース日：2015年11月10日
動作環境：apache, おそらくPHP5.3以上, おそらくMYSQL5以上あるいはもしかしたらPostgreSQL
<<<<<<< HEAD
製作者：日本標準機構（saso(a)hyoujun.jp）(a)を@に置き換えてください。
=======
製作者：日本標準機構（saso(a)hyoujun.jp）(a)を@に置き換えて下さい。
>>>>>>> f27fa745b6d22a1caba2d6250c7fd5b4b07554ca
著作権情報とライセンス情報：extentionフォルダ内及びbootstrapフォルダ内には日本標準機構ではない方が作成したスクリプトが含まれますので、それぞれのライセンスに従って下さい。それ以外のスクリプトは全て日本標準機構が作成しました。日本標準機構が作成したスクリプトはGNU GPLv3とします。
免責事項：このソフトウエアを使用したことによって生じたいかなる障害、損害、不具合等に関して、日本標準機構は一切責任を負いません。各自の責任においてご使用ください。

変更ログ
バージョン：2.3.1
リリース日：2015年11月10日
バグフィックス

バージョン：2.3
リリース日：2013年12月19日
最初のリリース
