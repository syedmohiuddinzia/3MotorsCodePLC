***________________________________ بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيم***

***_____________________________ PRAY FOR PALESTINE 🇵🇸***

***______________________________ PAKISTAN ZINDABAD 🇵🇰***

***Arduino CODE BY:***
***SYED MOHIUDDIN ZIA***
***0092 307 2099300***

# Requirement
```
- Each pump has pressure switch as a feedback.
- In Auto Mode, upon starting the process, if Pressure doesn't develop with in given time in Pump1 then it would stop Pump1 and transfer the command to Pump2, and same case for Pump 3.
- In Manual Mode, Each Pump can be started individually but not at the same time which means interlocking should be done and if pressure fails to develop there should be an indication for example pump1 is at Fault.
- And last thing if all three pumps fails to start it would generate an Alarm that will let the facility know about the status of Pumps.
```
# Requirement
**1. WinPro Ladder Software**  
```
https://plc4me.com/download-win-proladder-v3-27-fatek-plc-software-real-100/
```
# Pre Requisite
**1. Basic Ladder Logic Knowlege**  
```
1. Normally Open Input
2. Normally Close Input
3. Normally Open Output
4. Normally Close Output
5. Memory, Registers 
6. Counters, Timers
7. Etc.
```

# Reference

[WinProFaktek Instruction Manual](https://drive.google.com/drive/folders/1fcRhLmjpI39hsA_bJIU0bxqD0Tx-heUF?usp=sharing)

# * Ladder Logic Diagram
![Mnemonic1](https://github.com/syedmohiuddinzia/3MotorsCodePLC/blob/main/LadderLogic1.jpg)
![Mnemonic1](https://github.com/syedmohiuddinzia/3MotorsCodePLC/blob/main/LadderLogic2.jpg)

# * Mnemonic Program
![Mnemonic1](https://github.com/syedmohiuddinzia/3MotorsCodePLC/blob/main/Mnemonic1.jpg)
![Mnemonic2](https://github.com/syedmohiuddinzia/3MotorsCodePLC/blob/main/Mnemonic2.jpg)
