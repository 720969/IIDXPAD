# IIDXPAD

## Introduction

THIS PROJECT IS MODIFIED FROM [brokenithm-kb](https://github.com/4yn/brokenithm-kb)

Brokenithm-kb is very convenient for those who want to use iPad to play SUSPlayer without boring and tedious ipa installation process.

The same is true for someone want to use iPad as SDVX controller.

So I made this project named SDVXPAD.

We can use SDVXPAD to let your iPad, mobile phone or any other touchable device with a browser be able to serve as SDVX controller.I really like the convenience of web controller though it may have some performance limit due to network communication.

Then this is my(wufe8) iidx/bms version fork. Which use "asdf Space hjkl" keymap.

## Feature

Brokenithm-kb uses API SendInput from user32.dll to simulate keyboard input. Unlike Brokenithm-kb, SDVXPAD uses [DD.dll](https://github.com/ddxoft/master) to solve the issue that Brokenithm-kb's input cannot be received by some applications. In theory, SDVXPAD can also be extended to be the controller of other games.

In the IIDXPAD. I change the default port into 1000(old: 1116). And samples per second into 1000(old:100).
Besides, IIDXPAD add a mode parameter which can assign the keymap(`$IIDXPAD -m <number>`).

## Setup

The setup process is the same as Brokenithm-kb so if you have any problem you can refer to [this](https://github.com/4yn/brokenithm-kb)

## LICENSE
from origin version: [brokenithm-kb](https://github.com/4yn/brokenithm-kb)
It will follow them to be [GPL-3.0 License](https://github.com/4yn/brokenithm-kb/blob/dev/LICENSE)
