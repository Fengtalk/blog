# 针对SSH 协议(ssh://)配置代理向 GitHub 提交代码

使用 ssh 的好处就是在 clone 数据,或者提交数据到 github.com 时,不用在输入 github 的帐号密码.
下面是 ssh 的设置,打开 ~/.ssh/config 输入:

	Host github*
    	User git //你的用户名
    	Hostname github.com
    	Port 22
    	Proxycommand ssh root@proxy.yourcompany.com nc %h %p //你的代理服务器
    	IdentityFile  ~/.ssh/id_rsa
