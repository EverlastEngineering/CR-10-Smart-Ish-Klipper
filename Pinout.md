## CR-10 Smart Pinout Map

These are the pins as discovered. I will update as I uncover the rest, for sure there are at least two that were used for the display in the past.

A `!!` denotes that it is unconfirmed / to be investigated.

```
PA0 HIGH_POWERUP
PA1 !! tare_strain? Doubtful
PA2 !! LCD Tx ON SMART PRO
PA3 !! LCD Rx ON SMART PRO
PA4 Z_STOP_PIN
PA5 PROBE_TARE_PIN
PA6 CASE_LIGHT_PIN
PA7 FIL_RUNOUT_PIN
PA8
PA9 USART1_TX
PA10 USART1_RX
PA11 USART1_CTS / IIC_EEPROM_SDA
PA12 USART1_RTS / IIC_EEPROM_SCL
PA13
PA14
PA15 Connector J3 outside pin

PB0 TEMP_BED_PIN
PB1 TEMP_0_PIN
PB2 PROBE_ACTIVATION_SWITCH_PIN // Optoswitch to Enable Z Probe
PB3 Z_DIR_PIN
PB4 Z_STEP_PIN
PB5 Y_DIR_PIN
PB6 Y_STEP_PIN
PB7 X_DIR_PIN
PB8 X_STEP_PIN
PB9 E0_DIR_PIN
PB10 !!   
PB11 !!   
PB12 Connector J4 outside pin
PB13 HEATER_BED_PIN
PB14 HEATER_0_PIN
PB15 FAN0_PIN

PC0
PC1
PC2 E0_STEP_PIN
PC3 X_ENABLE_PIN Y_ENABLE_PIN Z_ENABLE_PIN E0_ENABLE_PIN
PC4 X_STOP_PIN
PC5 Y_STOP_PIN
PC6 BEEPER? Non-functional
PC7 SD_DETECT_PIN
PC8
PC9
PC10 
PC11
PC12
PC13 PC13 hotend fan candidate - non functional
PC14 !! PRO : CR-Touch yellow wire (bltouch control_pin?)
PC15 !! PRO : CR-Touch white wire (bltouch sense_pin?)

PD0
PD1
PD2 refered as a fan in places but I believe it's a copy paste error from the CR6 series.
```
