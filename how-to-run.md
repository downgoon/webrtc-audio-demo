# How to run

``` bash
$ npm install   // 安装node依赖包
$ npm start    // 启动后访问 http://localhost:3000
```

如果国外的``node``库访问慢，可以切换淘宝的库：``nrm use taobao``。安装后，在根目录会出现``node_modules``子目录，里面有很多依赖包（包括依赖的依赖）。``node.js``的``npm``跟``java``的``maven``在依赖管理上略有不同，``npm``是每个项目单独下载依赖，同一个依赖，不同的项目会重复下载，而``maven``是所有的项目的依赖都集中存放在``~/.m2/repository``目录下，避免了每个项目单独下载。
