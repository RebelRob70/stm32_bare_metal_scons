# stm32_bare_metal_scons
A project aimed to offer a bare-metal super-simple code-framework for STM32 that builds out-of-the-box using SCons. Thanks to SCons it will build on any of the platforms Win, Linux, MacOSX.

## Prerequisites
Install [GNU ARM Embedded Toolchain.](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm)  
Install [Python3.](https://www.python.org)  
Install [SCons.](https://www.scons.org)  

## To build the code  
First edit the SConstruct file according to which processor you would like to build for. Set the PROCESSOR_DERIVATIVE string equal to:    

 STM32F10X_LD     STM32F10X_LD: STM32 Low density devices  
 STM32F10X_LD_VL  STM32F10X_LD_VL: STM32 Low density Value Line devices  
 STM32F10X_MD     STM32F10X_MD: STM32 Medium density devices  
 STM32F10X_MD_VL  STM32F10X_MD_VL: STM32 Medium density Value Line devices  
 STM32F10X_HD     STM32F10X_HD: STM32 High density devices  
 STM32F10X_HD_VL  STM32F10X_HD_VL: STM32 High density value line devices  
 STM32F10X_XL     STM32F10X_XL: STM32 XL-density devices  
 STM32F10X_CL     STM32F10X_CL: STM32 Connectivity line devices  

Run SCons in the project-root.