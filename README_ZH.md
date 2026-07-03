# Terminology Cleaner

中文 | [English](README.md)


## 概览

交互式术语去重与清洗工具，用于整理术语质量和重复项。

## 主要能力

- 识别并处理重复术语。
- 辅助术语质量清洗。
- 适合作为本地术语表整理工具。

## 使用方式

按下方 Python 依赖和脚本说明准备术语表并运行。

## 状态

该仓库仍按当前 README 的说明维护或使用。

## 注意事项

清洗结果建议人工确认后再交付。

## 命令与配置参考

以下代码块从主 README 保留；命令、路径和配置键不翻译，复制时请以实际环境为准。

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

## 详细技术说明

主 README 保留了原始技术细节、历史说明、完整命令和文件结构。本文件作为中文版本维护核心说明；需要逐项核对命令时，请参照主 README 的代码块和路径。
