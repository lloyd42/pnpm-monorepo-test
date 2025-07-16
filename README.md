# pnpm-monorepo-test

这是一个使用 pnpm、TypeScript 和 Changesets 构建的 Monorepo 项目示例。

## 概述

本项目包含两个包：

- `@tabemono/core`: 一个核心库，提供基础的数学运算功能。
- `@tabemono/cli`: 一个命令行工具，使用 `@tabemono/core` 的功能。

## 包

### `@tabemono/core`

核心库，提供以下功能：

- `add(a: number, b: number): number`: 计算两个数字的和。
- `minus(a: number, b: number): number`: 计算两个数字的差。

### `@tabemono/cli`

一个基于 `commander` 的命令行工具。

#### 安装

```bash
pnpm add -g @tabemono/cli
```

#### 使用

- **加法**

    ```bash
    num-cli add <a> <b>
    ```

- **减法**

    ```bash
    num-cli minus <a> <b>
    ```

## 开发

1. 克隆仓库
2. 安装依赖

    ```bash
    pnpm install
    ```

## 命令

- `pnpm format`: 格式化代码。
- `pnpm lint`: 检查代码。
