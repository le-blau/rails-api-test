## 起動
`rails s`

## リクエスト
`curl -X POST http://localhost:3000/users -d 'user[name]=名前'`

## レスポンス
`{"id":1,"created_at":"2020-05-19T17:17:02.725Z","updated_at":"2020-05-19T17:17:02.725Z","name":"名前"}`