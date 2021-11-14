# nextjs_restapi_blogapp

- User
- Post（id, title, content, created_at）
- Task (id, title, created_at)

# objective

- ブログの投稿
- タスクの投稿

# specification

python, Django REST Framework, PostgreSQL, JWT, heroku

# Usage

`https://nextjs-api-blogapp.herokuapp.com/api/`

ブログ一覧取得
`list-post/`

idからブログを取得
`detail-post/<id>/`

タスク一覧取得
`list-task/`

idからタスクを取得
`detail-task/`

ユーザー作成
`register/`

JWTの取得
`auth/`

taskのPOST, PUT, DELETE
`tasks/`