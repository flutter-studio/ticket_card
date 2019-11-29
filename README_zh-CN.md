[English](./README.md) | 简体中文

# ticket_card

[![pub package](https://img.shields.io/pub/v/ticket_card.svg)](https://pub.dartlang.org/packages/ticket_card)

一个票据样式的卡片


## 使用
要使用此插件包,请将`ticket_card`作为依赖项添加到您的`pubspec.yaml`文件中,详见[dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

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
### 特别感谢react-native-vector-icons插件包及其开发者们
