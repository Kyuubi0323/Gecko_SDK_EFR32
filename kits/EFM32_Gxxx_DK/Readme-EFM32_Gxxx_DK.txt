====== Kit Examples ======

This package include examples for the EFM32_G8xx_DK and EFM32_G2xx_DK
development kits from Silicon Labs.

====== Dependencies ======

This package _requires_ the EM_BSP_COMMON and EFM32 CMSIS packages to be
installed at the same level as this package. If you did not get this as part
of the Simplicity Studio application, you should also download and install the
EFM32 CMSIS package. See the Changes file for required version.

The CMSIS package requires C99 support, and so does this package.

====== File structure ======

kits/EFM32_Gxxx_DK/config
   Configuration data for BSP and Drivers in EM_BSP_COMMON.

kits/EFM32_Gxxx_DK/examples
   Several example projects demonstrating various capabilities of the
   EFM32G890F128 and EFM32G290F128 and kit specific functionality.
   Project files for various IDEs/compilers are in subdirectories of
   each example. Use these as a starting point for your own development
   and prototyping of EFM32 software.

====== Updates ======

Silicon Labs continually works to provide updated and improved example code,
header files and other software of use for our customers. Please check

http://www.silabs.com/support/pages/document-library.aspx?p=MCUs--32-bit

for the latest releases.

====== License ======

License information for use of the source code is given at the top of
all C files.

Copyright 2015 Silicon Laboratories, Inc.
