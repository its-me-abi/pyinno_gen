# pyinno_gen

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Python](https://img.shields.io/badge/Python-3.6%2B-blue.svg)](https://www.python.org/)
[![Issues](https://img.shields.io/github/issues/its-me-abi/pyinno_gen.svg)](https://github.com/its-me-abi/pyinno_gen/issues)

> **Easily generate Inno Setup `.iss` scripts for Windows installers using Python!**

---

## 🚀 Overview

**pyinno_gen** is a Python tool for programmatically creating `.iss` files—scripts for [Inno Setup](http://www.jrsoftware.org/isinfo.php), a popular free installer for Windows programs.

- **Author:** [its-me-abi](https://github.com/its-me-abi)
- **Date:** 12/7/2025

---

## ✨ Features

- Dynamically generates `.iss` (Inno Setup Script) files.
- Simplifies building Windows application installers.
- Uses [jinja2](https://palletsprojects.com/p/jinja/) templating for script flexibility.

---

## ❓ What is Inno Setup?

[Inno Setup](http://www.jrsoftware.org/isinfo.php) lets you create professional Windows installers using customizable `.iss` scripts.

---

## 🛠️ Installation
two ways to install 

by pypi 
``` pip install pyinno-gen ```

or Clone the repository from github

```bash
git clone https://github.com/its-me-abi/pyinno_gen.git
cd pyinno_gen
pip install -r requirements.txt
```

---

## ⚡ Usage

Example:

```python
from pyinno_gen import pyinno_gen

args = {"MyAppName": "TestAPP2"}
pyinno_gen.generate_iss(args, input_path = "test/template.iss", output_path = "test/out.iss")
```

This generates a `.iss` file ready for Inno Setup!

---

## 📦 Requirements

- Python 3.6+
- [jinja2](https://palletsprojects.com/p/jinja/) (core dependency)

Tested on Python 3.12.x—should work on most versions!

---

## 📄 License

This project is licensed under the **GPL v3.0**.

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to open an [issue](https://github.com/its-me-abi/pyinno_gen/issues) or submit a pull request.

---

## 💬 Contact

Questions? Reach out to [its-me-abi](https://github.com/its-me-abi)!