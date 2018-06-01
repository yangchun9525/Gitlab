# Gitlab
Gitlab
---
1.去https://gitlab.com/  上新建一个账号 <br>
2.new一个project<br>
3.生成ssh<br>
4.将ssh文件添加入ssh输入框中<br>
5.上传代码<br>

如何生成ssh
---
1.打开git.bash执行

    ssh-keygen -t rsa -C "1434088223@qq.com" -b 4096<br>
2.当设置passphrase时，直接跳过<br>
3.打开id_rsa.pub文件，里面的key就是ssh<br>
