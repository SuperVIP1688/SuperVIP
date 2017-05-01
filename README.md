# 淘宝金币一键领取
<a href="http://www.duoduodazhe.com/App/Web/Taobao-Coin/" target="_blank">演示页面</a>

[源码下载](https://code.aliyun.com/duoduo/Taobao-Coin/repository/archive.zip?ref=master)

# 应用设置简要介绍
#### 网站统计
`index.html`
```html
<footer>
    <div class="hidden">
        <script>
            // 网站统计代码区域
            var _hmt = _hmt || [];
            (function() {
                var hm = document.createElement("script");
                hm.src = "https://hm.baidu.com/hm.js?aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa";
                var s = document.getElementsByTagName("script")[0];
                s.parentNode.insertBefore(hm, s);
            })();
        </script>
    </div>
</footer>
```
#### 样式编辑
`css/style.css`
```css
body {
    /*移动设备背景图片*/
    background-image: url("//cdn.qnssl.com/uploads/2017-03-03/0000.png");
}
.content {
    /*移动设备中心区域背景颜色*/
    background-color: #ddd;
    /*移动设备中心区域不透明度*/
    opacity: 0.8;
}

@media screen and (min-width: 999px) {
    body {
        /*电脑设备背景图片*/
        background-image: url("//cdn.qnssl.com/uploads/2017-03-03/0001.png");
    }
    .content {
        /*电脑设备中心区域背景颜色*/
        background-color: #ddd;
        /*电脑设备中心区域不透明度*/
        opacity: 0.8;
    }
}
```

#### 脚本编辑
`js/common.js`
```javascript
$(function() {
   $("#page").fadeIn(3000); // 淡入页面
});
```

#### 功能设置
`js/config.js`
```javascript
// 网站设置
var name = "官方网站"; // 网站名称（主站名称）
var home = "http://www.duoduodazhe.com/"; // 网站地址（主页网址）
var ICP = ""; // 网站备案/许可证号（可以不填）。举个栗子：var ICP = "京ICP证030173号-1";
var Mail = ""; // 站长邮箱（用于接收更新提醒）。举个栗子：var Mail = "admin@mail.com";

// 版本信息（不要修改）
var Version = 20170303;

// 功能设置　开启功能：true　关闭功能：false
var Ads = true; // 显示广告
var BaiduPush = true; // 百度推送
var Clock = true; // 页面时钟
var Remind = true; // 零点提醒
var Share = true; // 分享功能


// 广告设置
// 阿里妈妈（mm_memberid_siteid_adzoneid）
var Pid_Link = "mm_00000000_00000000_00000000"; // 淘宝联盟
var Pid_Window = "mm_00000000_00000000_00000000"; // 橱窗推广
```

# 附加功能开发进度
- [x] 广告开关
- [x] 百度推送
- [ ] 页面时钟
- [ ] 零点提醒
- [x] 分享功能
- [x] 广告设置

# 版权信息
#### 版权声明
- **版权归属**：`多多打折`
- **官方网站**：`http://www.duoduodazhe.com/`
- **演示页面**：`http://www.duoduodazhe.com/App/Web/Taobao-Coin/`
- **开源地址**：`https://code.aliyun.com/duoduo/Taobao-Coin`
- **源码下载**：`https://code.aliyun.com/duoduo/Taobao-Coin/repository/archive.zip`

#### 技术支持
- **邮箱地址**：`77518290`@`qq.com`
