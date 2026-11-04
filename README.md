---
language:
- ru
license: cc0-1.0
task_categories:
- text-generation
tags:
- kibor
- programming-language
- documentation
- code
pretty_name: KIBOR Programming Language Documentation
---

# KIBOR Programming Language — Official Documentation Dataset

Public documentation corpus for **KIBOR**, a scripting/programming language.

This dataset contains **284 text documents** describing KIBOR language features, commands, and code examples. Each document preserves the original text and code formatting as extracted from the documentation.

## Files
- `kibor_dataset.jsonl`: one JSON object per TXT document; fields: `id`, `title`, `source_url`, `language`, `programming_language`, `filename`, `text`.
- `kibor_all_documentation.txt`: combined plain-text corpus.
- `documentation/`: original TXT files, copied without modification.

Some documents share source pages and may contain identical text. No automatic rewriting or code modification was performed. Detected identical document bodies: **147** additional copies.

## Language / Язык
KIBOR is a distinct scripting/programming language. Code examples are **KIBOR**, not Python unless explicitly identified as embedded Python code.

## Origin / Источник
Documentation authored and published by the KIBOR language author. Original source URLs are retained in each record.

## License
CC0 1.0 Universal — published by the rights holder. If this license does not reflect your intent, edit this file **before publication**.

---

# KIBOR — официальный датасет документации

Открытый корпус документации языка программирования **KIBOR**: **284 TXT-документов**, описания команд и примеры кода.

Тексты и примеры кода сохранены без автоматического перефразирования. В `kibor_dataset.jsonl` содержится одна запись на каждый TXT-файл. Оригинальные URL сохранены. Одинаковые тексты могут встречаться в нескольких записях, если команды относятся к одной странице справки.

**Лицензия:** CC0 1.0 (проверьте перед публикацией).
