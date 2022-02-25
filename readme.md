# koishi-plugin-brainfuck

[![npm](https://img.shields.io/npm/v/koishi-plugin-brainfuck?style=flat-square)](https://www.npmjs.com/package/koishi-plugin-brainfuck)

在 Koishi 中编写并运行 [BrainFuck](http://www.muppetlabs.com/~breadbox/bf) 代码。

## 配置项

### cellSize

- 类型: `number`
- 默认值: `8`

每个单元占用的比特数。

### memorySize

- 类型: `number`
- 默认值: `1024`

允许的最大单元数目。如果超出这个数目将会抛出错误：max memory exceed。

### maxSteps

- 类型: `number`
- 默认值: `16384`

允许的最大步数。如果超出这个数目将会抛出错误：max step exceeded。

## 指令：brainfuck

- 基本语法：`brainfuck <code> -- <input>`
