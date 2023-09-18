---
theme: healer-readable
title: i18next 源码分析与简单实现
createTime: 2023 年 8 月 29 日
updateTime: 2023 年 8 月 29 日
---

# 前言
写过很多国际化项目，而这一类的项目往往有多语言切换的需求，部分的语言展示还需要页面布局的同步变化（如：阿拉伯语）。 实现国际化需求的工具库有很多，大部分是根据项目框架及运行机制进行处理的，如 vue-i18n、react-i18n、node-i18n 等，而这些框架也都是依赖于 i18next 这个项目进行二次开发。