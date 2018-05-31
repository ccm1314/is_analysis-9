# 接口：modMsg  [返回](../README.md)
用例： [logout](../modMsg.md)

- 权限：
    必须是已登录用户
   
- 功能：
    修改用户相关信息。
  
- API请求地址：
   接口地址：/v1/api/modMsg
   
- 请求方式 ：
post

- 请求参数说明:
userId,GITHUBNAME,PASSWORD

userId:老师为工号，学生为学号
GITHUBNAME:github用户名
PASSWORD:密码
- 返回实例：

        {
            "status": true,
            "info": success,
            "total": 0,
            "data": null
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|
  |total|返回学生人数，这里不用|
  |data|所有学生的数组，这里不用|

