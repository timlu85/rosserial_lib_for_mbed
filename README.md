# rosserial lib for Mbed 

## Description
ROS Serial Library for Mbed
 
Build from latest official source for kinetic (Branch: jade-devel) with some fix or change(maybe?). 
## Already Test
* Platform
```
NUCLEO-F401RE
```
## Changelog
* v1 initial release
> [Increase the tx/rx buffers to avoid communication error](https://github.com/yoneken/rosserial_stm32/commit/b7c9c778917331a2d9ffaca100477d6fba0ae6b2 "sources from yoneken's rosserial_stm32 repository") 
>> Fix undefined problem on **duration.h** and **time.h**
## Credits 
* Gary Servin make old ros_lib_kinetic for Mbed
* ros official repository
* yoneken's "rosserial_stm32" repository