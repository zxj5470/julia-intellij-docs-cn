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

For detailed use instruction, visit: https://julia-intellij.readthedocs.io/en/latest/

想要获取最新的不稳定版本，请访问：https://ci.appveyor.com/project/ice1000/julia-intellij/build/artifacts/

## 截图

![](https://plugins.jetbrains.com/files/10413/screenshot_17880.png)
![](https://plugins.jetbrains.com/files/10413/screenshot_17879.png)
![](https://plugins.jetbrains.com/files/10413/screenshot_17881.png)

## IDE 适用版本

本插件适用范围为
The plugin is compatible with any IntelliJ based IDE starting from 2016.1.
如果你还没有，请下载[IntelliJ IDEA 社区版](https://www.jetbrains.com/idea/),
免费哒！

## 备选方案

如果你不喜欢JetBrains IDE, 出门右拐搜索`JuliaPro` 或者 `Juno`.

或者:<br/>
在GitHub上搜索"Julia IntelliJ" (截止到2018/1/28),
有4个相关的repositories:

+ snefru/juliafy (incomplete syntax highlight, SDK management, file recognizing, only support MacOS)
+ sysint64/intellij-julia (this only recognize your file as a `Julia file`, and do nothing else)
+ satamas/julia-plugin (ditto)
+ ice1000/julia-intellij (超级多的 [功能特性](https://julia-intellij.readthedocs.io/en/latest/Features.html), can't list here)

知道该选什么了吧 😉

## Contributing

You're encouraged to contribute to the plugin in any form if you've found any issues or missing functionality that you'd want to see.
Check out [CONTRIBUTING.md](./CONTRIBUTING.md) to learn how to setup the project and contributing guidelines.

## Contributors

+ [@ice1000](https://github.com/ice1000)
+ [@zxj5470](https://github.com/zxj5470)
+ [@HoshinoTented](https://github.com/HoshinoTented)
+ [@Hexadecimal](https://github.com/Hexadecimaaal)
