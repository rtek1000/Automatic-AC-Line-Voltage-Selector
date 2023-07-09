# Automatic-AC-Line-Voltage-Selector
Automatic selector for 110VAC or 220VAC

- Usable for equipment that works with only 110V or for 110V or 220V devices with manual switch selection.
- - It can operate with only 1 relay, but the 47V zener diode must be kept in the scheme so as not to force the MOSFET.
-
- Operating mode is simple: the normally closed contact is for higher voltage connection (220V), when the AC line voltage is about 140Vac or less, the relay is activated.

![img](https://raw.githubusercontent.com/rtek1000/Automatic-AC-Line-Voltage-Selector/main/Doc/Manual%20selector%20example%201.png)

Schematic:
![img](https://raw.githubusercontent.com/rtek1000/Automatic-AC-Line-Voltage-Selector/main/Doc/Automatic%20AC%20Line%20Voltage%20Selector.png)

Board:
![img](https://raw.githubusercontent.com/rtek1000/Automatic-AC-Line-Voltage-Selector/main/Doc/Automatic%20AC%20Line%20Voltage%20Selector%20TL431_1.png)

## Licence:
- Hardware:

Released under CERN OHL 1.2: https://ohwr.org/cernohl
