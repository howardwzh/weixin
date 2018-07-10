## weixin
> 小程序

### 开发环境配置
1. [小程序申请与工具下载配置](https://mp.weixin.qq.com/debug/wxadoc/dev/)
2. [官方文档-完整过一遍，遇问题方便查询](https://developers.weixin.qq.com/miniprogram/dev/framework/MINA.html)
3. [开发框架wepy](https://tencent.github.io/wepy/document.html#/)
4. [各种问题解决方案](http://www.wxapp-union.com/special/solution.html)

### 创建项目
1. 使用wepy创建即可，注意后面的“重要提醒”
2. 然后参考wepy和小程序的文档进行开发吧

### 开发笔记

1. 全局安装或更新WePY命令行工具
```
npm install wepy-cli -g
```

2. 在开发目录中生成Demo开发项目, 1.7.0之后版本请移步wepy-cli文档
```
wepy init standard myproject
```

3. 切换至项目目录
```
cd myproject
```

4. 安装依赖
```
npm install
```

5. 开启实时编译
```
wepy build --watch
```