<p align="center">
  <img src="logo.png" alt="Coderly Logo" width="400">
</p>

<h1 align="center">Coderly</h1>

<p align="center">
  <strong>一款面向程序员的刷题学习应用</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-Kotlin-7F52FF?logo=kotlin" alt="Kotlin">
  <img src="https://img.shields.io/badge/Spring%20Boot-3.2-6DB33F?logo=springboot" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Vue-3-4FC08D?logo=vuedotjs" alt="Vue 3">
</p>

---

## 项目介绍

Coderly 是一款专为程序员打造的刷题学习应用，帮助你通过系统化的刷题训练提升编程技能。无论你是正在准备面试的求职者、在校学生，还是想要查漏补缺的开发者，Coderly 都能为你提供高效的学习体验。

应用涵盖 **10 大技术方向**，每个方向下按知识点拆分为三级结构（方向 → 模块 → 知识点），让你可以精准定位薄弱环节，有针对性地进行练习。

## 功能特性

### 知识点体系

覆盖计算机领域核心技术栈，构建完整的知识图谱：

| 方向 | 内容 |
|------|------|
| 数据结构 | 数组、链表、树、图、哈希表等 |
| 基础算法 | 排序、搜索、动态规划、贪心等 |
| 计算机数学基础 | 离散数学、线性代数、概率统计 |
| 计算机专业基础 | 操作系统、计算机网络、编译原理 |
| 数据库与缓存 | SQL、索引、事务、Redis、MySQL |
| 后端开发 | Spring Boot、微服务、设计模式 |
| 前端开发 | Vue、React、CSS、浏览器原理 |
| 移动端开发 | Android、iOS、Jetpack Compose |
| 人工智能与大模型 | 机器学习、深度学习、LLM |
| 运维与测试 | Docker、CI/CD、自动化测试 |

### 多题型智能答题

- **单选题** - 基础概念考察
- **多选题** - 综合理解检验
- **判断题** - 易错点辨析
- **简答题** - 支持 **AI 智能判分**，不再局限于客观题

每道题标注难度等级（简单 / 中等 / 困难），让你循序渐进地提升。

### 快速测验

从首页推荐题目中直接进入答题界面，快速检验对某个知识点的掌握程度。

### 挑战模式

自由定制你的刷题挑战：

- 选择题目来源：题库、收藏夹、错题本
- 筛选题目类型：全部、单选、多选、判断
- 设置难度范围：全部、简单、中等、困难
- 自定义题目数量：10 ~ 100 题

### 成就系统

答题解锁多种成就，持续激励你的学习：

- 等级成就 - 达到指定等级
- 连续登录 - 坚持每日学习
- 答题里程碑 - 累计答题 / 答对达到一定数量
- 方向达人 - 在特定技术方向表现突出
- 全能选手 - 涵盖所有技术方向

### 排行榜

基于每周答题数、答对数和正确率生成排行榜，查看自己的排名变化，与他人比拼学习效率。

### 收藏与错题本

- 收藏感兴趣的题目，方便日后回顾
- 自动记录答错的题目，支持错题重做
- 针对薄弱知识点反复强化

### 签到与经验值

- 每日签到获得经验值
- 答对题目、完成挑战均可获得额外经验
- 经验值累积提升等级，解锁更多成就

## 下载安装

前往 [Releases](https://github.com/kanerel/Coderly/releases) 页面下载最新版本的 APK 安装包，直接安装到 Android 设备即可使用。

## 技术架构

Coderly 采用前后端分离的架构设计，支持 Android 移动端和 Web 管理端双端访问。

| 端 | 技术选型 | 说明 |
|---|---|---|
| Android 客户端 | Kotlin · Jetpack Compose · Material3 · Hilt | 声明式 UI，流畅的交互体验 |
| 后端服务 | Spring Boot 3 · MyBatis-Plus · MySQL · Redis · JWT | RESTful API，JWT 认证 |
| Web 管理端 | Vue 3 · Element Plus · Vite · ECharts | 管理员后台，数据可视化 |
| 部署方案 | Docker Compose | 一键部署全部服务 |

## 问题反馈

如果你在使用过程中遇到问题或有功能建议，欢迎前往 [Issues](https://github.com/kanerel/Coderly/issues) 提交反馈。
