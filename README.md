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

请确保在使用本项目时遵守所有相关的法律法规和版权协议。# easy_qmainwindow
