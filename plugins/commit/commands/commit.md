---
description: Creates git commits using conventional commit format with appropriate emojis, following project standards and creating descriptive messages that explain the purpose of changes.
author: evmts
author-url: https://github.com/evmts
version: 1.0.0
---

# Commit Command

This slash command is a Git commit helper that:

1. Runs pre-commit checks by default (linting, building, generating docs)
2. Automatically stages files if none are staged
3. Analyzes code changes to suggest potential commit splits
4. Creates commits using conventional commit format with descriptive emojis

## Key Features
- Supports options like `--no-verify` to skip pre-commit checks
- Encourages "atomic commits" with focused, logical changes
- Provides a comprehensive list of commit types and corresponding emojis
- Offers guidelines for splitting complex commits

## Example Commit Messages
- "feat(module,...): add user authentication system"
- "fix(module,...): resolve memory leak in rendering process"
- "docs(module,...): update API documentation with new endpoints"

## Note
- 提交说明使用中文编写，确保清晰易懂
- 提交说明不添加作者信息和AI生成者信息，保持简洁
- 提交说明格式：
```bash
  `fix(模块名1,模块名2...): 修改内容综述
    - 模块名1: 模块名1的修改内容说明
    - 模块名2: 模块名2的改内容说明
    ...
    `
```
  使用冒号分隔模块和具体修改内容
- 提交说明应简洁明了，避免冗余描述
- 提交说明应遵循"做什么-为什么做"的原则，重点说明变更的目的和影
响
- 提交说明使用现在时态，避免使用"已经"、"正在"等时态词汇

The command aims to improve code quality, commit clarity, and developer workflow by providing structured commit guidance.

## Note
- 使用中文交流
