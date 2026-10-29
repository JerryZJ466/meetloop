# MeetLoop

活动组织与报名应用：Swift / iOS 和 TypeScript / React Native 为主，Kotlin / Android深化和自写Go后端为附加项。

## 当前状态

目前只有计划与文档；应用工程、业务代码、测试和部署尚未实现。 本次完成的是开工准备与计划审核，功能目标不代表已经掌握。

## 只从这份计划开始

- **[当前主计划 v3.1](docs/plans/plan.md)**：阶段顺序、工时、开发任务、验收及学到什么。
- **[每天3小时：前28天任务清单](docs/DAILY_28D.md)**：Windows起步，课程链接、每日练习、验收与Mac到货分支。
- [每日清单本机阅读](docs/DAILY_28D.html) · [每日清单PDF](docs/daily/学习执行清单_每天3小时_前28天_2026-10-29.pdf)
- [项目起步说明](docs/START_HERE.md)：实际学习状态和过关要求。
- [进度账本](docs/PROGRESS.md)：各关卡当前均待开始，用代码和验证证据更新。
- [岗位能力审核](docs/JOB_REQUIREMENTS_AUDIT.md)：官方样本、缺口与角色边界。
- [准备工作审核](docs/PREPARATION_AUDIT.md) · [时间与面试评估](docs/面试准备与时间评估.md) · [公共基础](docs/COMMON_FOUNDATIONS.md)
- [本机HTML版](docs/plans/plan.html) · [当前PDF快照](docs/plans/MeetLoop_开发与学习主计划_v3.1_2026-10-29.pdf)

主要对应iOS与移动跨端。RN不能替代浏览器、DOM/CSS和Web工程；Web基础由独立AgentDesk控制台训练，进一步的全栈求职专项单独估时。

- [实习目标：国内八家与美国岗位](docs/INTERNSHIP_TARGETS.md)

## 时间与优先级

首轮iOS准备每周13h MeetLoop、5h AgentDesk、3h公共基础；M3过关后9h/9h/3h。iOS投递检查约3-5个月，iOS+RN约7-11个月，AI应用/只读Agent约7-12个月，受控操作Agent约9-14个月。均从现在累计、按独立验收判断。Android/Go/FDE/平台不阻塞核心投递。

## 独立迭代

按需增加 `apps/ios`、`packages/registration-rn`、`apps/android`、`server`；不预建空壳工程。 本项目不依赖另一个项目的代码、文件或服务。远程仓库：[JerryZJ466/meetloop](https://github.com/JerryZJ466/meetloop)，public，默认分支main。

开始工作前拉取最新提交；每次完成可解释的小变化后检查diff、验证、commit和push。真实凭据、运行数据与本机历史资料保持Git忽略；依赖锁文件提交。

## 文档维护与历史

`docs/plans/plan.source.json` 是内容源；`python tools/build_plan_html.py` 同时生成Markdown与HTML。PDF为同版本固定快照，修改源后须另外更新PDF；元数据在`docs/CURRENT_PLAN.json`。**旧PDF仅供历史参考，执行顺序与工时以当前主计划为准。**

- [旧v2.2 PDF（历史）](docs/plans/MeetLoop_原计划_v2.2_2026-10-19.pdf)
- [旧v2.3 PDF（历史）](docs/plans/MeetLoop_方向评估与深化安排_v2.3_2026-10-28.pdf)

- [上一版主计划（历史）](docs/plans/MeetLoop_开发与学习主计划_v3.0_2026-10-29.pdf)
