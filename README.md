# 🎨 PRTTprint

### The best library to bring life to your terminal!

*Pretty Text Print — beautiful colors, sounds, spinners, tables and animations for the CLI.*

[![Python](https://img.shields.io/badge/python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Version](https://img.shields.io/badge/version-2.0.1-brightgreen)](https://github.com/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![PyPI](https://img.shields.io/badge/pypi-prttprint-orange)](https://pypi.org/)

[Install](#installation) | [Quick Start](#quick-start) | [Cheatsheet](#cheatsheet) | [Core](#core-basics) | [Storage](#storage) | [Features](#features) | [Examples](#examples) | [FAQ](#faq)

---

## About

**PRTTprint** is a single-file library that turns boring console output into a lively, colorful and interactive experience.

No external dependencies (except optional `wcwidth`), no complex setup — just:

```python
from PRTTprint import *
init()

ok('Done!')
