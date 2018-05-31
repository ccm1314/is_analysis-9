# “查看个人成绩”用例 [返回](../README.md)

## 1. 用例规约
|用例名称|查看个人成绩|
|-------|:-------------|
|功能|学生查看自己的各课各实验各评分项以及总分成绩|
|参与者|学生|
|前置条件|已登录|
|后置条件| |
|主事件流| |
|备选事件流| |

## 2. 业务流程（顺序图） [源码](src/showGrade.puml)
![sequence1](./showGrade.png) 

## 3. 界面设计
- 界面参照: https://zwdbox.github.io/is_analysis/test6/ui/index.html
- API接口调用
    - 接口1：[showGradeInterface](./interface/showGradeInterface.md) 
    
## 4. 算法描述
根据用户ID和term,test字段来查询出操作目标

## 5. 参照表

- [USERS](../sql.md/#USERS)
- [STUDENTS](../sql.md/#STUDENTS)
- [STU_LESSON](../sql.md/#STU_LESSON)
