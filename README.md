# 刘浩存电影数字档案馆

[![GitHub stars](https://img.shields.io/github/stars/celeste877/haocun-archive?style=social)](https://github.com/celeste877/haocun-archive)
[![GitHub license](https://img.shields.io/badge/license-CC%20BY--NC%204.0-lightgrey)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![ECharts](https://img.shields.io/badge/ECharts-5.5.0-aa74cc?logo=apacheecharts&logoColor=white)](https://echarts.apache.org/)

**从胶片数字化到档案知识化 · 基于语义网技术的智能电影档案平台**

🔗 **[在线访问](https://celeste877.github.io/haocun-archive/)** | 📧 [联系作者](mailto:195019192@qq.com)

---

## 📖 项目简介

刘浩存电影数字档案馆是一个以青年演员刘浩存及其参演电影为切入点的知识化电影档案平台。项目运用语义网技术（RDF、SPARQL、JSON-LD）将电影、演员、导演、奖项等异构数据转化为机器可理解的关联数据，并构建轻量级电影本体，实现数据之间的语义链接与智能检索。

平台旨在探索电影档案从传统“数字化”向“知识化”转型的路径，为影迷、学者和数字人文研究者提供可查询、可复用、可推理的电影知识库。

---

## ✨ 主要功能

| 模块 | 描述 |
|------|------|
| **人物档案** | 刘浩存个人简介、基本信息、演艺时间线、代表作品 |
| **作品库** | 全部电影作品卡片展示，按年份筛选、关键词搜索，模态框显示详情及在线观看链接 |
| **荣誉奖项** | 历年奖项与提名列表，按年份导航，支持获奖/提名标识 |
| **影像典藏** | 每部电影的宣传照 + 横向滚动剧照墙，点击放大浏览 |
| **角色小传** | 每个角色独立卡片，包含角色简介、经典台词，并支持用户留言（时空对话，本地存储） |
| **学术视野** | 语义网技术介绍、关联数据示例（JSON-LD）、知识图谱可视化（ECharts）、SPARQL 模拟查询 |
| **语义检索演示** | 多条件交互检索（导演、年份、合作演员、奖项），模拟 SPARQL 查询效果 |
| **数据概览** | 评分分布柱状图、获奖趋势折线图、合作演员排行、导演合作占比饼图 |
| **关于我们** | 项目介绍、技术架构、愿景、数据来源与版权声明、联系方式 |

---

## 🛠 技术架构

- **前端**：HTML5 / CSS3 (Flexbox + Grid) / JavaScript (ES6)
- **可视化**：ECharts 5.5.0（知识图谱、统计图表）
- **字体**：Google Fonts（Inter, Noto Serif SC）
- **语义标注**：JSON-LD（基于 schema.org）
- **数据存储**：localStorage（角色小传留言）
- **部署**：GitHub Pages


> 所有 `.htm` 文件均已通过统一导航栏（含“更多 ▾”下拉菜单）无缝连接。

---

## 📊 数据来源

- 电影信息、剧情简介：豆瓣电影、百度百科、IMDb
- 荣誉奖项：公开新闻报道、颁奖典礼官方信息
- 剧照与宣传图：电影官方物料（版权归原制片方所有，仅用于学术研究与非商业展示）

---

## 🧪 本地运行

由于项目为纯静态页面，无需任何构建步骤，只需将仓库克隆到本地，用任意 HTTP 服务器（如 Live Server）打开 `sy.htm` 即可。

```bash
git clone https://github.com/celeste877/haocun-archive.git
cd haocun-archive
# 使用 VS Code 的 Live Server 或其他工具启动

联系与反馈
如有建议或数据错误，欢迎通过邮件联系：195019192@qq.com

GitHub 仓库：https://github.com/celeste877/haocun-archive

在线网站：https://celeste877.github.io/haocun-archive/

## 📁 页面结构
