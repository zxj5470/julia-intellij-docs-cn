# Julia plugin for the IntelliJ Platform 中文文档

目前还在**开发**中，很多特性有待实现，可能会有一些小问题。

[![](https://tinyurl.com/y9e4n2zh)](https://github.com/ice1000/julia-intellij)
[![JetBrains plugins](https://img.shields.io/jetbrains/plugin/v/10413-julia.svg)](https://plugins.jetbrains.com/plugin/10413-julia)
[![JetBrains plugins](https://img.shields.io/jetbrains/plugin/d/10413-julia.svg)](https://plugins.jetbrains.com/plugin/10413-julia)
[![Join the chat at https://gitter.im/julia-intellij/Lobby](https://badges.gitter.im/julia-intellij/Lobby.svg)](https://gitter.im/julia-intellij/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<table>
  <tr>
    <th>CI</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>Travis CI (with IdeaC)</td>
    <td><a href="https://travis-ci.org/ice1000/julia-intellij"><img src="https://travis-ci.org/ice1000/julia-intellij.svg" alt="Travis CI Build status"></a></td>
  </tr>
  <tr>
    <td>AppVeyor (on Windows)</td>
    <td><a href="https://ci.appveyor.com/project/ice1000/julia-intellij"><img src="https://ci.appveyor.com/api/projects/status/jboqu7yt2vhqpmfr?svg=true" alt="AppVeyor Build status"></a></td>
  </tr>
  <tr>
    <td>CircleCI (with tests)</td>
    <td><a href="https://circleci.com/gh/ice1000/julia-intellij"><img src="https://circleci.com/gh/ice1000/julia-intellij.svg?style=svg" alt="CircleCI Build status"></a></td>
  </tr>
  <tr>
    <td>CodeShip (branch master)</td>
    <td><a href="https://app.codeship.com/projects/270342"><img src="https://app.codeship.com/projects/4c89a940-ec81-0135-9688-6eaa099eb415/status?branch=master" alt="CodeShip Build status"></a></td>
  </tr>
</table>
<p>

## 安装与使用

安装有IntelliJ IDEA (或其他JetBrains的IDE比如`PyCharm/CLionGoLand`等),
打开设置 `Settings | Plugins | Browse repositories`,
安装 `Julia` 插件, 然后创建工程


想要提前获取新的版本，请访问：[https://ci.appveyor.com/project/ice1000/julia-intellij/build/artifacts/](https://ci.appveyor.com/project/ice1000/julia-intellij/build/artifacts/)
想要了解 test 运行的情况，请访问 [https://circleci.com/build-insights/gh/ice1000/julia-intellij/master](https://circleci.com/build-insights/gh/ice1000/julia-intellij/master) .

### 视频介绍

+ YouTube上的英文介绍 : [https://www.youtube.com/watch?v=gjRhvPBiasU](https://www.youtube.com/watch?v=gjRhvPBiasU)
+ B站上的中文介绍: [https://www.bilibili.com/video/av20155813](https://www.bilibili.com/video/av20155813)

## 截图 

![](https://plugins.jetbrains.com/files/10413/screenshot_17880.png)
![](https://plugins.jetbrains.com/files/10413/screenshot_17879.png)
![](https://plugins.jetbrains.com/files/10413/screenshot_17881.png)
![](https://plugins.jetbrains.com/files/10413/screenshot_17891.png)
![](https://plugins.jetbrains.com/files/10413/screenshot_17932.png)
![](https://github.com/zxj5470/julia-intellij-docs-cn/blob/master/screenshots/pkg-manager.gif?raw=true)
### 绘图
![](https://user-images.githubusercontent.com/20026798/49950430-c72f1780-ff32-11e8-8498-68ebcad8c4b5.gif)

### 数据 (工作区)
![](https://user-images.githubusercontent.com/20026798/50019689-91f7f780-000e-11e9-85ce-ab602cab6505.png)

### 调试器
> 基于 DebuggerFramework 和 ASTInterpreter2
![](https://user-images.githubusercontent.com/20026798/50418049-670a7080-0864-11e9-96cf-d0ebc5b26431.gif)

## IDE 适用版本

本插件适用范围为基于IntelliJ平台的 IDE (PyCharm/CLion/PhpStorm等。版本号大于2016.1)
如果还没有相关 IDE ，请下载[IntelliJ IDEA 社区版](https://www.jetbrains.com/idea/), 这玩意免费哒！

## 备选方案

如果你不喜欢 JetBrains 家的 IDE, 出门右拐搜索 `JuliaPro` 或者 `Juno`.

或者:<br/>
在GitHub上搜索"Julia IntelliJ" (截止到2018/1/28),
有4个相关的repositories:

+ snefru/juliafy (incomplete syntax highlight, SDK management, file recognizing, only support MacOS)
+ sysint64/intellij-julia (this only recognize your file as a `Julia file`, and do nothing else)
+ satamas/julia-plugin (ditto)
+ ice1000/julia-intellij (超级多的 [功能特性](https://julia-intellij.readthedocs.io/en/latest/Features.html), can't list here)

知道该选什么了吧 😉

## Contributing
如果你已经找遍了issues里面的内容还是缺少你想要的功能的话，
欢迎翻阅[CONTRIBUTING.md](./CONTRIBUTING.md)的内容，里面有如何建立工程和开发指南。

## Contributors

+ [@ice1000](https://github.com/ice1000)
+ [@zxj5470](https://github.com/zxj5470)
+ [@HoshinoTented](https://github.com/HoshinoTented)
+ [@Hexadecimal](https://github.com/Hexadecimaaal)
