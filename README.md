WEB+DB PRESS　Vol.106

# todo-web-app
Kotlin, SpringBoot

## 仕様
- タスク管理
  - タスク、期限、完了チェック
  - 新規タスク登録
  - タスクの一覧確認
  - 編集、削除
  
## URL設計
メソッド | API | 役割
 --- | --- | ---
 GET | /todo/tasks |タスクを全件取得
 POST | /todo/tasks |タスクを一件作成
 GET | /todo/tasks/{id} |タスクを一件表示
 PUT | /todo/tasks/{id} |タスクを一件更新
 DELETE | /todo/tasks/{id} |タスクを一件削除
 
