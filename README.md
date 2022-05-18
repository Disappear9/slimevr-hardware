# SlimeVR硬件  
## 设计目标：  
1.IMU使用 ~MPU9250~ GY-91模块。  
2.去除充电电路， ~使用18650电池供电，没电直接更换电池。~  使用集中供电  
` 经测试，18650的钢制外壳会干扰磁力计`    
3.去除USB-TTL芯片，在第一次下载后就用不着了。  
4.预留第二IMU端口，使用RJ45接口。  
5. 使用 ~ESP32-WROOM~ ESP-12F  
` 上游已解决内存泄漏问题 `

## 其他
1.使用EDA软件为EASYEDA（立创EDA）  
2.文件 -> 打开 选择json文件即可导入  

# LICENSE
CC BY-NC-SA 3.0
署名-非商业性使用-相同方式共享 3.0
