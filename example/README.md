## *.bin
    烧录所用到的固件
## *.pack
    烧录算法文件，Keil补丁包。文件名需要与yaml中对应
## *.yaml
    配置文件，描述了目标芯片型号，烧录算法所在位置，烧录速率等


​    
```yaml
target_override: STM32F767NIHx  #目标芯片型号
pack:                           #烧录算法所在位置,可以存放多个
  ./Keil.STM32F7xx_DFP.3.1.1.pack
frequency: 10000000             #烧录速率
```