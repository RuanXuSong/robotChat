# webSocket

使用了 webSocket + koa + mysql 技术的聊天室页面软件

## 使用方法

1. 在 backEnd 文件夹中运行`yarn`，安装依赖。
2. 在 backEnd 文件夹中运行`yarn server`，运行服务器。
3. 在新窗口中打开 fontEnd 文件夹，用浏览器打开`h5/index.html`页面或者用`http-server`启动。
4. 聊天室客户端开启后会自动连接至本地服务器，如果服务器已经开启，可以在聊天室页面中看到历史记录否则会弹窗报错。
5. 发送消息: 在打开的聊天室页面中先输入你的用户名，再输入发送内容，点击发送按钮即可发送。
6. 注：该系统需要一个 `mysql` 的初始数据库，已经放到 `database` 文件夹下，使用 `Navicat for MySQL`软件导入到本地数据库即可。
