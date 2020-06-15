# 参考代码
https://github.com/yuchengstudio/8-bit-MCU/blob/master/mega128%E7%B3%BB%E5%88%97/reference/atmeg1284p_test.7z

# 数据同时存在flash 和 RAM 区域
<br/>如果仅仅加const修饰符时，数据会默认存在flash, 及RAM区间。
<>![image](https://github.com/yuchengstudio/8-bit-MCU/blob/master/mega128%E7%B3%BB%E5%88%97/reference/const_data_existin_flash%26RAM.png)

<br/>![image](https://github.com/yuchengstudio/8-bit-MCU/blob/master/mega128%E7%B3%BB%E5%88%97/reference/const_data_existin_flash%26RAM_2.png)

# 数据仅存在flash区域
<br/>如果需要数据仅仅存在于flash区间的话，需要加“ __flash”  修饰符
<br/>![image](https://github.com/yuchengstudio/8-bit-MCU/blob/master/mega128%E7%B3%BB%E5%88%97/reference/const_data_existin_flash.png)
