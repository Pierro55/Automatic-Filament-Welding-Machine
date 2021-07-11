# Automatic-Filament-Welding-Machine

##What is this?
This is an automatic filament welding machine. Its purpose is to weld left over filament and wind it on a spool afterwards. 

##General information
I designed and build this machine as part of my mechanical engineering bachelor thesis. Unfortunately, I didn't have enough time to program it and test it thoroughly but tested every single subsystem of the machine itself. The welding itself works really well. 
All parts are modular and interchangeable. I’ve attached my thesis report which goes into every little detail of the design and building process. It is written in Dutch but translating it should be doable. Maybe I will add an English version in the near future if I get enough requests (or maybe somebody else is so kind to translate it). If you can understand Dutch please read it with a grain of salt as Dutch isn’t my first language. I will roughly describe every process in English in this readme.

##Cutting system
![alt text]( https://github.com/Pierro55/REuse-Automatic-Filament-Welding-Machine/blob/main/Cutting%20Sytsem/Bill%20of%20materials.PNG)
The cutting system is designed to cut off the filament ends before welding them together and automatically eject the cutoff. The idea behind this system is to make the machine more reliable by controlling the shape of the filament ends. In my experiments I used a geared DC motor for this, which turned out to be too weak. I therefore had to ditch it for the final machine as there wasn’t enough time left. It can still be added to the machine because of its modularity.
The basic principle works as follows:
![alt text]( https://github.com/Pierro55/REuse-Automatic-Filament-Welding-Machine/blob/main/Cutting%20Sytsem/Cutting%20system%20basic%20principle.png = width=80)
The purple gear is connected to the motor. This gear moves the left brown arm through a rag pinion mechanism down and the right one up (and vice versa if the motor rotates the other direction). Both arms have a wedge (wig in Dutch) mounted in the middle. As the arms move closer to each other the wig cuts off filament which sits in the hole between the two arms.
The automatic ejection happens on the outside of the cutting system. As the motor moves the mechanism, a second mechanism, which is directly coupled with the motor shaft, moves two outputs. One is for the cutoff and the second one is for the to be welded filament. 

![alt text](https://github.com/Pierro55/REuse-Automatic-Filament-Welding-Machine/blob/main/Cutting%20Sytsem/Cutting%20automation%20principle.png)


