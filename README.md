**操作步骤**

1、打开`Shadowrocket`  

2、开启**HTTPS解密**并**安装、信任**Shadowrocket证书：

`配置` → 配置文件右边的`i` → `HTTPS解密` → 开启`HTTPS解密` → `生成新的CA证书` → 允许 → 返回点击`安装证书`，并点击`允许` → 前往手机的`设置` → 看到`已下载描述文件` → `安装` → 输入手机的解锁密码 → `安装` → `安装` → 前往手机的`设置` → `通用` → `关于本机` → `证书信任设置` → 找到`Shadowrocket…`点绿它以信任该根证书 → `继续`  

3、点击`配置` → `模块` → 右上角加号，添加想看国家的对应模块。

**日本**

```
https://raw.githubusercontent.com/prgding/TikTok/master/TiKTok-JP.conf
```

**台湾**

```
https://raw.githubusercontent.com/prgding/TikTok/master/TiKTok-TW.conf
```

**韩国**

```
https://raw.githubusercontent.com/prgding/TikTok/master/TiKTok-KR.conf
```

**美国**

```
https://raw.githubusercontent.com/prgding/TikTok/master/TiKTok-US.conf
```

4、添加以下`分流`，点击`配置` → 你使用的配置后的`i` → `规则` → 右上角加号 → `类型` → 选择`RULE-SET` → 策略 → 选择`PROXY`或者其他你想使用的策略（一般是对应地区的代理服务器节点） → 规则集URL文本框内填写

```
https://raw.githubusercontent.com/prgding/TikTok/master/TikTok.list
```

---

### 
