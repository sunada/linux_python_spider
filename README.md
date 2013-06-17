linux_python_spider
===================

I need to collect IPs in the Internet effectively and as many as possible. I use the spider - larbin to help me.

Larbin record htmls and urls. The later one is what I wanted. In order to increase the effection and save hard disk, I modify the code of larbin. Then, I get distinct hosts from these urls. Finally, I use python-build-adns and give it different nameservers to resolve the hosts and got IPs.

The original larbin can be download from http://larbin.sourceforge.net/index-eng.html. However, the original source files should be modified to install. The passage (http://www.cnblogs.com/sunada2005/archive/2013/05/07/3064847.html) will help you to install larbin on your linux. (Attension: The passage is written in Chinese.)






