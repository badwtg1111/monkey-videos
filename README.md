关于
====
一些常用的油㺅脚本, 主要用于下载音乐, 视频等.

这些脚本只解析出下载链接, 最终还是需要DownThemAll等下载工具. 视频的话也可以
直接播放的, 比如我常用vlc来播放youku的视频, 效果还可以, 至少不会像adobe
flash player那样把cpu拖到100%, 然后风扇使劲地转. vlc的播放效果很好.


安装
====
1. 安装firefox.
2. 安装greasemonkey扩展.
3. 选择你需要的脚本, 比如youtube/, 找到里面的.user.js文件, 下载, 双击,
应该就可以在firefox中打开, 它还会弹出一个提示框, 问你是否允许安装这个脚本,
点允许就可以安装到greasemonkey脚本库了.
4. 访问视频网站, 就可以在页面的右/左下角看到解析好的链接了. 如果需要批量下载
这些视频的话, 我推荐使用DownThemAll这个firefox的扩展, 很方便.


baidu_music
===========
用于下载music.baidu.com里的歌词, 一次能下载一页, 一页有50首, 可以用
DownThemAll 来批量下载, 但问题是, 百度会限制下载量, 一个IP一天只能下载几百
首的样子, 然后就会出错了.

这个脚本有一段时间不用了, 不晓得是否还有效.


youku
=====
解析youku.com的, 这个常用, 我看dota视频时就用它.

它会同时生成一个m3u格式的播放列表, 用vlc打开这个播放列表就可以看啦, 很方便.

之前有朋友要求把它移植到opera, chromium里, 我改了一下, 另存为了
youku-needjs.user.js, 但我没测试过.


youtube
=======
这个也常用, 只能说, youtube太强了, 一般的视频提供了flv, mp4, 3gp, webm等多
种格式, 还有从320p, 480p, 720p, 1080p等不同的分辨率, 相当牛X. 并且不管视频
大小, 都只有一个文件, 不像国内的youku, iqiyi, pptv, cntv之流, 还要把视频切
成n个小片段.


LeTV
====
乐视的, 还行, 暑假用了好多次.


PPS
===
pps的话, 好像还可以播放一些收费的视频, 因为它不像youku那样在服务端进行验证.
这个一段时间没用了.


iqiyi
=====
只想说, iqiyi整天没事儿变个什么劲啊. 它的解析方式这几个月变了好几次, 现在
这个脚本已经不能工作, 我也不想再更新了.

kankan
======
迅雷看看已经可以使用了, 里面的动漫还挺多的, 清晰度很好, 视频也没有被切割成
一段段的, 不需要合并了.

cntv
====
它也是分段的视频, 方式和优酷一样, 也可以得到一个播放列表,点开就能看了, 主要
用它看一些纪录片, 还有[原来如此]这个节目, 暑假给看了一遍.

funshion
========
风行网的还可以吧, 但是视频下到一半有时候就没了速度, 暑假用它下了全套的[星球
大战].

pptv
====
pptv的已经更新.

sohu
====
更新了, 为了看<生活大爆炸>. 支持三种清晰度.

netease
=======
这个能工作, 也可以用来下载公开课等.


tudou
=====
也可以用了, 有些视频会直接重定向到youku.com, 使用youku的视频解析算法.

vimeo
=====
vimeo.com, 里面有一些非常有趣的视频.

acfun
=====
acfun.tv, 由@只是说 推荐的网站.


COPYRIGHT
=========
`Copyright (C) 2013 LiuLang <gsushzhsosgsu@gmail.com>`

依照GNU General Public License v3协议发布, 协议内容请参看LICENSE文件.
