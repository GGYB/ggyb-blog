---
title: "ROS使用FLIR BFS相机"
date: 2021-04-24T12:06:22+08:00
categories: [ "ROS"]
tags: [ "相机", "驱动"]
draft: true
---


最近组里到了一台FLIR的型号为[BFS-U3-200S6C](https://www.flir.com/products/blackfly-s-usb3/?model=BFS-U3-200S6C-C)的USB相机。在ROS下使用时碰到了一些问题，因此在这里进行记录

## 安装Spinnaker SDK
这台相机无法直接作为uvc设备使用，需要搭载[Spinnaker SDK](https://www.flir.com/support-center/iis/machine-vision/downloads/spinnaker-sdk-and-firmware-download/)。

根据当前使用的系统版本Ubuntu 20.04, 下载了版本号为2.3.0.77的spinnaker。

## TODO 编写具体的相机SDK安装，ROS驱动，以及RVIZ等ROS组件与SpinView的QT版本冲突的解决。