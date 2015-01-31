---
layout: post
title: Raspberry Pi + WiringPi
---
Raspberry PiのGPIOをブラウザから操作できるようにするという目的のために。

1. Raspberry PiにWiringPiをインストール
2. Raspberry PiにWiringPi2 for Pythonをインストール
3. sudoなしでPythonでGPIOを制御

今回は、1. Raspberry PiにWiringPiをインストール

作業内容

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

