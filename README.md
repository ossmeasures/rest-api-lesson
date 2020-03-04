# RestAPI Lesson

<img src="https://fukatsu.tech/wp-content/uploads/2017/09/api-icon.png" width=70%>

## ✏️ はじめに

本課題を行うためには１回の OSS 会では完了できない可能性があります。<br>
数回の OSS 会を通して作業を進めましょう。あるいは自発的に勉強してみるのもよいと思います。<br>
本課題を行うためには３人チームを編成してもらいます。<br>
数回の OSS 会を通して課題を遂行できるように進めてみましょう。<br>

## 💪 課題

下記情報を持つ商品データの登録、検索、変更、削除を行う RESTFul な API を設計・実装してみましょう。

- 商品画像
- 商品タイトル（最大 100 文字）
- 説明文（最大 500 文字）
- 価格

リクエスト/レスポンスは JSON 形式とします。データ構造は任意です。<br>
画像は Base64 エンコードされた文字列を JSON に含めるか、画像のみ JSON ではなく、multipart/form-data 形式でアップロードを受け付ける API を作成してください。<br>
また、画像ファイルには http://localhost:8080/images/11.jpg などの URL でアクセスできるようにしてください。

動作確認には Postman , Insominia の REST Client アプリを利用すると便利です。

※ 目標達成時間 10 時間

## 💻 技術スタック

プログラミング言語および、フレームワークなどは基本的にはチームごとにお任せしますが、以下にオススメを挙げておきます。

- SpringBoot(Java)
- Express(Node.js)
- Rails(Ruby)

API 定義は、OpenAPI を使用してください。

- OpenAPI 3.0（Swagger）

## 🍰 成果物

### 必須

- API 仕様書が OpenAPI で記述されている。
- GitHub にソースコードが公開されている。
- ローカルでアプリケーションが動作する。

### 任意

デプロイがされているとベターです。各種クラウドサービスを利用してデプロイしてください。

- API 仕様書が HTML 形式で http://restapi.github.io/index.html などの URL で閲覧できる。
- WebAPI が https://restapi.now.sh などの URL で閲覧できる。
