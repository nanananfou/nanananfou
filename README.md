<div align="center">

# nanananfou

**嵌入式系统 · Qt 桌面应用 · 微信小程序**  
**Embedded systems · Qt desktop apps · WeChat Mini Programs**

[中文介绍](#中文) · [English profile](#english)

</div>

---

## 中文

我关注软硬件系统如何从原型走到可复现、可交接的工程：从传感器数据采集、固件状态机和串口通信，到桌面控制界面、诊断日志与验收文档。

### 技术方向

- **嵌入式控制** — STM32、ESP32、C、MicroPython；外设接口、通信协议与控制状态机。
- **桌面工具** — Qt、C++、CMake；任务编排、设备配置与故障诊断。
- **微信小程序** — 原生页面开发与多页交互，具体实践见下文。
- **边缘视觉** — K230、CanMV；图像观测与串口联动。
- **物联网与设备通信** — 串口、蓝牙与 MQTT；设备接入、消息交换及运行状态诊断。
- **工程验证** — 独立构建、分层测试、硬件验收与交接文档。

### 微信小程序开发

- **页面与样式：** 使用 WXML、WXSS 和 JavaScript 组织页面结构、视觉样式、事件与界面状态。
- **交互流程：** 将业务步骤拆成可导航的页面，处理表单输入、校验、操作反馈和页面间的数据传递。
- **联调与检查：** 在微信开发者工具中预览和调试，检查接口请求、数据回填及异常时的界面提示。

> **工程习惯：** 先记录现象，再定位故障；把软件测试结论与硬件实测结果分开记录。

---

## English

I work on turning hardware–software prototypes into systems that others can reproduce and maintain, from sensor interfaces, firmware state machines, and serial protocols to desktop controls, diagnostic logs, and acceptance documentation.

### Technical focus

- **Embedded control** — STM32, ESP32, C, and MicroPython; peripheral interfaces, protocols, and state machines.
- **Desktop tooling** — Qt, C++, and CMake; task orchestration, device configuration, and diagnostics.
- **WeChat Mini Programs** — Native page development and multi-page interactions; see the breakdown below.
- **Edge vision** — K230 and CanMV; visual observations and serial integration.
- **IoT and device communication** — Serial, Bluetooth, and MQTT; device integration, messaging, and status diagnostics.
- **Engineering verification** — Independent builds, layered tests, hardware acceptance, and handover documentation.

### WeChat Mini Program development

- **Pages and styling:** Use WXML, WXSS, and JavaScript to structure pages and manage styling, events, and UI state.
- **Interaction flows:** Break workflows into navigable screens, with form input, validation, feedback, and data passed between pages.
- **Integration and checks:** Preview and debug in WeChat DevTools; inspect API requests, how responses populate the UI, and error feedback.

> **Engineering practice:** Record the symptom before changing the system, and distinguish software test results from observations on hardware.
