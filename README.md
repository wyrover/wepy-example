# wepy-example


```
npm install -g wepy-cli 
wepy init standard wepy-example
cd wepy-example
npm install
wepy build --watch
```

微信开发者工具目录指向 wepy-example，不用指向 wepy-example/dist


编译然后预览，手机微信扫描二维码，在手机上预览应用


vscode 打开 webpy-example 浏览源码目录

wepy 是一种类 vue 的框架，先了解框架的生命周期


脚本的结构
``` js

import wepy from 'wepy'

@connect()

export default class Index extends wepy.page {
    config = {},            // 配置全局变量
    components = {},        // 注册组件
    mixins = {},            
    data = {},              // 可绑定数据
    computed = {},
    methods = {},           // 响应方法
    events = {},            // 事件
    onLoad() {              // 初始化
    }
}

```