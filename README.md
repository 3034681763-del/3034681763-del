# Hi, I'm Lyu Ziheng

哈尔滨工业大学（威海）本科生，关注机器人、嵌入式视觉、智能控制与大模型在真实机器人系统中的应用。

我目前主要在开发一个运行于 Jetson Orin Nano 的智慧农场机器人系统。这个项目把巡线、目标检测、OCR、大模型结构化解析、串口通信、底盘控制和机械臂动作组织在同一套任务状态机中，让机器人能够在实际场景里完成连续任务。

## About Me

- 机器人与嵌入式 AI 方向学习者
- 主要使用 Python / C / OpenCV / Paddle Lite / Linux / Git
- 熟悉 Jetson 端模型部署、摄像头调试、串口通信和任务流程调度
- 正在探索 OCR、多模态大模型和传统控制逻辑结合的机器人决策链路

## Current Focus

### Smart Farm Robot

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

## Public Repositories

- [`smartcar_baidu_21`](https://github.com/3034681763-del/smartcar_baidu_21): Python 机器人主项目，包含巡线、目标检测、OCR、大模型调用、串口通信和任务状态机。
- [`Vision_Smartrobot`](https://github.com/3034681763-del/Vision_Smartrobot): C 语言相关的视觉/智能机器人项目仓库。
- [`Vehicle_Warning`](https://github.com/3034681763-del/Vehicle_Warning): Lua 相关仓库，用于车辆/预警方向的探索。
- [`vehicle_wbt_21th_lane`](https://github.com/3034681763-del/vehicle_wbt_21th_lane): 早期车辆巡线相关仓库。

## Technical Interests

- Robotics software architecture
- Computer vision and object detection
- OCR and multimodal understanding
- Jetson edge deployment
- Embedded Linux development
- UART communication and real-time control
- Robotic-arm calibration and action-group design
- AI workflows for real-world robots

## Tech Stack

```text
Python / C / OpenCV / Paddle Lite / Linux / Git
Jetson Orin Nano / UART / OCR / AI Studio API
```

## What I Am Working On

- Building a stable task-state system for autonomous robot missions
- Improving camera, detection, OCR and chassis test tools
- Designing structured prompts for order parsing and visual reasoning
- Calibrating robotic-arm action groups for pickup, placement and harvesting
- Making the whole robot pipeline easier to deploy, debug and reproduce on Jetson

## Contact

- GitHub: [`3034681763-del`](https://github.com/3034681763-del)
- Email: `3034681763@qq.com`
- Location: 哈尔滨工业大学（威海）

---

I enjoy turning algorithms into machines that can actually move, observe, decide and finish tasks in the physical world.
