# Console Text Editor

**Python · Command-line interface · CSC1002 coursework**

A small, command-driven text editor created as a CSC1002 programming assignment at CUHK-Shenzhen. The program keeps a multiline text buffer in memory and applies editing commands entered at a terminal prompt.

## Features

- Character and word navigation, including line-start and line-end movement.
- Text insertion and appending, plus character and word deletion.
- Swapping neighboring words while tracking the cursor.
- Adding, deleting, reordering, and jumping between lines.
- Optional ANSI character highlighting and an active-line marker.
- Command validation and a dispatch table that maps commands to functions.

## What I practised

The project combines Python strings and lists, regular expressions for word boundaries, command parsing, and functions that update shared editor state. Boundary handling keeps the cursor valid when the text or active line changes.

## Scope

This is a programming coursework project. Text stays in memory; file loading, saving, and undo/redo are not implemented. It is a foundation for further improvements in testing, state organization, and terminal interaction.

See the **[source code and running instructions](https://github.com/madengmatthew/console-text-editor)** for the full project.

---

中文简述：这是我在 CSC1002 中完成的 Python 命令行文本编辑器，支持多行编辑、字符与单词移动、插入删除、单词交换和行重排，用于练习字符串处理、正则表达式、命令解析和状态管理。
