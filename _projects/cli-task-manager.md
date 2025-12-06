---
title: CLI Task Manager
tagline: Manage tasks from your terminal - because GUI is overrated!
github: https://github.com/yourusername/taskcli
---

A powerful command-line task manager for developers who live in the terminal.

## Why Another Task Manager?

Because I was tired of switching between my terminal and a GUI app. This brings task management into your natural workflow.

## Features

```bash
$ task add "Write blog post about CLI tools"
$ task list
$ task done 1
$ task stats
```

Simple commands, powerful results.

### Core Functionality

- **Add tasks** with tags, due dates, priorities
- **List and filter** by any criteria
- **Track time** spent on tasks
- **View stats** to understand your productivity
- **Sync** across machines via Git

### What Makes It Different

- **Fast**: Written in Rust for blazing performance
- **Scriptable**: Pipe it, grep it, awk it - it's Unix-friendly
- **Portable**: Single binary, no dependencies
- **Colorful**: Beautiful terminal UI with syntax highlighting

## Implementation

Built with:
- **Language**: Rust
- **Storage**: SQLite for reliability
- **Colors**: Crossterm for terminal styling
- **Parsing**: Clap for elegant CLI parsing

## Productivity Boost

Since building this, my task completion rate has improved significantly. The reduced friction of staying in the terminal makes tracking actually useful instead of a chore.

## Open Source

Free, open source, and accepting contributions. If you live in the terminal, give it a try!
