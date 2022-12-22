# STM32BLINK 
##  SEEL 5123 (Advanced Microprocessor) Assignment part 1 (device and tool setup and test)
### Group members: 
1. Mohamed Afifi Ahmed Mahmoud Khalil  
2. Mahmoud Abdelwase Mahmoud  
3. Omar Amgad elsayed abdelmonem  

### Task Description: 
Blink any of the onboard LEDs of any STM32 development board 

### Solution: 
A blocking delay is produced using HAL_DELAY() after which the LED is toggled in the main loop  
similar to the following code snippet

```
while(1) {
  HAL_Delay(1000);
  HAL_GPIO_TogglePin(LD4_GPIO_Port, LD4_Pin);
}
```

### video link: 
[blinking led example](https://drive.google.com/file/d/1xmcfUo0XEtkyhK-qzI2rws2aabZdJvAx/view?usp=sharing)
