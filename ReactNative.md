


---
title: ReactNative 学习日记
date: 2018-01-12 19:14:08
tags: ReactNative

---

> 这一篇是记录在[ReactNative中文网](https://reactnative.cn)学习，其中一些爬坑日记。

## 环境配置

> 个人的开发环境：Mac + iOS
>
>基于React Native 0.51
>
> 首要目标：react-native run-ios


配置环境，react-native的环境依赖；安装必须环境：
#### Homebrew

Mac 系统的包管理器，用于安装 NodeJS 和一些其他必需的工具软件。

> 打开终端，复制进去  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

#### Node

使用 Homebrew 来安装 Node.js.
> 终端输入  brew install node

<!--more-->

#### Yarn

Yarn 是 Facebook 提供的替代 npm 的工具，可以加速 node 模块的下载。React Native 的命令行工具用于执行创建、初始化、更新项目、运行打包服务（packager）等任务。

> npm install -g yarn react-native-cli

#### Xcode

作为iOS开发，这个必须会了，电脑上已安装。

#### Watchman

Watchman 是由 Facebook 提供的监视文件系统变更的工具。安装此工具可以提高开发时的性能（packager 可以快速捕捉文件的变化从而实现实时刷新）

> brew install watchman


----------
以上环境配置完成，解决各种终端错误后（配置流程参考[React Native 中文网](https://reactnative.cn/docs/0.51/getting-started.html)），然后可以开始测试初始化一个项目，执行以下命令：

react-native init AwesomeProject
> react-native init AwesomeProject
>
> cd AwesomeProject
>
> react-native run-ios

执行完 react-native run-ios 会从新弹出一个终端，也就是react-packager窗口，能看到模拟器正常启动，加载出第一个react-native应用，说明你成功搭建好环境了。

使用你喜欢的编辑器打开App.js并随便改上几行。
在 iOS Emulator 中按下⌘-R就可以刷新 APP 并看到你的最新修改！


----------
未完。。。。

<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA3Mzk4OTM0NV19
-->