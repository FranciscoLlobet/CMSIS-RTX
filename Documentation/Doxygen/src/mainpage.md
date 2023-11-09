﻿# Overview {#mainpage}

Keil RTX version 5 (RTX5) is a real-time operating system (RTOS) for Arm Cortex-M and Cortex-A processor-based devices that implements the [CMSIS-RTOS2 API](https://arm-software.github.io/CMSIS_6/latest/RTOS2/html/index.html) as its native interface.

The following sections provide further details:

 - \ref RTX5RevisionHistory lists the  explains how to setup an RTX v5 project in Keil MDK.
 - \ref rtx_system_reqs lists hardware, software, and resource requirements, as well as supported toolchains.
 - \ref theory_of_operation provides general information about the operation of CMSIS-RTOS RTX v5.
 - \ref config_rtx5 describes configuration parameters of CMSIS-RTOS RTX v5.
 - \ref cre_rtx_proj explains how to setup an RTX v5 project in Keil MDK.
\ifnot FuSaRTS
 - \ref creating_RTX5_LIB explains how to build your own CMSIS-RTOS RTX v5 library.
\endif
 - \ref misraCompliance5 describes the violations to the MISRA standard.
 - \ref rtos2_tutorial is an introduction into the usage of Keil RTX5 based on real-life examples.

## Access to CMSIS-RTX {#rtx_access}

CMSIS-RTX kernel is actively maintained in [**CMSIS-RTX GitHub repository**](https://github.com/ARM-software/CMSIS-RTX) and is also provided as a standalone [**CMSIS-RTX pack**](https://www.keil.arm.com/packs/cmsis-rtx-arm/versions/) in the [CMSIS-Pack format](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/index.html).

The table below explains the content of the **ARM::CMSIS-RTX** Pack.

 File/Directory        | Content
:----------------------|:---------------------------------------------------------
 📂 Config             | RTX configuration files **RTX_Config.h** and **RTX_Config.c**
 📂 Documentation      | A local copy of this documentation
 📂 Examples           | Example projects (MDK uVision and CMSIS-Toolbox)
 📂 Include            | Public header files of RTX software component
 📂 Library            | Library project files and pre-built libraries
 📂 Source             | Private header and source files of RTX software component
 📂 Template           | User code templates for creating application projects with CMSIS-RTX
 📄 ARM.CMSIS-RTX.pdsc | Pack description file in CMSIS-Pack format
 📄 LICENSE            | License Agreement (Apache 2.0)
 📄 RTX5.scvd          | SCVD file for RTOS-aware debugging with [Component Viewer and Event Recorder](https://arm-software.github.io/CMSIS-View/latest/index.html)

See [CMSIS Documentation](https://arm-software.github.io/CMSIS_6/) for an overview of CMSIS software components, tools and specifications.

## License {#rtx_license}

CMSIS-RTX is provided free of charge by Arm under the [Apache 2.0 License](https://raw.githubusercontent.com/ARM-software/CMSIS-RTX/main/LICENSE).