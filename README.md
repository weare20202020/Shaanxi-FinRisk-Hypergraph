# 📖 Shaanxi Province Financial Risk Monitoring & Early Warning System
## (陕西省金融风险监测与预警系统)

## 🌍 Overview (项目简介)

This project leverages **Knowledge Hypergraph technology** combined with **Large Language Models (LLMs)** and **Twin Neural Networks** to construct a regional financial risk early-warning model.

Through large-scale financial data cleaning and entity disambiguation, we successfully built a three-dimensional network of **"multi-entity – hyper-relation – attribute value"**, covering **5,000+ enterprises and financial institutions** in Shaanxi Province.

It also enables **dynamic visualization of financial risk contagion pathways**.

The project is carried out under a **provincial-level philosophy and social sciences research program**, led by a senior professor, with the aim of providing **forward-looking risk monitoring and early-warning support** for regulators and enterprises in Shaanxi Province.

---

本项目基于**知识超图技术**，结合**大语言模型 (LLM)** 与**孪生神经网络**，构建区域金融风险预警模型。

通过对海量金融数据的清洗与实体消歧，成功建立**"多实体–超关系–属性值"三维网络结构**，覆盖陕西省内**5000+ 家企业和金融机构**，并实现了**金融风险传染路径的动态可视化展示**。

该项目作为**省级哲学社会科学研究专项**，由专业教授带领完成，旨在为陕西省金融监管部门和企业提供**前瞻性的风险监测与预警支持**。

## 🚀 Key Features (技术特性)

- **Knowledge Hypergraph Modeling (知识超图建模)**：Captures complex relations among enterprises, financial institutions, industries, and cities
- **LLM-driven Data Cleaning (大语言模型驱动的数据清洗)**：Automates financial text and unstructured data cleaning & entity disambiguation
- **Twin Neural Network (孪生神经网络)**：For entity similarity recognition and risk contagion path inference
- **Interactive Visualization (交互式可视化)**：Supports node dragging, risk chain tracing, and dynamic highlighting

## 📊 Research & Application Value (研究与应用价值)

- **Risk Early-Warning (风险预警)**：Provides real-time dynamic monitoring for regulators
- **Decision Support (决策支持)**：Visualizes financial risk contagion chains in an intuitive way
- **Academic Contribution (科研价值)**：Promotes cross-disciplinary research on knowledge hypergraphs and financial risk management
- **Practical Applications (实际应用)**：Can be extended to banking, securities, insurance, and other financial risk management domains

## 🛠️ Deployment Guide (部署说明)

*[Deployment instructions to be added]*

---

*This project represents a significant advancement in regional financial risk management through the integration of cutting-edge AI technologies and comprehensive data analysis.*

# 陕西超图项目部署指南

## 📋 项目简介

这是一个基于React + TypeScript + Vite构建的陕西企业超图可视化项目，展示了陕西省内各企业的关联关系和行业分布。

## 🚀 快速开始（推荐）

### 方法一：使用自动部署脚本

1. **双击运行** `auto_deploy.py` 文件
   - 脚本会自动检查环境
   - 自动安装依赖
   - 自动启动服务器
   - 自动打开浏览器

2. **如果双击无效**，请：
   - 右键点击 `auto_deploy.py`
   - 选择"用Python打开"或"Open with Python"
   - 或者打开命令行，运行：`python auto_deploy.py`

## 🛠️ 手动部署方法

### 环境要求

- **Node.js** (版本 16.0 或更高)
- **npm** (通常随Node.js一起安装)

### 安装步骤

#### 1. 安装Node.js

如果您的电脑没有安装Node.js：

1. 访问 [https://nodejs.org/](https://nodejs.org/)
2. 下载并安装LTS版本（长期支持版本）
3. 安装完成后重启电脑

#### 2. 验证安装

打开命令行（Windows按 `Win+R`，输入`cmd`），输入以下命令验证：

```bash
node --version
npm --version
```

如果显示版本号，说明安装成功。

#### 3. 安装项目依赖

在项目文件夹中打开命令行，运行：

```bash
npm install
```

#### 4. 启动开发服务器

```bash
npm run dev
```

#### 5. 访问项目

浏览器会自动打开，或手动访问：
- http://localhost:5173
- 或 http://localhost:3000

## 📁 项目结构

```
陕西超图项目/
├── src/
│   ├── ShaanxiHypergraph.tsx    # 主要的超图组件
│   ├── App.tsx                  # 应用主组件
│   ├── main.tsx                 # 应用入口
│   └── index.css                # 样式文件
├── package.json                 # 项目配置和依赖
├── vite.config.ts              # Vite配置
├── tailwind.config.js          # Tailwind CSS配置
├── auto_deploy.py              # 自动部署脚本
└── README.md                   # 说明文档
```

## 🎯 功能特性

- **企业节点可视化**：显示陕西省内各大企业
- **行业超边**：按行业分类显示企业关联
- **城市超边**：按城市分组显示企业分布
- **交互功能**：
  - 拖拽移动企业节点
  - 点击选择企业
  - 悬停高亮显示
  - 超边动态更新

## 🔧 常见问题

### Q1: 双击Python脚本没有反应

**解决方案：**
1. 确保已安装Python
2. 右键点击脚本 → 选择"Open with" → 选择Python
3. 或者打开命令行，运行：`python auto_deploy.py`

### Q2: 提示"npm不是内部或外部命令"

**解决方案：**
1. 重新安装Node.js
2. 安装时确保勾选"Add to PATH"选项
3. 重启电脑后再试

### Q3: 依赖安装失败

**解决方案：**
1. 检查网络连接
2. 尝试使用国内镜像：
   ```bash
   npm config set registry https://registry.npmmirror.com
   npm install
   ```

### Q4: 端口被占用

**解决方案：**
1. 关闭其他可能占用端口的程序
2. 或者修改端口（在vite.config.ts中）

### Q5: 页面显示空白

**解决方案：**
1. 检查浏览器控制台是否有错误
2. 尝试刷新页面
3. 清除浏览器缓存

## 📞 技术支持

如果遇到问题：

1. **检查控制台输出**：查看命令行中的错误信息
2. **查看浏览器控制台**：按F12打开开发者工具
3. **重新安装依赖**：删除node_modules文件夹，重新运行`npm install`

## 🎨 自定义修改

如需修改企业位置或样式：

1. 打开 `src/ShaanxiHypergraph.tsx`
2. 找到企业数据定义部分
3. 修改坐标或样式
4. 保存后页面会自动刷新

## 📝 版本信息

- **项目版本**：1.0.0
- **创建时间**：2025年7月
- **技术栈**：React 18 + TypeScript + Vite + Tailwind CSS

---

**祝您使用愉快！** 🎉
