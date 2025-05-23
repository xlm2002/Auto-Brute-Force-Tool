基于GO，Python编写的混合爆破脚本

支持多种爆破模式，支持多线程、自动安装依赖、小内存环境爆破、自动安装后门以及字典库等多种功能

root@localhost:~# python3 xui.py

请选择爆破模式：

1.XUI面板爆破  2.哪吒面板爆破

3.HUI面板爆破  4.咸蛋面板爆破

5.SUI面板爆破  6.SSH爆破

7.Sub Store爆破  8.OpenWrt/iStoreOS爆破

输入 1、2、3、4、5、6、7 或 8（默认1）：

是否在SSH爆破成功后自动安装后门，后门命令需存放在（后门命令.txt）？(y/N)：

正在检测网络位置...

网络环境判断结果：非中国大陆（使用官方源）

✅ curl 已存在，跳过安装

✅ pip3 已存在，跳过安装

✅ 模块 requests 已安装

✅ 模块 openpyxl 已安装

✅ Go 1.23 已安装

检查 Go 包 golang.org/x/crypto/ssh ...

✅ 成功安装 Go 模块 golang.org/x/crypto/ssh

>>> 依赖环境检测完成 ✅

=== 爆破一键启动 ===

请输入源文件名（默认 1.txt）：

每个小文件行数（默认 5000）：

爆破完休息秒数（默认 2）：

爆破线程数（默认 250）：

每批次数量（默认 1000）：

是否使用 username.txt / password.txt 字典库？(y/N，默认使用 admin/admin 或 sysadmin/sysadmin 或 root/password): 
