# JSPrint

JSPrint is a Python package that provides a logging utility with different logging levels. It allows you to set the logging level and log messages with different levels such as log, warn, error, info, success, debug, and trace.

## Imports

- `datetime`: A module that supplies classes for working with dates and times.

## Classes

### 🎨 • Colour

A class that contains color codes for the console output.

#### Properties

- `white`: The white color code.
- `red`: The red color code.
- `green`: The green color code.
- `yellow`: The yellow color code.
- `blue`: The blue color code.
- `purple`: The purple color code.
- `cyan`: The cyan color code.
- `grey`: The grey color code.

### ✏️ • Styles

A class that contains style codes for the console output.

#### Properties

- `default`: The default style code.
- `bold`: The bold style code.
- `underline`: The underline style code.
- `reversed`: The reversed style code.
- `reset`: The reset style code.

### ⛏️ • Utils

A class that contains utility functions.

#### Methods

- `date()`: Returns the current date and time in the format of `[dd/mm/yyyy hh:mm:ss]`.

### 🚀 • JSP

A class that provides logging functionality.

#### Methods

- `__init__(self, log_level: str = "log")`: Initializes the JSPrint object with the specified logging level. The default logging level is `log`.
- `set_log_level(self, log_level: str)`: Sets the logging level to the specified level.
- `log(self, message: str)`: Logs a message with the `[LOG]` level.
- `warn(self, message: str)`: Logs a message with the `[WARN]` level.
- `error(self, message: str)`: Logs a message with the `[ERROR]` level.
- `info(self, message: str)`: Logs a message with the `[INFO]` level.
- `success(self, message: str)`: Logs a message with the `[SUCCESS]` level.

## Installation
#### Installation with PIP
```bash
pip install jsprint
```
#### Installation with PIP3
```bash
pip3 install jsprint
```
#### Installation with Poetry
```bash
poetry add jsprint
```
#### Installation with Poetry (dev)
```bash
poetry add jsprint --dev
```
