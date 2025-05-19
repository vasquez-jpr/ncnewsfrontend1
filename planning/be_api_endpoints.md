# Backend API endpoints

GET /api

GET /api/users
GET /api/users/:username

GET /api/topics
POST /api/topics

GET /api/articles
GET /api/articles/:article_id
GET /api/articles/:article_id (comment_count)
GET /api/articles/:article_id/comments
GET /api/articles/:article_id/comments (pagination)
GET /api/articles (sorting queries)
GET /api/articles (topic query)
GET /api/articles (pagination)

POST /api/articles
POST /api/articles/:article_id/comments
PATCH /api/articles/:article_id
DELETE /api/articles/:article_id

PATCH /api/comments/:comment_id
DELETE /api/comments/:comment_id

[
1 GET /api
2 GET /api/topics
3 GET /api/articles
4 GET /api/users
5 GET /api/articles/:article_id
6 GET /api/articles/:article_id/comments
7 POST /api/articles/:article_id/comments
8 PATCH /api/articles/:article_id
9 DELETE /api/comments/:comment_id
10 GET /api/articles (sorting queries)
11 GET /api/articles (topic query)
12 GET /api/articles/:article_id (comment_count)
13 GET /api/users/:username
14 PATCH /api/comments/:comment_id
15 POST /api/articles
16 GET /api/articles (pagination)
17 GET /api/articles/:article_id/comments (pagination)
18 POST /api/topics
19 DELETE /api/articles/:article_id
]

[
1 CORE: GET /api
2 CORE: GET /api/topics
3 CORE: GET /api/articles
4 CORE: GET /api/users
5 CORE: GET /api/articles/:article_id
6 CORE: GET /api/articles/:article_id/comments
7 CORE: POST /api/articles/:article_id/comments
8 CORE: PATCH /api/articles/:article_id
9 CORE: DELETE /api/comments/:comment_id
10 CORE: GET /api/articles (sorting queries)
11 CORE: GET /api/articles (topic query)
12 CORE: GET /api/articles/:article_id (comment_count)
13 ADVANCED: GET /api/users/:username
14 ADVANCED: PATCH /api/comments/:comment_id
15 ADVANCED: POST /api/articles
16 ADVANCED: GET /api/articles (pagination)
17 ADVANCED: GET /api/articles/:article_id/comments (pagination)
18 ADVANCED: POST /api/topics
19 ADVANCED: DELETE /api/articles/:article_id
]
