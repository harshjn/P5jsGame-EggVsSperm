# P5jsGame-EggVsSperm
A processing game that demonstrates flocking.
Game can be accessed at https://harshjn.github.io/P5jsGame-EggVsSperm/

Every element of the flock(also known as vehicle) has a predefined target (egg in this case), but it is able to observe only a narrow neighbourhood around it. 
Therefore, it makes decisions about which direction it wants to move in based on the following factors:
* Whether it can find the target in it's neighbourhood (seek the target).
* What direction other vehicles around it are doing (follow the herd).
* Avoid collision with other members.

Based on these factors, it calculates a force to locomote with. Force on the vehicle will be more closer to a target. With more motivation, it will move faster, but the maximum speed will be limited because of environmental constraints.
