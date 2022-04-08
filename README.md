# SlimeVR硬件  
## 设计目标：  
1.IMU使用MPU9250模块。  
2.去除充电电路，使用18650电池供电，没电直接更换电池。  
` 经测试，18650的钢制外壳会干扰磁力计`  
3.去除USB-TTL芯片，在第一次下载后就用不着了。  
4.预留第二IMU端口，使用RJ45接口。  
5.使用ESP32-WROOM。  
