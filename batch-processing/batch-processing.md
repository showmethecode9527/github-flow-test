1. 托管本地静态文件
以下批处理，在 `E:\test` 目录启用 `http-server`
```
@echo off
start cmd /k "cd/d E:\test&&echo serving on 222&&http-server -p 222"
```

2. 批处理打开指定网站
```
path=%path%; C:\Program Files (x86)\Google\Chrome\Application\chrome.exe
start chrome.exe http://localhost:222/
```