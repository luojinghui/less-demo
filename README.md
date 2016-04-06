# Less_demo_01
### 介绍Less
   Less 是一个Css 预编译器,意思指的是它可以扩展Css语言,添加功能如允许变量(variables),混合(mixins),函数(functions) 和许多其他的技术，让你的Css更具维护性，主题性，扩展性。
### 练习一
1. 在html头部引入less文件：

    `<link rel="stylesheet/less" type="text/css" href="../less/style.css"/>`
2. 在引入less.js文件之前，先配置less：

    `less = {

        env: "development", // or "production"

        async: false,       // load imports async

        fileAsync: false,   // load imports async when in a page under

        // a file protocol

        poll: 1000,         // when in watch mode, time in ms between polls

        functions: {},      // user functions, keyed by name

        dumpLineNumbers: "comments", // or "mediaQuery" or "all"

        relativeUrls: false,// whether to adjust url's to be relative

        // if false, url's are already relative to the

        // entry less file

        rootpath: ":/a.com/"// a path to add on to the start of every url

        //resource

        };`