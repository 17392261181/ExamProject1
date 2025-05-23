# ExamProject - 在线考试系统

基于Spring Boot构建的智能在线考试平台，支持多角色协同工作，提供完整的考试流程管理解决方案。

## 功能特性

### 学生端
- 在线实时考试（支持选择题/填空题）
- 考试历史记录查询
- 倒计时自动提交
- 即时成绩反馈

### 教师端
- 题库管理系统（CRUD）
- 智能组卷功能
- 考生成绩统计
- 用户信息维护

### 管理员端
- 系统用户管理
- 权限分配
- 操作日志
- 系统监控

## 技术栈
- **后端框架**: Spring Boot 3.4.4
- **持久层**: MyBatis + MySQL
- **安全控制**: Session-Based认证 + 自定义拦截器
- **API风格**: RESTful
- **构建工具**: Maven

## 系统亮点
- 三层架构清晰分离（Controller/Service/Mapper）
- 自动阅卷算法实现
- 实时考试状态监控
- 跨域安全解决方案
- 完善的异常处理机制

## 环境要求
- JDK 17+
- MySQL 8.0+
- Maven 3.6+

