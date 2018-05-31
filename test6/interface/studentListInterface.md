# 接口：studentList  [返回](../README.md)
用例： [studentList](../studentList.md)

- 权限：
    无
   
- 功能：
    查看学生列表。
  
- API请求地址：
   接口地址：/v1/api/getStudentList
   
- 请求方式 ：
get

- 请求参数说明:
无

- 返回实例：

        {
            "status": true,
            "info": "studentList",
            "total": 60,
            "data": [
                {
                "userId":"201510414107",
                "username":"高强",
                "githubName":"gqbzd",
                "className":"软工1班"
                },
                ...
            ]
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|
  |total|返回学生人数|
  |data|所有学生的数组,userId:学号,username:用户名,githubName:github帐户,className:班级|

