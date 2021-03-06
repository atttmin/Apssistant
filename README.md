# 简体中文使用说明

## 支持情况

功能\版本号|CC|CS6|CS5|CS4|CS3|CS2|CS|7|6|![Illustrator](https://helpx.adobe.com/content/dam/help/mnemonics/ai_cc_app_RGB.svg)
----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:
**[禁用<kbd>Alt</kbd>菜单键](#1禁用-alt-菜单键)**|😃|😃|😃|😃|😃|😃|😃|😃|😃|😃|
**[前景拾色器快捷键](#2前景色拾色器快捷键)**|😃|😃|😃|🙂|🙂|🙂|🙂|🙂|🙂|🤢|
**[快速创建新图层](#3快速创建新图层)**|😃|😃|😃|😃|😃|😃|😃|😃|😃|🤢|
**[自动保存](#4自动保存)**|😃|😃|😃|😃|😃|😃|😃|😃|😃|🤢|
**[修改撤销 / 重做快捷键](#5修改撤销重做快捷键)**|😃|😃|😃|😃|😃|😃|😃|😃|😃|🤢|
**[锁定为英文输入法](#6锁定为英文输入法)**|😃|😃|😃|😃|😃|😃|😃|😃|😃|🤢|
**🔥[快速旋转笔刷<br>Fast rotating brush](https://gum.co/brotate)**|😃|😃|😃|😃|😃|😃|😃|🤢|🤢|🤢|
**[修改笔刷范围](#7修改笔刷范围)**|😃|😃|😃|😃|🤢|🤢|🤢|🤢|🤢|🤢|
**[自动启动 Photoshop](#8自动启动-photoshop)**|😃|😃|😃|🤢|🤢|🤢|🤢|🤢|🤢|🤢|
**[HUD 拾色器增强](#9hud-拾色器增强)**|😃|😃|😃|💀|💀|💀|💀|💀|💀|🤢|
**[可选扩展界面](#10高级设置)**|😃|💀|💀|💀|💀|💀|💀|💀|💀|💀|

😃 完美支持 | 🙂 支持 | 🤢 不支持 | 💀 无此功能 |

*_后续功能支持仅针对 Photoshop 最新版本_

----------

## 下载

1. [最新版本](https://github.com/millionart/Apssistant/releases/latest)（根据系统选择 x32 或 x64）
2. 解压缩 zip 到任意位置

----------

## 使用说明

1. 运行 Apssistant.exe
2. 选择 Photoshop.exe 位置
3. 右键点击状态栏中 <img src="https://raw.githubusercontent.com/millionart/Apssistant/master/source/Data/tray.ico" width="22px" height="22px" /> 图标，选择 Preferences
4. （可选）选择界面语言
5. 正确选择**当前使用的 Photoshop 版本**
6. （可选）更改其他设置（详见 [功能介绍](#功能介绍)）
7. 保存

----------

## 功能介绍

*_以下全部功能需要在 **常规** 界面正确选择 Photoshop 版本号_

### 1.禁用 <kbd>Alt</kbd> 菜单键

防止单击 <kbd>Alt</kbd> 触发菜单，同时对 Illustrator 生效

*_不支持数位板扩展键_

### 2.前景色拾色器快捷键

#### A.前景色拾色器快捷键加强

##### 使用前：

**点击**快捷键打开前景色拾色器面板，选色，点击确定

缺点：需要多次移动鼠标，操作全部集中在惯用手。

##### 使用后：

**按住**快捷键打开前景色拾色器面板，选色，**松开**快捷键自动确定

优点：双手平衡分工，操作更顺畅自然。

*_Photoshop CS4 及其以前版本（最低至 Photoshop 6）注意：_

在使用 前景拾色器快捷键时需满足以下条件：

* 前景色处于可点击状态（非全屏模式）
* 使用画笔工具或铅笔工具
* 使用系统默认主题

如在非系统默认主题（即经典主题或任何自定义）下不能使用前景拾色器快捷键功能，请选择以下方法之一解决：

* 修改界面颜色——项目“三维物体”——颜色选第五行第一个或在“其他”中选择 色调 34 / 饱和度 83 / 亮度213（红 236 / 绿 233 / 蓝 216）
  * Windows XP 用户：桌面右键菜单——属性——外观——高级——项目“三维物体”
  * Windows 7 用户：控制面板——外观和个性化 ——更改半透明窗口颜色——高级外观设置——项目“三维物体”
* 至 _Data\\Imagesearch\\**PS版本号**_ 目录下修改对应版本的参考图片并以 PNG 格式替换。

#### B.前景色拾色器与滴管工具合并至 <kbd>Alt</kbd>

此功能可将拾色器与 <kbd>Alt</kbd> 取色合并，使用 Photoshop CS5 以前版本的前景色拾色器触发方式。

*_与“禁用 <kbd>Alt</kbd> 菜单键”冲突。_

#### C.前景色拾色器与滴管工具合并至 <kbd>Alt</kbd>（优化）

效果同上，仅 Photoshop CS5 及以上版本可见，使用内置快捷键触发前景色拾色器面板。

*_与“禁用 <kbd>Alt</kbd> 菜单键”冲突。_

### 3.快速创建新图层

点击快捷键快速创建普通图层而无需确认。

*_官方快捷键：<kbd>Alt</kbd><kbd>Shift</kbd><kbd>Ctrl</kbd>+<kbd>N</kbd>_

### 4.自动保存

可选定时提醒及定时静默保存，可关闭。

*_注意：_

保存时间不宜低于2分钟，5分钟以下会有卡顿感。

保存时间过久的文件建议将保存间隔调大。

### 5.修改撤销/重做快捷键

此功能为方便经常重装并习惯改键的用户设计，将默认的4个快捷键循环更换如下：

 *功能* | *修改前* | *修改后*
 :----:|:----:|:----:
后退一步|<kbd>Alt</kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd>|<kbd>Ctrl</kbd>+<kbd>Z</kbd>
还原/重做|<kbd>Ctrl</kbd>+<kbd>Z</kbd>|<kbd>Shift</kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd>
前进一步|<kbd>Shift</kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd>|<kbd>Ctrl</kbd>+<kbd>Y</kbd>
校样颜色|<kbd>Ctrl</kbd>+<kbd>Y</kbd>|<kbd>Alt</kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd>

### 6.锁定为英文输入法

此功能针对亚洲用户设计，防止输入法导致快捷键冲突。

可在系统托盘菜单中开关。

### 7.修改笔刷范围

按住快捷键后可以用鼠标左右移动修改笔刷尺寸、上下移动修改笔刷硬度。

*_仅用于 Photoshop CS4 及以上版本_

### 8.自动启动 Photoshop

设置启动 Apssistant 时自动运行 Photoshop。

*_目前仅支持 Photoshop CS5+（包括 32 位），其他版本待测试。_

### 9.HUD 拾色器增强

此功能只适用于 Photoshop CS5 及以上版本，需在 首选项 中打开 OpenGL 支持方可使用。

打开 OpenGL 方法：

>编辑——首选项——性能——高级设置——启用 OpenGL 绘图

部分显卡不支持此选项（复选框为灰色），可尝试修改注册表或升级显卡驱动（或换显卡……）。

**精确** 勾选“精确”将不需要按住空格键切换选色区域。前景拾色器将自动识别。

**中心** 勾选“中心”将自动定位到屏幕中心显示 HUD 拾色器。

### 10.高级设置

可选扩展界面，具体参数详见官方说明：
[中文](https://helpx.adobe.com/cn/photoshop/kb/enable-optional-extensions-photoshop-cc.html) |
[English](https://helpx.adobe.com/photoshop/kb/enable-optional-extensions-photoshop-cc.html) |
[日本語](https://helpx.adobe.com/jp/photoshop/kb/enable-optional-extensions-photoshop-cc.html) |
[한국어](https://helpx.adobe.com/kr/photoshop/kb/enable-optional-extensions-photoshop-cc.html)

*_英语以外的版本可能内容不全_

----------

## 注意事项

* 快捷键修改不支持数位板扩展键。
* 套索工具状态下使用 HUD 拾色器可能导致假死。
* 连续快速使用快捷键可能导致 Photoshop 不稳定。
* 某些软件可能导致本软件有严重的性能损失，请在使用本软件及 Photoshop 时禁用其 进程/服务。（如 Gdipp、MacType）
* 任何人均不会对本软件造成的任何不良后果承担责任
* 直接运行未经编译的脚本会有性能问题
