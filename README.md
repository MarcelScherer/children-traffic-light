# children-traffic-light
traffic light to play for children

<img src="https://github.com/MarcelScherer/children-traffic-light/blob/main/Docu/PXL_20201018_121728001.jpg" alt="drawing" width="200px"/>  | 
<img src="https://github.com/MarcelScherer/children-traffic-light/blob/main/Docu/IMG_20201010_204619.jpg" alt="drawing" width="290px"/>  | 
<img src="https://github.com/MarcelScherer/children-traffic-light/blob/main/Docu/IMG_20201012_210220.jpg" alt="drawing" width="250px"/>  </p>

all parts that need to be created for the project with a 3D printer can be found at [https://www.thingiverse.com/thing:4626621](https://www.thingiverse.com/thing:4626621
)</p> </p>

First you have to create two times each of the three traffic lights red, yellow and green:</p>
wirering            |  pic
:-------------------------:|:-------------------------:
<img src="https://github.com/MarcelScherer/children-traffic-light/blob/main/Docu/led-light.png" width="425"/>   |  <img src="https://github.com/MarcelScherer/children-traffic-light/blob/main/Docu/IMG_20201010_204253.jpg" width="325"/> 
</p> </p>

Afterwards a board is needed, which controls the 6 lamps with the help of a transistor. I used a BC327 in my example, but since I am not a hardware expert, I can't say if there is a better solution. Mine works:</p>
wirering            |  pic
:-------------------------:|:-------------------------:
<img src="https://github.com/MarcelScherer/children-traffic-light/blob/main/Docu/transistor.png" width="425"/>   |  <img src="https://github.com/MarcelScherer/children-traffic-light/blob/main/Docu/PXL_20201014_192111883.jpg" width="325"/> 

Finally, a potentiometer must be connected with which the time of a green/red phase can be set between 2 and 20 seconds:</p>
<img src="https://github.com/MarcelScherer/children-traffic-light/blob/main/Docu/timer%20poti.png" width="425"/> </p>

At last you have to flash the [cpp](https://github.com/MarcelScherer/children-traffic-light/blob/main/children-traffic-light/src/main.cpp) file to the arduino 

