http://hackerzhou.me/2012/04/accelerate-apps-store.html/comment-page-2

完整版脚本可以直接用(sudo) python optimize_app_store_hosts.py调用，运行完成后会在当前目录下生成两个文件，apple_ip.txt包含了App Store不同的IP地址以及各自的ping响应时间，hosts文件包含了一个自动选取ping响应最快的那个IP生成的hosts列表，大家贴到C:\Windows\system32\drivers\etc\hosts（Windows），/etc/hosts（Mac）文件中就可以了，同时也可以传到越狱了的苹果设备中去。

Note: Windows 用户执行命令python optimize_app_store_hosts.py，Mac用户执行sudo python optimize_app_store_hosts.py，因为Mac下只有root可以发出ICMP数据包。
