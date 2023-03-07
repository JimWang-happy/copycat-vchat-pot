# pansyjoint-pot

pansyjoint后端

# 如何使用
这是个Koa nodejs服务器，主入口`index.js`，`npm start`启动，默认端口3009

使用的是自动路径匹配机制，`controller`文件夹下的js表示控制器层→方法层，路径按名字匹配
如`controller/Project.js`里有一个方法`queryProject`，那么访问`localhost:3009/Project/queryProject`即可。

暂未实现针对`GET/POST`等HTTP METHOD的差异支持。