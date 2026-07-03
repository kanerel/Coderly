<p align="center">
  <img src="logo.png" alt="Coderly Logo" width="120">
</p>

<h1 align="center">Coderly</h1>

<p align="center">
  <strong>一款面向程序员的刷题学习应用</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-Kotlin-7F52FF?logo=kotlin" alt="Kotlin">
  <img src="https://img.shields.io/badge/Spring%20Boot-3.2-6DB33F?logo=springboot" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Vue-3-4FC08D?logo=vuedotjs" alt="Vue 3">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</p>

---

## 功能特性

- **知识点体系** - 10 大技术方向，三级知识树结构
- **多题型支持** - 单选、多选、判断、简答，简答支持 AI 判分
- **挑战模式** - 自定义题目来源、类型、难度和数量
- **成就系统** - 等级、连续登录、答题数等多种成就解锁
- **排行榜** - 基于每周答题数据的排名
- **收藏与错题本** - 收藏题目，自动记录错题并支持重做
- **签到与经验** - 每日签到、答题、挑战均可获得经验值

## 技术栈

| 端 | 技术 |
|---|---|
| Android | Kotlin · Jetpack Compose · Material3 · Hilt |
| 后端 | Spring Boot 3 · MyBatis-Plus · MySQL · Redis · JWT |
| Web 管理端 | Vue 3 · Element Plus · Vite · ECharts |

## 下载

前往 [Releases](https://github.com/kanerel/Coderly/releases) 页面下载最新版本。

## 预览

<p align="center">
  <img src="preview.png" alt="App Preview" width="800">
</p>

## 快速开始

```bash
# 克隆完整项目仓库
git clone https://github.com/kanerel/Coderly-private.git

# 一键部署
cd Coderly-private
chmod +x deploy.sh
./deploy.sh
```

## 项目结构

```
Coderly-private/
├── backend/          # Spring Boot 后端服务
├── web-frontend/     # Vue 3 Web 管理端
├── mobile-frontend/  # Android 移动端
├── db/               # 数据库脚本与题库
├── docker-compose.yml
└── deploy.sh
```

## 相关链接

- [完整源码（私有仓库）](https://github.com/kanerel/Coderly-private)
- [问题反馈](https://github.com/kanerel/Coderly/issues)

## License

MIT
