<b>常见问题：</b><br />
1，出现了“No module named appindicator” 详细错误如下：
Traceback (most recent call last):
> File "/usr/lib/rhythmbox/plugins/DoubanFM/init.py", line 8, in 

&lt;module&gt;


> > import appindicator
ImportError: No module named appindicator

(rhythmbox:11232): Rhythmbox-WARNING : Could not load plugin DoubanFM


(rhythmbox:11232): Rhythmbox-WARNING : Error, impossible to activate plugin '豆瓣电台插件'

因为插件使用了python的appindicator 模块，请使用sudo apt-get install python-appindicator安装python-appindicator 模块，安装后就可以正常使用了