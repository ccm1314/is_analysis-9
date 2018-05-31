# 接口：showGrade  [返回](../README.md)
用例： [showGrade](../showGrade.md)

- 权限：
    学生or老师
   
- 功能：
    查看学生成绩列表。
  
- API请求地址：
   接口地址：/v1/api/showGrade
   
- 请求方式 ：
get

- 请求参数说明:
无or{term,test}

如果不传参数，返回所有学期所有实验的各项成绩
如果传参数，term:某学期，test:某次实验（term与test必须同时传，不能单独只传其中任意一个）

- 返回实例：

        {
            "status": true,
            "info": "studentList",
            "total": 60,
            "data": [
                {
                "userId":"201510414107",
                "userName":"高强",
                "courseId":"52",
                "courseName":"信息管理系统",
                "AjudgeGrade":20,
                "Ajudge":"还可以",
                "BjudgeGrade":20,
                "Bjudge":"还可以",
                "CjudgeGrade":20,
                "Cjudge":"还可以",
                "DjudgeGrade":20,
                "Djudge":"还可以",
                "allGrade":80,
                "termTest":"第一学期#第二次实验"
                },
                ...
            ]
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|
  |total|返回成绩个数|
  |data|所有成绩的数组,<br>userId:学号,username:用户名,<br>courseId:课程ID,courseName:课程名称<br>AjudgeGrade:A项评分，Ajudge:A项评价（下同）<br>allGrade:总分|

