# LoRaWAN code

Version 1.0.0, 29/11/2019

# About this code

This code is from Congduc Pham and can be found here: https://github.com/FabienFerrero/UCA_Education_Board/tree/master/Code/LORAWAN/ABP/Arduino_LoRa_UCA

To run this code, you will need to create a device in The Things Network and change the code with the appropriate keys in hex format.

The keys are at line 137, 138 and 150;

to modify the message sent, you have to change the payload at line 681.

# Caution please !
Please use this code for tests only, the limitations of the LoRaWAN protocol are not respected. The delay between two messages is approximately 5 seconds.
