---
layout: post
title:  A Phone Dialpad for your Flutter Application
tag: [flutter代码库, Dialog]
date: 2019-08-14
---

 


## [立即下载 ️⬇️ ](https://codeload.github.com/eopeter/flutter_dialpad/zip/master) 


 
![](https://flutterawesome.com/content/images/2019/07/A-phone-dialer-widget.jpg)
 
>
> A phone dialer widget that can be added to any Flutter Application to enable ability to dial a number.
>

 
# flutter_dialpad

A phone dialer widget that can be added to any Flutter Application to enable ability to dial a number. This could be combined with a voip application to enable placing calls.

This is a purely Dart widget with no dependency on Android or iOS except for the flutter_dtmf package it uses for DTMF tone generation on pressing a button. You can turn it off my setting ```enableDtmf: false```

## Getting Started

```
@override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: Colors.black,
      body: SafeArea(
        child:
            DialPad(
                enableDtmf: true,
                backspaceButtonIconColor: Colors.red,
                makeCall: (number){
                    print(number);
                }
            )
        ),
    );
  }

```
## Screenshots

![iOS Screenshot](screenshots/screenshot1.png?raw=true "iOS Screenshot") | ![Android Screenshot](screenshots/screenshot2.png?raw=true "Android Screenshot")
|:---:|:---:|
| iOS Screenshot | Android Screenshot |

## To Do
[Done] Add DTMF Tones
* Shrink Ouput to Fit
* Support for Local Numbers in Text Input Mask

## Github主页 👉[eopeter/flutter_dialpad](http://github.com/eopeter/flutter_dialpad)