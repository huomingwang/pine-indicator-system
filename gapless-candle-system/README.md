# Gapless Candle System

一个用于消除股票跳空视觉干扰的 Pine Script K线显示系统。

## 核心思想

传统股票K线存在跳空：

- 高开
- 低开
- 缺口

会影响：

- K线结构观察
- 推动力分析
- 连续趋势判断

本系统通过：

当前K线开盘价 = 上一根K线收盘价

实现：

- 去跳空
- K线连续化
- 更容易观察真实推动方向

## 功能

- Gapless K线显示
- 自定义回溯周期
- 保留真实 high / low / close
- 视觉连续化

## 文件结构

- indicators/
  Pine 指标源码

- docs/
  指标逻辑说明

- README.md
  项目介绍
