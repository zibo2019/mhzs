# 麻花助手（Xposed Plugin）

麻花助手，这是一款Xposed插件，旨在净化麻花影视手机版。当前是功能还不是很完善，使用软件时注意**助手所支持的麻花影视
 版本支持**，**支持 EdXposed 框架**，不支持 Exposed 框架，不支持 Virtual Xposed 框架。
 目前插件在逍遥安卓模拟器4.4/5.1/7.1，均测试成功.

## 更新日志

* 麻花助手 0.6.5 Beta 2019/03/05 [支持官网2.6.1版本]
    1. 提升稳定性；
    2. 支持Exposed框架。
    
* 麻花助手 0.6.4 Beta 2019/03/04 [支持2.6.X版本]
    1. 提升稳定性。

* 麻花助手 0.6.2 Beta 2019/03/03 [支持2.6.X版本]
    1. 去除启动页广告；
    2. 去除启动页5s倒计时；
    3. 去除启动页历史广告显示；
    4. 去除“推荐”、“电影”、“电视剧”页面中存在的广告；
    5. 去除视频播放页面的广告；
    6. 为助手添加图标；
    7. 为助手添加设置菜单；
    8. **获取视频播放地址（测试）**；
    9. 去除主界面升级提示。

* 麻花助手 0.5.1 Beta 2019/02/22 [仅支持2.5.0版]
    1. 去除启动页广告；
    2. 去除启动页5s倒计时；
    3. 去除启动页历史广告显示；
    4. 去除“推荐”、“电影”、“电视剧”页面中存在的广告；
    5. 去除视频播放页面的广告；
    6. 为助手添加图标；
    7. 为助手添加设置菜单。

* 麻花助手 0.1 Beta 2019/02/16
    1. 去除启动页广告；
    2. 去除启动页5s倒计时；
    3. 去除启动页历史广告显示；
    4. 去除“推荐”、“电影”、“电视剧”页面中存在的广告；
    5. 去除视频播放页面的广告。
    
## 近三次开发进度

* 2019/03/04
    1. 提升助手稳定性；
    2. 仅支持麻花影视2.6.0和2.6.1版本，版本号叠至0.6.4 beta。 

* 2019/03/03
    1. 提升助手稳定性；
    2. 更新插件 VideoURLPlugin，支持新的加密方式，在视频播放界面添加按钮可以获取播放地址；
    3. 更新插件 VideoURLPlugin，在视频播放界面添加360P,480P,720P,1080P按钮可以获取播放地址；
    4. 仅支持麻花影视2.6.0和2.6.1版本，版本号叠至0.6.2 beta。  

* 2019/02/27
    1. 提升助手稳定性；
    2. 添加插件 NoUpdatePlugin，仅去掉主页提示升级；
    3. 更新插件 VideoURLPlugin，在视频播放界面添加按钮可以获取480p播放地址；
    3. 仅支持麻花影视2.6.0和2.6.1版本，版本号叠至0.6.1 beta（未生成APK文件）。   

    
## 如何安装
    
   软件运行需要 Xposed 环境，请安装 Xposed 框架后，在 Xposed
   中启用该框架。
   
## 使用帮助
   
   **麻花助手**首次运行时，在 Android6.0 + 的设备上需要申请读写SD卡权限，请给予其权限。
   目前**麻花助手**还处于测试期间，功能还不是很完善，在部分设备上运行可能会出现问题。
   首次运行**麻花助手**模块，请重新启动手机（Xposed模块需要）。当然软件已经开源，
   如果您是开发者，您可以定制您需要的功能。部分功能介绍如下：
     
   1. 在“**全局设置**”中，您可以选择是否启用插件，如果此选项为“否”，那么所有的功能都将会禁用；  
   2. 在“**详细设置**”中目前包含“**广告净化**”，“**底部栏设置**”，“**去除5s启动**”三个设置；  
   3. 在“**广告净化**”中，可以自定义广告净化；  
   4. 在“**底部栏设置**”中，可以自定义首页底部五个选项卡的显示与隐藏；  
   5. “**去除5s启动**”开启后，可自动进入首页;  
   <!--6. “**假装微信分享**”开启后，可以在点击微信分享到微信群或者分享到朋友圈后，直接返回，即成功分享。此功能主要用于**观看热门影视**。  -->
   6. “**获取视频地址**”该功能尚处于测试阶段。开启后，将会在视频播放页面添加四个按钮，分别是360P,480P,720P,1080P，点击即可自动复制到剪切板。
   如果没有蓝光特权，则将无法获取到1080P地址。获取到的视频地址是**.m3u8格式**,播放链接的时效性仅有几小时且直接复制到浏览器无法播放，
   请使用视频播放器或者是m3u8视频解析链接播放。**如果播放时一直是0KB/s，请复制该链接至站外播放**。
   
## 问题反馈
* 提交 issue
* 发邮件至 haoyu3@163.com ，邮件主题注明“**麻花助手+版本号**”

## 致谢
   **感谢 “晓星” 帮忙测试Edxposed框架**

## 捐赠

<figure class="half">
    <img src="https://github.com/1595901624/mhzs/blob/master/alipayc.jpg?raw=true">
    &nbsp;
    <img src="https://github.com/1595901624/mhzs/blob/master/wechatc.jpg?raw=true">
</figure>
<!--![支付宝捐赠](https://github.com/1595901624/mhzs/blob/master/alipayc.jpg?raw=true)-->

<!--![微信捐赠](https://github.com/1595901624/mhzs/blob/master/wechatc.jpg?raw=true)-->

   
   
