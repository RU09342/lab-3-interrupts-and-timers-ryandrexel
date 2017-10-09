# README for Button Interrupt

Ryan E. Drexel
	
	Created 05 October 2017
	Updated 09 October 2017

Embedded Systems- Dr. Tang and Mr. T.

Button Interrupt is a C language program designed to run on five MSP430 microprocessors (listed below)
	MSP430G2553
	MSP430FR6989
	MSP430F5529
	MSP430FR2311
	MSP430FR5994
Button Interrupt uses interrupts to trigger events rather than a polling system. Polling is not nearly 
as power efficient as interrupts. An interrupt sets off a flag when the check passes, and then the processor
goes into an interrupt service routine. In the case of this script, the ISR flips an LED.