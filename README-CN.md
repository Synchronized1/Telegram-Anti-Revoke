# Telegram-Anti-Revoke

<!--
[![Version](https://img.shields.io/badge/beta-v0.1.3-blue.svg)](https://github.com/SpriteOvO/Telegram-Anti-Revoke/releases)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/SpriteOvO/Telegram-Anti-Revoke/pulls)
-->
[![Platform](https://img.shields.io/badge/platform-windows-orange.svg)](https://github.com/SpriteOvO/Telegram-Anti-Revoke)
[![Version](https://img.shields.io/github/v/release/SpriteOvO/Telegram-Anti-Revoke)](https://github.com/SpriteOvO/Telegram-Anti-Revoke/releases)
[![Downloads](https://img.shields.io/github/downloads/SpriteOvO/Telegram-Anti-Revoke/total.svg)](https://github.com/SpriteOvO/Telegram-Anti-Revoke/releases)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

:earth_americas: [English](/README.md) | :earth_asia: 简体中文

Telegram 本地消息防撤回插件。

## :mag: 预览
![](/Resource/Preview.gif)

## :sparkles: 特性
* 阻止本地消息被服务器撤回。
* 被撤回的消息将被标记上 “已删除” 。
* 插件具有极好的兼容性。
* 标记的内容支持多语言自动识别。  
目前已支持自动识别：  
*英语、简体中文语、繁体中文语、日语、韩语*
* 您仍然可以主动删除消息。

## :tomato: 兼容性
目前仅兼容 Windows Telegram 1.9.0 ~ 2.1.6 或更高。

## :hamburger: 用法
1. 前往 [发行页面](https://github.com/SpriteOvO/Telegram-Anti-Revoke/releases) 下载最新版本插件。  
2. 关闭正在运行的 Telegram 进程。  
3. 复制 *version.dll* 文件到 Telegram 根目录。  
4. 运行 Telegram 程序。

## :bug: 报告
请使用 [问题跟踪器](https://github.com/SpriteOvO/Telegram-Anti-Revoke/issues) 报告问题或提出新功能。

<!--
如果发生崩溃，请在报告问题时提供以下信息：
* *ArLog.txt* 文件。（与 *version.dll* 文件同于一个目录）
* 您正在使用 Telegram 的哪个版本？
* 您正在使用哪个操作系统？
* 崩溃时您是否做了什么操作？
* 复现崩溃的步骤？（可选）
* 更多有用的信息？
-->

如 Telegram 发布了新版本更新且变动较大，插件可能会出错或导致崩溃。  
请报告该问题并等待插件更新。
<!--勿重复报告已报告的问题，谢谢！-->

## :gem: 第三方
* JsonCpp ([MIT License](https://github.com/open-source-parsers/jsoncpp/blob/master/LICENSE))
* MinHook ([BSD License](https://github.com/TsudaKageyu/minhook/blob/master/LICENSE.txt))

## :beer: 鸣谢
* 感谢 [采蘑菇的小蘑菇] 提供编译 Telegram 的帮助。
* 感谢 [dummycatz] 指出跨模块 malloc/free 内存崩溃的原因。

## :warning: 警告
此开源项目及插件是非官方的，且仅用于教育目的。