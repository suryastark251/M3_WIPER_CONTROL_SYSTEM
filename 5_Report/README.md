# PROJECT TITLE - WIPER CONTROL SYSTEM

# ABSTRACT :

 A wiper is a vital component that cleans raindrops or any other liquid from the windscreen of a car. Previously, the wipers had to be activated manually by setting the frequency. The operation of increasing the wiper speed is modified as a result. The project's purpose is to improve the systems of older cars by providing automated transmission. wiping technology, to improve the system by including a sensor and actuator, and to develop a basic programme that would work with the system completely. the structure The principle of this proposed wiper system is similar to that of other existing conventional wipers. Regardless of the fact that To drain water from the windscreen, this system will be updated to an automatic control system using a Peripheral Interface.


# INTRODUCTION
Wiper system is the utility project. It is used to clean the wind shield of the car at the front and rear. Wiper works by removing oil,dust,rain water and dirt.That get struck to the wind shield and the arm is provided by the motor.The warm gear is able to generate the force required to move the wipers as fast as they need to move. now a days we have an automatic wiper control when ever we stop wiping in between the process it will automatically comes to initial position this is the new wiper system as behined in the wiper arm.The car wipers that have been available in the present day market are manual systems that work on the principle of manual switching.Our proposed system proposes an automatic wiper system that automatically switches ON the wiper on detection of rain and stops the wiper action when rain stops. This system eases the work of driver by eliminating the manual human intervention for initiating the wiper action, thereby contributing to the comfort driving.
This Wiper Speed Control System is utilised in all sorts of automobiles, and its primary function is to remove rain air drops from the vehicle's front screen. Because driving a vehicle in the rain is quite difficult, we will use wipers to clear the front screen of the vehicle, which is a mirror, so that we may drive the vehicle even in the rain.

# WORKING 
* The RED LED is considered for the ACC position. Once the push button is pressed for 2 seconds, the RED LED keeps continuously glowing until the stop of the engine signifying the engine condition to be turned ON.
* On press of the user input push button, the other three Blue, Green and Orange LEDs come ON one at a time with the set frequency. The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz.
* The LED glow pattern stops on the 4th press; the wiper action starts with the next press.
* If the push button is pressed for 2 seconds continuously, the RED light goes off and the pattern stops bringing it to default position which signifies the engine is turned OFF.

# REQUIREMENTS FOR THE PROJECTS ARE :
## STM32Cube IDE :
* STM32Cube software ecosystem. STM32CubeIDE is an advanced C/C++ development platform with peripheral configuration, code generation, code compilation, and debug features for STM32 microcontrollers and microprocessors. It is based on the Eclipse®/CDT™ framework and GCC toolchain for the development, and GDB for the debugging. It allows the integration of the hundreds of existing plugins that complete the features of the Eclipse® IDE.


## Xpack Packages :

### Windows Build Tools:
* The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.

### OpenOCD :
* Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.

### QEMU :
* The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.

## COMPONENTS USED IN PROJECT:

### STM32F407G-DISC1

STM32F407 series of microcontrollers are high-performance MCUs designed for medical, industrial and consumer applications. It is based on ARM Cortex-M4 and offers up to 168MHz. The STM32F407VGT6 is the onboard chip which comes in a 100-pin LQFP package.

The STM32F407G-DISC1 is a Discovery Kit allows users to easily develop applications with the STM32F407 high performance microcontrollers with ARM cortex-M4 32-bit core. It includes everything required either for beginners or for experienced users to get quickly started. Based on the STM32F407VGT6, it includes an ST-LINK/V2 or ST-LINK/V2-A embedded debug tool, two ST MEMS digital accelerometers, a digital microphone, one audio DAC with integrated class D speaker driver, LEDs and push buttons and an USB OTG micro-AB connector.

### Features Of STM32F407G
* Flash memory of up to 1 megabyte.
* OTP memory of 512 bytes.
* Compact Flash, SRAM, PSRAM, NOR, and NAND memories are supported by this flexible static memory controller.
* Sleep, Stop, and Standby modes are low-power modes.
* 16-stream DMA controller with FIFOs and burst support for general-purpose DMA.
* Up to 54 Mbytes/s 8- to 14-bit parallel camera interface.
* Generator of true random numbers.
* Hardware calendar, CRC calculating unit, 96-bit unique ID RTC, subsecond accuracy.


 ## 4 W'S
#### WHAT IS WIPER SYSTEM
  * Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
#### WHY WIPER SYSTEM
  * To keep the windscreen clean enough to give adequate view at all times.
#### WHEN SHOULD USE WIPER SYSTEM 
  * The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
#### WHO DISCOVERED WIPER SYSTEM
 * Mark Anderson invented on 1902
# SWOT Analysis 
## Strength
* Visibility
* The wiper does not stop in the middle of the window during drive.
* Safety

## Weakness 
* High cost
* Not automatic

## Opportunities
* Rain sensing and automatic operation can be implemented as further enhancement.


