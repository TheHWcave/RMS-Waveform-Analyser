This spreadsheet can models periodic wave forms and calculates the True RMS value as well as the AC-coupled True RMS, which is what your True RMS multimeter displays, and the value displayed by averaging meters (not True RMS). 

The Excel and ODS versions have the same models.


I presented this model and walked through some of the wave forms in a YouTube video on True RMS
You find it and additional material on my channel “TheHWcave” 


In all models:
Column A shows 100 sample values (from row 8 onwards) 
Populate the equivalent rows in column B "Wave" with amplitude values, either by typing them in (as in the blank worksheet) or using mathematical functions like I did for the other worksheets. 

cell B4 shows the DC coupled  ( that is DC+AC) True RMS 
cell B5 shows the DC coupled average, that is the DC value if there is one
cell C4 shows the AC coupled True RMS (that is what your True RMS multimeter will display)
cell D6 shows what a non-true RMS, that is an averaging multimeter like the RS-Pro RS-14 will display


The first worksheet "blank" is intended to manually fill in sample values in to the WAVE column B

as inspiration, the following wave forms are included:

worksheet "sine" is a sine wave form. You can change period and amplitude in cells B1 and B2 respectively

worksheet "sine_full_rect" is a sine wave after a full bridge rectifier. You can change period and amplitude (peak) in cells B1 and B2 respectively

worksheet "sine_half_rect" is a sine wave after a half-way rectifier. You can change period and amplitude (peak) in cells B1 and B2 respectively

worksheet "square" is a square wave going from +peak to -peak. You can change duty cycle and amplitude (peak) in cells B1 and B2 respectively

worksheet "pulse" is a pulse wave going from +peak to 0. You can change duty cycle and amplitude (peak) in cells B1 and B2 respectively

worksheet "exp" is a wave with an exponentially rising slope like from charging a capacitor. You can change Tau (exponent) and amplitude (peak) in cells B1 and B2 respectively

worksheet "sine-pulse" is the sin(x)/x wave. You can change period and amplitude (peak) in cells B1 and B2 respectively 

worksheet "AM1" is a carrier sine wave amplitude modulated by a modulation sine wave with twice the frequency of the carrier.  You can change period, amplitude (peak) and modulation depth in cells B1, B2 and D2 respectively 

worksheet "AM2" is a carrier sine wave amplitude modulated by a modulation sine wave with 1/8th  the frequency of the carrier.  You can change period, amplitude (peak) and modulation depth in cells B1, B2 and D2 respectively 

