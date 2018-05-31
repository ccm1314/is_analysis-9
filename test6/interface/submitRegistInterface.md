# 接口：submitRegist  [返回](../README.md)
用例： [submitRegist](../submitRegist.md)

- 权限：
    学生or老师
   
- 功能：
    查看学生成绩列表。
  
- API请求地址：
   接口地址：/v1/api/submitRegist
   
- 请求方式 ：
post

- 请求参数说明:
{userId,term,test}

userId:学号,<br>
term:某学期,<br>
test:某次实验<br>
（term与test必须同时传，不能单独只传其中任意一个）

- 返回实例：

        {
            "status": true,
            "info": "success",
            "total": 0,
            "data":null
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|
  |total| 0|
  |data| null| 

