# STM32_Lithium_Batt_Monitor (V1.0)

![image](https://github.com/user-attachments/assets/9f856c08-15f5-470d-a94d-47cddac84abd)


### Goal of the project
To build a basic lithium battery monitoring system using STM32 (e.g., Nucleo board) that measures:
1. Voltage
2. Current
3. Logs and displays data (serial/LED/LCD)
4. Sets foundation for AI-powered SoC/SoH estimation later

## Functional Requirements
- [ ] Measure battery voltage via ADC
- [ ] Measure current using ACS712
- [ ] Estimate battery state of charge
- [ ] Log data to serial
- [ ] Add low-battery warning
      
## Component list / bill of materials 
1. STM32 Nucleo controller
2. ACS712 current sensor
3. OLED I2C display module
4. Resistors for voltage divider circuitry
5. 18650 lithium ion battery
6. Battery holder
7. Power ON/OFF switch

## Software requirements
1. STM32 CubeIDE for programming
   
