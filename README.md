### Render deploy時の注意⚠️

・ Nodeのバージョンが古いと、Promiseの非同期処理がうまくいかないため、「NODE＿VERSION」で環境変数を指定すること

・ Nodeではalertメソッドはないため、try catchでalertを使用しないこと

・ 後はサーバー側のログをしっかりみながら、エラーを解決していって