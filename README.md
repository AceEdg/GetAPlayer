# 一个整合了(所有?)web悬浮播放器的库

## 01.APlayer
> 原项目地址：https://github.com/DIYgod/APlayer
>
> MetingJS插件(是为 APlayer 添加网易云、QQ音乐等支持的插件): https://github.com/metowolf/MetingJS
#### 直接引入到`<head>`
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/AceEdg/GetaMusicPlayer@main/aplayer/css/APlayer.min.css">
```
#### 直接引入到`<body>`
```
<div id="aplayer"></div>
<script src="https://cdn.jsdelivr.net/gh/AceEdg/GetaMusicPlayer@main/aplayer/js/APlayer.min.js"></script>
```
#### 导入配置文件`APlayer-config.js`(文件在aplayer文件夹里)
```
<script src="https://cdn.jsdelivr.net/gh/AceEdg/GetaMusicPlayer@35b60c41c02faecb68389bc78e63464168b819a0/aplayer/APlayer-config.js"></script>
```
 `APlayer-config.js`**文件可自定义修改,详情可自定义的参数可查看官方文档**`https://aplayer.js.org/#/zh-Hans/?id=%E5%8F%82%E6%95%B0`
 
## 1.1(不想手动添加音源可以使用)APlayer+MetingJS插件
#### 和上面一样直接引入到`<body>`(不需要删除任何代码)
```
<script src="https://cdn.jsdelivr.net/npm/meting@2/dist/Meting.min.js"></script>
```
***注意：MetingJS插件的配置文件无法和Aplayer原生配置文件互用***
#### ↓↓↓所以这是MetingJS的配置代码，也是是直接引入`<body>`
```
<meting-js
	name="rainymood"
	artist="rainymood"
	url="https://rainymood.com/audio1110/0.m4a"
	cover="https://rainymood.com/i/badge.jpg"
	fixed="true">
	<pre hidden>
		[00:00.00]This
		[00:04.01]is
		[00:08.02]lyric
	</pre>
</meting-js>
```
**↑↑↑代码可自定义修改(参数和APlayer原生配置差不多)**

## 02.xf-MusicPlayer
> 原项目地址: https://gitee.com/xfwlclub/xf-MusicPlayer
#### 直接引入到`<body>`
```
<!-- 配置播放器 -->
<div id="xf-MusicPlayer"></div>

<!-- 引入插件 -->
<script src="/xf-MusicPlayer/js/xf-MusicPlayer.min.js"></script>
```

## 03.QPlayer
> 原项目地址: https://github.com/Jrohy/QPlayer
> 
> WordPress版: https://github.com/Jrohy/QPlayer-WordPress-Plugin
>
> https://moeshin.com/archives/QPlayer2-WordPress.html
>
> Z-Blog版: https://moeshin.com/archives/QPlayer2-ZBlog.html
>
>   https://github.com/moeshin/QPlayer2-ZBlog
>
> Typecho版：https://moeshin.com/archives/QPlayer2-Typecho.html
>
>   https://github.com/moeshin/QPlayer2-Typecho
#### 直接引入到`<head>`
```
<link rel="stylesheet" href="css/player.css">
```
