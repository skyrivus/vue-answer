## what's vue-answer？
    这是大数据的时代，也是一个信息爆炸的时代，如此海量的信息，一个人应该如何去选择，去接受，去吸收？
    (This is the era of big data, but also an era of information explosion, such a huge amount of information Wang, how should everyone choose to accept, to absorb?)

    这也是Answer想解决的问题：信息价值
    (That's what Answer wants to solve.)
----

### target
    * 答案-对主流信息进行分类，评价，排行
      (Answer -- the classification, evaluation, and ranking of the mainstream information)

    * In Answer, Guide to information acquisition, all the people on the street.
      (在答案,为你推介获取正确信息的指南，也作为你披荆斩棘的引路人)

    * In Answer, you can easily find friends who have been in the same predicament.  all the people on the street
      (在答案，你可以轻易找到曾经历相同困境的朋友,披荆斩棘的同伴)

----
### how to use ?
    // 安装运行所需依赖
    npm install

    // 启动
    npm run dev
----
### UI exhibition
  ![image](https://github.com/ifredom/vue-answer/raw/master/test/testsrc/1.png)
  ![image](https://github.com/ifredom/vue-answer/raw/master/test/testsrc/2.png)
  ![image](https://github.com/ifredom/vue-answer/raw/master/test/testsrc/3.png)
  ![image](https://github.com/ifredom/vue-answer/raw/master/test/testsrc/4.png)
### 下载安装
  ![image](https://github.com/ifredom/vue-answer/raw/master/test/testsrc/ifredom-answoe-code.png)
  二维码有时效性，如果已失效，那么你可以在download文件夹中找到apk安装包

----

### project structure
    .
    -- build                            // 项目构建相关代码
    |   |-- build.js                     // 生产环境构建代码
    |   |-- check-version.js             // 检查 node、npm 等版本
    |   |-- dev-client.js                // 热重载相关
    |   |-- dev-server.js                // 构建本地服务器
    |   |-- utils.js                     // 构建工具相关
    |   |-- webpack.base.conf.js         // webpack 基础配置（出入口和 loader）
    |   |-- webpack.dev.conf.js          // webpack 开发环境配置
    |   |-- webpack.prod.conf.js         // webpack 生产环境配置
    |-- config                           // 项目开发环境配置
    |   |-- dev.env.js                   // 开发环境变量
    |   |-- index.js                     // 项目一些配置变量（开发环境接口转发将在此配置）
    |   |-- prod.env.js                  // 生产环境变量
    |   |-- test.env.js                  // 测试环境变量
    |-- myself                           // 平时的小练习
    |-- server_mock                      // 后台接口数据
    |   |-- router                       // 接口router管理
    |   |-- controller                   // 接口控制器
    |-- src                              // 源码目录
    |   |-- api                          // ajxa请求接口地址
    |   |-- components                   // vue 公共组件
    |   |-- page                         // 页面
    |   |-- image                        // 图片
    |   |-- style                        // CSS样式
    |   |-- router                       // 路由
    |   |-- vuex                         // vuex 的组件状态统一管理
    |   |-- App.vue                      // 页面入口文件
    |   |-- main.js                      // 程序入口文件，加载各种公共组件
    |-- static                           // 静态文件，比如一些图片，json数据等
    |-- test                             // 自动化测试相关文件
    |-- .babelrc                         // ES6语法编译配置
    |-- .editorconfig                    // 定义代码格式
    |-- .eslintignore                    // ESLint 检查忽略的文件
    |-- .eslistrc.js                     // ESLint 文件，eslint检测规则配置，如需更改，在此添加
    |-- .gitignore                       // git 上传需要忽略的文件
    |-- README.md                        // 项目说明
    |-- index.html                       // 入口页面
    |-- package.json                     // 项目基本信息
    .
