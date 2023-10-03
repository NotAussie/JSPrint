# 🚀 JSPrint
### An introduction to JSPrint.
JSPrint is a custom Python package that brings the JavaScript logging system to Python.

# 📋 • Badges
### Our statistics, information and more.
<!-- PYPI -->
![PyPI - Python Version(s)](https://img.shields.io/pypi/pyversions/jsprint?style=for-the-badge&logo=python&logoColor=white&label=Python%20versions&color=blue)
![PyPI - Version](https://img.shields.io/pypi/v/jsprint?style=for-the-badge&logo=pypi&logoColor=white&label=Version&color=blue)
![PyPI - Status](https://img.shields.io/pypi/status/jsprint?style=for-the-badge&logo=pypi&logoColor=white&label=Development%20status&color=blue)
![PyPI - Downloads](https://img.shields.io/pypi/dm/jsprint?style=for-the-badge&logo=pypi&logoColor=white&color=blue)
![PyPI - Format](https://img.shields.io/pypi/format/jsprint?style=for-the-badge&logo=pypi&logoColor=white&color=blue)

### 

![GitHub commit activity](https://img.shields.io/github/commit-activity/m/notaussie/jsprint?style=for-the-badge&logo=github&logoColor=white)
![GitHub contributors](https://img.shields.io/github/contributors/notaussie/jsprint?style=for-the-badge&logo=github&logoColor=white&color=blue)
![GitHub pull requests](https://img.shields.io/github/issues-pr/notaussie/jsprint?style=for-the-badge&logo=github&logoColor=white)
![GitHub issues](https://img.shields.io/github/issues/notaussie/jsprint?style=for-the-badge&logo=github&logoColor=white)
![GitHub forks](https://img.shields.io/github/forks/notaussie/jsprint?style=for-the-badge&logo=github&logoColor=white)

###

# 📦 • Installation
### JSprint is available on PyPI, so you can install it with pip.
```bash
pip install jsprint
```
### Or
```bash
pip3 install jsprint
```

### 

# 📚 • Usage
### Example of using JSPrint.
```python
# This code demonstrates how to use the JSP class to log messages with different levels of severity.

# Import JSPrint
from jsprint import JSP

# Create a new instance of the JSP class with a log level of "info"
logger = JSP(log_level="log")

# Log a message with each of the available levels
logger.log("This is a log message")
logger.warn("This is a warning message")
logger.error("This is an error message")
logger.info("This is an info message")
logger.success("This is a success message")
logger.debug("This is a debug message")
logger.trace("This is a trace message")

# Edit the log level
set_log_level("warn")
```

### 

# 📝 • Documentation
### JSPrint documentation is still in it's early stages.
View the documentation [here](https://github.com/NotAussie/JSPrint/blob/main/Docs/docs.md#jsprint)

### 

# 📜 • License
### JSPrint is licensed under the MIT license.
```text
MIT License

Copyright (c) 2023 NotAussie

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```