# Terminology Cleaner

<!-- bilingual-readme:start -->

## 双语说明 / Bilingual Documentation

> 本节提供整篇 README 的中英双语维护说明；下方保留原始详细说明、命令、路径和配置示例。
> This section provides bilingual maintenance notes for the full README; the original detailed notes, commands, paths, and configuration examples are preserved below.

### 中文

**概览**：交互式术语去重与清洗工具，用于整理术语质量和重复项。

**主要能力**：
- 识别并处理重复术语。
- 辅助术语质量清洗。
- 适合作为本地术语表整理工具。

**使用方式**：按下方 Python 依赖和脚本说明准备术语表并运行。

**状态**：该仓库仍按当前 README 的说明维护或使用。

**注意事项**：清洗结果建议人工确认后再交付。

### English

**Overview**: Interactive terminology deduplication and cleaning tool for improving glossary quality and resolving duplicates.

**Key capabilities**:
- Identifies and handles duplicate terms.
- Assists terminology quality cleanup.
- Works as a local glossary-maintenance utility.

**Usage**: Prepare the glossary and run the scripts according to the Python dependency notes below.

**Status**: This repository is maintained or used according to the current README notes.

**Notes**: Cleaned output should be reviewed manually before delivery.

<!-- bilingual-readme:end -->

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Interactive terminology deduplication and quality cleaning tool.

## Features

- **Batch Processing** — Clean entire directories of terminology tables
- **Case Control** — Optional ignore-case normalization
- **Punctuation Removal** — Strip noise characters for cleaner matching
- **Quality Checks** — Filter out low-quality or malformed entries
- **Similarity Detection** — Identify near-duplicate terms with adjustable threshold
- **Interactive Mode** — Review and confirm merges one by one

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
python main.py
```

The interactive CLI will guide you through:
1. Selecting cleaning options (case, punctuation, quality, similarity)
2. Setting similarity threshold (0–100)
3. Choosing single-file or batch mode

## Configuration

Edit `config.py` to adjust default thresholds and behavior.

## Project Structure

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

## License

[MIT](LICENSE)