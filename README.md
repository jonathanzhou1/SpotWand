# SpotWand
Experimental code to make Boston Dynamic's Spot robot's arm follow a path determined by data in a csv file.
Initial code taken from spot-sdk at https://github.com/boston-dynamics/spot-sdk/blob/master/LICENSE(https://github.com/boston-dynamics/spot-sdk/blob/master/LICENSE).
This repository is purely for educational purposes only.

## Features
Added a simulation mode with matplotlib to see the path of your coded trajectory before running it on the Spot.
To run the simulation, run ```python3 <file path> --simulate```
To run the Spot, run ```python3 <file path> <spot ip addr>```

## Files:
```arm_rose_curve.py``` is a file that draws a rose curve with Spot's arm using polaroid equations.
```arm_follow_wand.py``` makes Boston Dynamic's Spot robot's arm follow a path determined by data in the ```wand_log.csv``` file. Note: the columns of data used in ths csv file are normalized around 0 to make the positions relative to spot's arm.
