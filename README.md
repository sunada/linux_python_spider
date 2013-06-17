my_larbin
===================

I need to collect IPs in the Internet effectively and as many as possible. I use the spider - larbin to help me.

Larbin fetchs and saves htmls and urls. The later one is what I need. In order to save time and hard disk, I modify the code of larbin to only save urls.

The original larbin can be download from http://larbin.sourceforge.net/index-eng.html. However, the original source files can not run successfully. It should be modified to run. The passage (http://www.cnblogs.com/sunada2005/archive/2013/05/07/3064847.html) will help you to install larbin on your linux. (Attension: The passage is written in Chinese.) I have modified the original larbin.  Now it can work for you.

Steps:
1. install gcc/g++/make
2. install makedepend (centos) or use command: "sudo apt-get install xutils-dev" (ubuntu)
3. tar -zxvf my_larbin.tar.gz
4. cd my_larbin
5. ./configure
6. make
7. ./larbin

Then larbin will fetch urls and save it to the directory 'save'.

the 'doc' in my_larbin will help you more.


Becuase I do not need to save html, I remove the function. Replace the original saveuseroutput.cc in my_larbin/src/interf with the one I put in the repo and configure/make the code again, the spider larbin will only save urls.
