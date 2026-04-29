# Hi, I'm Lyu Ziheng

中文 | [English](#english)

## 中文

哈尔滨工业大学（威海）本科生，关注机器人、嵌入式视觉、智能控制与大模型在真实机器人系统中的应用。

我目前主要在开发一个运行于 Jetson Orin Nano 的智慧农场机器人系统。这个项目把巡线、目标检测、OCR、大模型结构化解析、串口通信、底盘控制和机械臂动作组织在同一套任务状态机中，让机器人能够在实际场景里完成连续任务。

### 关于我

- 机器人与嵌入式 AI 方向学习者
- 主要使用 Python / C / OpenCV / Paddle Lite / Linux / Git
- 熟悉 Jetson 端模型部署、摄像头调试、串口通信和任务流程调度
- 正在探索 OCR、多模态大模型和传统控制逻辑结合的机器人决策链路

### 当前关注

我的主要项目是 [`smartcar_baidu_21`](https://github.com/3034681763-del/smartcar_baidu_21)，一个面向农场场景的自主机器人代码仓库。

项目能力包括：

- 双摄像头输入：巡线摄像头与任务摄像头
- Paddle Lite 巡线模型推理
- 目标检测模型识别作物、货物、货架、仓库、订单机、配送点等目标
- OCR 识别订单和楼宇姓名文本
- 大模型 API 输出结构化 JSON 结果，用于任务决策
- UART 串口与底盘、机械臂下位机通信
- 基于 `world_y`、航向角和检测结果的任务状态机
- 机械臂动作组标定、取货、放置、采摘和归纳流程

这个项目让我更关注一个问题：如何让 AI 模型真正嵌入机器人闭环，而不是只停留在离线识别结果上。

### 公开仓库

- [`smartcar_baidu_21`](https://github.com/3034681763-del/smartcar_baidu_21): Python 机器人主项目，包含巡线、目标检测、OCR、大模型调用、串口通信和任务状态机。
- [`Vision_Smartrobot`](https://github.com/3034681763-del/Vision_Smartrobot): C 语言相关的视觉/智能机器人项目仓库。
- [`Vehicle_Warning`](https://github.com/3034681763-del/Vehicle_Warning): Lua 相关仓库，用于车辆/预警方向的探索。
- [`vehicle_wbt_21th_lane`](https://github.com/3034681763-del/vehicle_wbt_21th_lane): 早期车辆巡线相关仓库。

### 技术方向

- 机器人软件架构
- 计算机视觉与目标检测
- OCR 与多模态理解
- Jetson 边缘端部署
- 嵌入式 Linux 开发
- UART 通信与实时控制
- 机械臂标定与动作组设计
- 面向真实机器人的 AI 工作流

### 技术栈

```text
Python / C / OpenCV / Paddle Lite / Linux / Git
Jetson Orin Nano / UART / OCR / AI Studio API
```

### 正在做的事

- 构建稳定的机器人任务状态机
- 完善摄像头、检测、OCR 和底盘测试工具
- 设计用于订单解析和视觉推理的结构化 Prompt
- 标定机械臂取货、放置、采摘等动作组
- 让完整机器人流程更容易在 Jetson 上部署、调试和复现

### 联系方式

- GitHub: [`3034681763-del`](https://github.com/3034681763-del)
- Email: `3034681763@qq.com`
- Location: 哈尔滨工业大学（威海）

---

## English

[中文](#中文) | English

I am an undergraduate student at Harbin Institute of Technology, Weihai, interested in robotics, embedded vision, intelligent control, and the use of large language models in real-world robotic systems.

I am currently building a Jetson Orin Nano based smart farm robot. The system connects lane following, object detection, OCR, structured LLM reasoning, serial communication, chassis control, and robotic-arm actions through one task-state pipeline, enabling the robot to complete continuous missions in physical environments.

### About Me

- Robotics and embedded AI learner
- Mainly working with Python, C, OpenCV, Paddle Lite, Linux, and Git
- Familiar with Jetson model deployment, camera debugging, UART communication, and task scheduling
- Exploring how OCR, multimodal large models, and traditional control logic can work together in robotic decision-making

### Current Focus

My main project is [`smartcar_baidu_21`](https://github.com/3034681763-del/smartcar_baidu_21), an autonomous robot codebase for farm-like scenarios.

Core capabilities include:

- Dual-camera input for lane following and task perception
- Paddle Lite inference for lane following
- Object detection for crops, goods, shelves, warehouses, order machines, and delivery points
- OCR recognition for order and delivery text
- Large-model API calls that return structured JSON for task decisions
- UART communication with lower-level chassis and robotic-arm controllers
- Task-state scheduling based on `world_y`, heading angle, and detection results
- Robotic-arm action-group calibration for pickup, placement, harvesting, and sorting

This project has made me care more about one practical question: how to embed AI models into a closed-loop robot system, rather than leaving them as offline recognition tools.

### Public Repositories

- [`smartcar_baidu_21`](https://github.com/3034681763-del/smartcar_baidu_21): A Python robotics project with lane following, object detection, OCR, LLM calls, UART communication, and task-state scheduling.
- [`Vision_Smartrobot`](https://github.com/3034681763-del/Vision_Smartrobot): A C-based repository related to vision and smart robotics.
- [`Vehicle_Warning`](https://github.com/3034681763-del/Vehicle_Warning): A Lua-related repository for vehicle warning exploration.
- [`vehicle_wbt_21th_lane`](https://github.com/3034681763-del/vehicle_wbt_21th_lane): An early repository related to vehicle lane following.

### Technical Interests

- Robotics software architecture
- Computer vision and object detection
- OCR and multimodal understanding
- Jetson edge deployment
- Embedded Linux development
- UART communication and real-time control
- Robotic-arm calibration and action-group design
- AI workflows for real-world robots

### Tech Stack

```text
Python / C / OpenCV / Paddle Lite / Linux / Git
Jetson Orin Nano / UART / OCR / AI Studio API
```

### What I Am Working On

- Building a stable task-state system for autonomous robot missions
- Improving camera, detection, OCR, and chassis test tools
- Designing structured prompts for order parsing and visual reasoning
- Calibrating robotic-arm action groups for pickup, placement, and harvesting
- Making the whole robot pipeline easier to deploy, debug, and reproduce on Jetson

### Contact

- GitHub: [`3034681763-del`](https://github.com/3034681763-del)
- Email: `3034681763@qq.com`
- Location: Harbin Institute of Technology, Weihai

---

I enjoy turning algorithms into machines that can actually move, observe, decide, and finish tasks in the physical world.
