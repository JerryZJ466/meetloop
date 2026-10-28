# MeetLoop

活动组织与报名应用，用于深入学习 Swift / iOS 与 TypeScript / React Native，辅以 Kotlin / Android 和最小 Go 后端。

## 当前状态

目前是计划与文档仓库，应用代码尚未实现。文档里的功能、测试和性能目标不是已完成成果。

## 从这里开始

- [方向与深化安排](docs/plans/plan.html)
- [学习时间与面试验收](docs/面试准备与时间评估.md)
- [前四周任务](docs/START_HERE.md)
- [当前计划 PDF](docs/plans/MeetLoop_方向评估与深化安排_v2.3_2026-10-28.pdf)
- [原 16 页计划 PDF](docs/plans/MeetLoop_原计划_v2.2_2026-10-19.pdf)

当前时间估算以“学习时间与面试验收”为准；PDF 保留完整阶段与课程细则。

## 产品范围

首版：活动列表 → 活动详情 → 报名 / 取消 → 我的报名。先用本地数据建立独立开发能力，再接 API。

- iOS：SwiftUI 起步，UIKit 专项，状态、并发、内存、网络与性能。
- RN：共享报名模块，原生宿主契约、原生能力、生命周期与 Release 构建。
- Android：原生列表 / 详情与 RN 宿主，不要求复制全部 iOS 页面。
- Go：一个服务与数据库，保留鉴权、资源权限、事务、约束与幂等。

## 目录

```text
docs/                 计划、课程入口与验收标准
tools/                独立文档生成工具
_local/               本机历史资料与校验记录，Git 已忽略
```

实现时按需增加 `apps/ios`、`apps/android`、`packages/registration-rn`、`server` 和测试目录。现在不创建空壳工程。

## 文档更新

`docs/plans/plan.source.json` 是本仓库独立的计划源文件。运行 `python tools/build_plan_html.py` 更新 HTML。PDF 是固定快照，不会随 HTML 自动更新。

## 仓库与迭代

远程仓库：[GitHub 上的 meetloop](https://github.com/JerryZJ466/meetloop)。默认分支为 `main`，当前设为公开。此项目不依赖 AgentDesk 的代码、文件或服务。

每次完成一个可解释、可验证的小任务后提交：

```bash
git status
git add <本次修改的文件>
git commit -m "描述本次完成的变化"
git push
```

跨设备开始工作前先拉取最新提交；较大的实验使用独立分支。历史资料、凭据与运行数据按 `.gitignore` 保持在本地。计划、虚构样例和应用源码随仓库迭代。
