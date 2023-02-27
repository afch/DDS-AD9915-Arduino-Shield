# DDS-AD9915-Arduino-Shield
DDS (Direct Digital Synthesis) Analog Devices AD9915 Arduino Shield by GRA &amp; AFCH
The difference between the two RF Shield Units is only in the maximum clocking frequency of the DDS core
In DDS AD9915 Shield Unit it is nominally 2.5 GHz and it can be overclocked to 3 GHz
In DDS AD9914 Shield Unit it is nominally higher than 3.5 GHz and can be overclocked to 4 GHz
The firmware is the same for AD9914 and AD9915 except for the inscription on the OLED screen, you need to change line 14 in the DisplayMenu.ino file to display.printin(F("DDS AD9915"));
Link for repository: <a href="https://github.com/afch/DDS-AD9914-Arduino-Shield"> Analog Devices AD9914 Arduino Shield </a>
