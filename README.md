Robot-Movement
==============
main.c
==============
example code for using the implementation of motors.c

motors.h 
==============
a header that contains the functions:

  `void turnRightSlight()`
    --this turns the robot right less than 45 degrees
    
  `void turnLeftSlight()` 
  --this turns the robot left less than 45 degrees
  
  `void turnRightLarge()`
  --this turns the robot right more than 45 degrees
  
  `void turnLeftLarge()`
  --this turns the robot left more than 45 degrees
  
  `void forward()`
  --moves robot forward
  
  `void reverse()`
  --moves robot in reverse
  
  `void setUpTimerA()`
  --initializes TACCRO and TACCR1 to a maximum of 60% duty cycles as to not burn the motor controller
  
motors.c 
==============
 the implementation of these functions

DOCUMENTATION:
==============
 I got help here from C2C Colin Busho on how to change my logic high and low to 
using PWM and how TA0 and TA1 applied to the different registers. I also got help from C2C Caleb Ziegler on 
ideas for how to code here, specifically how to clear the TACCTL for reverse.

 
