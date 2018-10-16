# STM32H743_USBCDC_FS



SETUP:
1.	Connect OTG cable and STlink cable into development board
2.	Make sure Jumper Jp4 ON
 


3.	Install en.stsw-stm32102 Driver 
4.	Flash the Bin with Target 
5.	Open Terminal and set the USB parameter as below

 
6.	Type your text in input window and  text will be loop backed to output window. 

Developer Reference: 
1.	Bug in MX_USB_DEVICE_Init() function, added HAL_PWREx_EnableUSBVoltageDetector() ; to detect USB in Host machine.
2.	Increased heap size from 0x200 to 0x700 in startup_stm32h743xx.s file.
3.	Legacy reference ,
https://www.youtube.com/watch?v=Jpul3w10tOU

4.	Threats followed ,
https://community.st.com/s/question/0D50X00009XkYZLSA3/stm32h7-nucleo-usb-fs-cdc?t=1538638870978
https://community.st.com/s/question/0D50X00009XkYZLSA3/stm32h7-nucleo-usb-fs-cdc



