### GPIO
- Output
```python
import RPi.GPIO as GPIO
GPIO.setup(pin_number, GPIO.OUT)
# set initial I/O state
GPIO.output(pin_number, GPIO.HIGH)
GPIO.output(pin_number, GPIO.LOW)
```
- Input
```python
import RPi.GPIO as GPIO
get_input = GPIO.input(pin_number)
```
### [PWM](https://sourceforge.net/p/raspberry-gpio-python/wiki/PWM/)

```python
import RPi.GPIO as GPIO
GPIO.setmode(GPIO.BOARD)
GPIO.setup(12, GPIO.OUT)

# To create a PWM instance
p = GPIO.PWM(12, 0.5)

# To start PWM
# p.start(duty) where duty = 0.0~100.0
p.start(1)

# To change the frequency
p.ChangeFrequency(freq) # where freq is the new frequency in Hz

# To change the duty cycle
p.ChangeDutyCycle(duty)

# To stop PWM
p.stop()
GPIO.cleanup()
```


### WebServer
- [PermissionError: [Errno 13] Permission denied](https://stackoverflow.com/questions/38298652/permissionerror-errno-13-permission-denied-flask-run)\
  80 is a privileged port\
  use a higher port such as 5000 to avoid this problem\
  or need sudo privileges.\
- 
