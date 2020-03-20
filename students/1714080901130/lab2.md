# 实验二：用例建模

## 1. 实验目标
1. 创建并完善个人选题
2. 掌握UML用例建模的概念和过程
3. 使用Markdown编辑实验报告

## 2. 实验内容

1. 创建个人选题
2. 使用StarUML绘制个人选题的用例图
3. 使用Markdown编辑实验二报告并完善实验一报告 

## 3. 实验步骤

1. 创建个人选题：书店仓库管理系统
2. 系统功能：
 - 查封主播直播间
 - 结算直播工资
3. 使用StarUML绘制用例图
 - 根据功能建立Use Case
 - 确定系统的Actor
 - 建立Use Case和Actor之间的联系
4. 编辑用例规约
## 4. 实验结果

![用例图](./lab2_UseCaseDiagram1.jpg)


图1：虎牙直播平台的用例图



## 表1：查封主播直播间的用例规约  

用例编号  | UC01 | 备注  
-|:-|-  
用例名称  | 查封主播直播间  |   
前置条件  | 管理员收到观众举报直播内容非法     | *可选*   
后置条件  | 管理员成功登陆管理系统     | *可选*   
基本流程  | 1. 管理启动系统查封功能；  |*用例执行成功的步骤*    
~| 2. 系统检测直播主播内容；  |   
~| 3. 系统开放直播间；  |   
  
扩展流程  | 2.1 系统发现主播直播内容非法，封掉直播间，**提示“非法直播”**；  |*用例执行失败*  


## 表2：结算主播工资的用例规约  

用例编号  | UC02 | 备注  
-|:-|-  
用例名称  | 结算主播工资  |   
前置条件  |                        | *可选*   
后置条件  |                        | *可选*   
基本流程  | 1. 主播点击工资结算按钮；  |*用例执行成功的步骤*    
~| 2. 系统根据本月成果（礼物量，订阅数）显示工资数目；  |   
~| 3. 主播核对后，点击确认按钮；  |   
~| 4. 系统显示银行卡号填写界面；  |  
~| 5 主播填写银行卡号；               |    
~| 6. 系统自动转账；                 |   
~| 7. 系统显示转账成功；              |   
扩展流程  | 5.1 系统发现卡号错误，**提示“银行卡有误”**；  |*用例执行失败* 
         | 6.1 系统发现系统账户余额不足，**提示“余额不足，管理员会尽快处理”**；  | 
