# Beaglebone-Black Pwm - Servo

## Notes :
BeagleBone Black hardware has 8 PWM outputs mapped to 14 pins on the P8 and P9 headers, some of these PWM outputs can be muxed to one of two alternate pins. For example, EHRPWM0B, can be muxed to either P9_21 or P9_29 but not to both pins at the same time 
Books : 
“Getting started with Beaglebone” Ch5 → Analog output PWM   
“Beaglebone for dummies” Ch6 →  how to enable and control of the GPIO-pwm pins. 
“Beaglebone home automation” Ch2 → pwm example , dimming a led with Adafruit’s BBB_IO library 
“Getting started with Beaglebone Linux powered electronic projects with Python and Javascript” Ch5 →  Pwm with Adafruit_BBBIO library 

## Hyperlinks : 

### Servo 
* (https://github.com/go-lab/smart-device/wiki/BeagleBone-Black-for-Servo-Motor) : Configuring header pins for PWM
* (https://learn.adafruit.com/controlling-a-servo-with-a-beaglebone-black?view=all) : Controlling a servo with Python
* (http://beagleboard.org/support/BoneScript/ServoMotor/) : Controlling servo with Bonescript
* (http://www.toptechboy.com/tutorial/beaglebone-black-lesson-12-control-a-servo-from-python-using-pwm/)
* (https://www.linux.com/learn/tutorials/776799-servo-control-from-the-beaglebone-black)

### PWM
* (http://www.mathworks.com/help/supportpkg/beaglebone/examples/pin-muxing.html) : how to read the pin muxing configuration from within MATLAB and change the pin muxing configuration to be compatible with I/O blocks used in a Simulink model.
* (http://oroboto.net/2014/03/29/beaglebone-pwm-motor-control/) 
* (http://www.toptechboy.com/tutorial/beaglebone-black-lesson-6-control-pwm-signals-on-gpio-pins-from-python/)
* (http://www.toptechboy.com/beaglevone-black-rev-c/beaglebone-black-lesson-7-create-a-dimable-led-circuit-with-pwm-in-python/)
* (http://www.toptechboy.com/beaglevone-black-rev-c/beaglebone-lesson-8-digital-input-from-gpio-pins-in-python/) 
* (http://www.toptechboy.com/tutorial/beaglebone-black-lesson-9-reading-analog-inputs-from-python/) 
* (http://www.toptechboy.com/beaglevone-black-rev-c/beaglebone-black-lesson-10-dimable-led-using-potentiometer/)


## Complementary links :
* (https://www.arduino.cc/en/Tutorial/PWM) : What is Pwm
* (https://en.wikipedia.org/wiki/Pulse-width_modulation) 
* (http://www.ee.teihal.gr/labs/electronics/web/downloads/What_is_PWM_and_why_is_it_useful.pdf)
* (https://learn.sparkfun.com/tutorials/pulse-width-modulation) 


