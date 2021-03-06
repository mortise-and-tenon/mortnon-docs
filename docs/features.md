# 特性支持

> 框架提供如RuoYi、Guns等优秀框架提供的用户、权限等管理能力，能力上覆盖目前市面上大部分优秀开源项目已实现的功能。

## 我们的特性

1. 建议大家采用统一的代码风格，遵循《alibaba Java编程规范》，我们所有的代码也会按照这种方式进行pmd扫描，保证代码质量。
2. api文档的集成，直接扫描代码注释来生成api文档，而不是单独写一大堆浪费时间的注解来生成api，保证注释、代码、文档的一致性，也希望用这种方式推动项目组成员养成注释的习惯。我们计划提供一个idea插件来帮助规范代码风格，创建文档，创建项目等工作。
3. 统一的日志规范和风格，方便直接接入监控，提供一个简单可用的监控方案。
4. 区分环境的配置代码化能力，不需要在不同环境去改成不同的配置。
5. 提供数据库代码化能力，数据库与代码是一致的，同时可以让新加入项目组的人只要ide里运行代码即可开始调试工作。
6. 提供完善的打包、部署脚本，包括机器直接部署和容器部署。
7. 如有可能，希望在不增加研发成本的前提下，探索TDD的可能。
8. 基于领域模型的软件设计模式
9. 原生支持多租户能力
10. 还有一些其他可以加快大家研发速度和代码质量的特性，我们会在过程中不断的增加，敬请期待。

## 特性列表

- [x] Java 注释直接生成接口文档和调试工具（`smart-doc`、`swagger`）2021-04-13
  - [ ] 演示文档
- [x] `slf4j` + `logback` 日志打印，日志分区分打印，包含 `api-digest`(用于业务监控)，`service-digest`(服务摘要)，`web-digest`(web层摘要)，`dal-digest`(数据层摘要)，`default`(全量日志)，`common-error`(错误日志，用于错误监控) 2021-04-14
  - [ ] 演示和说明文档
- [ ] 如何与 `Grafana` 集成，形成一套合理的监控方案
- [x] 支持阿里巴巴 Java 开发手册中的错误码 2021-04-14
- [x] 基于 `Java validator` 的接口参数验证能力 2021-04-14
- [x] 基于领域模型设计的代码组织结构 2021-04-13
- [ ] DO 与领域模型，领域模型与展示模型之间的转换方案
  - [ ] 说明文档
- [x] 接入 `Mybatis` 2021-04-14
- [x] 配置多数据源（可选）2021-04-14
- [ ] 数据库代码化的实现，完成编写 DO 类 -> 生成数据库 -> 生成 Mapper 和 xml 的流程（`Hibernate` 把模型生成数据库表）
  - [ ] 演示和说明文档
- [ ] 区分环境的配置代码化能力 `application.yml`
- [ ] 打包和部署脚本，`Linux` 和 `Windows` 双平台
  - [ ] 演示和说明文档
- [ ] `Docker` 容器化部署
- [ ] `Docker-Compose` 部署方案
- [ ] `IDEA` 插件
- [ ] 集成 `vue-admin` 前端
- [ ] 多租户方案
- [ ] 国际化方案
- [ ] 用户登录
- [ ] 用户管理
- [ ] 操作日志
- [ ] 登录日志
- [ ] 定时任务
- [ ] 部门管理
- [ ] 岗位管理
- [ ] 菜单管理
- [ ] 角色管理
- [ ] 字典管理
- [ ] 参数管理
- [ ] 通知公告
- [ ] 在线用户
- [ ] 服务监控
- [ ] 在线构建
