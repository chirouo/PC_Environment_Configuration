# 新电脑



## 触摸板

改三指当中指

## 必用软件清单

沟通：

- QQ
- 微信
- 腾讯会议

网盘：

- 百度网盘
- 夸克网盘
- 迅雷

娱乐：

- qq音乐
- bilibili

web开发（可选）：

- navicate17（百度网盘）
- apifox

JB全家桶：

- 2023版本idea（百度网盘）
- 2023版本pycharm（百度网盘）

文档：

- zotero
- xmind
- 腾讯文档
- onenote（微软自带）
- wps（[教学1](https://www.bilibili.com/video/BV1UW4Ce8EWo/)[教学2](https://www.bilibili.com/video/BV1dysSepEUo/)）注：这两个教学看一下再装wps
- word（微软自带）
- excel（微软自带）
- powerpoint（微软自带）

编辑器：

- vscode

工具：

- ToDesk
- Clash for Windows / Clash Verge
- geek
- everything
- 7zip
- snipaste
- utools

linux：

- VMware（百度网盘）
- MobaXterm（百度网盘）

## 文件目录结构

- SchoolStudy
- Temp
- 将SchoolStudy、Temp、用户文件夹固定到快速访问

## windows右键“新建”自定义（regedit）

[视频](https://www.bilibili.com/video/BV12g411F79m/):

1. 通过改.md项的ShellNew 

   - 增加一个NullFile（新建空白文件）或

   - FileName（新建模板文件，值填模板文件的路径）

2. 通过改.md项的默认值"XX" + 新建一个项对应前面的默认值"XX",值填你想要的名字“XX”
   - 修改新建项时项的名字

3. 通过改计算机\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Discardable\PostSetup\ShellNew
   中的`class `

   - 排序 新建的项

   - 删除 不需要的新建项

   注：BMP文件不在class中，要想删除参考这篇[博客](https://www.cnblogs.com/[![img](https://i0.hdslb.com/bfs/reply/9f3ad0659e84c96a711b88dd33f4bc2e945045e0.png)live41](https://search.bilibili.com/all?from_source=webcommentline_search&keyword=live41&seid=6595502123390268598)/p/18214635)

## windows自定义右键的快捷打开程序

[博客]([windows11右键菜单新增项增加md文件，使用Typora_如何将typore加到右键菜单里-CSDN博客](https://blog.csdn.net/qq_42445433/article/details/127549533))：

1. 方案一：重点关注
2. 方案二：和本节无关，实际内容是“自定义右键新建项”

# 开发环境配置

## 后端环境配置

[博客](https://blog.csdn.net/chirou_/article/details/144530654)：
软件：navicate17、mysql8安装、maven安装（包含配置settings）、idea2023安装

springboot2 mysql8 maven

## 配置文件

.vimrc

.ideavimrc --mklink--> .vimrc
