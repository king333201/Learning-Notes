# Learning Notes

个人嵌入式开发学习笔记，系统整理从底层硬件到应用层协议的知识体系。

## 目录

| 文件 | 内容 |
|------|------|
| [C语言.mdx](./C语言.mdx) | 指针、函数指针、指针函数、const 修饰规则 |
| [FREERTOS.mdx](./FREERTOS.mdx) | 任务状态、抢占式调度、时间片轮转 |
| [STM32F103C8T6.mdx](./STM32F103C8T6.mdx) | 内存结构、变量存储、启动流程、时钟树、GPIO、NVIC、DMA |
| [硬件.mdx](./硬件.mdx) | 二极管/三极管/MOS管、电容滤波、GPIO中断配置 |
| [通讯协议.mdx](./通讯协议.mdx) | ADC、IIC、SPI、UART、CAN、MODBUS |

## 知识体系

```
C语言基础 ──→ MCU体系结构 ──→ 外设驱动 ──→ RTOS
    │                           │
    └──→ 硬件基础 ──→ 通讯协议 ──┘
```

## 协议覆盖

- **IIC**：同步半双工、开漏+上拉、起始/停止条件、ACK/NACK
- **SPI**：四线全双工、推挽输出、CPOL/CPHA 四种模式
- **UART**：异步全双工、TTL/RS232/RS485、DMA+IDLE 不定长接收
- **CAN**：差分信号、多主仲裁、帧结构、过滤器、CAN FD
- **MODBUS**：RTU/ASCII/TCP、功能码、CRC16、异常处理

## 许可证

MIT License