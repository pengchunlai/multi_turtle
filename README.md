# multi turtle

<img src="https://img.shields.io/badge/-Ubuntu-6F52B5.svg?logo=ubuntu&style=flat">
<img src="https://img.shields.io/badge/Ubuntu-18.04-purple?logo=ubuntu&style=flat">
<img src="https://img.shields.io/badge/ROS-melodic-brightgreen">

これは、Turtlebot3を複数台動かすためのソースです。
必ず、各ドキュメントを読んでください

ローカルにあるやつは古い可能性があります。
https://github.com/nabeya11/multi_turtle に最新版のドキュメントが上がっています。

## readable documents

ドキュメントは以下の通りです。

### [use_multi_tools.md](use_multi_tools.md)

このツールの起動方法、使い方を記しています。

### [create_package.md](create_package.md)

制御器のプログラムの作成方法です。

### [PC_setup.md](PC_setup.md)

PC環境のセットアップ方法を記載しています

### [TB3_setup.md](TB3_setup.md)

turtlebot3のラズパイのセットアップ方法が記されています

## packages description

全部で以下の４パッケージあります

### multi_navigation

turtlebot3に他のロボットを避けながら移動させるパッケージです。また、目的地を指定しての移動も可能です。

### multi_sim

上のコードをgazebo(シミュレータ)上で動かすためのパッケージです
このパッケージを編集しないでください

### pubsub_cplus

- 速度指令の送信
- 固体から見た他ロボットの相対位置の読み取り
を行うexample(C++)コードです。

### example_python

- 速度指令の送信
- 固体から見た他ロボットの相対位置の読み取り
を行うexample(Python)コードです。
