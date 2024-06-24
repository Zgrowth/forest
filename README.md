# forest
autojs蚂蚁森林自动收能量

## 说明
简单粗暴实现自动收取能量，仅通过点击和循环实现。点点star给点鼓励👏🏻👏🏻👏🏻

## 如何使用
1. 安装任意版本的Auto.js，可使用[AutoX](https://github.com/kkevsekk1/AutoX/releases)，启动后将无障碍服务打开，然后将该软件允许后台运行
2. 复制[代码](https://raw.githubusercontent.com/Zgrowth/forest/master/forest.js)，然后在Autojs首页新建一个文件，将代码粘贴
3. 修改代码中的一些坐标轴位置。如何获取坐标轴位置？打开手机的开发者模式，然后找到指针位置打开即可。[link](https://www.cnblogs.com/harry66/p/13438789.html)
```
var find_energy_points = '970,1580'; // 找能量的坐标轴位置，以逗号分隔
var onekey_collect_points = '550,1400'; // 一键收的坐标轴位置，以逗号分隔
var nine_palace_grid_password = [
  '535,1480',
  '800,1480',
  '800,1745',
  '800,2010',
  '535,2010',
]; // 九宫格密码滑动的坐标轴位置
```
[找能量、一键收按钮位置](https://cdn.jsdelivr.net/gh/Zgrowth/image@master/20240624/1000028967.54xmi147sv.jpg)

4. 首页添加定时任务，每天早上定时运行，可自动解锁，目前仅支持九宫格

