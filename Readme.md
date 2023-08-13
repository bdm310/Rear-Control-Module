# Porsche 997/987 Rear Control Unit
This is a repository of information about the rear control unit on these 911/Boxster/Cayman cars. Part number of the unit shown is 997-618-260-08.

Connector C is yellow and on the right when looking at connector side of board with connector latches on top.

Useful Pins
- C12 - right stop light - VN450P output 1
- C11 - left stop light - VN450P output 2
- C10 - side marker left - BTS611 (next to VN450P) output 1
- B5 - side marker right - BTS611 (board edge) output 2
- B10 - rear fog - BTS640 (board edge)

Measurements
- Fog light current sense resistor - 4.74kOhm
- Fog light wattage is 21W only on one side - 1.75A
- DEPO LED fog light measures at 180mA

## Mods for LED Rear Lights
- Lift pins 4, 6 on VN450P (red boxes)
- Lift pin 5 on both BTS611 (red boxes)
- Replace sense resistor on BTS640 (board edge) with a 47kOhm 0603 resistor(yellow box)
- Bonus point - solder one side of the original 4.74kOhm resistor to this empty pad so that it's right there if someone wants to revert these modifications (teal box)

![Modified Areas](<Board Top - Modifications.jpg>)