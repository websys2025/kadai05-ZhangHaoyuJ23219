## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* リクエストとレスポンスのフォーマット

* 郵便番号APIは、郵便番号を指定して住所情報（都道府県、市区町村、町名）を取得できるWeb APIである。エンドポイントは https://zipcloud.ibsnet.co.jp/api/search で、GETメソッドにより ?zipcode=郵便番号 の形式でリクエストする。レスポンスはJSON形式で、住所情報が格納されている。
* 
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* エンドポイントと機能
* リクエストとレスポンスのフォーマット

* 私が調査したのはDog API（https://dog.ceo/dog-api/）である。`https://dog.ceo/api/breeds/image/random/数` にアクセスすると、指定した数のランダムな犬の画像をJSON形式で取得できる。GETメソッドを使用し、レスポンスには画像URLが含まれている。シンプルで使いやすいAPIである。
* 
### Q3-3. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* Web APIの利便性や課題など

* 外部APIの呼び出しは少し複雑だと感じたが、正しい形式でリクエストを作成する方法を学ぶことができた。APIはとても便利な仕組みであり、無料で公開している方々に感謝の気持ちを持った。
