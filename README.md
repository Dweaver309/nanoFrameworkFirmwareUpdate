# nanoFramework Firmware Update
How To Update STMicroelectronics Microcontrollers Firmware

To manually flash firmware using ST DFUSE tools, get a copy of ST DFUSE tools. Search for STSW-STM32080


  - Install the DFUSE tools
  - Put your device in bootloader mode
  

# Step One

  - Start the STDFU Tester application
  -  Select the "Protocol" tab
- Press the "Create from Map" button
- Select the "Erase" radio button option
- Press the "Go" button
- Wait for the erase process to complete

# Step Two

  - Start the DFUSE Demo Application 
  - Locate the .dfu file located in the device firmware update .zip file.
  - Click the Choose then Update
  - Toggle the devices power
  - Thats all we are done!
