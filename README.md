<!-- duma520 (杜玛) 是一名 AI 辅助开发者，在 GitHub 维护 60+ 个实用工具仓库，涵盖 MAME 模拟器插件、DSH 插件、桌面效率工具、SQLite 数据库管理、网络基础设施脚本、色彩与图像处理以及 AI 开发辅助工具。 -->
# 杜玛 / duma520

> **产品经理 + 测试工程师，代码交给 AI。**  
> 用最少的精力，把具体、琐碎、真实存在的痛点，变成开箱即用的工具。

---

## 🎮 MAME 模拟器插件

解决街机模拟场景中那些“小到没人做、但真的烦”的问题。

| 项目 | 一句话价值 |
|---|---|
| **[mame_kbd](https://github.com/duma520/mame_kbd)** | MAME 实时键位映射显示插件：画面下方常驻 P1–P4 四列键位表，按键即时高亮，不用反复切菜单查键位。 |
| **[MAME_2P](https://github.com/duma520/MAME_2P)** | MAME 多玩家输入镜像插件 copilot2p：把 1P 的每一次按键实时复制给 2P/3P/4P，单人也能体验多人街机的热闹。 |
| **[mame_autopress](https://github.com/duma520/mame_autopress)** | MAME 自动按键插件：每个玩家一页，4 个方向与每个按键各自独立开关，不用物理按键就持续连发或按住；带按键级总开关与「保存为默认 / 重置本 ROM」。 |

> 三个项目都有**极其详尽的中文文档**，从安装到源码导读、故障排查一应俱全。

---

## 🧩 DSH 插件

给 DeepSeek Harness（DSH）宿主用的插件：装上即扩展界面或能力，不改宿主源码；与普通「AI 工具」不是一类东西。

| 项目 | 一句话价值 |
|---|---|
| **[dsh-composer-butler](https://github.com/duma520/dsh-composer-butler)** | DSH 输入框工具栏的显隐总开关：一个「⋯」按钮列出所有插件挂上去的控件，逐项勾选即可隐藏或显示，只隐藏不卸载，状态自动持久化，随时一键全部恢复。 |
| **[dsh-push-hub](https://github.com/duma520/dsh-push-hub)** | DSH 推送中枢：一个工具把消息推到微信/飞书/钉钉/企业微信/QQ/Telegram/Slack/Discord/Matrix/群晖 Chat/邮件共 12 个通道，自动分块、限流、失败判定；带发文件、收消息、改消息、撤回、表情、流式消息与进度表情，凭据只存本机不入库。 |
| **[dsh-notify-sender](https://github.com/duma520/dsh-notify-sender)** | DSH 通知发送器：把本机已接通的 12 类通道账号汇成一个中文列表，勾几个发几个，只发不收、不建连接、不存凭据；每个账号标注「能不能用 / 为什么不能用」，改动实时保存。 |
| **[dsh-nav-pins](https://github.com/duma520/dsh-nav-pins)** | DSH 侧栏面板：把左侧栏那一列面板图标收成一条 8px 细线，点箭头展开收起；不常用的面板可逐个固定掉，折叠态与固定选择都落盘，重启不丢。 |
| **[dsh-turn-notify](https://github.com/duma520/dsh-turn-notify)** | DSH 回合通知：每轮对话结束（完成/出错/中断/截断，可选超时/无进展/工具失败/关键词/等你回答）自动往「通知发送器」已选好的 IM 账号推一条摘要；Agent 弹提问时列出全部选项并给推荐项打 ⭐（只提醒不代答）。带冷却、静默时段、排除清单，不用再盯着屏幕等结果。 |
| **[dsh-session-manager-patch](https://github.com/duma520/dsh-session-manager-patch)** | DSH 会话管理器上限热修补丁：放开 dsh-session-manager 0.7.8 写死的「批量操作最多 200 项」，装好后可一次勾选全部会话做批量删除、导出、移动，不用再分批点十几次；以补丁形式覆盖，卸载即恢复原样。 |
| **[dsh-tg-archiver](https://github.com/duma520/dsh-tg-archiver)** | DSH 版 Telegram 频道归档工具：把 telegram-channel-archiver 命令行封装成 5 个原生工具（环境自检 / 看下载进度 / 扫频道索引 / 启停下载 / 建归档任务），在对话里直接下整频道的视频与文件，不用记命令行参数、不用一直开着终端。 |

---

## 🀄 棋牌 & 游戏工具

| 项目 | 一句话价值 |
|---|---|
| **[Mahjong_Calculator](https://github.com/duma520/Mahjong_Calculator)** | 国标麻将算番器：81 番种全支持，输入手牌即出番数与听牌，含番表、手机/平板 Web 版与命令行 API。 |
| **[DaxiaSaveEditor](https://github.com/duma520/DaxiaSaveEditor)** | 《大侠狂想曲》存档修改器：免费开源，用来修改单机游戏存档。 |
| **[LingShouSaveEditor](https://github.com/duma520/LingShouSaveEditor)** | 《灵兽江湖》存档修改器：修改的目的是增加乐趣而非剥夺乐趣，合理使用。 |
| **[GamepadDisplay](https://github.com/duma520/GamepadDisplay)** | 手柄状态监视器：把 Xbox / PS / Switch 手柄的每个按键、摇杆坐标、十字键与扳机实时画在界面上，按键可改名、布局可换，支持多套预设方案并自动保存；调键位、排手柄故障、做教程截图时一眼看清手柄到底在报什么。 |

---

## 🖥️ 桌面效率 & 自动化

| 项目 | 一句话价值 |
|---|---|
| **[Mouse_Click_Simulator](https://github.com/duma520/Mouse_Click_Simulator)** | 高级鼠标点击模拟器：模拟鼠标点击、移动和键盘操作，适用于自动化测试、游戏辅助与办公重复任务。 |
| **[MouseSimulatorMove](https://github.com/duma520/MouseSimulatorMove)** | 鼠标抖动模拟器：定时微小幅度移动鼠标并复位，模拟用户活动、防止系统休眠。 |
| **[Program_Launcher](https://github.com/duma520/Program_Launcher)** | 程序启动器：分组管理应用、文档与文件夹，支持快捷搜索与批量操作。 |
| **[SimpleTimer](https://github.com/duma520/SimpleTimer)** | 多功能计时器：正计时、倒计时与预设时间管理，适合工作计时与学习专注。 |
| **[Schedule_Manager](https://github.com/duma520/Schedule_Manager)** | 排班表管理系统：日历 + 列表双视图，适用于医院、工厂、餐厅、零售等排班场景。 |
| **[IntervalTracker](https://github.com/duma520/IntervalTracker)** | 间隔追踪器：记录什么时间做了什么，自动计算两次记录的时间间隔，用间隔洞察规律。 |
| **[KeyForge](https://github.com/duma520/KeyForge)** | 后台按键测试工具：向已最小化或后台运行的窗口发送按键，不干扰当前鼠标键盘操作。 |
| **[Alarm_Clock_App](https://github.com/duma520/Alarm_Clock_App)** | 闹钟、计时器、秒表三合一：支持番茄工作法、渐进式唤醒与冥想引导，并按中国法定节假日自动跳过节假日闹钟；多用户登录、SQLite 存储、一键备份恢复。 |
| **[SpeedMonitor](https://github.com/duma520/SpeedMonitor)** | 任务栏网速监视器：在 Windows 任务栏常驻显示实时上 / 下行速度，可拉出浮动窗与迷你曲线图，按三段阈值变色告警；带开机自启、历史记录与多网卡选择，盯住带宽有没有被偷偷吃掉。 |
| **[System_Monitor](https://github.com/duma520/System_Monitor)** | 硬件监控面板：经 OpenHardwareMonitor / WMI 读取 CPU、GPU 温度、负载与风扇转速，常驻托盘、可置顶、更新间隔可调；取不到传感器时自动转模拟数据方便先调界面。想看机器是不是过热降频时用它。 |
| **[Window_Capture_Plugin](https://github.com/duma520/Window_Capture_Plugin)** | 窗口画面捕获插件：内置 20 种捕获方式（dxcam / mss / GDI / WinRT / UIAutomation 等），把任意前台或后台窗口的画面按帧取出来；附 FastAPI + uvicorn 服务，可被其他程序远程调用取帧，适合做自动化与视觉识别前级。 |
| **[Window_Capture_Tester](https://github.com/duma520/Window_Capture_Tester)** | 窗口捕获方法对比测试台 v3.0：让 DWM / GDI / dxcam / mss 几种截屏方式同时去抓同一个窗口，直接对比成功率、帧率与单帧耗时，帮你选出在这台机器与目标程序上真正稳的那一种。 |
| **[Windows_Update_Pauser](https://github.com/duma520/Windows_Update_Pauser)** | Windows 更新暂停开关：一键暂停或恢复系统更新，界面直接显示「最多还能暂停几天」与「下次更新时间」，不用翻设置页一层层点；演示、考试、跑长任务前临时按住更新用。 |

---

## 💾 数据 & 文档管理

| 项目 | 一句话价值 |
|---|---|
| **[Excel_Manager](https://github.com/duma520/Excel_Manager)** | 电子表格数据管理系统：SQLite 后端 + 图形界面，支持多用户、条码/二维码生成与数据统计。 |
| **[Universal_DB_Editor](https://github.com/duma520/Universal_DB_Editor)** | 通用 SQLite 可视化编辑器：无需编程经验也能查看、编辑和管理数据库文件。 |
| **[Database_Manager](https://github.com/duma520/Database_Manager)** | SQLite 数据库管理器：图形界面完成建表、查询与数据维护，新手和专业人士都能上手。 |
| **[DataRegisterManager](https://github.com/duma520/DataRegisterManager)** | 资料登记管理系统：Python + SQLite + PySide6，单文件部署、开箱即用。 |
| **[Text_Manager](https://github.com/duma520/Text_Manager)** | 高级文本管理工具：分类、标签、全文检索与 Markdown 编辑，SQLite 存储。 |
| **[DirectoryScannerApp](https://github.com/duma520/DirectoryScannerApp)** | 目录扫描管理系统：扫描、组织并展示目录文件结构，支持中文/拼音搜索与批量管理。 |
| **[DirectoryComparison](https://github.com/duma520/DirectoryComparison)** | 目录文件比对工具：快速找出两个文件夹里哪些文件相同、缺失、多余。 |
| **[Hex_Viewer](https://github.com/duma520/Hex_Viewer)** | 多文件十六进制比对工具：并排十六进制视图 + 差异高亮，适合逆向与数字取证。 |
| **[Finance_App](https://github.com/duma520/Finance_App)** | 人民币收支管理系统：记录收入、支出、借款与还款，并对账目做数据分析。 |
| **[MenuManager](https://github.com/duma520/MenuManager)** | 高级点菜管理系统：菜单管理、订单处理、支付结算与数据分析一体，PyQt5 跨平台。 |
| **[Hex_Record_App](https://github.com/duma520/Hex_Record_App)** | 十六进制位置记录本：按行列表格记录每个 Hex 偏移的用途与说明，支持搜索、统计、导入导出与打印；多用户登录（SHA-256）、历史记录与一键备份恢复。逆向、协议分析、存档改写时把「这个地址是什么」整理成可查的笔记。 |
| **[Vision_Recorder](https://github.com/duma520/Vision_Recorder)** | 视力情况登记系统：按用户记录左眼 / 右眼 / 双眼的检查数据，生成曲线图看变化趋势，SQLite 存储、多用户可切换。给孩子或自己长期跟踪视力、每次复查拿上一次结果对比时用。 |

---

## 🌐 网络 & 基础设施

| 项目 | 一句话价值 |
|---|---|
| **[crawl_proxies](https://github.com/duma520/crawl_proxies)** | 代理爬取脚本：从多个网站提取代理 IP，支持验证、去重、保存和挂机模式。 |
| **[DNS_Detector](https://github.com/duma520/DNS_Detector)** | DNS 服务器检测工具：检测全球主流 DNS 服务器的响应速度、可用性和可靠性，帮你选最优配置。 |
| **[Docker_Image_Puller_dumafu](https://github.com/duma520/Docker_Image_Puller_dumafu)** | Docker 镜像下载工具：支持多架构（amd64/arm）、断点续传、完整性校验与群晖 NAS 专用格式。 |
| **[Iperf_GUI](https://github.com/duma520/Iperf_GUI)** | iperf3 图形化工具：完整参数支持、结果可视化、配置保存与历史记录，不用再背命令。 |
| **[Network_Diagnostic_Tool](https://github.com/duma520/Network_Diagnostic_Tool)** | 网络故障诊断工具：集成系统网络诊断命令，图形化执行测试、排查、性能分析与监控。 |
| **[port-scanner](https://github.com/duma520/port-scanner)** | 端口扫描工具：多线程扫描指定主机的开放端口并标注端口作用，结果可保存。 |
| **[Media_Wall](https://github.com/duma520/Media_Wall)** | 家庭局域网媒体海报墙：扫描 NAS 或本地磁盘，按一级子目录自动分分区，生成可拖动海报墙网页；手机/平板/电视扫码即看，支持断点续传、多设备进度同步与回收站。 |
| **[AccessWorker](https://github.com/duma520/AccessWorker)** | 网址访问量模拟器：导入 URL 列表与代理列表，自动爬取并测活代理，多线程轮换访问、可无人值守连跑；带多用户登录、SQLite 记录与备份恢复。用于压测自有站点、验证访问统计与 CDN 命中。 |
| **[BluetoothScanner](https://github.com/duma520/BluetoothScanner)** | 蓝牙设备扫描器：用 bleak 扫描周边 BLE 设备，列出名称、MAC、信号强度 RSSI 与服务 UUID，结果可导出 CSV、支持事件回调与多平台运行。找丢在角落的手环耳机、排查蓝牙设备连不上时用。 |
| **[Check_ble_name_change](https://github.com/duma520/Check_ble_name_change)** | BLE 设备改名检测：持续监听指定的蓝牙设备，一旦广播名称发生变化就记录前后对比与时间戳。用来验证固件改名流程是否生效、确认设备有没有被别人重新配对或篡改广播。命令行运行，依赖 bleak。 |
| **[DHCPDetectorGUI](https://github.com/duma520/DHCPDetectorGUI)** | DHCP / 仿冒 DHCP 服务器检测器：在多张网卡上发探测包，列出所有响应者的 IP、网关、DNS 与响应耗时，超时与重试可调、结果存 JSON。怀疑局域网里有第二台路由器私发地址导致上不了网时用它定位。 |
| **[ONVIFCameraScanner](https://github.com/duma520/ONVIFCameraScanner)** | 网络摄像头全协议扫描器 v6：同时探测 ONVIF、GB28181 与 MJPEG 三类设备，列出 IP、厂商、型号与取流地址，支持 PTZ 云台控制。装监控时批量摸清内网有几台摄像头、分别开在哪个端口用。 |
| **[telegram-channel-archiver](https://github.com/duma520/telegram-channel-archiver)** | Telegram 频道批量归档工具：先把频道扫成可筛选索引，再按文案 / 关键词 / 体积批量下载（分片断点续传、换线路自动重连、重名加时间戳）；附代理池采集与两级测活、一键切换线路、自适应速度看板。 |
| **[UPnPMirror](https://github.com/duma520/UPnPMirror)** | DLNA 投屏快速版：自动发现局域网里的电视与盒子，把本地文件或网络流地址直接推过去播放，省掉中间转码与拖拽。只想「把这段视频扔到客厅电视上」时最短的一条路。 |
| **[UPnPReceiver](https://github.com/duma520/UPnPReceiver)** | DLNA / UPnP 投屏接收端：把电脑变成可被电视和手机投屏的目标设备，内置 HTTP 接收服务器负责接收推送来的媒体并播放。手机想投到电脑屏幕、或临时把电脑当演示屏时用它。 |
| **[Proxy_Manager_Studio](https://github.com/duma520/Proxy_Manager_Studio)** | 代理节点管理控制台：集中管理订阅与节点，内置 Xray / sing-box / mihomo / Hysteria2 / TUIC 等内核，可切换系统代理与 TUN、批量测延迟与下载测速、跑健康检查与自动切换、管理 Telegram 专用代理；带节点分享二维码、配置导入与日志面板。 |
| **[UPnPWindows](https://github.com/duma520/UPnPWindows)** | DLNA 投屏三合一：投屏端、接收端与参数设置装在同一个界面，QtMultimedia 负责播放、内置本地文件服务器、多网卡可选。既能把片子推到电视，也能把电脑当接收屏，家里几台设备互投不用再装三个软件。 |

---

## 🔐 安全 & 系统工具

| 项目 | 一句话价值 |
|---|---|
| **[Password_Cracker_GUI](https://github.com/duma520/Password_Cracker_GUI)** | 7z/ZIP/RAR 压缩包密码恢复工具：字典攻击 + AI 智能生成双模式。 |
| **[Secure_Calculator_Pro](https://github.com/duma520/Secure_Calculator_Pro)** | 安全计算器：支持复杂数学表达式与变量管理，采用安全评估机制防止恶意代码执行。 |
| **[ProcessManager_app](https://github.com/duma520/ProcessManager_app)** | Windows 进程管理工具：查看、管理和控制系统上运行的所有进程。 |
| **[MD5CalculatorApp](https://github.com/duma520/MD5CalculatorApp)** | 多算法哈希计算工具：MD5/SHA1/SHA256/SHA512，支持文本、单文件、多文件与整目录批量计算。 |
| **[Cachefly_Enum](https://github.com/duma520/Cachefly_Enum)** | CacheFly 文件枚举检测工具：从 1MB 到 10TB+ 探测 CDN 测试文件的存在性与响应速度。 |
| **[DeepSeek_Key_Manager](https://github.com/duma520/DeepSeek_Key_Manager)** | DeepSeek API Key 集中管理器：批量登记多个 Key 并逐个查余额，可编辑 .env、自定义列与字段、操作留日志、结果导出。手上一堆 Key 分不清哪个还能用、余额还剩多少时，用它一张表看全。 |
| **[Multi-process_Keystroke_Emulator](https://github.com/duma520/Multi-process_Keystroke_Emulator)** | 多进程按键模拟器：把进程分到「按 A / 无操作 / 按 D」三列，给指定进程持续发按键或手柄信号（vgamepad 虚拟手柄、usb.core 直发 USB、pynput 键鼠），彼此互不干扰；带多用户登录与配置持久化。 |

---

## 🤖 AI & 开发辅助

| 项目 | 一句话价值 |
|---|---|
| **[PCConfigChecker](https://github.com/duma520/PCConfigChecker)** | PC 配置检测工具：评估计算机是否适合人脸识别开发，检测硬件与 AI 框架环境并给出评分建议。 |
| **[AI_HardwareScannerApp](https://github.com/duma520/AI_HardwareScannerApp)** | AI 加速能力检测工具：全面评估硬件对 AI 运算的支持能力与加速潜力。 |
| **[AI_ModelTestingApp](https://github.com/duma520/AI_ModelTestingApp)** | 深度学习模型验证与测试工具：图形化界面，支持 YOLO、MobileNet 等模型与 TensorRT/ONNX/OpenVINO 等推理框架。 |
| **[GPU_Acceleration_Detection_Toolkit](https://github.com/duma520/GPU_Acceleration_Detection_Toolkit)** | GPU 加速检测工具包：检测 CUDA、ROCm、Metal、OpenCL、oneAPI 等可用加速方案。 |
| **[GPU_Test](https://github.com/duma520/GPU_Test)** | 智能检测系统测试套件：验证视频帧处理在不同硬件（CPU/CUDA）、算法与处理模式下的性能和正确性〔本地未找到同名目录〕。 |
| **[gen_ai_model_gui](https://github.com/duma520/gen_ai_model_gui)** | AI 模型生成工具：通过简单配置生成基础 CNN 模型并导出 ONNX，降低建模门槛。 |
| **[real_time_detection_v1](https://github.com/duma520/real_time_detection_v1)** | 实时变化检测系统：实时检测并标记屏幕区域、应用程序窗口或摄像头画面中的动态变化。 |
| **[real_time_detection_v2](https://github.com/duma520/real_time_detection_v2)** | 智能变化检测系统 V2 重制版：适用于安防监控、游戏录制、UI 测试与运动分析。 |
| **[GitHub_Release_Monitor](https://github.com/duma520/GitHub_Release_Monitor)** | GitHub Releases 监控程序：自动检查你关注的仓库是否有新版本发布。 |
| **[vol_connect_workbuddy](https://github.com/duma520/vol_connect_workbuddy)** | 火山软件开发平台（voldev）的 WorkBuddy 多账号中继：把火山 Codex 接到 WorkBuddy，额度用完自动换号、登录过期自动刷新，做 Responses⇄Chat 协议转换，含 25 个上游真实模型与 PySide6 中文控制面板。 |
| **[AccelerationApp](https://github.com/duma520/AccelerationApp)** | GPU / CPU 加速计算框架：矩阵运算与图像处理可走多个后端（OpenCL、多进程 CPU、SIMD），带任务队列、结果缓存与性能监控面板，在界面里直接对比同一算法在不同后端上的耗时。给自研程序挑加速方案时当基准台用。 |
| **[AI_Model_Train](https://github.com/duma520/AI_Model_Train)** | 紧凑型深度学习训练台：在图形界面里配置数据与训练参数、一键启动并实时看进度与指标，不用每次去改命令行脚本。给模型做小规模试跑、验证超参方向时用。tkinter 编写，主程序单文件即可运行。 |
| **[CPUAccelerationDetector](https://github.com/duma520/CPUAccelerationDetector)** | CPU 加速能力检测器：逐项测出这台机器支持哪些指令集（SSE / AVX / NEON / SIMD），以及 numba / Cython / OpenCL 等加速运行时是否可用，结果落 JSON 缓存。给程序选加速路径、判断「为什么这段代码没快起来」时先跑它。 |
| **[CPU_Accelerator](https://github.com/duma520/CPU_Accelerator)** | CPU 加速计算插件框架 v2.2：以插件形式挂载计算任务，内置 numba JIT 与 diskcache 结果缓存、多进程并行、缓存策略与任务优先级配置。把重计算函数塞进插件就能享受加速与缓存，不必自己重写调度层。 |
| **[DeepSeek_Balance_Monitor](https://github.com/duma520/DeepSeek_Balance_Monitor)** | DeepSeek 余额监视器：定时查询账户余额，余额变化时弹窗或托盘通知，记录写入 SQLite 并支持导出 CSV；Key 从 .env 读取不外泄。几个项目一起烧额度时，用它盯住哪天会突然没钱。 |
| **[FaceRecognitionSystem](https://github.com/duma520/FaceRecognitionSystem)** | 人脸数据库编辑器与识别台：维护公开人脸数据集、增删改样本并建索引，支持屏幕框选识别人脸、模型在线下载、代理设置、相似度阈值可调与调试 / 性能双模式。做本地人脸检索、批量整理照片人物时用。 |
| **[GPU_Accelerator](https://github.com/duma520/GPU_Accelerator)** | GPU 加速插件框架 v1.0.5：按插件加载与卸载计算任务，可选 FP32 / FP16 / TF32 / MIXED 四种精度模式，内置性能测试与显存监控。想在精度与速度之间找平衡、又不想重写调度代码时用它兜底。 |

---

## 🎨 颜色 & 图像处理

| 项目 | 一句话价值 |
|---|---|
| **[Color_Name_Finder](https://github.com/duma520/Color_Name_Finder)** | 颜色识别工具：集成 12 大颜色标准体系、20,000+ 预定义颜色，支持屏幕取色与多标准名称匹配。 |
| **[Color_Database_Builder_GUI](https://github.com/duma520/Color_Database_Builder_GUI)** | RGB 颜色数据库管理工具：结构化建库、CSV/JSON 批量导入导出与可视化预览〔本地未找到同名目录〕。 |
| **[Color_Plugin](https://github.com/duma520/Color_Plugin)** | 颜色查询插件 ColorLookup：按 RGB 查颜色名称、管理自定义色库、查找相似色与 RGB/HEX 转换〔本地未找到同名目录〕。 |
| **[Color_Namer_App_v2](https://github.com/duma520/Color_Namer_App_v2)** | HSL/RGB 颜色命名工具：把颜色数值转换成直观的中文名称，方便沟通和记录。 |
| **[Color_Space_Generator_App](https://github.com/duma520/Color_Space_Generator_App)** | 多色彩空间数值生成器：RGB/HSL/CMYK/YUV/Lab/HEX 六种空间，可导出 CSV/JSON/SQLite。 |
| **[Generate_Macaron_Colors](https://github.com/duma520/Generate_Macaron_Colors)** | 马卡龙色系生成器：基于 HSV 精确控制饱和度与亮度，生成柔和甜美的配色系列。 |
| **[Image_To_Icon_Converter](https://github.com/duma520/Image_To_Icon_Converter)** | 图片转 ICO 图标转换器：PNG/JPG/BMP 批量转 ICO，支持多尺寸选择与保持宽高比。 |
| **[AdvancedIconGenerator](https://github.com/duma520/AdvancedIconGenerator)** | 高级图标生成工具：把图片、文字、SVG、Emoji 与图表转成专业图标，支持多格式输出。 |
| **[Image_Canvas_Stitcher](https://github.com/duma520/Image_Canvas_Stitcher)** | 图片自由拼接工具：在无限画布上拖放多张图片，调整位置/大小/层次/透明度后导出成一张大图。 |
| **[ImageManagerApp](https://github.com/duma520/ImageManagerApp)** | 图片管理系统：高效组织、管理和检索图片资源，面向家庭、摄影与设计场景。 |
| **[ScreenToGIF](https://github.com/duma520/ScreenToGIF)** | 屏幕录制转 GIF 工具：捕获指定屏幕区域，多线程处理帧，支持实时预览与帧编辑。 |
| **[QRCodeDecoder](https://github.com/duma520/QRCodeDecoder)** | 二维码/条形码解码工具：跨平台图形界面，一键解码各类二维码与条形码。 |
| **[AV_Wall](https://github.com/duma520/AV_Wall)** | 影音海报墙扫描器：扫描本地或 NAS 上的媒体目录，识别影片与剧集并生成可浏览的海报墙索引，按一级子目录自动分区。片子越存越多、文件名越来越乱时，用它把库重新理成能一眼挑片的样子。 |
| **[Color_Generator_App](https://github.com/duma520/Color_Generator_App)** | 高级色彩生成器：按色系分类与颜色类型批量生成配色，可指定生成数量，结果一键复制色值或保存成清单。做 UI 配色、挑主题色、需要一次拿到一整组协调颜色时用。PyQt5 编写。 |
| **[Color_Namer_App_v1](https://github.com/duma520/Color_Namer_App_v1)** | RGB 转中文颜色名：输入 RGB 数值，在颜色库里按 LAB 色彩空间计算距离，给出最接近的中文颜色名与匹配度。写文案、做设计说明、给颜色起名字时，比对着色卡猜要准得多。tkinter 编写，依赖 numpy。 |
| **[DeMosaic](https://github.com/duma520/DeMosaic)** | AI 去马赛克与图像增强：载入模型时自动下载权重，可按进程选择用 CPU 还是 GPU，把低清、压缩痕迹重、细节糊掉的图片放大修复。批量处理老照片、截图与素材图时用。基于 torch，tkinter 界面。 |
| **[Floor_Plan_Editor](https://github.com/duma520/Floor_Plan_Editor)** | 房屋平面图绘制器 v2.1：用房间、门窗、顶点三级编辑画出户型，网格吸附对齐、实时自动保存、历史记录可回退。量完房想马上把尺寸落成一张能改的图、又不想装 CAD 时用它。PySide6 编写。 |
| **[Heatmap_Analyzer](https://github.com/duma520/Heatmap_Analyzer)** | 进程画面热力图分析器：针对指定进程窗口按多种方式捕获画面，把像素变化累积成热力图，热力图类型、透明度与残影消失时间可调。想知道某个程序界面上哪块区域一直在动、操作热区在哪时用它。 |
| **[Image_Diff_Tool](https://github.com/duma520/Image_Diff_Tool)** | 图像差异比较器：单图模式看细节、双图模式逐像素比出差异并高亮，支持直接粘贴图片、结果另存。改版前后对截图、确认渲染或压缩有没有真的改动画面时用。基于 OpenCV + PIL，PyQt5 界面。 |

---

## 🧰 其他小工具

| 项目 | 一句话价值 |
|---|---|
| **[MSU2_MINI_V2](https://github.com/duma520/MSU2_MINI_V2)** | USB 副屏小工具：0.96 寸 USB 直插式小屏的桌面伴侣，12 种显示模式 + 防烧屏保护 + MiniMark 自由编程。 |
| **[Express_Query](https://github.com/duma520/Express_Query)** | 快递查询系统：把所有平台的快递单号集中管理，一个界面看清全程，含智能分类与时效预估。 |
| **[Phone_Number_Manager](https://github.com/duma520/Phone_Number_Manager)** | 电话号码管理系统：自动识别号码归属地与运营商、分析号码详情，支持特殊服务号码查询。 |
| **[Justice_Epstein_DataSet_DownloaderGUI](https://github.com/duma520/Justice_Epstein_DataSet_DownloaderGUI)** | 美国司法部 Epstein 案件文件批量下载工具：DataSet9~11 的 PDF 一键抓取。 |
| **[ShakeWindow](https://github.com/duma520/ShakeWindow)** | 窗口抖动效果演示程序：直观演示 Windows 窗口抖动动画的实现效果。 |
| **[Test_Taskbar_Progress](https://github.com/duma520/Test_Taskbar_Progress)** | Windows 任务栏进度条测试程序：演示在任务栏直接显示操作进度的效果。 |
| **[DeepSeekFishPet](https://github.com/duma520/DeepSeekFishPet)** | DeepSeek 肥鱼娘桌宠：一只住在 Windows 桌面上的小鲸鱼拟人少女。 |
| **[Readme](https://github.com/duma520/Readme)** | 个人杂记与资料汇总仓库：把有用的东西集中起来，方便自己查阅〔本地未找到同名目录〕。 |
| **[Auto_Adjust_Thread](https://github.com/duma520/Auto_Adjust_Thread)** | 窗口画面色彩自动还原：捕获指定窗口画面后按 RGB 平衡、亮度、对比度、饱和度自动拉回真实色彩，调好的参数可存成预设（SQLite）。截图偏色、录屏发灰、不同机器画面不一致时用它统一。 |
| **[ICCardAnalyzerApp](https://github.com/duma520/ICCardAnalyzerApp)** | IC 卡数据分析系统：读入 IC 卡 dump 文件，做格式校验与特征提取（信息熵、滚动码预测、密钥结构分析），把扇区与密钥整理成可读报告并导出 HTML。分析门禁卡、公交卡这类 M1 卡的数据结构时用。 |
| **[NFCScanner](https://github.com/duma520/NFCScanner)** | NTAG 读写管理器 v4.0：对 NTAG216 标签做读取、写入、格式化与加密（Fernet），支持 CSV 批量导入导出与串口设备热刷新。批量制作 NFC 标签、给标签内容加一层加密保护时用。PyQt5 编写。 |
| **[PAC_Studio](https://github.com/duma520/PAC_Studio)** | PAC 分流工作室：生成、编译、应用与一键还原 PAC 代理自动配置脚本，支持 `--apply-pac --silent` 静默应用与 `--restore` 回滚。要按域名清单做代理分流、又不想手动改系统设置时用它。 |
| **[Process_Selection_Dialog](https://github.com/duma520/Process_Selection_Dialog)** | 进程画面轨迹记录器 v3.11：框选捕获区域、同时盯多个进程的画面，把目标移动轨迹记下来并做轨迹分析、热力图、速度统计与路径预测（scipy / sklearn）。做操作路径复盘、自动化取点、界面行为研究时用。 |
| **[RGB_Generator_App](https://github.com/duma520/RGB_Generator_App)** | 多色彩空间数值生成器 v3.0：在 RGB / HSL / HSV / CMYK / YUV / Lab / HEX 之间互相换算并批量生成数值，结果可导出 CSV。做调色、写样式变量、给程序批量造测试颜色时用。tkinter 编写。 |
| **[M3U_Live_Editor](https://github.com/duma520/M3U_Live_Editor)** | M3U 直播源编辑器：台标自动匹配、批量增删改、两份列表按编号并排对比，可一键测速筛掉失效频道、扫描频道 ID；内置播放内核与流中继，改完当场预览。整理 IPTV 源、维护自家直播清单时用。PySide6 编写。 |
| **[MapLocator](https://github.com/duma520/MapLocator)** | 地址定位与街景查看器：输入地址或坐标，在国内外多个地图服务之间切换定位，直接调出街景；带搜索历史与数据库备份恢复。核对门店地址、确认某个位置到底长什么样时用。PySide6 编写。 |
| **[Visit_Website](https://github.com/duma520/Visit_Website)** | 命令行批量访问器：从文本读入 URL 列表与代理列表，多线程轮换 UA 与代理逐个访问，可用代理自动回写文件、日志可查。压测自己的站点、验证访问日志与统计是否正常时用。 |
| **[GUI_TEST](https://github.com/duma520/GUI_TEST)** | 智能检测系统测试套件：把加速后端（CPU / CUDA）、图像算法（原始差分 / 高斯模糊）、帧处理器（单线程 / 多线程）三大模块的 18 个用例做成界面，点一下逐项跑完并显示状态与耗时。改完底层算法先跑它，确认没把别的路径跑坏。 |
| **[XMLPrekit](https://github.com/duma520/XMLPrekit)** | XML 数据编辑与预处理工具：表格化逐行编辑 XML 节点，可按模板批量添加条目、CSV 双向导入导出、条件筛选；多用户与一键备份恢复。手工改几百条 XML、又怕改坏结构时用它。PySide6 编写。 |

---

> 带〔本地未找到同名目录〕标注的条目，表示该仓库在本地 `G:\Python_Code` 下没有同名项目目录（可能归档在别处或仅线上维护）。

---

## 🎵 音频 & 媒体处理

| 项目 | 一句话价值 |
| --- | --- |
| **[Advanced_Music_Converter](https://github.com/duma520/Advanced_Music_Converter)** | 简谱转音乐工具：识别简谱里的音符与和弦，生成 MIDI 文件并带钢琴卷帘可视化预览，可边听边改后保存。手里有简谱想听成声音、或把纸面旋律变成可编辑 MIDI 时用。PySide6 编写。 |
| **[Audio2Score](https://github.com/duma520/Audio2Score)** | 音频转简谱工具 v2.2：用 librosa 分析音频的音高与节奏，把听到的旋律反向写成简谱，支持单文件与整个文件夹批处理并导出结果。想把一段旋律记下来、或把录音整理成谱面时用。PySide6 编写。 |
| **[AudioToTextConverter](https://github.com/duma520/AudioToTextConverter)** | 音频转文字工具：基于 FunASR 本地识别，选好模型路径后把音频转成文字并实时显示进度，结果可导出。会议录音、访谈素材转文字稿时用；识别在本机跑，不上传云端。PyQt5 编写。 |
| **[Audio_Editor](https://github.com/duma520/Audio_Editor)** | 音频编辑器：在波形图上拖选片段后做裁剪、淡入淡出、音量与速度调整、高低通滤波与响度标准化，改完直接导出。剪铃声、处理录音毛刺、批量修音量时用。PySide6 编写。 |
| **[Process_Audio_Capturer](https://github.com/duma520/Process_Audio_Capturer)** | 进程音频转字幕工具：只抓指定进程输出的声音，用 vosk 离线识别实时转成字幕，音频设备与采样率可选。想把某个软件或播放器里的语音变成文字、又不希望录进整机声音时用。PyQt5 编写。 |

## 🧠 关于我的开发方式

GitHub 简介里我写得很直白：

> **“不要问，问就是懒，问就是 AI 做的，问就是不知道。”**

我的角色是**产品经理 + 测试工程师**：定义问题、设计功能、反复实测、迭代文档。代码主要由 AI 生成，我一边用一边改。这种方式让我能把精力集中在“做什么”和“好不好用”上，而不是纠结“怎么写”。

因此你会发现我的项目有一个共同特征：**功能边界清晰，文档比代码更厚**。README 里通常包含从零开始的安装步骤、实测踩过的坑、以及面向 AI 搜索引擎的结构化摘要——目的只有一个：**让你不用问我，也能自己跑起来。**

---

## 🔧 技术栈

- **语言**：Python（主力）、Lua（MAME 插件）
- **界面**：PyQt5 / PySide6 / Tkinter
- **数据**：SQLite
- **领域**：模拟器工具链、桌面自动化、网络基础设施、数据管理、色彩与图像、AI 开发辅助

---

## 💬 支持 & 联系

- **Issues 优先**：所有技术支持通过各仓库的 GitHub Issues 公开进行，让问题和答案沉淀在公共空间。
- **博客**：[cnblogs.com/dumafu](https://www.cnblogs.com/dumafu)（早期文章存档）
- **历史别名**：杜玛府 / 杜玛府工作室

---

> **60+ 个仓库，大部分是“有人真的需要”的小工具。**  
> 如果你也在某个具体场景里被一个小问题反复折磨，这里大概率有一个能直接拿走用的东西。

## 许可

本项目采用 **GNU Affero General Public License v3.0（AGPL-3.0）** 发布。

- 完整许可证条文见仓库根目录 [LICENSE](LICENSE)。
- 你可以自由使用、修改、分发，包括用于商业用途，无需另行获得授权。
- 若你修改后分发，或以网络服务方式提供本软件，必须按 AGPL-3.0 公开相应源代码。
- 本仓库自 2026-11-23 起改用 AGPL-3.0；此前已按 MIT / BSD-3-Clause 发布的版本，其接收者依原许可证获得的授权继续有效。
