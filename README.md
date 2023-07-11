主要是三个文件：

用cmd运行ntchat-flask.py，运行之后启动HTTP服务，写其他代码调用。

pip install flask[async]

Pyinstaller -F --collect-data=ntchat ntchat-flask.py
