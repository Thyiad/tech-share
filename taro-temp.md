### 前言

- 2011 微信发布
    > 短短1年突破1用户、通讯、交友、服务用户生活
    > 丰富的商户公众号，微信浏览器（QQ浏览器x5内核）的h5网页
- 2015 微信jssdk
    > 早期只是内部使用，未公开api：
    > ``` javascript
    > WeixinJSBridge.invoke('', {
    > 
    > }, function(res){
    > 
    > })
    > wx.xxx
    > ```
    ``` javascript
    document.addEventListener("WeixinJSBridgeReady", function () {
        audio.play();
    }, false);
    ```
- 2016 微信小程序

### 小程序缺陷

### 框架

- wepy
- mpvue
- mpx
- taro
- uni-app
- chameleon

### taro基本用法

### 对比小程序写法

### 注意点
taro不支持动态节点，比如list遍历时塞入一个节点

### 对比其他技术及未来

- 快应用
- pwa
- 小程序标准白皮书