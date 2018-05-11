# API说明
## 概述
所有接口的参数如果传入有误，会返回参数说明，如登陆接口，需要传入*passwd*参数，值为参数，如果传的不是*passwd*，则会返回本接口的说明。



:book:
### 登陆 **login.php**
参数：*passwd*：值为密码

### 修改密码 **changePasswd.php**
参数：*oldPasswd*：旧密码
参数2：*newPasswd*：新密码

### 布置登陆任务_资源 **addLoginQQ.php**
参数：*loginStr*：QQ号和密码之间用5个逗号隔开 **,,,,,** ，每两组帐号之间用五个横杠隔开 **-----** 

### 布置加QQ好友_资源 **addAddQQ.php**
参数：*addQQStr*：每两个QQ号之间用五个逗号隔开

### 布置加QQ群_资源 **addAddQun.php**
参数：*addQunStr*：每两个群号之间用五个逗号隔开

### 布置昵称_资源 **addNick.php**
参数：*nickStr*：每两个昵称之间用五个逗号隔开

### 布置头像_资源 **addAvatar.php**
参数：*avatarStr*：每两个头像的base64之间用五个逗号隔开

### 布置会话内容_资源 **addSendText.php**
参数：*addStrStr*：，每两个会话之间用五个逗号隔开

### 布置会话图片_资源 **addSendImg.php**
参数：*addImgStr*：每两个图片base64之间用五个逗号隔开

### 布置gps_资源 **addGps.php**
参数：*gpsStr*：每两组gps之间用五个逗号隔开

### 布置打码账号密码_资源 **addDama.php**
参数：*loginStr*：帐号和密码之间用5个逗号隔开 **,,,,,** ，每两组帐号之间用五个横杠隔开 **-----** 
