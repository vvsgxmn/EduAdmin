# 基于SpringBoot+Vue的教务系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

EduAdmin 是一款面向高校教学运行的智慧教务平台，贯通学院专业建档、开课排课、学生自主选课、课堂考勤、成绩评定与调课审批；学生、教师、管理员三角色协同，选修选课规则后端强制校验，适合毕设、课设与学习参考。

## 主要功能模块

- **用户认证模块**：学生/教师/管理员统一登录注册，JWT 鉴权并按角色跳转对应门户
- **学生门户模块**：学期周历课表、选修课自主选课/退选、个人考勤查阅、官方成绩单与 GPA、教务公告
- **教师履约模块**：教学任务与选课名单、课堂考勤点名、平时/期末成绩录入、调课申请流转
- **选课规则模块**：仅选修可自选、每学期最多两门、选过不可再选、容量 CAS 与节次冲突检测
- **开课排课模块**：教学任务绑定学期教师教室节次，检测教师/教室时段冲突，容量不得小于已选人数
- **管理中台模块**：学院专业班级学期教室与用户、课程库、调课审批、成绩考勤监督、教务通知发布

## 技术架构

- **后端**：Spring Boot + MyBatis-Plus + JWT + Lombok
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E5%AD%A6%E7%94%9F%E9%A6%96%E9%A1%B5.png" alt="学生首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E5%AD%A6%E6%9C%9F%E8%87%AA%E4%B8%BB%E9%80%89%E8%AF%BE.png" alt="学期自主选课" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E5%AD%A6%E6%9C%9F%E5%91%A8%E5%8E%86%E8%AF%BE%E8%A1%A8.png" alt="学期周历课表" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E6%95%99%E5%B8%88%E6%8E%88%E8%AF%BE%E4%B8%AD%E5%BF%83.png" alt="教师授课中心" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E8%AF%BE%E5%A0%82%E8%80%83%E5%8B%A4%E7%82%B9%E5%90%8D.png" alt="课堂考勤点名" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E7%AE%A1%E7%90%86%E9%A6%96%E9%A1%B5.png" alt="管理首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E4%B8%93%E4%B8%9A%E7%AE%A1%E7%90%86.png" alt="专业管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/eduadmin/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->

## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）
