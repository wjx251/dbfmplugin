<h3>当前最新版本为007版本，请使用最新版 本.最新版本主要修复了：不能启动插件</h3>

<h3><font color='red'>【更新】发现有不少朋友说10.10的版本不能使用，这个主要是因为在11.04中使用了新版的rhythmbox,而新的rhythmbox更新了api，因此本插件也更新了相应的代码，导到低于10.10版本带的rhythmbox不能使用，如果你是10.04以下的版本，请升级你的rhythmbox到最新的版本就可以使用本插件了。</font>


<h1>这是什么(Introduction)</h1>

这是一个Rhythmbox的插件。这个插件能够通过你的豆瓣的帐号，连接到豆瓣电台，在线播放随机的歌曲，并支持“喜欢”，“不喜欢”等操作，同步骤到豆瓣电台。<br>
<br>
<h1>屏幕截图(Screenshot)</h1>

<img src='http://hnyangfei.appspot.com/media/aglobnlhbmdmZWlyDQsSBU1lZGlhGLmLBAw/%E5%BC%A0%E4%BF%A1%E5%93%B2%20-%20%E4%B8%8D%E8%A6%81%E5%AF%B9%E4%BB%96%E8%AF%B4_002.png' />

<img src='http://hnyangfei.appspot.com/media/aglobnlhbmdmZWlyDQsSBU1lZGlhGImbBAw/%E8%96%9B%E5%87%AF%E7%90%AA%20-%20%E5%A4%8D%E5%88%BB%E5%9B%9E%E5%BF%86_007.png' />

<img src='http://hnyangfei.appspot.com/media/aglobnlhbmdmZWlyDQsSBU1lZGlhGPGiBAw/%E8%96%9B%E5%87%AF%E7%90%AA%20-%20%E5%A4%8D%E5%88%BB%E5%9B%9E%E5%BF%86_005.png' />

<img src='http://hnyangfei.appspot.com/media/aglobnlhbmdmZWlyDQsSBU1lZGlhGKGQBQw/%E8%8F%9C%E5%8D%95_004.png' />

<h1>功能特性(Feature)</h1>

<blockquote><ul>
<blockquote><li>使用豆瓣电台帐号，播放随机歌曲</li>
<li>当前更表播放完成后，自动刷新新的歌曲列表</li>
<li>对歌曲支持豆瓣电台的“喜爱”，“不喜爱”</li>
<li>支持豆瓣电台的频道列表：例如：粤语歌曲，英文歌曲......</li>
</blockquote></ul></blockquote>

<h1><a href='http://code.google.com/p/dbfmplugin/wiki/ToDo'>待实现的功能</a></h1>

<h1>如何安装(Install)</h1>

<blockquote>下载deb包，点击安装。进入“插件”窗口，设置你的账号。点击播放</blockquote>

<h1>002版本主要新加的功能有：</h1>

1,增加电台频道的选择，可以随心所欲的选择自已喜欢的类型听。<br>
<br>
2,支持对歌典做喜欢，不喜欢的操作，并同步到豆瓣上。<br>
<br>
3,一批歌曲播放完毕后，将清空播放列表，不会象以前一至累加。<br>
<br>
4,修正了部分情况下，放的是公共电台的歌曲，不是放的私人电台歌曲的问题。<br>
<br>
5,修正了部分网络慢的情况下，不自刷新歌曲列表的问题。<br>
<br>
<h1>002版本存在的问题：</h1>

1,由于官方的status-icon（状态图标)插件的关系，默认运行情况下，状态栏菜单没有办法出现。需要到“编辑”-“插件”里面先将status-icon（状态图标)插件先去掉勾选，<br>
<br>
再选中，菜单即可出来。该问题我将会尽快修复，已经写信咨询过了rhythmbox小组，他们暂时还没有回复，回复后即修正该问题。或者你知道解决这个问题的方式，请告诉我一下，谢谢.cdredfox#gmail.com<br>
<br>
<h1>003版本主要新增功能：</h1>
1,本版没有增加任何新功能，主要修正了一个紧急的bug:在ubuntu10.10或Rhythmbox 0.13下不能正常使用的bug<br>
<br>
<h1>004版本主要新增功能：</h1>
1,002，003版中去掉的任务栏图标又回来了，并且不再依赖status-icon插件，打开豆瓣插件就可以用<br>
<br>
2,状态栏菜单的调整，操作起来更清楚<br>
<br>
3,增加了“不再播放”的功能，相当于官网上的那个“垃圾桶”<br>
<br>
4,当选择“取消喜欢”，“不再播放”时，会自动停止当前在播放歌典，跳到下一首播放，并同步到douban<br>
<br>
5,增加了豆瓣官方电台最近新加的三个电台频道<br>
<br>
6,修正了上一版中出现的部分bug<br>
<br>
7,其它内部优化<br>
<br>
<h1>005版本主要新增功能：</h1>

1,增加了豆瓣电台新增的频道 电影原声频道(OSD)<br>
<br>
2,设置界面可以关闭/打开 托盘的豆瓣电台图标,部分用户不太喜欢这个图标，所以提供了关闭的方法，同时也解决了在非ubuntu系统下，报错找不到 appindicator 模块的问题。非ubuntu系统用户，请慎重打开托盘图标。<br>
<br>
3.托盘图标增加了  ［下一首］，·［暂停］ 控制按纽<br>
<br>
ps:新版本中，手盘图标默认是不打开的，如果需要，可以在 插件 的配置界面中，将 是否启用任务栏图标 勾上即可，<br>
<br>
<h1>006版本主要新增功能：</h1>

1.豆瓣新增了两个频道 :电子频道与爵士频道<br>
<br>
2.修改了频道获取方式，以后豆瓣官方推出新的频道，或者修改频道，不用再升级版本。可以同步获取到<br>
<br>
<h1>007版本主要新增功能：</h1>
1.修正了官方增加了R&B电台导致报错的问题<br />
2.修正了rhthmbox修改了API，导致报错然问题