# baidu-2019_spring-festival_game
百度2019春节活动小游戏

需要准备，手机调试USB接口，开发者模式->USB接口->权限全部打开

主要使用的方法：        
1.手机截屏后，RGB转换HSV,提取白色圆形作为初始点坐标    
2.根据中间暗红色长方形像素，提取目标点坐标    
3.两点间距离乘时间系数，确定press_time   

提高精度方式：
多次截屏计算距离取平均

待改进：
1.两点间距离乘时间系数算press_time，但游戏非线性，需要分段或其他    
2.目标点坐标存在较大误差   

目前可达到的最高结果：300分   
ipython新手，希望大佬能指教，感谢~
