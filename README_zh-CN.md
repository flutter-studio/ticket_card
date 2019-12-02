[English](./README.md) | 简体中文

# ticket_card

[![pub package](https://img.shields.io/pub/v/ticket_card.svg)](https://pub.dartlang.org/packages/ticket_card)

一个票据样式的卡片

<div align=left>
<img src="https://github.com/flutter-studio/ticket_card/blob/master/screen_shot.jpg" width = "280"  alt="图片名称" align=center />
  </div>


## 使用
要使用此插件包,请将`ticket_card`作为依赖项添加到您的`pubspec.yaml`文件中,详见[dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

## 组件

### TicketCard

| 属性                 | 描述                                                                                                                                                                               |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| lineFromTop  | 分割线距离顶部的距离 |
| lineRadius | 分隔线两边的圆角半径 |
| lineColor  | 分割线的颜色 |
| decoration | 票式卡片装饰器 |
| child | 票式卡片的子组件 |

## 示例

``` dart
// 引入包
import 'package:flutter_icons/flutter_icons.dart';
import 'package:flutter/material.dart';

            TicketCard(
              decoration: TicketDecoration(
                shadow: [TicketShadow(color: Colors.black, elevation: 6)],
                border: TicketBorder(
                  color: Colors.green,
                  width: 0.1,
                  style: TicketBorderStyle.dotted
                )
              ),
              lineFromTop: 100,
              child: Container(
                height: 200,
                width: 200,
                color: Colors.white,
                child: Text(
                  "sdfsf",
                  style: TextStyle(color: Colors.black),
                ),
              ),
            )
```
