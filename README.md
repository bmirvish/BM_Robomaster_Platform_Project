# BM_Robomaster_Platform_Project
MY 2020-2021 Year Project to produce a gyroscope controlled platform

The platform will have 3 degrees off freedom and will be controlled via the hand motions of the user.  This will be achieved by an accelerometer equiped band that will be worn on the users hand, and will send commands to a primary STM32 via an I2C line.  This STM32 will determine the angles the hand is held at and from there, transmit this data via a serial line to a 2nd STM32 on the platform, which will determine the requisite motor commands to achieve the desired position, and command the 3 servo motors via a PWM line.
