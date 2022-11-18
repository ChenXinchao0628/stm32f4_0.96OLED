# STM32-HAL库模拟IIC方式驱动0.96寸OLED屏幕


本仓库包含以下内容：

1. OLED驱动文件
2. HAL工程
3. keil5工程


## 使用说明

1. 该例程可直接烧录至STM32F4芯片运行，使用了两个GPIO引脚
2. 根据OLED数据线和时钟线引脚修改oled.c文件中OLED_Init中的时钟使能
3. 注意在oled.h文件的宏定义中SCL引脚和SDA引脚
4. 详细配置请查阅HAL配置及程序注释
