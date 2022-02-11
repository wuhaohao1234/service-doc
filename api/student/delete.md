# 删除学生

#### `POST /api/student/delete`
##### `v1.0.0`
返回所有学生

## 请求格式
### `Headers`
`Content-Type: application/json;charset=utf-8`

### `Body`
* `{object[]}` 没查到数据应返回空数组
  * `{integer} id` 学生id

## 成功返回
### `Headers`
`Content-Type: application/json;charset=utf-8`
