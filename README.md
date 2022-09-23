# HexAreaChecker
This file is the viewer of the Hex file. Main purpose is to check the address space.

It supports Motorola S-record format (.s19, .mot) and Intel HEX format (.hex), and automatically determines the format when reading. 

## Correspondence: 
  Motorola S-record format: Record Field=S0~S3, S5~S9 (S4 is not responding because it is Reserved)
  Intel HEX format: Recode Type=00~05

HexAreaChecker also checks the data length and checksum, so it can be used for confirming the checksum after editing data. Numbers are written in hexadecimal notation except for the "No." column of the Summary sheet.

## Sample Hex file
![gif](http://toowaki.web.fc2.com/picture/HexAreaChecker_img_EN.png)
