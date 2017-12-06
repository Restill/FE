# 需求调研方法论总结
## 什么是需求调研
对于一个应用软件来说， 需求调研是软件生命周期的最初阶段。在这个阶段中需求人员与客户频繁的接触，获取用户需求，分析归纳整理并于用户确认后，
产出需求说明文档，用来指导后续的系统设计，系统开发阶段。

## 需求调研方法论
好的方法论可以指导工作更高质量的完成。在需求调研阶段我们主要借助UML中的用例图和泳道图来帮我们梳理用户需求

### UML
Unified Modeling Language (UML)又称统一建模语言
是一堆大神提出的一个规范，用来描述建模的概念， 详情见百科[UML词条](https://baike.baidu.com/item/%E7%BB%9F%E4%B8%80%E5%BB%BA%E6%A8%A1%E8%AF%AD%E8%A8%80/3160571?fr=aladdin&fromid=446747&fromtitle=UML)

### 用例图
用例图（User Case）是外部用户（被称为参与者）所能观察到的系统功能的模型图。
主要用来获取需求、指导测试。
用例图主要包括以下几种元素：
- Actor(参与者)： 系统外部与系统进行交互的角色，通常情况下是人，但不是特指人
- Use Case(用例)： 参与者想要系统提供的功能，通常用动词短语来描述
- 系统边界：边界内表示系统内部，边界外表示系统外部，一般用方框表示。
- 箭头： 用来描述参与者，用例，以及系统边界之间的相互关系

### 泳道图
在需求调研分析阶段，建议使用泳道图来描述业务流程。  
纵向泳道表示不同的参与者。  
泳道中的各个节点表示流程节点/功能节点。  
这样可以更清晰的看出每个参与者会使用到系统的什么功能，同时也能够更清晰的看到宏观的业务流程

## 需求调研不同阶段
### 调研计划制定
项目经理按照项目任务书自顶向下分解调研任务，安排调研资源。  
安排资源时要注意尽量避免开大会的形式，提高效率  

### 调研期间
主要通过与客户面对面的会议交流来收集、确认需求。  

会议类型主要分为收集类和确认类两类。  
收集类会议需要引导客户主动介绍业务流程、预期目标、当前业务痛点等  
确认类会议室我方需求人员理解需求后跟客户逐条确认

会议注意点：
- 不要开大会
- 会前一定要有准备，需要针对不同的部门、角色提出问题，列出问题清单或确认清单
- 会议期间一定要有分工，谁做主讲人，谁做记录人，主讲人主要负责沟通，记录人主要负责记录
- 会议期间主讲人一定要控场，聚焦在重点业务场景，不要太发散，同时也要控制好会议环境，避免成为菜市场
- 会后要及时的总结归纳，整理调研结果并分析问题

### 调研结束
调研结束后，需要有相应的产出文档：
- 用例图
- 泳道图
- 需求规格说明书：在用例图，泳道图的基础上，补充文字解释说明并填充细节
- 原型图： 与客户进行需求确认时，通过原型图来确认更容易接受，方便客户更具象的理解系统的产出物