# CentOS7 Claude Code + Claude Code Router

## Disclaimer

This repository provides automation scripts for packaging Claude Code for offline use on CentOS 7.
It does **NOT** modify any original code. All rights of `@anthropic-ai/claude-code` belong to Anthropic.

Users must comply with [Anthropic's Usage Policy](https://www.anthropic.com/legal/aup)
and [Claude Code Terms](https://code.claude.com/docs/en/legal-and-compliance).
This project is intended for personal/internal use only. Node.js is distributed under the [MIT License](https://github.com/nodejs/node/blob/main/LICENSE).

## 免责声明

本仓库仅提供自动化打包脚本，方便在无网络的 CentOS 7 环境中使用 Claude Code。
不对原始代码做任何修改，`@anthropic-ai/claude-code` 的所有权利归 Anthropic 所有。
使用者需自行遵守 Anthropic 使用条款，本项目仅供个人/内部学习使用，不得用于商业目的。

---

离线安装包，适用于 CentOS 7 x86_64。

包含：
- [@anthropic-ai/claude-code](https://www.npmjs.com/package/@anthropic-ai/claude-code)
- [@musistudio/claude-code-router](https://www.npmjs.com/package/@musistudio/claude-code-router)
- Node.js v22（patched glibc 2.17）

## 安装方式

从 [Releases](../../releases) 下载最新压缩包，解压后执行：

```bash
tar -xzf claude-{version}-centos7-x86_64.tar.gz -C ~/
~/claude-{version}/install.sh
source ~/.bashrc
```
