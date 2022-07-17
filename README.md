# c_7652
最新2022网易云代挂源码-每天300首
<br/></br>
[下载地址](https://www.uuid2.com/7652.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>支持充值 会员使用 每日签到打卡任务 刷歌曲播放 刷粉丝等
第一步
把安装包上传到服务器并解压
第二步
把cniao8.sql导入到数据库
第三步
在application\database.php文件设置数据库连接名 用户名 密码
必须设置伪静态 宝塔可以直接选择thinkphp的伪静态保存即可
第四步
https://console.cloud.tencent.com/captcha/graphical申请一个图形验证，登录后台域名/admin 初始账户admin初始密码123456 然后系统设置把申请到的APPID 和App Secret Key，默认操作全部需要VIP可以在后台修改，建议手动签到和打卡无需VIP
填入保存（不填写用户无法登录）
第五步
之后监控两个地址：http://apics.isfx.cn/api/api/song?key=监控密钥 和 http://apics.isfx.cn/api/api/sign?key=监控密钥
监控密钥在后台可以设置 监控时间可以自己先访问这两个url根据每次监控返回时间设置时间，可以用宝塔计划任务-访问URL（但宝塔最低设置监控一分钟）
伪静态规则
code
location / {
 if (!-e $request_filename){
   rewrite  ^(.*)[        Discuz_CODE_1        ]nbsp; /index.php?s=$1  last;   break;
 }
}<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/uimage/40861641798242.gif" alt="最新2022网易云代挂源码-每天300首">
