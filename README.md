# 多智能体强化学习游乐场
# Multi-Agent Reinforcement Learning Playground

🎮 **交互式MARL算法学习平台** / **Interactive MARL Algorithm Learning Platform**

---

## 🚀 快速开始 / Quick Start

**在线体验 / Online Demo**: [https://Yuzx-001.github.io/marl-playground](https://yuzc-001.github.io/marl-playground/)

**本地运行 / Local Run**: 下载 `index.html` 用浏览器打开即可 / Download `index.html` and open in browser

---

## ✨ 主要功能 / Key Features

### 🤖 四种算法 / Four Algorithms
- **MAPPO** - 多智能体近端策略优化 / Multi-Agent Proximal Policy Optimization
- **QMIX** - 单调值函数分解 / Monotonic Value Function Factorisation  
- **MADDPG** - 多智能体DDPG / Multi-Agent Deep Deterministic Policy Gradient
- **MASAC** - 多智能体软演员评论家 / Multi-Agent Soft Actor-Critic

### 🌍 三种环境 / Three Environments
- **捕食者猎物** / **Predator-Prey** - 合作竞争场景 / Cooperative-competitive scenario
- **交通控制** / **Traffic Control** - 多车协调 / Multi-vehicle coordination  
- **资源收集** / **Resource Collection** - 资源竞争合作 / Resource competition & cooperation

### 🎛️ 实时调节 / Real-time Control
- **参数调节** / **Parameter Tuning** - 20+ 滑块参数 / 20+ slider parameters
- **环境配置** / **Environment Config** - 网格大小、智能体数量 / Grid size, agent numbers
- **可视化** / **Visualization** - 实时图表、智能体动画 / Real-time charts, agent animation

---

## 📦 部署方法 / Deployment

### 方法1: GitHub Pages
```bash
1. 创建仓库 / Create repo: marl-playground
2. 上传文件 / Upload: index.html  
3. 设置Pages / Enable Pages: Settings → Pages → main branch
4. 访问 / Visit: https://yourusername.github.io/marl-playground
```

### 方法2: Vercel (推荐 / Recommended)
```bash
1. 登录 / Login: vercel.com
2. 导入仓库 / Import repo from GitHub
3. 部署 / Deploy: 一键部署 / One-click deploy
4. 获得链接 / Get URL: https://project.vercel.app
```

---

## 🎯 使用指南 / User Guide

### 基本操作 / Basic Operations
1. **选择算法** / **Select Algorithm** → MAPPO, QMIX, MADDPG, MASAC
2. **选择环境** / **Choose Environment** → 三种多智能体场景 / Three multi-agent scenarios  
3. **调节参数** / **Tune Parameters** → 使用滑块实时调节 / Use sliders for real-time tuning
4. **开始训练** / **Start Training** → 观察可视化结果 / Watch visualization results

### 参数说明 / Parameter Guide
- **学习率** / **Learning Rate** (0.0001-0.01) → 控制学习速度 / Controls learning speed
- **折扣因子** / **Discount Factor** (0.9-0.999) → 长短期奖励权衡 / Long vs short-term reward balance  
- **网格大小** / **Grid Size** (5×5 到 25×25) → 环境复杂度 / Environment complexity
- **智能体数量** / **Agent Numbers** → 影响协作难度 / Affects cooperation difficulty

---

## 🛠️ 技术栈 / Tech Stack

- **前端** / **Frontend**: React 18 + 纯CSS / React 18 + Pure CSS
- **图表** / **Charts**: 自制SVG组件 / Custom SVG components  
- **部署** / **Deploy**: 静态网站 / Static website
- **依赖** / **Dependencies**: 零依赖 / Zero dependencies

---

## 📚 教育应用 / Educational Use

### 适用课程 / Suitable Courses
- 强化学习 / Reinforcement Learning
- 多智能体系统 / Multi-Agent Systems
- 机器学习实验 / Machine Learning Labs
- 人工智能课程 / AI Courses

### 教学优势 / Teaching Advantages
- **直观可视化** / **Intuitive Visualization** → 看到算法行为 / See algorithm behavior
- **参数理解** / **Parameter Understanding** → 调节观察效果 / Tune and observe effects
- **无需安装** / **No Installation** → 浏览器即用 / Browser ready
- **双语支持** / **Bilingual Support** → 中英文切换 / Chinese-English switch

---

## 🔧 自定义配置 / Custom Configuration

### 环境参数 / Environment Parameters
```javascript
// 捕食者猎物环境 / Predator-Prey Environment
{
  grid_size: 10,           // 网格大小 / Grid size
  num_predators: 3,        // 捕食者数量 / Predator count  
  num_prey: 2,             // 猎物数量 / Prey count
  catch_reward: 10.0,      // 捕获奖励 / Catch reward
  vision_range: 3          // 视野范围 / Vision range
}
```

### 算法参数 / Algorithm Parameters  
```javascript
// MAPPO 参数 / MAPPO Parameters
{
  lr_actor: 0.0003,        // 演员学习率 / Actor learning rate
  lr_critic: 0.001,        // 评论家学习率 / Critic learning rate  
  gamma: 0.99,             // 折扣因子 / Discount factor
  clip_ratio: 0.2          // 裁剪比率 / Clip ratio
}
```

---

## 🤝 贡献 / Contributing

欢迎提交问题和拉取请求！/ Welcome to submit issues and pull requests!

**问题反馈 / Issue Reports**: [GitHub Issues](https://github.com/yourusername/marl-playground/issues)

---

## 📄 许可证 / License

MIT License

---

## ⭐ 点星支持 / Star Support

如果觉得有用请点星！/ Please star if useful!

**让多智能体强化学习更简单！/ Making Multi-Agent RL Simpler!** 🚀
