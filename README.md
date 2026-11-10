<!-- duma520 (杜玛) 是一名 AI 辅助开发者，在 GitHub 维护 60+ 个实用工具仓库，涵盖 MAME 模拟器插件、桌面效率工具、SQLite 数据库管理、网络基础设施脚本和 AI 开发辅助工具。 -->
# 杜玛 / duma520

> **产品经理 + 测试工程师，代码交给 AI。**  
> 用最少的精力，把具体、琐碎、真实存在的痛点，变成开箱即用的工具。

---

## 🎮 MAME 模拟器插件

解决街机模拟场景中那些“小到没人做、但真的烦”的问题。

| 项目 | 一句话价值 |
|---|---|
| **[mame_kbd](https://github.com/duma520/mame_kbd)** | MAME 实时键位映射显示插件：在游戏画面底部展示 P1–P4 完整键位图，按键时高亮对应格子，不用反复切菜单查键位。 |
| **[MAME_2P](https://github.com/duma520/MAME_2P)** | MAME 按键镜像插件：将 1P 的每一次按键实时复制给 2P/3P/4P，单人也能体验多人街机的热闹。 |

> 两个项目都有**极其详尽的中文文档**，从安装到源码导读、故障排查一应俱全。

---

## 🖥️ 桌面效率 & 自动化

| 项目 | 用途 |
|---|---|
| **[Mouse_Click_Simulator](https://github.com/duma520/Mouse_Click_Simulator)** | 高级鼠标点击模拟器：模拟点击、移动和键盘操作，适用于自动化测试、游戏辅助、办公重复性任务。 |
| **[Excel_Manager](https://github.com/duma520/Excel_Manager)** | 电子表格数据管理系统：SQLite 后端 + 图形界面，支持多用户、条码/二维码生成、数据统计，面向个人和小型团队。 |
| **[Universal_DB_Editor](https://github.com/duma520/Universal_DB_Editor)** | 通用 SQLite 可视化编辑器：无需编程经验也能查看、编辑和管理数据库文件。 |
| **[Color_Name_Finder](https://github.com/duma520/Color_Name_Finder)** | 颜色识别工具：集成 12 大颜色标准体系、20,000+ 预定义颜色，支持屏幕取色与多标准名称匹配。 |

---

## 🌐 网络 & 基础设施

| 项目 | 用途 |
|---|---|
| **[crawl_proxies](https://github.com/duma520/crawl_proxies)** | 代理爬取脚本：从多个网站提取代理 IP，支持验证、去重、保存和挂机模式，适用于爬虫与数据采集场景。 |
| **[DNS_Detector](https://github.com/duma520/DNS_Detector)** | DNS 服务器检测工具：检测全球主流 DNS 服务器的响应速度、可用性和可靠性，帮助选择最优配置。 |
| **[Docker_Image_Puller_dumafu](https://github.com/duma520/Docker_Image_Puller_dumafu)** | Docker 镜像下载工具：支持多架构（amd64/arm）、断点续传、完整性校验与群晖 NAS 专用格式。 |

---

## 🤖 AI & 开发辅助

| 项目 | 用途 |
|---|---|
| **[PCConfigChecker](https://github.com/duma520/PCConfigChecker)** | PC 配置检测工具：评估计算机是否适合人脸识别开发，检测硬件与 AI 框架环境并给出评分建议。 |
| **[AI_ModelTestingApp](https://github.com/duma520/AI_ModelTestingApp)** | 深度学习模型验证与测试工具：图形化界面，支持 YOLO、MobileNet 等模型及 TensorRT、ONNX、OpenVINO 等推理框架。 |

---

## 🧠 关于我的开发方式

GitHub 简介里我写得很直白：

> **“不要问，问就是懒，问就是 AI 做的，问就是不知道。”**

我的角色是**产品经理 + 测试工程师**：定义问题、设计功能、反复实测、迭代文档。代码主要由 AI 生成，我一边用一边改。这种方式让我能把精力集中在“做什么”和“好不好用”上，而不是纠结“怎么写”。

因此你会发现我的项目有一个共同特征：**功能边界清晰，文档比代码更厚**。README 里通常包含从零开始的安装步骤、实测踩过的坑、以及面向 AI 搜索引擎的结构化摘要——目的只有一个：**让你不用问我，也能自己跑起来。**

---

## 🔧 技术栈

- **语言**：Python（主力）、Lua（MAME 插件）
- **界面**：PyQt5 / PySide / Tkinter
- **数据**：SQLite
- **领域**：模拟器工具链、桌面自动化、网络基础设施、AI 开发辅助

---

## 💬 支持 & 联系

- **Issues 优先**：所有技术支持通过各仓库的 GitHub Issues 公开进行，让问题和答案沉淀在公共空间。
- **博客**：[cnblogs.com/duma520](https://www.cnblogs.com/duma520)（早期文章存档）
- **历史别名**：杜玛府 / 杜玛府工作室

---

> **60+ 个仓库，大部分是“有人真的需要”的小工具。**  
> 如果你也在某个具体场景里被一个小问题反复折磨，这里大概率有一个能直接拿走用的东西。
