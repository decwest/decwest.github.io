---
layout: post
title: DWPP has been merged into Nav2 <br/>DWPPがNav2に統合されました！
date: 2026-01-20 18:02:28+0000
inline: false
related_posts: false
---

2026年1月20日に，Dynamic Window Pure Pursuit (DWPP) をNav2のRegulated Pure Pursuit Controllerに追加する[PR #5783](https://github.com/ros-navigation/navigation2/pull/5783)がマージされました！

これにより，`use_dynamic_window` オプションを有効にすることで，Nav2本体でDWPPを利用できるようになりました．

Nav2公式ドキュメント：

- [Regulated Pure Pursuit Controller Configuration](https://docs.nav2.org/lyrical/configuration_and_development/configuration_guide/controller_plugins/configuring_regulated_pp/)
- [Add Dynamic Window Pure Pursuit Option to Regulated Pure Pursuit Controller](https://docs.nav2.org/lyrical/configuration_and_development/migration_guides/kilted/Kilted/#add-dynamic-window-pure-pursuit-option-to-regulated-pure-pursuit-controller)
