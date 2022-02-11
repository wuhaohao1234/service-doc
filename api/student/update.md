# 更新学生

#### `POST /api/student/update`
##### `v1.0.0`
返回所有学生

## 请求格式
### `Headers`
`Content-Type: application/json;charset=utf-8`

### `Body`
* `{object[]}` 没查到数据应返回空数组
  * `{integer} id` 学生id
  * `{string} name` 学生名称
  * `{integer} age` 学生年龄

## 成功返回
### `Headers`
`Content-Type: application/json;charset=utf-8`

### `Body`
* `{object}`
  * `{integer} id` 学生id
  * `{string} name` 更新后学生名称
  * `{integer} age` 更新后学生年龄
