> 这个是本人自己在开发使用的过程中的maven的依赖的总结，长期维护，让自己在使用的时候不需要到处找
# 提交代码规范
Header 只有一行，由三个字段组成：type（必需）、scope（可选）和 subject（必需）。

核心 Type（提交类型）：

feat：新增功能（feature）
fix：修复 Bug
docs：仅修改了文档（如 README.md）
style：代码格式调整（不影响代码逻辑，如去掉多余空格、代码格式化等）
refactor：代码重构（既不是新增功能，也不是修复 Bug 的代码变动）
perf：性能优化（Performance）
test：增加或修改测试用例
chore：构建过程、依赖库或辅助工具的变动（如更新 npm 包、修改 maven 配置）
build：影响构建系统或外部依赖的更改（如 Maven、Gradle、npm 配置）
ci：修改 CI/CD 配置文件和脚本（如 GitHub Actions、GitLab CI）
revert：回滚之前的 commit
Scope（影响范围）： 用于说明本次提交影响的范围，比如 auth、user、pom 等。如果是全局修改可以省略。

Subject（简短描述）： 简短描述本次修改的内容。

动词开头，比如 "新增"、"修复"、"更新"
结尾不要加句号 .
