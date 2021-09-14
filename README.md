# GIT提交说明检查工具

# 使用方式
拷贝commit-msg到本地项目的.git/hooks目录下

# 支持规则
要求commit内必需要含有以下字段
- feat: 新功能
- fix: bug 修复 (带Jira里的bug编号)
- refactor: 重构（非新功能也不是bug修复的变动）
- perf: 性能优化改进
- cicd: 构建过程或辅助工具变更
- test: 新增或修订单元测试
- docs: 文档变更
- style: 样式变更
- revert: 回滚到上一个版本

# commit示例
- ====feat:<1.0.1>: 新增某某功能====
- ====fix:<bug 1001>: 修正某某bug====
- ====docs:<1.0.2>: 新增某某说明文档====
