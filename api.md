# API说明
## 概述
所有接口的参数如果传入有误，会返回参数说明，如登陆接口，需要传入*passwd*参数，值为参数，如果传的不是*passwd*，则会返回本接口的说明。



:book:
### 登陆 **login.php**
参数：*passwd*：值为密码

### 修改密码 **changePasswd.php**
参数：*oldPasswd*：旧密码*newPasswd*：新密码

### 布置登陆任务_资源 **addLoginQQ.php**
参数：*loginStr*：QQ号和密码之间用5个逗号隔开 **,,,,,** ，每两组帐号之间用五个横杠隔开 **-----** 。
