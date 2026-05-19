#api仕様

## POST /api/stocks/update
説明:在庫の一覧を表示する
リクエスト:{ "id": "1", "quantity": "3" }
レスポンス:{ "status": "success", "message": "在庫を更新しました" }
## GET /api/stocks
説明:在庫の一覧を更新する
レスポンス:[{ "id": "1", "name": "醬油", "quantity": 2 }]