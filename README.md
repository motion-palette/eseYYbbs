#私設2ch互換避難所の使い方#
##元になったスクリプト##
* 絆板
   - http://age.s22.xrea.com/kizuna/readme.html


##オリジナルからの変更点##
* 以下の機能追加
  - sage進行対応
  - ID表示機能
  - 板ごとの管理パスワード対応
  - 板名の変更機能
  - 板の停止、再開機能
  - 掲示板説明の追加
  - したらば、わいわいkakikoからのログインポート
  - BAN、BAN解除機能
  - NGワード機能の追加
  - スレ建て権限の追加（anyone or 管理者）

##コマンド入力フォーム##
スレ建てフォームおよび、レス入力欄

##コマンド##
###以下は対象のスレのレス欄からのみ###
* レスの削除  
  - 名前欄:削除
  - メール欄:パスワード
  - 本文欄:削除レス番指定(>>5、>>10-20等)


* BAN
  - 名前欄:BAN
  - メール欄:パスワード
  - 本文欄:BANレス番指定(数字、1件のみ)


* IP確認
  - 名前欄:IP確認
  - メール欄:パスワード
  - 本文欄:書き込みIPを確認したいレス番指定(数字、1件のみ)


* IP確認全件
  - 名前欄:IP確認全件
  - メール欄:パスワード
  - 本文欄:空欄

* NGワード取得  
  - 名前欄:NGワード取得
  - メール欄:パスワード
  - 本文欄:なし


* NGワード更新
  - 名前欄:NGワード更新
  - メール欄:パスワード
  - 本文欄:改行区切りNGワード（全件上書き）


* NGワード追加
  - 名前欄:NGワード追加
  - メール欄:パスワード
  - 本文欄:改行区切りNGワード（既存のNGワードに追加）  

###以上は対象のスレのレス欄からのみ###


* BAN解除
  - 名前欄:BAN解除
  - メール欄:パスワード
  - 本文欄:IP(形式はIP確認で取得できる形式)


* スレッドの削除
  - 名前欄:削除
  - メール欄:パスワード
  - 本文欄:スレのURL(http://www.example.com/test/read.cgi/bbs/1234567890/ 等、改行で区切って複数一括削除可)


* スレッドの過去ログ化(いわゆるDAT落ち)
  - 名前欄:倉庫
  - メール欄:パスワード
  - 本文欄:スレのURL(http://www.example.com/test/read.cgi/bbs/1234567890/ 等、改行で区切って複数一括削除可)


* IDの表示非表示切り替え(スレ単位ではなく板単位になります)
  - 名前欄:ID
  - メール欄:パスワード
  - 本文欄:なし

* スレ建て制限の切り替え
  - 名前欄:スレ建て制限
  - メール欄:パスワード
  - 本文欄:なし

*したらばログのインポート
  - 名前欄:したらば
  - メール欄:パスワード
  - 本文欄:インポートするスレのURL(http://jbbs.livedoor.jp/bbs/read.cgi/game/42885/1380206807/ 等、改行で区切って複数一括インポート可)


*わいわいkakikoログのインポート
  - 名前欄:YY
  - メール欄:パスワード
  - 本文欄:インポートするスレのURL(http://yy24.kakiko.com/test/read.cgi/slyman/1386395763/ 等、改行で区切って複数一括インポート可)


*Janeのdatファイルのインポート
  - 名前欄:Jane
  - メール欄:パスワード
  - 本文欄:datファイルの中身を貼り付け


* 板管理パスワードの変更
  - 名前欄:パスワード変更
  - メール欄:旧パスワード
  - 本文欄:新パスワード(#[英数字8文字以上]の形)


* 板名変更
  - 名前欄:板名変更
  - メール欄:パスワード
  - 本文欄:新板名


*名無しデフォルト名変更
  - 名前欄:名無し設定
  - メール欄:パスワード
  - 本文欄:名無し時の表示名


* 板説明更新
  - 名前欄:板説明更新
  - メール欄:パスワード
  - 本文欄:html本文  
      許可されるタグは以下
     - <div>
     - <span>
     - <b>
     - <h1>
     - <h2>
     - <h3>
     - <h4>
     - <h5>
     - <a>
     - <img>
     - <br>
     - <object>


* 板停止(書き込み禁止)
  - 名前欄:板停止
  - メール欄:パスワード
  - 本文欄:なし


* 板再開(書き込み禁止解除)
  - 名前欄:板再開
  - メール欄:パスワード
  - 本文欄:なし

