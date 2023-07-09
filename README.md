# Automatic-AC-Line-Voltage-Selector
Automatic selector for 110VAC or 220VAC

- Usable for equipment that works with only 110V (to protect against wrong connection to 220V) or for 110V / 220V devices with manual switch selection.
- - It can operate with only 1 relay, but the 47V zener diode (D4, D5) must be kept in the scheme so as not to force the MOSFET (Q2).
-
- Operating mode is simple: the normally closed contact (NC) is for higher voltage connection (220V), when the AC line voltage is about 140Vac or less, the relay is activated.
- - The circuit has no hysteresis, so it may oscillate if the AC line voltage is at the threshold.
-
- Note: The wire colors in the example are merely illustrative:

![img](https://raw.githubusercontent.com/rtek1000/Automatic-AC-Line-Voltage-Selector/main/Doc/Manual%20selector%20example%201.png)

Schematic:
![img](https://github.com/rtek1000/Automatic-AC-Line-Voltage-Selector/blob/main/Doc/Automatic%20AC%20Line%20Voltage%20Selector%201.png)

Board:
![img](https://raw.githubusercontent.com/rtek1000/Automatic-AC-Line-Voltage-Selector/main/Doc/Automatic%20AC%20Line%20Voltage%20Selector%20TL431_1.png)

## Licence:
- Hardware:

Released under CERN OHL 1.2: https://ohwr.org/cernohl
