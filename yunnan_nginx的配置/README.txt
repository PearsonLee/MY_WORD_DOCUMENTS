
8.31上安装了solea和eagle
solea需要跳转8.33上的kujira
针对红网登陆solea做了nginx跳转配置

格尔网管上配置：
1. 添加kujira的跳转
2. 因为eagle不需要跳转kujira，同时dais4上程序中已经写死了对eagle访问的url，所以不修改端口号，

8.31上的配置：
3. 修改8.31上tomcat的监听端口号为8081，
4. 可以通过yum安装nginx，配置/etc/nginx下的nginx.conf文件
