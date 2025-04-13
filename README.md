# EasyMainWindow 中文说明文档

EasyMainWindow 是一个简化版的 `QMainWindow` 类，旨在提供更简单的 API 来创建和管理窗口控件。它允许用户通过简单的函数调用添加各种控件，并自动处理控件的位置和大小调整。

## 前置条件

- Python 3.6 或更高版本
- PyQt5 或 PySide2

## 安装

可以通过以下命令安装：

```bash
pip install easy_qmainwindow
```

## 使用方法

首先，确保你已经安装了 `PyQt5` 或 `PySide2`。然后，你可以使用 `EasyMainWindow` 类来创建和管理你的窗口。

```python
from easy_qmainwindow import EasyMainWindow

def on_button_click():
    print("Button clicked!")

app = EasyMainWindow("My Easy Window")
app.add_button("my_button", "Click Me", connect_func=on_button_click)
app.show()
```

## 构建方法

项目使用 `setuptools` 进行打包。你可以通过以下命令构建项目：

```bash
python setup.py sdist bdist_wheel
```

## 许可证

本项目采用 MIT 许可证。请查看 `LICENSE` 文件了解更多信息。

## 贡献

如果你有任何改进意见或想要贡献代码，请随时提交 Pull Request 或创建 Issue。

## 注意

请确保在使用本项目时遵守所有相关的法律法规和版权协议。

# EasyMainWindow English Documentation

EasyMainWindow is a simplified version of the `QMainWindow` class, designed to provide a simpler API for creating and managing window widgets. It allows users to add various widgets through simple function calls and automatically handles the positioning and resizing of widgets.

## Prerequisites

- Python 3.6 or higher
- PyQt5 or PySide2

## Installation

You can install it using the following command:

```bash
pip install easy_qmainwindow
```

## Usage

First, ensure that you have installed `PyQt5` or `PySide2`. Then, you can use the `EasyMainWindow` class to create and manage your window.

```python
from easy_qmainwindow import EasyMainWindow

def on_button_click():
    print("Button clicked!")

app = EasyMainWindow("My Easy Window")
app.add_button("my_button", "Click Me", connect_func=on_button_click)
app.show()
```

## Build Method

The project uses `setuptools` for packaging. You can build the project using the following command:

```bash
python setup.py sdist bdist_wheel
```

## License

This project is licensed under the MIT License. Please check the `LICENSE` file for more information.

## Contribution

If you have any suggestions for improvement or want to contribute code, please feel free to submit a Pull Request or create an Issue.

## Note

Please ensure that you comply with all relevant laws and regulations and copyright agreements when using this project.

