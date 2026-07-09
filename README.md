# CNC PSU and Driver Board

Project under development...

CNC PSU and Driver Board. Hardware design of a modular CNC controller integrating a 400W LLC power supply with stepper and DC motor drivers.

## Main Features
- Universal AC input: 85 VAC to 265 VAC
- 400W LLC resonant power supply
- Active Power Factor Correction (PFC)
- Stepper motor drivers
- DC motor drivers
- Microcontroller
- Compatible with grblHAL firmware

## Main Components
- **PFC Controller:** [L4986A](https://www.st.com/en/power-management/l4986.html)

- **Auxiliary Power Supply:** [VIPER222L](https://www.st.com/en/power-management/viper222.html)

- **Microcontroller:** [STM32F411CEU6](https://www.st.com/en/microcontrollers-microprocessors/stm32f411ce.html)

- **Stepper Motor Driver:** [STSPIN820](https://www.st.com/en/motor-drivers/stspin820.html)

- **DC Motor Driver:** [STSPIN840](https://www.st.com/en/motor-drivers/stspin840.html)

## Development Tools
- **PCB Design:** Altium Designer
- **Firmware:** [grblHAL](https://github.com/grblHAL/STM32F4xx)
