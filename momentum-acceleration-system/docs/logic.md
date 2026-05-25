# Acceleration Sensitive Logic

## powerBase

价格实体和上下影线组合后的基础动能。

用于衡量单根K线本身的推动质量。

## power

powerBase × adjustedVolume / open

代表成交量参与后的真实推动力度。

## powerSma

power 的 9 周期均线。

用于判断当前动力是否明显高于平均水平。

## isBullishAccelerate

阳线加速。

条件：

- power > powerSma × 2
- adjustedVolume >= volumeSma × 1.2
- 当前K线是阳线

## isBearishAccelerate

阴线加速。

条件：

- power > powerSma × 2 ×1.2
- 当前K线是阴线

## Core Philosophy

这个系统不是单纯看涨跌幅。

而是结合：

- 实体长度
- 上下影线
- 成交量
- 平均动能

判断当前K线是否出现加速推动。
