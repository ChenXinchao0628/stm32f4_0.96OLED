# STM32-HAL库硬件IIC方式驱动0.96寸OLED屏幕


本仓库包含以下内容：

1. OLED驱动文件
2. HAL工程
3. keil5工程


## 使用说明

1. 该例程可直接烧录至STM32F4芯片运行，使用了芯片的I2C1
3. 如果移植请注意在oled.c文件中修改HAL_I2C_Mem_Write()使用的I2C
4. 详细配置请查阅HAL配置及程序注释
