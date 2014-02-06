julome-libraries
================

This is a collection of my personal libraries that i am using in my projects.

To use the libraries, add the .c/.h source files in Atmel Studio 6, then include the library .h that you need. Also, you wiil need to place any appropriate init function calls in your header routine (e.g. imu_init();). See the examples inside the code.

---------------------------------------------------
Libraries:

- usart.h/usart.c           - Communicates an AVR card to ohter device or to the computer by USB port
- twi_master.h/twi_master.h - TWI AVR capable using interrupts
- MPU6050.h/MPU6050.c       - Configure and read meters of MPU6050
