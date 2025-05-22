Note: EV-RE Syllabus is divided into two categories - (i) Embedded Systems (ii) Power Electronics. Students are required to mandatorily do at least 4 tasks from each category in Level 1. It is recommended to do all the tasks in each level. Students will be given extra points for successful completion of 3-star rated tasks.

## Task 1 - LTspice and KiCad  

Design and simulate a 555 timer-based astable multivibrator using LTspice to observe frequency and pulse width behavior. Use KiCad to create a schematic of an LED blinking circuit and design a PCB layout with proper footprints and routing. This task introduces simulation and PCB design fundamentals.

**Outcome**

-  Understand SPICE-based circuit simulation and EDA workflows.
-  Generate schematic, layout, and simulation results.

**Resources**

[LTSpice](https://www.electronicshub.org/astable-multivibrator-using-555-timer/)

[KiCad](https://www.youtube.com/watch?v=BVhWh3AsXQs) 


## Task 2 - Point Turn of a Vehicle with Ultrasonic Sensor(Embedded)

Build an obstacle-avoiding robot using an HC-SR04 ultrasonic sensor, Arduino, and a motor driver. The vehicle should detect obstacles and perform a point turn by rotating in place to change direction. It combines sensor data processing with differential motor control.

**Outcome**

- Vehicle can detect and avoid obstacles.
- Performs point turn autonomously when close to an object.

[Resources](https://projecthub.arduino.cc/) 


## Task 3 - Temperature and Humidity Detection(Embedded)

Use the LM35 analog temperature sensor to monitor ambient or localized heat (e.g., near a soldering iron). When temperature exceeds a threshold, turn on an LED using a BJT as a switch. In parallel, use the DHT11 digital sensor to read and display temperature and humidity on a 16x2 LCD.
       
**Outcome**

- Understand analog and digital sensor interfacing.
- Implement threshold-based switching and data display.

**Resources**

- [Temperature detection using LM35](https://lastminuteengineers.com/lm35-temperature-sensor-arduino-tutorial/)
- Temperature and humidity using DHT11:
  
  1. https://www.engineersgarage.com/articles-arduino-dht11-humidity-temperature-sensor-interfacing/
  2. https://www.engineersgarage.com/articles-arduino-dht11-humidity-temperature-sensor-interfacing/ 



## Task 4 - BLDC Motor And Hall Effect Sensor(Embedded)

Connect a BLDC motor with a Hall effect sensor to measure its speed. The output of the Hall sensor is read by Arduino to calculate RPM and display it via the Serial Monitor. This task demonstrates motor speed sensing and signal interpretation.
 
**Outcome**

- Gain insight into motor speed sensing and the magnetic properties of the Hall effect sensor.

[Resources](https://makersportal.com/blog/2018/10/3/arduino-tachometer-using-a-hall-effect-sensor-to-measure-rotations-from-a-fan)

[BLDC](https://www.ti.com/lit/ab/slvaeg3b/slvaeg3b.pdf?ts=1747321126596) 


## Task 5 - Battery Capacity Measurement(Power Electronics)

Monitor the voltage of a Li-ion battery using analog input on Arduino. Use a MOSFET as a switch to disconnect the load when voltage drops below a safe threshold. Ensures safe battery operation and demonstrates basic battery protection logic.

**Outcome**

- Demonstrate battery protection via voltage monitoring and switching.

[Resource](https://www.instructables.com/Arduino-cell-capacity-meter/) 

## Task 6 - Battery Charging(Power Electronics)

Charge the Li-on battery using solar panels and a solar charging module.

**Outcome**

- Understand practical implementation of solar-based charging.

**Resource**

- https://www.electronicshub.org/solar-battery-charger-for-18650/
- https://www.youtube.com/watch?v=kEttqWJrdww



## Task 7 - Solar Tracker(Embedded)
Use LDRs and a servo motor controlled by Arduino to orient a solar panel toward the strongest light source. The system maximizes solar energy collection using dual LDR comparison logic and basic actuator control.

**Outcome**

- Achieve energy maximization through sun-tracking mechanisms.

[Resource](https://projecthub.arduino.cc/Aboubakr_Elhammoumi/arduino-solar-tracker-77347b) 


## Task 8 - Simple Electric Circuits Simulation on MATLAB(Power Electronics)
Learn the basics of Simulink in MATLAB by designing a simple RLC or transistor-based circuit. Simulate voltage, current, and frequency responses over time using virtual probes and scopes.

**Outcome**

- Understand MATLAB-Simulink for circuit modeling and waveform analysis.

**Resource** 

- https://youtu.be/vxzR3W2BcRk 
- https://youtu.be/lSbEVgCpJCc

## Task 9 - Blink LED WITH STM32(Embedded)

Learn the basics of Simulink in MATLAB by designing a simple RLC or transistor-based circuit. Simulate voltage, current, and frequency responses over time using virtual probes and scopes.

**Outcome**

- Learn basic STM32 programming and GPIO control.
  
**Reference**

- Introduction to STM32: [STM32StepByStep:STM32MCU basics - stm32mcu](https://wiki.st.com/stm32mcu/wiki/STM32StepByStep:STM32MCU_basics#:~:text=STMicroelectronics%20is%20manufacturing%20the%20STM32%20MCUs%20which%20are,cores%2C%20optimized%20for%20cost%20and%20power%20sensitive%20MCUs.)
Software Installations Required: [STM32StepByStep:Step1 Tools installation - stm32mcu](https://wiki.st.com/stm32mcu/wiki/STM32StepByStep:Step1_Tools_installation)
  1. STM32CubeMX 
Link: [STM32CubeMX - STM32Cube initialization code generator - STMicroelectronics ](https://www.st.com/en/development-tools/stm32cubemx.html)
Description:
STM32CubeMX is a graphical tool for configuring STM32 peripherals and generating initialization code. You’ll learn how to select your MCU, configure clocks, GPIOs, and peripherals like ADC, UART, PWM, etc.
  2. STM32CubeIDE or Keil uVision IDE 
Link: STM32CubeIDE - [Integrated Development Environment for STM32 - STMicroelectronics](https://www.st.com/en/development-tools/stm32cubeide.html)
Keil uVision software and installation tutorial for stm32 development
[MDK-ARM Version 5.42a Evaluation Software Request Keil uVision Install](https://www.keil.com/demo/eval/arm.htm)
Description:
STM32CubeIDE is the official free IDE from ST for coding, compiling, and debugging STM32 applications.Keil uVision is an alternative IDE known for high performance and advanced debugging (limited in the free version).
  3. STM32CubeProgrammer
[STM32CubeProg - STM32CubeProgrammer software for all STM32 - STMicroelectronics](https://www.st.com/en/development-tools/stm32cubeprog.html)
Description:
STM32CubeProgrammer is used to flash firmware onto STM32 boards through ST-Link, USB, or UART. This task covers installing the tool and performing basic memory read/write operations.
- Introduction to STM32 MCU, STM32CubeIDE and STM32CubeMX
[Introduction to STM32: Back to the Basics](https://www.youtube.com/playlist?list=PLnMKNibPkDnFa5bR8U78UXs6b5bzKXxq-)
Description:
You’ll learn about STM32 development workflow: selecting a microcontroller, configuring it using STM32CubeMX, writing firmware in STM32CubeIDE, and debugging with ST-Link. This section ties the entire toolchain together.
- Microcontroller Architecture and STM32 Basics
[Hardware and Software used in this series Part - 1 | STM32 | STM32 CUBE MX | KEIL IDE | T - 1](https://www.youtube.com/playlist?list=PL_zvrXFdKgZrLsAkLo_1qPeW7cPOCyEiK)
Description:
Explores microcontroller internals—registers, buses, timers, interrupts, memory mapping—and introduces the STM32F4 architecture. You’ll also get familiar with commonly used development hardware.
- Step-by-step Beginner tutorial
https://youtu.be/dnfuNT1dPiM?si=AWWPWCj4IhBKq_rs
Description:
Teaches about starting a new project in STM32 CubeIDE, STM32 chip configuration(ioc files), Clock configuration, project files, controlling GPIO in STM32, HAL_Delay function, ST-LINK upgrade and STM32 debugger / programmer, building and running your code.
- STM32F446RE Board architecture
https://youtu.be/7h4Hv-XK0eM?si=sVv8VpOYjYfym9Re
Description:
Detailed hardware overview of the STM32F446RE Nucleo board, including pinout, onboard peripherals (ST-Link, LEDs, buttons), memory layout, and how to interface it with external modules.
- STM32 Register Programming
[STM32F4 REGISTER PROGRAMMING - YouTube](https://www.youtube.com/playlist?list=PLfIJKC1ud8ghc4eFhI84z_3p3Ap2MCMV-)
Description:
Covers low-level register-based programming, bypassing the HAL library. You’ll learn how to manipulate peripheral registers directly for GPIOs, timers, and ADC, which gives better performance and deeper understanding.

*Optional/Additional Resources*

- [STM32 EcoSystem (Development Environment) Setup – DeepBlue](https://deepbluembedded.com/stm32-ecosystem-development-environment-setup/) 
  Description:
  Covers how to set up STM32CubeMX and STM32CubeIDE, update firmware packages, and manage libraries for your board in a systematic way.
  
- [STM32 HAL Library Tutorial – HAL Library Examples - DeepBlue](https://deepbluembedded.com/stm32-hal-library-tutorial-examples/)
  Description:
  Provides structured tutorials on using STM32's Hardware Abstraction Layer (HAL) APIs to develop applications more easily and portably.
  
- [Getting Started With STM32 ARM Cortex MCUs – DeepBlue](https://deepbluembedded.com/getting-started-with-stm32-arm-cortex-mcus/)
  Description:
  This article briefly discusses some STM32 MCUs and the ARM Cortex architecture generally used in them.
  
- [MOOC - STM32CubeMX and STM32Cube HAL basics - YouTube](https://www.youtube.com/playlist?list=PLnMKNibPkDnGtuIl5v0CvC81Am7SKpj02)
  Description:
  Massive Open Online Course (MOOC) to help you understand peripheral configuration and C programming using HAL drivers via STM32CubeMX and   STM32CubeIDE.
  
- [Artificial Intelligence on STM32](https://www.youtube.com/playlist?list=PLnMKNibPkDnG9IC5Nl9vJg1CKMAO1kODW)
  Description:
  An advanced (optional) module exploring how to run machine learning models on STM32 MCUs using STM32Cube.AI and TinyML techniques.
  
  **Note**: Every STM32 NucleoBoard variant has its own Datasheet, Reference Manual and Schematic manual so please ensure to download these       pdfs correctly depending on the part number of the NucleoBoard you are using.


 ## Task 10 - Auto Night Lamp Using LED for Electric Vehicles(Embedded)
 Design a light-sensitive LED circuit using an LDR and a BJT transistor. The LED turns on when light levels drop, simulating an automatic 
 headlamp system for EVs. Test using a mobile flashlight for light detection.
 
 **Outcome**
 
- Auto night lamp system for EVs demonstrated with mobile flashlight simulation.

**Reference**

- https://www.electronicshub.org/auto-night-lamp-using-high-power-led/
- https://www.youtube.com/watch?v=OtppaXX8yl0

## Task 11 - Buck Converter on LTspice (Power Electronics)
 Design and simulate a DC-DC buck converter in LTspice. Observe input and output voltages, inductor current waveform, and switching 
 frequency. Understand step-down conversion and efficiency aspects.
 
 **Outcome**
 
- Visualize voltage conversion from high to low DC using simulation.
  
 [Resource](https://youtu.be/emVtB1MsHww?si=BS6Jju7_RirBna_o)

## Task 12 - Wireless Charger Simulation on Tinkercad (Power Electronics)
Simulate inductive power transfer between a transmitter and receiver coil on Tinkercad using basic circuit blocks. Demonstrates wireless charging principles through virtual components and LED indication.

**Outcome**

- Understand basic working of wireless charging systems.

[Resource](https://www.learnelectronicsindia.com/post/exploring-wireless-power-transfer-using-tinkercad?srsltid=AfmBOorL5XwN6-OC655Uns4wW-KPn64g-k_5P3haALkai24Sesq2gdKA)

## Task 13 - Utilizing Transistors as Switches and Voltage Regulators (Power Electronics)
Understand how transistors can be used as digital switches and basic voltage regulators. Begin by using an Arduino to send a digital signal to the base of a transistor to control an LED (ON/OFF). Then, explore how a transistor introduces voltage drop by simulating a circuit in Tinkercad—observe how voltage reduces across the LED after adding a transistor.

**Outcome**

- Gain practical knowledge of using a transistor as a switch and insight into voltage regulation principles relevant to buck converters.

[Resource](https://www.electronics-tutorials.ws/transistor/tran_4.html)


## Task 14 - LED Brightness Control Using PWM and MOSFET (Power Electronics)
Use an Arduino and an N-channel MOSFET to control LED brightness through Pulse Width Modulation (PWM). The Arduino sends a signal to the MOSFET’s gate, allowing current flow between the drain and source. By varying the PWM duty cycle, you can control the LED’s brightness—higher duty cycle means more brightness, and lower duty cycle means dimmer output.

**Outcome**

- Understood how MOSFETs operate as switches and how PWM controls power delivery efficiently, making MOSFETs ideal for such applications.

[Resource](https://www.electronics-tutorials.ws/transistor/tran_7.html)

## Task 15 - AC to DC Conversion and Observing Direct DC vs. Rectified DC (Power Electronics)
Simulate an AC signal using Arduino’s PWM output, then convert it to DC using half-wave rectification. Use a diode to block the negative cycle and a capacitor to filter the signal, producing rectified DC. Compare the LED brightness when powered by a direct DC source (battery) versus rectified DC output.

**Outcome** 

- Understood the basics of AC to DC conversion, diode rectification, and how filtering improves DC quality. Observed that LEDs glow brighter on stable DC compared to filtered rectified DC.

**Resource**

- https://www.electronics-tutorials.ws/diode/diode_4.html
- https://youtube.com/shorts/EJIPexVo41I?si=ZktI8eMw61oEgu0D



## Task 16 - Generating an AC-Like Signal Using a 555 Timer and MOSFETs (Power Electronics)
Use a 555 Timer IC to generate a square wave signal and drive two N-channel MOSFETs in a push-pull configuration. As the timer alternates between HIGH and LOW, one MOSFET connects the load to ground while the other pulls it to Vcc, producing an AC-like square waveform. The MOSFETs amplify the signal, enabling the circuit to handle higher current loads.

**Outcome**

- Learn how to convert DC to an AC-like signal using a 555 Timer and MOSFETs. Observe power amplification.
  
[Resource](https://electronoobs.com/eng_circuitos_tut14_2.php?utm_source=chatgpt.com)

## Task 17 - Building a Basic H-Bridge Motor Driver using MOSFETs (Power Electronics)
You are required to design and build a basic H-Bridge motor driver circuit using N-Channel and/or P-Channel MOSFETs. The H-Bridge should allow you to control the direction of a DC motor using digital signals (e.g., from Arduino or switches).
 
**Outcomes** 

- Demonstrate the ability to control the rotation direction of a DC motor using an H-Bridge configuration.

[Resource](https://www.build-electronic-circuits.com/h-bridge/)







