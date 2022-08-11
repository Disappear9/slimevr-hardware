# SlimeVR硬件（D9MOD）  
## 设计目标：  
1.IMU使用 GY-91模块。  
2.去除充电电路，使用集中供电     
3.去除USB-TTL芯片，在第一次下载后就用不着了。  
4.预留第二IMU端口，接口使用RJ11。  
5. 使用 ESP32-WROOM-32E 作为MCU

## 更新日志
1.使用XC6210替换AMS1117  
2.对信号线重新layout  
3.拼板设计，打样后用钢锯/台锯沿孔洞切割  

## 其他
1.使用EDA软件为EASYEDA（立创EDA）  
2.文件 -> 打开 选择json文件即可导入  

### 固件  
https://github.com/Disappear9/SlimeVR-Tracker-ESP  

# 项目进度  
- [x] 初始版本设计
- [x] 打样
- [x] 验证Core板运行状态
- [x] 验证AUX板运行状态
- [x] Core板外壳设计
- [x] AUX板外壳设计
- [x] 外壳打印验证
- [x] 绑带设计
- [x] 总装测试

# TODO  
1.腰部连线臃肿，需要设计PDU  
2.外壳不舒适，减小板子体积并优化外壳  
3.手柄干扰磁力计，下代更换IMU为42688  

# LICENSE
CC BY-NC-SA 3.0
署名-非商业性使用-相同方式共享 3.0
