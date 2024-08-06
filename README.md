# ClassBoardLite

第三代 ClassBoard, 更轻更快更自由。

## TODO

前后端分离，前端纯网页，依靠封装 websocket 的 wsapi.js 提供的 API 与后端通信（并提供自定义通信功能），分为三个 Page ：

- background.html: 背景页面

- settings.html: 处理设置，维护在 config.json 文件中

- packages.html: 切换其他主题

后端 : 处理 websocket 请求，同时包含托盘、自启动等与系统互动的 feature

文件结构：

```
- .
    - pages
        - packages.html
        - settings.html
    - themes
        - plasma
            - css
            - js
            - background.html
            - extra_settings.html
    - config.json
    - backend.exe
    - start.bat
```

需要自备 chrome 浏览器。