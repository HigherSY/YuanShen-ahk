## 前言

游戏启动后，运行脚本文件（PRTS For YuanShen.ahk），自动在后台运行

在任务栏里找到图标（绿色H图标）右键选择 Exit 即可退出

> 本脚本利用防火墙断网，会重置 Windows 防火墙至默认状态并添加相关规则，如果有需求完事后可自行关闭

如遇一直不能上网，重新运行一次脚本即可

## 按键功能

> （“+”表示同时按住两个键）

    大写锁定 + J：开始主循环
    大写锁定 + K：停止主循环

以下为附加功能

    大写锁定 + W：自动按住 W
    大写锁定 + 左Shift：自动按住 左Shift
    大写锁定 + I：手动断网
    大写锁定 + U：手动联网

主要流程

1. 走到海边（最佳情况是通过短按 W 键，使角色满体力进入漂浮状态）
2. 按下 大写锁定 + J 启动循环
3. 等着
4. 到达目的地附近，按下 大写锁定 + K 停止工作

脚本可用记事本直接打开编辑，注释已经写的很明白了

修改后请从任务栏退出脚本（绿色H图标）重新加载