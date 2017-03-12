#网易音乐盒

使用 [Electron](http://electron.atom.io/) 构建的网易云音乐的跨平台第三方客户端。

项目来源于 [stkevintan](https://github.com/stkevintan) 的使用 [NW.js](https://github.com/nwjs/nw.js) 构建的网易云音乐的跨平台第三方客户端 --- [Cube](https://github.com/stkevintan/Cube)。

我将该应用从 [NW.js](https://github.com/nwjs/nw.js) 平台迁移至  [Electron](http://electron.atom.io/) 平台运行。

##搭建

###1、初始化：

需要安装好 [node.js](https://nodejs.org/en/) 环境，使用 npm 安装依赖包：

	git clone https://github.com/issac2015/Cube-In-Electron.git
	cd Cube-In-Electron/app
	npm install 

如果由于网络问题，安装不了依赖包，可以使用淘宝的 [cnpm](https://npm.taobao.org/) 来安装。


###2、在 [Electron](http://electron.atom.io/) 平台中运行

2.1、下载 [Electron](http://electron.atom.io/) 平台

	git clone https://github.com/electron/electron.git

由于网络问题，在国内下载速度一般很慢。可以选择淘宝NPM镜像提供的electron压缩包。[https://npm.taobao.org/mirrors/electron/](https://npm.taobao.org/mirrors/electron/)

如：[https://npm.taobao.org/mirrors/electron/1.6.1/electron-v1.6.1-win32-x64.zip](https://npm.taobao.org/mirrors/electron/1.6.1/electron-v1.6.1-win32-x64.zip)

如果你想在 Linux 系统或 Mac系统中运行，只需下载对应系统下的 [Electron](http://electron.atom.io/) 平台即可。

2.2、运行 app 应用

方法一：解压压缩包，进入该目录，双击 “electron.exe”，然后把 “app” 文件夹拖拽进去即可运行。

<img src="/images/img-1.png" style="display: block;margin: auto;width: 450px;"/>

方法二：进入解压目录后（即与“electron.exe”同路径下），将“app”文件夹复制进 “resources”文件夹中。

再次双击“electron.exe”就可以打开该应用。

##截图

导入本地音乐文件：

<img src="/images/img1.png" style="display: block;margin: auto;width: 450px;"/>

搜索歌曲：

<img src="/images/img2.png" style="display: block;margin: auto;width: 450px;"/>

私人FM：

<img src="/images/img3.png" style="display: block;margin: auto;width: 450px;"/>

设置界面：

<img src="/images/img4.png" style="display: block;margin: auto;width: 450px;"/>


##备注

这个文件夹`Cube-In-Electron\app\src`中存放的是 [Cube](https://github.com/stkevintan/Cube) 项目的源码，使用 [gulp](http://www.gulpjs.com.cn/) 打包后，[Cube](https://github.com/stkevintan/Cube) 项目生成的压缩文件输出在 `Cube-In-Electron\app\dist`文件夹中。





