# 运行
通过以下命令运行服务器：
uvicorn main:app --reload
# 端口被占用
改变启动端口方式：在启动命令后加--port来改变启动端口,例如 uvicorn main:app --reload --port 18080

kill应用的方式:在Windows环境下使用netstat -aon|findstr "8000"查看占用8000端口的应用的PID，然后在任务管理器中找到对应应用结束。


自动生成的交互式 API 文档：http://127.0.0.1:8000/docs