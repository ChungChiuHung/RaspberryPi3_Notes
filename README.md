# RaspberryPi3_Notes
Tutorial Notes 

### References
- [ElectroicWings](https://www.electronicwings.com/raspberry-pi/raspberry-pi-introduction)

### [WireingPiLibary](https://www.electronicwings.com/raspberry-pi/raspberry-pi-introduction)
WiringPi is a library written in C used to access GPIO pins for ***BCM2835 (Broadcom Processor) Soc***
```
sudo apt-get update
sudo apt-get upgrade
```
Install Git
```
sudo apt-get install git-core
```
Get WiringPi
```
git clone git://git.drogon.net/wiringPi
```

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
