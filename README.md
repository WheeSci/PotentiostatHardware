PotentiostatHardware
====================

Eagle files for low voltage potentiostat design based on TI LaunchPad.
  Through hole connections on the left side of the main board fit to the left header of a TI Launchpad MSP430g2 development board with g2553 microprocessor.  One through hole connection on the right side lines up with ground on LaunchPad header.
  This design uses PDIP components.  Op amps are powered from +5 volt source next to mini-usb hub on LaunchPad board.  LDO represented as 1.8 volt should be +2.5 volt.  Separate board segments for; Main board (left), stirring paddle (upper right), comm board (bottom right) and multiplexer (center right).  Stirring paddle accepts coin vibrating motor to stirr solution.  Comm board is used to adapt early version (1.4) of LaunchPad to communicate with g2553 chip.  The comm board is not needed on LaunchPad version 1.5 or later.  A rotary switch allows the user to select one of twelve resistors that determine the current gain for the instrument.  Resistors are ganged together at the multiplexer board. 
