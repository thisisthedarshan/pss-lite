# pss-lite

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![LexLoom](https://img.shields.io/badge/Built%20with-LexLoom-blueviolet)](https://github.com/thisisthedarshan/LexLoom)

A lightweight syntax definition for the **Portable Test and Stimulus Standard (PSS)**.

## Overview

`pss-lite` provides a universal syntax specification for PSS, enabling consistent syntax highlighting across multiple editors including VS Code, Vim, and Notepad++. 

This project uses the [LexLoom](https://github.com/thisisthedarshan/LexLoom/tree/main) engine to generate editor-specific syntax files from a single, intent-based JSON definition.

## Features

- **Comprehensive Keyword Support**: Includes flow control, structural, and built-in type keywords for PSS 3.0.0.
- **Language Injection**: Supports C++ and SystemVerilog syntax highlighting inside triple-quoted strings (commonly used for `exec` blocks).
- **Multi-Platform**: Designed to be compiled into various formats using the LexLoom toolchain.

## Built With

This project is built using [LexLoom](https://github.com/thisisthedarshan/LexLoom/tree/main), a universal syntax DSL and generator. The core logic is defined in `pss.json`, which follows the [LexLoom schema](https://github.com/thisisthedarshan/LexLoom/blob/main/schema/lexloom.schema.json).

## License

This project is licensed under the [MIT License](LICENSE). 
Copyright (c) 2026 Darshan
