# Lodestone Protocol（磁石协议）
**一种与编程语言无关的协议，用于在 CommonMark 中嵌入 DAG 元数据，实现智能体会话知识收敛。** 别名：MD‑DAG。

📖 规范文档 · [Rust 参考实现](https://github.com/lodestone-protocol/lodestone-md) · [版本发布](https://github.com/lodestone-protocol/lodestone-spec/releases)

---

## 什么是 Lodestone？
Lodestone 协议（别名 MD‑DAG）定义了一套极简、具备确定性的方案，通过 HTML 注释将机器可读的 DAG 元数据嵌入 CommonMark 文档。专为 AI 智能体系统设计，提供跨多智能体、多会话环境下**共享、无冲突、以文件为状态源的知识载体**。

- **当前版本**：v1.3.0（正式冻结版）——查看 [发布页](https://github.com/lodestone-protocol/lodestone-spec/releases/tag/v1.3.0)
- **基础标准**：CommonMark 0.31.2
- **合规验证**：25 组 Golden Fixture 测试用例，完整覆盖全部 14 项诊断码

## 仓库说明
| 仓库 | 用途 | 许可证 |
|---|---|---|
| [lodestone-spec](https://github.com/lodestone-protocol/lodestone-spec) | 协议规范、错误码注册表、Golden Fixtures（权威来源） | Apache‑2.0 |
| [lodestone-md](https://github.com/lodestone-protocol/lodestone-md) | Rust 参考实现（23 项测试，通过 clippy 静态检查） | MIT |

后续各类语言实现（`lodestone-py`、`lodestone-ts` …）将根据第三方需求陆续加入本组织。

## 快速上手
1. 阅读 [协议规范](https://github.com/lodestone-protocol/lodestone-spec/blob/main/spec/v1.3.md)（建议先阅读 §1‑§3，了解设计理念与基础语法）
2. 体验 [Rust 参考实现](https://github.com/lodestone-protocol/lodestone-md#quick-start)
3. 拉取 [Golden Fixtures 测试集](https://github.com/lodestone-protocol/lodestone-spec/tree/main/fixtures)，用于验证你自行编写的任意语言实现

## 贡献指南
- **协议规范修改**：前往 [lodestone-spec](https://github.com/lodestone-protocol/lodestone-spec/issues) 提交 Issue。协议当前为 v1.3 正式冻结，任何改动都需要 ADR 级别的充分讨论。
- **参考实现缺陷**：前往 [lodestone-md](https://github.com/lodestone-protocol/lodestone-md/issues) 提交 Issue。
- **ADR 决策边界**：参阅 [lodestone-spec/CONTRIBUTING.md](https://github.com/lodestone-protocol/lodestone-spec/blob/main/CONTRIBUTING.md)

## 行为准则与安全说明
友好交流，互相尊重。安全漏洞请通过对应仓库的 GitHub 安全建议通道私下上报，不要公开提交 Issue。

---

🌐 [English](./README.md) · Lodestone Protocol 是独立开源项目。
