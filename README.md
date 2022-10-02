# rk3399-安卓10

## 固件说明

安卓10固件代码基于荣品king 3399 安卓10代码

固件名称: rk3399_a10_hdmi_rotation0_max_resolution_2160p.img

## 解决问题

修复固件默认屏幕方向

允许以原生2060p显示

调整鼠标右键功能为返回

## 已知问题

#### 2160p显示时会有异常绿线画面
使用 `adb shell wm size 2048x1080` 设置为其他分辨率显示


## 额外帮助

### 隐藏底部导航栏

`adb shell setprop qemu.hw.mainkeys 1 && adb shell killall com.android.systemui`
