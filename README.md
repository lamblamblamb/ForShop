﻿#### ForShop

运行：

代码在编译器中编写，最后实时编译后在微信开发工具上看效果


* 使用了wepy
* 先全局安装wepy    npm install wepy-cli -g
* 安装依赖    npm install
* 开启实时编译  wepy build --watch
* 在微信开发者工具上打开dist文件，即可实时看效果

样式：
    less

 目录

    src
      api
         api.js //接口地址
      components
         common  //公用组件
      images //整个项目需要使用的图片
      pages //页面
      utils //工具
        region //地区
        request //请求
        tip.js//提示
        wxRequest.js//请求封装
      app.wpy

图标库
http://www.iconfont.cn/collections/detail?spm=a313x.7781069.0.da5a778a4&cid=1312
