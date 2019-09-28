---
layout:     post
title:      "Realization of the Tetris Game Based on FPGA "
date:       2019.09.05
author:     "qianting"
header-img: "img/in-post/Tetris/tag-bp.jpg"
catalog: True
tags:
    - Postgraduate
---


## Realization of the Tetris Game Based on FPGA. 2018

Tetris game is a popular game in the world. Its basic rule is to rotate, move, drop and place all kinds of squares which are automatically output by the game, so that it can be arranged into a complete row or rows and eliminate the score. This design was based on the FPGA development board and was implemented in the VHDL hardware design language with a focus on modular design.

Moreover, We tried to control the game using gestures instead of buttons. If  the palm  was detected on the left side of the screen, it meant moving to the left. And the pawl on the right side represented moveright, the upper side represented the rotate, and the underside represented the acceleration. The center area of the screen was an invalid area to avoid mistakes.

Several hardware-dependent modules were developed for interacting with the player: a 7-segment display controller and a VGA  controller .
![](/img/in-post/Tetris/模块.png)
![](/img/in-post/Tetris/结果.jpg)
![](/img/in-post/Tetris/手势.gif)
