# RaspberryPi3_Notes
Tutorial Notes
- [C/C++](DevWithC.md)
- [Python](DevWithPython.md)

[Pinout](https://github.com/raspberrypi/documentation/blob/develop/documentation/asciidoc/computers/os/using-gpio.adoc)
![image](https://github.com/ChungChiuHung/RaspberryPi3_Notes/assets/52248840/49c28d5e-d1c4-4ede-90d6-f85b6b11f2af)


[Get the Hardware Information in Raspberry Pi OS](https://www.geeksforgeeks.org/how-to-find-all-the-hardware-information-in-raspberry-pi-os/)
- Get the details of CPU
```
cat /proc/cpuinfo
```
- Get the Raspberry Pi Model number & other information
```
cat /sys/firmware/devicetree/model
```
- Get the hardware details
```
cat /proc/version
```
- Get the Swapping Memory
```
free -h
```
