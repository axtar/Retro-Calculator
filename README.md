# Retro Calculator - RPN | Algebraic

#### This repository contains some information and ideas for building a retro calculator and is provided *as-is* for educational, experimental, and hobbyist purposes only.
##
>[!WARNING]
> #### This is a hobbyist project. The project has not been tested for compliance with electrical, safety, or electromagnetic standards (e.g., CE, FCC).<br>
> ### If you choose to build or use the calculator, you are doing so at your own risk.

>[!CAUTION]
> <img align="left" width="50" src="Images/warning_sign_small.png" />
> ### Nixie tubes and associated circuitry operate at potentially dangerous voltages.

>[!NOTE]
> - The project is not affiliated with any of the service providers mentioned in this repository.

##
#### Project Status 
- **Software: under construction**
- **Hardware: under construction**

#### Features
- 6 display types
  - nixie: IN-16, IN-17 and B-5870
  - numitron: IV-9
  - vfd: IV-8
  - 7-segment LED
-	2 calculator engines: RPN (reverse polish notation) or algebraic
- 14 digits with decimal points, minus signs and dynamic scientific notation
-	arbitrary-precision arithmetic up to 32 digits (experimental)
-	30+ math operations
-	easy tube replacement
- LED backlighting/underlighting (nixie versions only)
-	mechanical keyboard with 40 switches
-	custom keycap legends and colors
-	RTC with battery backup
-	clock, stopwatch and timer modes
-	ESP32 based controller board
-	PIR, GPS and temperature sensor module (optional)
-	works with a standard DC 12V/2A regulated power supply (wall wart)
-	3D printed case
-	no network connection is needed; all settings can be adjusted using the keyboard
- Optional web based features: configuration, device mirroring and stack register display
-	open-source firmware

#### Numitron IV-9 version
![RPNIV9](Images/rpn_iv9.jpg)
