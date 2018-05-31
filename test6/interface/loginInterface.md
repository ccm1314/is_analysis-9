# 接口：login  [返回](../README.md)
用例： [login](../login.md)

- 权限：
    无
   
- 功能：
    用户以正确的身份登录。
  
- API请求地址：
   接口基本地址/v1/api/login
   
- 请求方式 ：
post

- 请求参数说明:
userId,password

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

