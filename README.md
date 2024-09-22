This project begun as building a small solid state Tesla coil just for fun.
After successfully used on CTU FEE presentations, commercial journey has begun...

![image](https://github.com/user-attachments/assets/eb60aef6-0363-419b-b6fb-f86851f63534) ![image](https://github.com/user-attachments/assets/a66bd5f8-7536-4858-8648-89b4dbd509a4) ![image](https://github.com/user-attachments/assets/032f86a3-a958-4ab6-b5a0-a5657ae5ff10)

SSTC has STM32F030 as main conroller. It controls power voltage and enabled/disables power self-oscillating circuit. STM32 is performing MIDI note synthesis from two possible input sources - bluetooth VCP and traditional 5-pin MIDI. This can be done by 2 methods - modulation of power voltage by buck converter - one mode. And by enabling/disabling power oscillator in rythm of played note - second mode. In "CW" mode is also possibility to play multiple notes at ones while in interrupter mode only one note at a time. Disadvantage of CW mode is high power consumption and thus power losses causing overheating after few minutes.



Bluetooth name: SSTC_SNxx (xx serial number)

Bluetooth PIN: 7390



Tesla Coil is for safety reasons powered by external 36V/5A SMPS, so no lethal voltage is available anywhere.

Video in action:

https://youtu.be/WxlvXRLJuSU

https://youtube.com/shorts/vosLOoO7MRc

While its electronics:

![image](https://github.com/user-attachments/assets/60e506f0-7798-44bb-a88b-fc2842600a09) ![image](https://github.com/user-attachments/assets/e2a8e370-b9ba-4dac-a9f7-66d4ad19270d)


This SSTC has 2 switches for mode setting and 2 POTs for manual mode setting.

![image](https://github.com/user-attachments/assets/68e4f71e-f0cf-4f78-bfaa-ac3ca1352f65)


3-way switch on left swithes between modes:

left: Interrupter based MIDI (single note)

mid:  Manual mode

right:CW modulated MIDI (max 4 notes at a time)


2-way switch on right:

left:  MIDI INPUT

right: BLUETOOTH INPUT

(for manual mode it also switches between POTs input and bluetooth input)




