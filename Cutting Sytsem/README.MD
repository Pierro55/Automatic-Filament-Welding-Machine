## Cutting system
<img src="https://github.com/Pierro55/REuse-Automatic-Filament-Welding-Machine/blob/main/Cutting%20Sytsem/images/Bill%20of%20materials.PNG" width=70% height=70%>

The cutting system is designed to cut off the filament ends before welding them together and automatically eject the cutoff. The idea behind this system is to make the machine more reliable by controlling the shape of the filament ends. In my experiments I used a geared DC motor for this, which turned out to be too weak. I therefore had to ditch it for the final machine as there wasn’t enough time left. It can still be added to the machine because of its modularity.

### Basic Principle
The basic principle works as follows:

<img src="https://github.com/Pierro55/REuse-Automatic-Filament-Welding-Machine/blob/main/Cutting%20Sytsem/images/Cutting%20system%20basic%20principle.png" width=30% height=30%>

The purple gear is connected to the motor. This gear moves the left brown arm through a rag pinion mechanism down and the right one up (and vice versa if the motor rotates the other direction). Both arms have a wedge (wig in Dutch) mounted in the middle. As the arms move closer to each other the wig cuts off filament which sits in the hole between the two arms.
The automatic ejection happens on the outside of the cutting system. As the motor moves the mechanism, a second mechanism, which is directly coupled with the motor shaft, moves two outputs. One is for the cutoff and the second one is for the to be welded filament. 

<img src="https://github.com/Pierro55/REuse-Automatic-Filament-Welding-Machine/blob/main/Cutting%20Sytsem/images/Cutting%20automation%20principle.png" width=70% height=70%>
