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
### PWM

### WebServer
- [PermissionError: [Errno 13] Permission denied](https://stackoverflow.com/questions/38298652/permissionerror-errno-13-permission-denied-flask-run)\
  80 is a privileged port\
  use a higher port such as 5000 to avoid this problem\
  or need sudo privileges.\
- 
