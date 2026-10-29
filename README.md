# kimi-break

针对 **Kimi Code** 的渗透测试 / 破甲（Jailbreak）系统提示词。

A red-team system prompt (`SYSTEM.md`) for Kimi Code — jailbreak / armor-piercing research artifact.

## 简介

本仓库是一段针对 Kimi Code CLI 的自定义系统提示词（`SYSTEM.md`），用于 AI 安全研究与红队评估。使 Agent 在渗透测试等敏感场景中不触发拒绝行为。

## 特色

完全未修改原系统提示词，只做了增加，最大幅度利用Kimicode本身的工程优势。

## 使用

### Windows

将项目中的SYSTEM.md替换至`C:\Users\<你>\.kimi-code\SYSTEM.md`，替换前请备份原文件,如果目录下没有这个文件是正常的，直接放在这里就行了。

### MacOS && Linux

将项目中的SYSTEM.md替换至`~/.kimi-code/SYSTEM.md`，替换前请备份原文件,如果目录下没有这个文件是正常的，直接放在这里就行了。

## 免责声明

本项目仅用于**授权环境**下的 AI 安全研究、红队评估与提示工程教学。请勿将其用于任何违反服务条款或法律法规的实际操作。使用者自行承担一切后果。
