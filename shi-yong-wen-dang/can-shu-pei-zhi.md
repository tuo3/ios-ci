config.json 配置说明

##### 一级数组

项目的缩写，例如 临海麻将=&gt;lhmj

##### 二级数组

项目的通用参数

* app\_name App名称

* url\_scheme  同魔窗配置

* wechat\_appid 微信AppId
* wechat\_appsecret 
* splashscreen\_logo
* enterprise
* app-store 

##### 三级数组

具体打包方式下的参数

* bundle\_id 
* apple\_id
* apple\_passwd
* apple\_team\_id
* apple\_codesigning\_identity
* channel\_no
* magicwindow\_appkey
* getui\_appid
* getui\_appkey
* getui\_appsecret



##### 完整示例：

```
    "app_name":"多多开化麻将",  
    "url_scheme":"ddkhmj",
    "wechat_appid":"wx7f90037f86595d61",
    "wechat_appsecret":"d28585616e5ceb3a6fac0be8b233fa1f",
    "splashscreen_logo":"shanshan",
    "enterprise":{
      "bundle_id":"cn.duoduo100.khmj2",
      "apple_id":"it.service@linjiahaoyi.com",
      "apple_passwd":"Ljhy2016!",
      "apple_team_id":"N7PE9Q52X4",
      "apple_codesigning_identity":"iPhone Distribution: Shanghai GeGe Medical Technology Co., Ltd",
      "channel_no":"70020002",
      "magicwindow_appkey":"YZS2DC100FDC4SG6KIV6L0DEFPK53GN8",
      "getui_appid":"vGpoXDrCal5tG4mNLwe8p5",
      "getui_appkey":"g3lKudHq29A7Xm9RdMcIO8",
      "getui_appsecret":"GQmOoyR0VOAg9vNvUI95fA"
    },
    "app-store":{
      "bundle_id":"cn.duoduo100.khmj",
      "apple_id":"wangjunyang100@sina.cn",
      "apple_passwd":"Tuomi12345",
      "apple_team_id":"XAAG59Q9H9",
      "apple_codesigning_identity":"iPhone Distribution: wang junyang",
      "channel_no":"70020003",
      "magicwindow_appkey":"YZS2DC100FDC4SG6KIV6L0DEFPK53GN8",
      "getui_appid":"vGpoXDrCal5tG4mNLwe8p5",
      "getui_appkey":"g3lKudHq29A7Xm9RdMcIO8",
      "getui_appsecret":"GQmOoyR0VOAg9vNvUI95fA"
    }
  },
```



