# 查询所有学生

#### `GET /api/student/all`
##### `v1.0.0`
返回所有学生

## 成功响应
### `Headers`
`Content-Type: application/json;charset=utf-8`

### `Body`
* `{object[]}` 没查到数据应返回空数组
  * `{integer} id` 学生id
  * `{string} name` 学生名称
  * `{integer} age` 学生年龄