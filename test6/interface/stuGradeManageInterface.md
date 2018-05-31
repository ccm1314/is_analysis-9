# 接口：stuGradeManage  [返回](../README.md)
用例： [stuGradeManage](../stuGradeManage.md)

- 权限：
    必须是老师
   
- 功能：
    对学生成绩进行增删改查。
  
- API请求地址：
   接口地址：/v1/api/stuGradeManage
   
- 请求方式 ：
get/post

- 请求参数说明:
type,stuId,term,test,AjudgeGrade,Ajudge,BjudgeGrade,Bjudge,CjudgeGrade,Cjudge,DjudgeGrade,Djudge
<br>
type:表示是要进行哪种操作(crud)<br>
stuId:学号

- 返回实例：

        {
            "status": true,
            "info": "success",
            "total": 0,
            "data": null
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|
  |total|0|
  |data| |

