## 微信小程序 WeUI使用

仅使用weui-wxss的样式，也可以按需引入component组件使用。

### 仅使用weui-wxss样式
先打开两个链接，
+ [weui-wxss](https://github.com/Tencent/weui-wxss/)
+ [WeUI组件库预览-小程序码](https://developers.weixin.qq.com/miniprogram/dev/extended/weui/)
打开两个页面之后，继续以下的操作。
1. 打开weui-wxss的样式仓库中的master/dist/example，可以看到很多组件的使用样例
2. 使用手机微信扫描小程序码，查看组件的样式
3. 根据样式，找到weui-wxss的样例，查看使用到的样式
4. 拉取weui-wxss源代码，并把[dist/style](https://github.com/Tencent/weui-wxss/tree/master/dist/style)目录下的文件放到小程序的style目录中，然后在app.wxss中使用import导入
5. 找到目标的样式，拷贝、粘贴到自己的代码中，即可
通过以上几步，可以定位到目标组件的样式，然后，就可以自己使用了。
