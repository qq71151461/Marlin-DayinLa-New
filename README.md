# 打印啦盒子固件
<img align="right" src="http://www.dayin.la/images/logo.png" />
<img align="right" src="Documentation/Logo/Marlin%20Logo%20GitHub.png" />

新增命令：
M95 X0 Y0 Z0 调整打印机最小行程
M96 X150 Y150 Z150 调整打印机最大行程
M97 X0 Y1 Z0 E0 调整移动方向
M98 X0 Y1 Z0 调整限位器高低电平触发

M223 获取当前固件型号以及版本信息
M249 调节LED灯光
M254 获取当前XYZ偏移量，以及打印速度，流量