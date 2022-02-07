# 概述
自用

本项目仅限学习交流使用, 用于商业用途产生的纠纷或使用该项目进行非法牟利, 产生一切不当后果与本人无关

本仓库仅用于个人学习使用!!!本仓库仅用于个人学习使用!!!本仓库仅用于个人学习使用!!!
禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。本仓库拥有者对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失!

#手机运行:
# 安卓手机安装运行方法:[点击查看](https://github.com/hajiuhajiu/jdsign1112/blob/master/icon/Termux.md)

# git hub action
禁action跑，Action 打开方式 setting--actions ......Actions permissions
.........Allow all actions...save 

# docker 一键安装：
下载putty，进入终端，复制下面命令，按提示操作，默认回车：
wget https://cdn.jsdelivr.net/gh/hajiuhajiu/jd-base@main/install_scripts/docker_install_jd.sh -O docker_install_jd.sh && chmod +x docker_install_jd.sh && bash docker_install_jd.sh

安装完成后输入docker设备地址如192.168.1.1:5678 用户名admin密码admin5678 添加cookie，设定运行时间即可。

# 扫码获取ck失效! 需要手动找cookie[点击查看](https://github.com/hajiuhajiu/scripts/blob/master/icon/GetJdCookie.md)  

安装docker可视化管理工具portainer,管理docker容器察看状态 
两步安装, 安装完成后 输入 ip地址:9000 (如:http://192.168.1.1:9000/)访问
docker pull portainer/portainer

docker run -d -p 9000:9000 -v /root/portainer:/data -v /var/run/docker.sock:/var/run/docker.sock --name dev-portainer portainer/portainer
