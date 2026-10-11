# MiniCodeAgent
A local software development agent


# 整体开发路线

按照从简单到复杂的顺序推进，每个阶段完成后再进入下一阶段。

- 搭建最小可运行项目

当前阶段：

创建项目目录、虚拟环境、依赖配置和入口程序，理解 Code Agent 的基本运行方式。

- 实现 LLM 调用与单 Agent

接收用户任务，调用模型，获得回答；再逐步引入工具调用，让 Agent 可以实际操作代码仓库。

- 实现代码仓库操作工具

文件搜索、文件读取、代码修改、Git 状态查询、命令执行和安全校验。

- 实现自动开发闭环

代码修改 → 测试 → 错误分析 → 自动修复 → 再次测试。

- 升级为多 Agent 系统

引入 Planner、Coding、Test、Review Agent，完成任务拆解、调度、状态管理和质量门禁。

- 完善工程化能力

Git worktree、Docker 隔离、任务恢复、评测体系、CI/CD 和部署审批。





