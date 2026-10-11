# DeployMate AI 🚀

### An AI Skill for Safer, Evidence-Based Deployment Troubleshooting

## 📌 Overview

DeployMate AI helps developers troubleshoot deployment failures through structured diagnosis, practical fixes, and verification steps.

Instead of guessing solutions, it uses available error messages and project information to identify likely causes and recommend safe troubleshooting actions.

## 🎯 Problem

Developers often struggle with deployment failures caused by missing dependencies, incorrect configuration, missing environment variables, and application startup errors.

Unverified fixes can introduce further problems or risk production data.

## 💡 Solution

DeployMate AI provides a structured troubleshooting workflow that:

- Collects relevant error information.
- Identifies likely causes using available evidence.
- Recommends minimal, reversible fixes.
- Provides verification steps.
- Warns users about destructive operations.
- Protects sensitive information such as API keys and passwords.

## ✨ Key Features

- Build failure troubleshooting
- Dependency error diagnosis
- Environment variable guidance
- Runtime and startup error analysis
- Secret protection guidance
- Production safety recommendations
- Step-by-step verification

## 🛠️ Technology

- Markdown-based AI skill instructions
- Large Language Model (LLM) skill workflow
- Scenario-based test cases

## 🧪 Test Coverage

The planned test cases cover:

1. Missing build script
2. Missing dependency
3. Missing environment variable
4. Application startup failure
5. Destructive command safety
6. Secret exposure protection

Note: These are planned test scenarios. They must be executed against a compatible AI agent before reporting verified results.

## 🔐 Safety Principles

- Never request passwords or secret tokens.
- Prefer minimal and reversible changes.
- Warn before potentially destructive actions.
- Protect production data.
- Never claim that a fix succeeded without verification.

## 📂 Project Structure

```text
DeployMate-AI/
├── SKILL.md
├── README.md
└── test-cases.md