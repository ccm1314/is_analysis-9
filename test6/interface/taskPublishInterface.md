# 接口：taskPublish  [返回](../README.md)
用例： [taskPublish](../taskPublish.md)

- 权限：
    老师
   
- 功能：
    作业的发布，与规定作业上交时间。
  
- API请求地址：
   接口地址：/v1/api/taskPublish
   
- 请求方式 ：
post

- 请求参数说明:
{userId,term,test,taskDetail,time}

userId:学号,<br>
term:某学期,<br>
test:某次实验<br>
taskDetail:作业详细<br>
time:规定上交时间<br>
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

