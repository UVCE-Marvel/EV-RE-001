## Task 1 - Build Chassis
Design a custom RC car chassis in CAD software with weight distribution suitable for stability and sensor mounting. Ensure it is compatible with MARVEL’s 3D printer specifications and modular for component integration.

**Outcome**

- Designed and modeled a functional RC chassis suitable for 3D printing.


- Applied basic principles of mechanical design and weight balancing.


## Task 2 - SPI Communication (Embedded)
Implement SPI communication between Arduino and a peripheral device like an SD card module, OLED, or another microcontroller. Learn about MOSI, MISO, SCK, and SS signals and how full-duplex data transfer works.

**Outcome**

- Learn the master-slave data exchange using SPI.


- Implemented SPI for sensor or peripheral communication.

**Resource**

- Notes:
  
  1. https://www.circuitbasics.com/basics-of-the-spi-communication-protocol/
  2. https://learn.sparkfun.com/tutorials/serial-peripheral-interface-spi/all 
  3. https://www.ti.com/lit/an/slva704/slva704.pdf?ts=1667176595632&ref_url=https%253A%252F%252Fwww.google.com%252F 
- https://microcontrollerslab.com/spi-communication-between-two-arduino-boards/ 

## Task 3 - I2C Control (Embedded)
Use Arduino or STM32 to interface multiple I2C devices like an LCD, sensor (e.g., MPU6050), and EEPROM on the same bus. Learn about address management and master-slave data protocols.

**Outcome**

- Understood multi-device communication via I2C.

- Successfully controlled and read data from I2C-based modules.
  
[Resource](https://circuitdigest.com/microcontroller-projects/arduino-i2c-tutorial-communication-between-two-arduino) 

For notes refer to the previous task


## Task 4 - Make a Lithium-ion Battery Pack (Power Electronics)
Assemble a 3-cell Li-ion battery pack to deliver 12V with a 3S 20A 12V BMS module.

**Outcome**

- Built a functional Li-ion battery pack.

- Gained hands-on experience with battery wiring and BMS integration.
  
**Resource**
- https://youtu.be/K1IGCC_aeio
  
## Task 5 - Working with Multiple Sensors (Embedded - 3 star)
Integrate at least 3 sensors (like IR, ultrasonic, DHT11) into the RC car chassis to gather real-time data. Use Arduino to process and respond to the data. Demonstrates full system integration and real-world automation.

Outcome:

- Created an application-based smart RC car using multiple sensors.


- Combined mechanical, electrical, and programming skills effectively.


## Task 6 - Smart Active Battery Balancer (Power Electronics - 3 star)
Build a system to balance voltages between 2 or more Li-ion cells using Arduino, IRF830 MOSFETs, and CL100 transistors. Transfer excess charge from higher-voltage cell to lower-voltage cell and display voltages via serial.

**Outcome**

- Implemented active balancing of Li-ion cells.

- Understood the significance and working of active vs passive balancing.
  
**Resource**

[Notes](https://www.renogy.com/academy/batteries/Lithium-Battery-Balancing#:~:text=When%20charging%2C%20the%20highest%20charged,charge%20levels%20across%20all%20cells)

[Notes](https://cellsaviors.com/blog/active-passive-balancing?utm_source=chatgpt.com) 

[Notes](https://320volt.com/en/balancing-li-ion-li-polymer-batteries-battery-balancing-circuit/) 


## Task 7 - Regenerative Braking System Demo (Power Electronics - 3 star)
Demonstrate regenerative braking using a 9V DC motor connected to a circuit with LED, transistor, and pushbutton. When the motor is stopped via braking, the back EMF lights up the LED, simulating energy recovery in EVs.
      
**Outcome**

- Demonstrated energy recovery during braking.

- Understood core principle of regenerative braking in EVs.
  
**Resource**

[Notes](https://testbook.com/mechanical-engineering/regenerative-braking-system)  


## Task 8 - Interfacing STM32 Nucleo with L298N Motor Driver (Embedded)
Connect an STM32 board to an L298N driver module and control a DC motor's speed and direction using PWM and logic pins. Learn motor driver interfacing and STM32 timer control.

**Outcome**

- Controlled DC motor speed and direction using STM32.

- Gained understanding of interfacing motor drivers with microcontrollers.
  
**Resource**

[116.STM32CubeIDE L298N Motor. PWM with STM32 F446RE Nucleo](https://youtu.be/26-3AUVJldA?si=C-fTCPhmV-Am3TXT)


## Task 9 - Interfacing STM32 Nucleo with Servo Motor (Embedded)
Use STM32 to control a servo motor by generating PWM signals through internal timers. Adjust pulse width to change the angle of the servo and observe precision motion control.

**Outcome**

- Controlled servo positioning using STM32-generated PWM.

- Understood timer and GPIO configurations for servo control.
  
**Reource**

[102. STM32CubeIDE Servo Motor. PWM with STM32F446RE Nucleo](https://youtu.be/HN9sKhKxy7M?si=PWNLnY7xKlvPANHh)


## Task 10 - Configuring ADC in STM32 Nucleo Board (Embedded - 3star)
Configure the STM32’s internal ADC to read analog voltages (e.g., from a potentiometer or sensor). Learn resolution, reference voltage, sampling time, and read techniques via polling or interrupt.

**Outcome**

- Successfully read and processed analog data via ADC.

- Understood ADC setup, resolution, and data acquisition methods.
  
**Resource**

[STM32 ADC #1. How to configure ADC || Single Channel Polling Mode](https://youtu.be/MDnWdi4BCAo?si=WdMwDWYDIr_Hgpe1)







