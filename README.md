# HomeworkSystem

## 说明

[SoftwareStructure](https://github.com/vuhe/SoftwareStructure) 仓库的 Kotlin 版本

软件构造课程作业练习的 Kotlin 版本，本系统为练习作品

如果您认为本系统侵犯了您的权益，可以联系我处理

如果您需要提交 PR，请在 PR 中说明提交的必要性

## 运行

本系统运行环境需要 java 11+

如果需要运行本系统，可以执行 `main` 包下的 `MainApplication`

进行单元测试可以执行 `test` 包下的测试类，
由于严格意义上来说未对外开放的接口不能测试，代码中出现了需要测试而不规范的权限，
因此测试类可能会经常出现变化


**注意：由于软件需要依赖部分包，因此使用了 gradle 管理，如果不执行 gradle 获取包可能不能正确运行**


## 测试

测试文件以一个模块为单位建立测试类

每个模块中的一个功能点都有一个测试方法检验代码
