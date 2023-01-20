# STM32G4 Altium Designer Library
This project is based on the file from [stm32 official file](https://www.st.com/resource/en/cad_symbol_library/stm32g4_cad.zip). And this version is based on v1.1 and which is released on V1.1 FEBRUARY 28，2019 .
![stm32g4_cad.zip version 1.0](/img/version_info.png)

I build it using Altium Designer 2019, but I think you can use the intergration file on any altium designer version (version > 10).

# About STM32G4
For now, there are three series is include in STM32G4 series and they are STMG4x1, STM32G4x3 and STM32G4x4 depending on if they include FSMC or High-Resolution Timer. 
![stm32g4 series overview](/img/en.stm32g4_series_ss2024.jpg)

The STM32G4x1 are mixed-signal microcontrollers with an Arm® Cortex®-M4 core (with FPU and DSP instructions) running at 170 MHz. These are entry-level devices in the STM32G4 series .They cover 10 packages: LQFP32, UFQFPN32, LQFP48, UFQFPN48, WLSP49, LQFP64, UFBGA64, LQFP80, LQFP100 and BGA100. 
![stm32g4x1 series overview](/img/en.stm32g4x1_line_ln2128.jpg)

The STM32G4x3 are mixed-signal microcontrollers with an Arm® Cortex®-M4 core (with FPU and DSP instructions) running at 170 MHz. These are performance devices in the STM32G4 series, which embed a maximum number of analog peripherals. They include LQFP48, UFQFPN48,LQFP64, LQFP80, WLCSP81, LQFP100, BGA100 and LQFP128.
![stm32g4x3 series overview](/img/en.stm32g4x3_line_ln2129.jpg)

The STM32G4x4 Hi-resolution line specifically addresses digital power conversion applications, such as D-SMPS, lighting, welding, inverters for solar systems and wireless chargers. They cover LQFP48, UFQFPN48, LQFP64, UFBGA64, LQFP80, WLCSP81, LQFP100, BGA100 and LQFP128.
![stm32g4x4 series overview](/img/en.stm32g4x4_line_ln2130.jpg)



## The library List
This library includes 13 packages and 102 devices. Here is the pakages list: 
LQFP32 7x7x1.4:
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G431K6Tx
	STM32G431K8Tx
	STM32G431KBTx

	STM32G441KBTx
~~~~~~~~~~~~~~~~~~~~~~~~~

UFQFPN32 5x5x0.55: 
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G431K6Ux
	STM32G431K8Ux
	STM32G431KBUx

	STM32G441KBUx
~~~~~~~~~~~~~~~~~~~~~~~~~

LQFP48 7x7x1.4:  
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G431C6Tx  
	STM32G431C8Tx
	STM32G431CBTx

	STM32G441CBTx

	STM32G471CBTx
	STM32G471CCTx
	STM32G471CETx

	STM32G473CBTx
	STM32G473CCTx
	STM32G473CETx

	STM32G474CBTx
	STM32G474CCTx
	STM32G474CETx

	STM32G484CETx
~~~~~~~~~~~~~~~~~~~~~~~~~

UFQFPN48 7x7x0.55: 
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G431C6Ux
	STM32G431C8Ux
	STM32G431CBUx

	STM32G441CBUx

	STM32G471CBUx
	STM32G471CCUx
	STM32G471CEUx

	STM32G473CBUx
	STM32G473CCUx
	STM32G473CEUx

	STM32G474CBUx
	STM32G474CCUx
	STM32G474CEUx

	STM32G484CEUx
~~~~~~~~~~~~~~~~~~~~~~~~~

WLSP49 3.15x3.13, pitch 0.4: 
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G431CBYx

	STM32G441CBYx
~~~~~~~~~~~~~~~~~~~~~~~~~

LQFP64 10x10x1.4: 
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G431R6Tx
	STM32G431R8Tx	
	STM32G431RBTx

	STM32G441RBTx

	STM32G471RBTx
	STM32G471RCTx
	STM32G471RETx

	STM32G473RBTx
	STM32G473RCTx
	STM32G473RETx

	STM32G474RBTx
	STM32G474RCTx
	STM32G474RETx

	STM32G484RETx
~~~~~~~~~~~~~~~~~~~~~~~~~

UFBGA64 5x5x0.6: 
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G431R6Ix
	STM32G431R8Ix
	STM32G431RBIx

	STM32G441RBIx
~~~~~~~~~~~~~~~~~~~~~~~~~

LQFP80 12x12x1.4:
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G471METx

	STM32G474METx

	STM32G484METx
~~~~~~~~~~~~~~~~~~~~~~~~~

WLCSP81 4.02x4.27, pitch 0.4:
~~~~~~~~~~~~~~~~~~~~~~~~~
STM32G473MEYx
~~~~~~~~~~~~~~~~~~~~~~~~~

LQFP100 14x14x1.4: 
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G431V6Tx	
	STM32G431V8Tx
	STM32G431VBTx

	STM32G441VBTx

	STM32G471VBTx
	STM32G471VCTx
	STM32G471VETx

	STM32G473VBTx
	STM32G473VCTx
	STM32G473VETx

	STM32G474VBTx
	STM32G474VCTx
	STM32G474VETx

	STM32G484VETx
~~~~~~~~~~~~~~~~~~~~~~~~~

TFBGA100 8x8, pitch 0.8: 
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G471VBHx
	STM32G471VCHx
	STM32G471VEHx

	STM32G473VBHx
	STM32G473VEHx

	STM32G474VBHx
	STM32G474VCHx
	STM32G474VEHx

	STM32G484VEHx
~~~~~~~~~~~~~~~~~~~~~~~~~

?UFBGA100 ??:
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G471VBIx
	STM32G471VCIx
	STM32G471VEIx

	STM32G473VBIx
	STM32G473VCIx
	STM32G473VEIx

	STM32G474VBIx
	STM32G474VCIx
	STM32G474VEIx
~~~~~~~~~~~~~~~~~~~~~~~~~


LQFP128 14x14x1.4:
~~~~~~~~~~~~~~~~~~~~~~~~~
	STM32G471QBTx
	STM32G471QCTx
	STM32G471QETx
	
	STM32G473QBTx
	STM32G473QCTx
	STM32G473QETx
	
	STM32G474QBTx
	STM32G474QCTx
	STM32G474QETx
	
	STM32G484QETx
~~~~~~~~~~~~~~~~~~~~~~~~~

	