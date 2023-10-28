# MF50
Capacitive replacement PCB for the IBM M50.

![MF50 kicad](https://i.imgur.com/UvGCcPZ.png)

This PCB is designed for the M50. Although it shares the F50's matrix and bears similarities to the capacitive PCB from the F50, I think it is unlikely it would function with the F50's original controller and I cannot guarantee it will fit at all.

---

I have tested this in my own M50. I ordered it from JLCPCB with 0.6mm thickness. 

It is designed to be used with the SMD Model F Controller: https://deskthority.net/viewtopic.php?t=24597

I used the "standard" version of the controller, and it fit nicely - but not precisely - in the bottom case.

I do not know if it is compatible with the "4704" version of the controller.

You must have some sort of insulation between the bottom of the PCB and the plate. I cut an insulating layer out a sheet of 0.1mm PVC purchased from here: https://www.amazon.com/dp/B095N7TMZH

**You MUST ground the backplate to the controller** - this is not shown in the image below.


![IMG_20231028_001553](https://github.com/taylorswift22/MF50/assets/22061508/08a33d1c-f700-4207-a491-4c0386bf98e7)


QMK-xwhatsit firmware made by purdeaandrei can be found here: http://35.164.28.200:5000/#/xwhatsit/ibm/f50/universal/LAYOUT

I have not tested this with normal xwhatsit firmware.

---

This project is open source, but I do not endorse it as a starting point for your own Model F PCB project.

Credits:
- purdeaandrei
- dorkvader
- vivilazuli
- theMK
