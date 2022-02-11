# 添加学生

#### `POST /api/student/add`
##### `v1.0.0`
返回所有学生

## 请求格式
### `Headers`
`Content-Type: application/json;charset=utf-8`

### `Body`
* `{object[]}` 没查到数据应返回空数组
  * `{string} name` 学生名称
  * `{integer} age` 学生年龄

## 成功返回
### `Headers`
`Content-Type: application/json;charset=utf-8`

### `Body`
* `{object}`
  * `{integer} id` 学生id

