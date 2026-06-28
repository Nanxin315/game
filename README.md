# 🚇 基于Claude Code开发的3D跨端地铁跑酷小游戏

## ✨ 项目简介
本项目依托本地搭建的 **Claude Code AI编程智能体** 全程辅助开发，复刻经典地铁跑酷玩法，一款纯前端3D网页无尽跑酷游戏，支持电脑键盘、手机触控双端适配，开箱即玩。
全程开发流程：本地部署Claude Code → 向AI描述需求迭代生成完整游戏代码 → 推送GitHub并部署Pages在线游玩。

## 🎮 在线体验地址
- 电脑端：https://nanxin315.github.io/game/index0.html
- 移动端：https://nanxin315.github.io/game/index1.html

## 📦 技术栈
- 3D渲染：Three.js
- 页面：HTML5 + CSS3
- 游戏逻辑：原生JavaScript ES6+
- 音频：Web Audio API（程序合成音效，无外部音频资源）
- 数据存储：浏览器LocalStorage
- AI开发工具：Claude Code CLI
- 部署：Git + GitHub Pages

## 🎯 核心功能
1. **双端操控**
   - PC：方向键/AWSD移动、跳跃下蹲、P暂停、R重开
   - 手机：左屏滑动换轨道，右屏上下滑跳跃/下蹲
2. **完整跑酷体系**
   三轨道场景、多种障碍物、金币连击计分、动态递增难度、警察追逐机制
3. **道具&商城系统**
   磁铁/双倍分数/喷气背包/滑板拾取特效；金币商城购买库存道具、钥匙复活
4. **角色自定义**
   5套预设人物，自由更换上衣/帽子/鞋子配色
5. **本地数据持久化**
   最高分、累计金币、道具库存、每日免费游玩次数自动保存
6. **原生程序化音效**
   内置BGM与各类操作音效，支持音量开关

## 🛠️ Claude Code 本地搭建流程（极简）
1. Windows安装Git Bash，配置系统环境变量
2. 终端执行官方脚本安装Claude Code CLI
3. 配置cc-switch工具，填入API密钥接入大模型
4. 进入项目文件夹执行`claude`启动本地AI智能体，读取项目文件协作开发

## 🚀 快速本地运行
1. 克隆仓库
```bash
git clone https://github.com/nanxin315/game.git
cd game
```
2. 直接打开对应HTML文件
- 电脑端：`index0.html`
- 移动端：`index1.html`
3. 浏览器打开即可游玩，无需安装任何依赖

## 📁 项目目录
```
game/
├── index0.html   # PC端完整游戏（HTML+CSS+JS单文件）
├── index1.html   # 移动端适配版本
└── README.md     # 项目说明文档
```

## 🧠 AI开发流程
1. 本地部署Claude Code智能体，创建项目工作区
2. 向AI描述游戏完整需求，由AI设计整体技术架构
3. 分模块迭代生成代码：场景→角色→操控→道具商城→音频→跨端适配
4. 本地运行测试，将卡顿、碰撞bug等问题反馈AI自动修复优化
5. 代码完成后Git推送仓库，开启GitHub Pages实现在线访问

## 📝 开源协议
本项目基于 [MIT License](LICENSE) 开源，可自由学习、二次修改。

## 📬 反馈与贡献
如果你发现了 bug，或有改进建议，欢迎通过 Issues 提出。也欢迎提交 Pull Request！

## 💡 补充说明
完整开发细节、测试复盘、问题解决方案见课程大作业报告，本README仅为项目快速使用指南。
