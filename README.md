# オンラインクイズアプリケーション2(仮)

## 紹介:Info
~~~
これはオンライン上でクイズ形式の問題を解答することで学習するためのアプリケーションです。
誰(非ログイン)でも問題に解答することができますが、ユーザ登録することで成績を記録することができ、他のユーザと成績を競ったり学習状況を把握することができます。
問題を作成することも可能ですが、作成するためにはまず権限を得る申請が必要になります。
~~~

~~~
※注意
登録した情報はこのアプリケーションの使用以外の目的では利用しません。
個人で作成しているため、バグが多かったりセキュリティ面が弱いかもしれません。個人情報やパスワードなどは注意してください。

2016年内には完成予定。。。かも知れません。
~~~

---
## 試してみる:Play
機能は未実装。 (2016年5月10日の時点)  
https://quizwebapp2.herokuapp.com/

---
## 概要:About
+ Web上で学習するためのWebアプリケーションです。
+ 学習者はパソコンやスマホなどのブラウザ上で動作します。
+ 問題作成は申請後に許可されたユーザのみ可能です。
+ さまざまなクイズ形式の問題を解答することで勉強していきます。
+ 成績などはデータベース(SQLite)に記録され、グラフなどで可視化されます。
+ スマホ版アプリではオフラインでの学習も予定しています。

---
## 開発について:Environment
+ 開発環境は[Cloud9][1]を利用しています。
+ ソースコードの管理は[GitHub][8]を利用しています。
+ 実行環境は[Heroku][7]を利用します。
+ 開発は[ionic][2]([node.js][3])をベースに行う予定です。
+ 学習以外の部分はHTMLベース、学習(クイズ)部分はJavascriptベースの予定です。
  + HTMLの表示関連には[angular.js][4]を利用する予定です。([ionic][2]を利用するため)
  + クイズの描画には[phina.js][5]を利用する予定です。
+ スマホアプリへの変換は[Cordova][6]を利用する予定です。

---
## やるべきこと:ToDo
詳細は[Wiki][10]を御覧ください。
+ ~~実行環境の準備~~(2016年5月10日完了)
+ 開発環境に関する学習。(随時)
  + ionicおよびAngularJSについて
  + Gitについて
+ 実装する機能
  + ユーザ管理
  + 問題作成
  + 問題検索
  + 成績の管理(可視化など)
+ その他いろいろ

---
## 更新履歴:Log
+ 2016年5月11日
  + README.mdおよびWikiのトップページの修正
+ 2016年5月10日
  + Wikiを作成し、開発メモの内容をWikiに移動
  + 実行環境(Heroku)の構築
+ 2016年5月09日
  + サンプルサイトの作成
  + README.mdの新規作成

---
## 以前作成したクイズアプリ:Old Version
[オンライン勉強会-ON会-][100]

[1]: https://c9.io/ "Cloud9"
[2]: http://ionicframework.com/ "Ionic"
[3]: http://nodejs.jp/ "Node.js 日本ユーザグループ"
[4]: https://angularjs.org/ "AngularJS"
[5]: https://github.com/phi-jp/phina.js "phi-jp/phina.js"
[6]: https://cordova.apache.org/ "Apache Cordova"
[7]: https://www.heroku.com/home "Heroku"
[8]: https://github.com "GitHub"

[10]: https://github.com/snowman8765/quizwebapp/wiki "quizwebapp wiki"

[100]: http://snowman8765.sakura.ne.jp/onkai/ "オンライン勉強会-ON会-"
