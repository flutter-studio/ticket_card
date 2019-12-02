English | [简体中文](./README_zh-CN.md)

# ticket_card

[![pub package](https://img.shields.io/pub/v/ticket_card.svg)](https://pub.dartlang.org/packages/ticket_card)

A ticket-style card

<div align=left>
<img src="https://github.com/flutter-studio/ticket_card/blob/master/screen_shot.jpg" width = "280"  alt="图片名称" align=center />
  </div>

## Usage
To use this plugin, add `ticket_card` as a [dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

## Widget

### TicketCard

| Prop                 | Description                                                                                                                                                                               |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| lineFromTop  | The distance from the top of the divider |
| lineRadius | The radius of the rounded corners on either side of the divider |
| lineColor  | The color of the dividing line |
| decoration | Ticket-style card decorator |
| child | A child component of a ticket card |


## Example

``` dart
// Import package
import 'package:ticket_card/ticket_card.dart';
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

