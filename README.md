# robomaster_study

RoboMaster 算法组学习区（中国科大 RoboWalker 战队预备队员）。

对标任务：[算法组新生提前批大作业 · Camera-IMU 联合标定](https://git.lug.ustc.edu.cn/water5/rw-algorithm-train-2027/-/blob/main/task/calibration/)

## 目录

| 文件 | 说明 |
|---|---|
| [Camera-IMU联合标定_新手教程.md](Camera-IMU联合标定_新手教程.md) | **主文档**。任务书逐条翻译、硬件实测状态、核心概念速成、C0→C4 分阶段路线图、12 个实测坑、答辩 8 问 |
| [Camera-IMU联合标定_新手教程.md#9-答辩速查8-个必答问题](Camera-IMU联合标定_新手教程.md) | 验收前自测 |

## 硬件与代码

工作区（实现代码、采集工具、协议解析）：
<https://github.com/AAAtrucklrx/robowalker->

其中与学习直接相关的：

- `calib/imu_h7.py` —— H7 IMU 二进制协议解析（含完整证据链，可当"怎么逆向一个协议"的范例）
- `tools/capture_h7.py` —— 相机 + IMU 数据集采集
- `doc/H7_IMU协议.md` —— 协议结论与验证方法
- `doc/相机取流诊断.md` —— 海康 U3V 工业相机故障排查全记录

## 一句话总结这道题

> 考点不是"会不会用 OpenCV"，而是**能不能对自己产出的每一个数字负责**。