## Threats 
* Once the board repaired cannot be replaced quickly

# REQUIREMENTS
## High level requirements
| ID | Description | Status |
| --- | --- | --- | 
| HR_01 | ACC Mode Operation |	Implemented |
| HR_02 |	Wiper ON |	Implemented |
| HR_03 |	Wiper Speed Change |	Implemented |
| HR_04 |	Wiper OFF |	Implemented |
## Low level requirements
| ID |	Description | Operation |	Status |
| --- | --- | --- | --- |
| LR_01 |	Button pressed once for 2 secs | Red LED ON |	Implemented |
| LR_02 |	Button pressed second time | 1 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_03	|Button pressed third time | 4 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_04	|Button pressed fourth time | 8 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_05 |	Button pressed again for two seconds |Turn Off all LEDs |	Implemented |



# Tools Used for Implementation :

## STM32Cube IDE :
* STM32Cube software ecosystem. STM32CubeIDE is an advanced C/C++ development platform with peripheral configuration, code generation, code compilation, and debug features for STM32 microcontrollers and microprocessors. It is based on the Eclipse®/CDT™ framework and GCC toolchain for the development, and GDB for the debugging. It allows the integration of the hundreds of existing plugins that complete the features of the Eclipse® IDE.

## Xpack Packages :

### Windows Build Tools:
* The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.

### OpenOCD :
* Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.

### QEMU :
* The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.





## USAGE OF PREPROCESSOR/POINTERS/FUNCTION POINTERS/STRUCT/TYPE DEF

## Preprocessor:
The C preprocessor is a macro processor that is used automatically by the C compiler to transform your program before actual compilation. It is called a macro processor because it allows you to define macros, which are brief abbreviations for longer constructs.

## The C preprocessor provides four separate facilities that you can use as you see fit:

Inclusion of header files. These are files of declarations that can be substituted into your program.
Macro expansion. You can define macros, which are abbreviations for arbitrary fragments of C code, and then the C preprocessor will replace the macros with their definitions throughout the program.
Conditional compilation. Using special preprocessing directives, you can include or exclude parts of the program according to various conditions.
Line control. If you use a program to combine or rearrange source files into an intermediate file which is then compiled, you can use line control to inform the compiler of where each source line originally came from.

## Pointers:
Pointers:
The Pointer in C, is a variable that stores address of another variable. A pointer can also be used to refer to another pointer function. A pointer can be incremented/decremented, i.e., to point to the next/ previous memory location. The purpose of pointer is to save memory space and achieve faster execution time.
Like variables, pointers in C programming have to be declared before they can be used in your program. Pointers can be named anything you want as long as they obey C’s naming rules. A pointer declaration has the following form.

 syntax:
data_type * pointer_variable_name;

Types of Pointers in C:
1.Null Pointer
2.Void Pointer
3.Wild pointer
4.Dangling pointer

## Funtion Pointer:
In the C function pointer is used to resolve the run time-binding. A function pointer is a pointer that stores the address of the function and invokes the function whenever required.
In C, we can use function pointers to avoid code redundancy.
1) Unlike normal pointers, a function pointer points to code, not data. Typically a function pointer stores the start of executable code.
2) Unlike normal pointers, we do not allocate de-allocate memory using function pointers.

## Struct:
A structure is a key word that create user defined data type in C. A structure creates a data type that can be used to group items of possibly different types into a single type.

‘struct’ keyword is used to create a structure. 

A structure variable can either be declared with structure declaration or as a separate declaration like basic types.Structure members cannot be initialized with declaration. 

Structure members can be initialized using curly braces ‘{}’. For example, following is a valid initialization. 
Structure members are accessed using dot (.) operator.

## Type def:
typedef, which you can use to give a type a new name. Following is an example to define a term BYTE for one-byte numbers.After this type definition, the identifier BYTE can be used as an abbreviation for the type unsigned char

By convention, uppercase letters are used for these definitions to remind the user that the type name is really a symbolic abbreviation, but you can use lowercase.

You can use typedef to give a name to your user defined data types as well. For example, you can use typedef with structure to define a new data type and then use that data type to define structure variables directly

Syntax: typedef data_type new_name



# TEST CASES and Corresponding Output

## High Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | check if the BUTTTON is pressed  | program execution | Microcontroller/Engine starts | LED ON(RED)| PASS |
| 2 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(BLUE)| PASS |
| 3 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(GREEN)| PASS |
| 4 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(ORANGE)| PASS |
| 5 | check if the BUTTTON is pressed  | - | Microcontroller/Engine stops | LED TURNED OFF| PASS |









## Low Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | check if the BUTTTON is pressed  | program execution | Microcontroller/Engine starts | LED ON(RED)| PASS |
| 2 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is slow | LED ON(BLUE)| PASS |
| 3 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is moderate | LED ON(GREEN)| PASS |
| 4 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is good | LED ON(ORANGE)| PASS |
| 5 | check if the BUTTTON is pressed again | - | Microcontroller/Engine stops | LED TURNED OFF| PASS |



