---
# This is the icon of the page
icon: token
# This control sidebar order
order: 5
# A page can have multiple categories
category:
  - Guide
# A page can have multiple tags
tag:
  - Advanced
  - Guide
# this page is sticky in article list
sticky: true
# this page will appear in starred articles
star: true
---

# 2FA

要启用双因素身份验证，需要在手机上安装支持 TOTP 的验证器，例如 [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2)

然后登录 AList 管理并进入“个人资料”页面，点击“启用 2FA”按钮，用你的 2FA 应用扫描二维码，输入你的 2FA 应用生成的代码。

最后，单击“验证”按钮启用 2FA。



## **如何解除2FA验证：**

 如何进入Alist所在的文件夹
   1. **Windows**：进入到Alist所在的文件夹输入：**alist.exe cancel2fa**
   2. **Linux**	   ：也一样进入Alist所在的文件夹输入，**./alist cancel2fa**
   3. **docker**	：docker直接输入 **docker exec -it alist ./alist cancel2fa**

 **以上输入删除后发现还有重启即可~**
