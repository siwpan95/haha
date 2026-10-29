> 📦 **已归档（Archived — 仅作参考）**
> 本仓库已收入归档仓 **dev-toolkit**（代码与完整 git 历史一并迁入，原仓冻结不再开发）。
> 历史分支见归档仓的 `archive/haha` 分支；活跃维护请前往 **dev-toolkit**。
> _This repo is archived into dev-toolkit; development continues there. Do not commit here._

# haha（MVC 消息应用）

一款 tkinter MVC 架构的演示应用（消息显示）。

## 语言 / 类型
- Python / tkinter 图形界面演示（MVC 架构）

## 目录要点
- `main.py` —— 装配入口（Model → View → Controller）
- `app/` —— model、view、controller 三层
- `helloworld/` —— 76 种语言的 Hello, World! 源文件（附属演示模块，**保持零依赖、不被任何框架浸染**）
- `helloworld-cordis/` —— 基于 Cordis（真实 `cordis` + `@cordisjs/plugin-loader`）的组合层，
  把上面 76 种语言收编为一等组件，支持运行时热插拔与跨语言共识校验。详见其自身 README。

## 运行方式与依赖
- 运行：`python main.py`
- 依赖：无（仅标准库 tkinter）

## 测试状态
- py_compile 语法检查通过（7 个 .py）
- GUI 窗口程序，未运行（仅编译）
