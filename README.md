# IX-RXV2

# 部署提示

|**注意事项**|
|:---------|
|**因使用本项目执行其他活动所产生的所有后果本项目概不负责！！！！**|
|**禁止向任何网站转发本项目！！！！**|
|**注意项目名字中不要包含Shadowsocks（ss）、VLESS、VMESS、Trojan（tj）、Xray、V2ray**|
|**如果能继续使用的，请保持低调！！！**|
|**滥用可能导致账户被删除！！！**|
|**![捕获11](https://user-images.githubusercontent.com/97718560/149460474-ef468afb-94c4-4138-8794-93c2b9d8028a.png)<br>点击Use this template后修改项目名，将readme.md中的Cptmacmillan2022007替换为自己的用户名和修改后的项目名再进行部署，非常重要，切记！！！！**|
|**若出现We couldn't deploy your app because the source code violates the Salesforce Acceptable Use and External-Facing Services Policy.提示，则返回仓库，>Setting>Repository name修改仓库名。**|
|**选择不向任何网站转传是为了更长久的相聚，愿你能发现墙外美好而又有趣的地方。**|
|**带有删除线的部分表示不适用或已经废弃。**|
|**目前heroku只支持http1.1，请不要再问是否支持tcp等其他协议。**|

# Xray/V2Ray VLESS
|**属性**|**值**|
|:------:|:----:|
|**地址**|优选IP<br>应用名.heroku.com|
|**端口**|443|
|**用户ID**|87b5c352-90d7-4ee1-9d1e-b03231c9fc53<br>**注意：务必使用自己创建的UUID。不要使用本项目中示范的UUID！**|
|**流控**|n/a|
|**加密**|none|
|**传输协议**|ws|
|**伪装类型**|none|
|**伪装域名**|xxxx.workers.dev(CF Workers反代地址)<br>应用名.heroku.com|
|**路径**|/ID-vless|
|**底层传输安全**|tls|
|**跳过证书验证**|false|
|**SNI**|xxxx.workers.dev(CF Workers反代地址)<br>应用名.heroku.com|

# Xray/V2Ray Trojan
|**属性**|**值**|
|:------:|:----:|
|**地址**|优选IP<br>应用名.heroku.com|
|**端口**|443|
|**用户ID**|87b5c352-90d7-4ee1-9d1e-b03231c9fc53<br>**注意：务必使用自己创建的UUID。不要使用本项目中示范的UUID！**|
|**流控**|n/a|
|**加密**|none|
|**传输协议**|ws|
|**伪装类型**|none|
|**伪装域名**|xxxx.workers.dev(CF Workers反代地址)<br>应用名.heroku.com|
|**路径**|/ID-trojan|
|**底层传输安全**|tls|
|**跳过证书验证**|false|
|**SNI**|xxxx.workers.dev(CF Workers反代地址)<br>应用名.heroku.com|

# Trojan Ws+Tls客户端支持状态
|**客户端**|**是否支持Trojan Ws+Tls？**|
|:--------:|:------------------------:|
|**2dust V2RayN<br>2dust V2RayNG**|是，需要电脑端4.27以上版本且有.net framework 6.0及更高版本<br>手机端敬请期待|
|**OpenWrt SSRPlus**|是|
|**OpenWrt SSRPlus**|是，需要最新版本passwall|
|~~**QV2Ray**~~|~~否~~|

# CloudFlare Workers反代代码

