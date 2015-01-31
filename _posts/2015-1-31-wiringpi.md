---
layout: post
title: Raspberry Pi + WiringPi
---
Raspberry PiのGPIOをブラウザから操作できるようにするという目的のために。

1. 今回 ＞ __Raspberry PiにWiringPiをインストール__
2. Raspberry PiにWiringPi2 for Pythonをインストール
3. sudoなしでPythonでGPIOを制御
4. ブラウザから操作
5. 


作業内容
Raspberry PiにWiringPiをインストール

+ gitバージョンを確認
+ WiringPiをインストール
+ WiringPiがインストールできたのを確認
+ GPIOの状態を確認


```

$
$ git --version
git version 1.7.10.4

$
$ git clone git://git.drogon.net/wiringPi
$ cd wiringPi
$ git pull origin
$ cd wiringPi
$ ./build

$
$ gpio -v
gpio version: 2.22

$
$ gpio readall
$


```

