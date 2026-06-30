# chplus-game-sudoku — 数独

中文编程语言 **CH+** 的游戏示例。中级。9x9 数独,填数字使每行每列每宫不重复。

> 配套工具链:[chplus-toolchain](https://github.com/k4m7v2pz/chplus-toolchain)

## 安装

先装 CH+ 工具链(需要系统有 `g++` 或 `clang++`):

```bash
git clone git@github.com:k4m7v2pz/chplus-toolchain.git
cd chplus-toolchain/cli
cargo install --path .
```

装好后 `chplus` 命令即可用。

## 运行本游戏

```bash
git clone git@github.com:k4m7v2pz/chplus-game-sudoku.git
cd chplus-game-sudoku
chplus run
```

按提示输入即可。

## 项目结构

```
chplus-game-sudoku/
├── 主函数.ch       游戏源码
├── chplus.toml     项目配置
└── README.md       本文件
```

## 命令速查

```bash
chplus run           # 运行游戏
chplus check         # 只检查不运行
chplus fmt           # 格式化代码
chplus lint          # 静态分析
chplus build         # 编译为 .chex
chplus clean         # 清理产物
```

## 学习要点

这是 CH+ 的入门示例,你能从源码里学到:

- `定义(空类型) 主函数()` — 函数定义
- `控制台输出()` / `控制台输入()` — 输入输出
- `如果 / 否则如果 / 否则` — 条件
- `对于 / 当` — 循环
- `定义(整型) / 定义(字符串)` — 变量

打开 `主函数.ch` 直接读,中文关键字,应该能看懂。

## 立场

本项目反对收费中文编程(易语言、火山等),坚持开源、免费、跨平台。
详见 [工具链立场声明](https://github.com/k4m7v2pz/chplus-toolchain/blob/dev/STATEMENT.md)。

## 许可证

AGPL-3.0 + Commons Clause 1.0,与 CH+ 官方一致。
