# 第一个 Progressive Web App

- 1. 创建静态页面.(UI 初始化)
- 2. 引入 app.js
- 3. 使用 Service Workers 预缓存 App Shell

应用离线工作:

1. 注册 service worker
2. 用户首次访问页面时将会触发安装事件。在此事件处理程序内，我们将缓存应用所需的全部资产。