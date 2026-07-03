# Terminology Cleaner

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)

[English](README.md) | 中文

## 概览

交互式术语去重与清洗工具，用于整理术语质量和重复项。

## 主要能力

- 识别并处理重复术语。
- 辅助术语质量清洗。
- 适合作为本地术语表整理工具。

## 使用方式

按下方 Python 依赖和脚本说明准备术语表并运行。

## 注意事项

清洗结果建议人工确认后再交付。

## 命令与配置参考

以下命令、路径和配置键保持原样，复制时请以实际环境为准。

```bash
pip install -r requirements.txt
```

```bash
python main.py
```

```
.
├── main.py                # Entry point
├── cleaner.py             # Core cleaning logic
├── similarity_detector.py # Fuzzy matching engine
├── config.py              # Default settings
├── logger.py              # Logging utilities
├── utils.py               # Helper functions
└── CHANGELOG.md           # Version history
```
