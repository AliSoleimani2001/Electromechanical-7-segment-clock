# Electromechanical-7-segment-clock

Digital clocks are often made out of a series of 7-segment displays, which light up to represent the needed numbers.We use 28 micro servos. When in use, each segment’s bright yellow surface is clearly visible. When “off,” they’re turned to reveal a slim black edge that goes largely unnoticed.
The device is powered by an Arduino Uno, along with a DS1302 RTC module. Two PCA9685 16-channel PWM drivers control the motors directly, and as they run off of I2C, more servos/digits could even be added if needed. 

We use :
  Arduino UNO R3
  DS1302
  PWM PCA9685 (2X)
  T-pro Mini Servo SG90 9G (28X)
