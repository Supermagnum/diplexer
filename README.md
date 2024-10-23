# diplexer
HF+6M lowpass and 4M highpass

The lowpass filter has: 71.5mhz -42dB. 
Highpass filter 52.5mhz -45dB. 50.5mhz -50db

Highpass Ltspice analysis setup:
![highpass-parts.png](highpass-parts.png)

Highpass frequency analysis ( insertion loss, insertion phase, and return loss):
![highpass.png](highpass.png)

Highpass Z-in and Z out analysis:
![highpass-imp.png](highpass-imp.png)


Lowpass LTspice analysis setup:
![lowpassfilter-parts.png](lowpassfilter-parts.png)

Lowpass filter frequency analysis ( insertion loss, insertion phase, and return loss):
![lowpassfilter.png](lowpassfilter.png)

Lowpass filter Z-in and Z out:
![lowpassfilter-Z.png](lowpassfilter-Z.png)

PCB board screenshot:
![board-picture-kicad.png](https://github.com/Supermagnum/diplexer/blob/main/board-picture-kicad.png)

I had to draw the 1111 SMD footprint because it wasn't included in the Kicad database.
I hope that I haven't messed up.
Shematic for the diplexer:
https://raw.githubusercontent.com/Supermagnum/diplexer/refs/heads/main/diplexer.pdf

BOM for capacitors and connectors:
https://github.com/Supermagnum/diplexer/blob/main/BOM.xls

Inductors:
You have to make these yourself!
https://github.com/Supermagnum/diplexer/blob/main/Inductors.pdf

Suitable box:
https://www.hammfg.com/part/1457N1601E

All bolt holes is M3.

PCB boards and assembly:
<a href="https://www.pcbway.com/project/shareproject/HF_6M_lowpass_and_4M_highpass_diplexer_37973d8c.html"><img src="https://www.pcbway.com/project/img/images/frompcbway-1220.png" alt="PCB from PCBWay" /></a>







