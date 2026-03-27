# My Planner

A static personal planning web app for goals, tasks, and calendar-based scheduling.

`little-trial` is the repository name. `My Planner` is the product-facing name used in the app UI.

## 项目简介 / Overview

这是一个纯前端的个人规划工具，适合用来管理目标、每日待办和截止日期。
它不依赖后端，也不需要安装，直接打开 `index.html` 就可以使用。

This is a fully static personal planning tool for managing goals, daily tasks, and deadlines.
It has no backend dependency and no install step. You can open `index.html` directly in a browser and start using it.

## 截图 / Screenshots

### Calendar View

![Calendar view](assets/screenshots/calendar-view.jpg)

### Dashboard View

![Dashboard view](assets/screenshots/dashboard-view.jpg)

### Settings And Backup Tools

![Settings view](assets/screenshots/settings-view.jpg)

## 我为什么做它 / Why I Built It

我想做一个打开就能用的轻量级规划工具，把目标、任务和时间安排放在同一个界面里，而不是分散在多个应用中。
这个项目的重点不是复杂系统，而是把个人规划流程做得清晰、顺手、低门槛。

I wanted a lightweight planner that opens instantly and keeps goals, tasks, and scheduling in one place instead of spreading them across multiple apps.
The focus of this project is not system complexity. It is about making personal planning clear, fast, and approachable.

## 核心功能 / Features

- 目标管理：创建、编辑、删除、恢复目标，并按截止日期追踪进度。
- 待办管理：支持独立任务、关联任务、完成状态切换和批量整理。
- 日历视图：按日期查看目标、任务和时间压力。
- 仪表盘视图：把目标、待办和已完成内容集中在一个界面里。
- 重复任务：支持按天生成重复任务。
- 个性化设置：支持主题色、背景和分类配置。
- 数据备份：支持 JSON 导出与导入，便于本地备份和迁移。

- Goal management: create, edit, delete, restore, and track goals by deadline.
- Task management: supports independent tasks, goal-linked tasks, completion toggles, and bulk organization.
- Calendar view: shows goals, tasks, and deadline pressure by date.
- Dashboard view: brings active goals, to-dos, and completed items into one screen.
- Repeating tasks: supports daily repeat generation.
- Visual customization: includes theme, background, and category settings.
- Data backup: supports JSON export and import for local backup and transfer.

## 技术实现 / Tech Notes

- 单文件应用，核心界面和逻辑集中在 [index.html](index.html)。
- 使用原生 JavaScript 管理状态和交互逻辑。
- 使用 Tailwind CSS CDN 和 Font Awesome 处理基础样式与图标。
- 数据保存在浏览器 `localStorage`，当前使用的存储键是 `dailyPlannerPro_v16`。
- 无构建流程、无数据库、无服务端部署要求。

- The app is primarily implemented in a single file: [index.html](index.html).
- State and interactions are handled with vanilla JavaScript.
- Tailwind CSS CDN and Font Awesome are used for styling and icons.
- Data is stored in browser `localStorage` under the key `dailyPlannerPro_v16`.
- There is no build step, database, or backend deployment requirement.

## 本地运行方式 / How To Run

1. 下载或克隆这个仓库。
2. 直接在浏览器中打开 [index.html](index.html)。
3. 创建目标和任务后，数据会自动保存在当前浏览器。

1. Download or clone this repository.
2. Open [index.html](index.html) directly in a browser.
3. After you create goals and tasks, the data is saved automatically in the current browser.

## 数据存储说明 / Data Persistence

- 所有数据默认保存在当前浏览器的本地存储中。
- 如果清除浏览器站点数据、切换浏览器或更换设备，本地数据不会自动同步。
- 可以通过设置面板导出 JSON 备份，再在另一台设备中导入。

- All data is stored in the current browser's local storage by default.
- If you clear browser site data, switch browsers, or change devices, the data will not sync automatically.
- You can export a JSON backup from the settings panel and import it on another device.

## 限制与后续计划 / Limitations And Next Steps

- 当前版本没有账号系统或云端同步。
- 当前版本是单用户、本地优先的使用方式。
- 数据依赖浏览器本地存储，因此需要手动备份。
- 后续可以继续扩展为 GitHub Pages 在线演示、多设备同步或更细致的统计视图。

- The current version has no account system or cloud sync.
- The current version is designed as a single-user, local-first tool.
- Data depends on browser local storage, so manual backup is important.
- Future extensions could include a GitHub Pages demo, multi-device sync, or more detailed analytics views.

## 作者贡献 / My Contribution

- 我定义了这个工具的使用场景、功能范围和交互流程。
- 我围绕“目标 + 日历 + 待办”的结构持续迭代界面和功能细节。
- 我完成了前端页面组织、本地数据流和备份机制的实现与整理。

- I defined the use case, feature scope, and interaction flow for this tool.
- I iterated on the UI and feature details around a goals plus calendar plus tasks workflow.
- I implemented and organized the front-end structure, local data flow, and backup behavior.

## License

This project is released under the MIT License.
