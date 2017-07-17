# zero

#### PC端项目列表相关

##### PC端项目列表节点数量
###### URL
> [https://www.weitianshi.cn/project/getNodeCount](https://www.weitianshi.cn/project/getNodeCount)

###### 支持格式
> JSON

###### HTTP请求方式
> POST

###### 请求参数
>
|参数|必选|类型|说明|
|:-----  |:-------|:-----|-----             |
|user_id    |true    |string|用户id     |


###### 返回字段
> 
|返回字段|类型  |说明                              |
|:-----    |:------|:-----------------------------   |
|data  |json |具体数据     |
|status_code  |int    |状态码 【详见文档结尾】  |
|error_msg  |string | 错误信息 【成功不会返回此字段】|         
     

###### 成功接口示例
> 
```
{
    "status_code": 2000000,
    "data": {
        "total": {
            "schedule_id": "0",
            "schedule_name": "全部",
            "schedule_count": 1972
        },
        "node_list": {
            "1": {
                "schedule_name": "项目线索",
                "schedule_id": 1,
                "schedule_count": 2
            },
            "2": {
                "schedule_name": "考察",
                "schedule_id": 3,
                "schedule_count": 2
            },
            "3": {
                "schedule_name": "引荐投资方",
                "schedule_id": 5,
                "schedule_count": 4
            },
            "4": {
                "schedule_name": "投资协议",
                "schedule_id": 6,
                "schedule_count": 1
            }
        }
    }
}
```
