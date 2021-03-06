# タイトル：Screen Chat （仮）

---

## 内容
中小企業のweb担当者向け、web制作のディレクションサポートツール

## 補足
※今回のアプリを作ろうと思った背景
初めてwebのディレクションを1年前くらいにやった際に、どういう手順で進んだらいいか全くわからなくて、プロジェクトの進行管理がうまくいかなかったことがあった。なので、1年前の自分のように「完全素人」な中小企業のweb担当者（もっと言えば1人でweb制作を外部の人とやりとりしないといけない状況になっている担当者）の助けになるアプリを作りたいと思った。

※ターゲット
ターゲットは上記にもある通り、「初めてwebのディレクションをすることになり、社内にもリソースがあまりなく、当然プログラミングやデザインの知識もない」中小企業のweb担当者（と、そのプロジェクトの受注側にいるデザイナー、エンジニア）



## 仕様言語・技術（予定）
- PHP： ログイン、ユーザー情報登録・編集ページ、メイン画面（ログインはfacebookログインもあったほうが良いかも…と思っていたりします。時間的に無理そうなら削ります。）
- Milkcocoa：チャット部分（これのみ？）
- Node.js（とSocket.IO）：メイン画面の共有、アップロードしたファイルのリアルタイム共有
※ここは発表までの3ヶ月間（できれば提出までの2ヶ月間）でしっかりできるようにしておきたいです。


## アプリで出来ること

1.直感的にdrag&dropで画像などの資料を取り込める。
2.打ち合わせ相手とリアルタイムで画面共有ができ、チャットもできる。
3.web制作のステップごとに流れを追えるコンテンツが付いている。（初心者登録している人限定）
4.各ステップごとに必要な資料の雛形もアップロードされている。（初心者登録している人限定）
5.締め切り日の設定が出来て、前日になるとアラートを飛ばす。
6.プロジェクトごとにルームを立ち上げられる（プレミアム版）
7.ユーザー数無制限で使える。（プレミアム版）


## 通常のファイル共有・管理サービス（prottやslack）との違い
- 使い方がシンプル（というか限定的？）→基本的にweb制作のやりとりをすることに特化
- 初心者登録してある人の画面には、常にサポートツールが出てくる。（一番主張したいのはここ。なんか結局、あの手のツールって「ある程度web界隈のことがわかっている人or使い慣れてる人」しか使えない。と思っている。実際うちの会社でも、「スプレッドシートでいっか〜、わかりにくいし。ああいうツール。」みたい話があります）


## メインページの画面について

AUNというサービスの左右にそれぞれ初心者お助け用ツール（左側）、チャットエリア（右側）がついているようなイメージです。
ものすごいざっくりした画面はデザイン無視でeditarea.htmlに作りました。2016.03.07更新