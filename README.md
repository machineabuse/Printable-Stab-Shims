# Printable-Stab-Shims
Printable stabilizer shims for your thin keyboard PCB


## 1.0 Description
This repository holds a handful of .STLs for stabilizer shims for various situations you may encounter. If you need just a basic shim to go on top of the pcb, got you covered. If you need something to go on the back (component) side of the PCB; I've provided a range of shapes just in case you happen to have components in the way. These shims are designed for Adapting full sized 1.6mm stabilizers to 1.2mm thickness PCBs.

I would suggest that if you are getting these printed, get more than you need printed in case you need to modify the files further.

When using these below the PCB, Take a long hard look at the componentry to make sure the shims are not interfering with anything. Also check after mounting your stabs that no intereference with your case is present. Might be awkward! 🤪


## 2.0 Printing

2.1.1 - Type 1
- This is the simplest pattern. This is meant to be used between the stab housing and the PCB. I would suggest using this variation if you are using long pole switches as it raises the bottom out height by 0.4mm.
![image](https://user-images.githubusercontent.com/8606354/171822812-ab467275-32d1-495c-a101-2ce69875d9c5.png)

2.1.2 - Type 2
- The "dogbone" pattern. This is designed to be used below the PCB, it has a symmetrical relief on either side to ensure these fit around hot swap sockets and other components that may get in the way.
- ![image](https://user-images.githubusercontent.com/8606354/171823253-b4bc6779-a900-4c5d-9d49-08ccc70d5364.png)

2.1.3 - Type 3
- The assymetric pattern. Designed to be used below the PCB, Type 3 is designed to be used in conjuction with Type 2 in cases where PCB componentry obstructs the fit. If you have a diode directly in the path of your mount, this may be the way to go.
![image](https://user-images.githubusercontent.com/8606354/171823279-766ad50d-da1b-4d8a-ba27-681fdbbf4289.png)

2.1.4 - Type 4
- The washer type. Used below the PCB. When all else fails to fit, you gotta do what you gotta do I guess.
![image](https://user-images.githubusercontent.com/8606354/171823288-98944f09-cda8-4a90-9d06-74fdefc52e37.png)


### 2.2 Print configurations

The "continuous " Options are modeled in one continuous outer perimeter in an effort to increase the overall quality of the print.

| Type 1     | Type 2    | Type 3    | Type 4 |
|------------|-----------|-----------|-----------|
| 1x ![image](https://user-images.githubusercontent.com/8606354/171824102-25b651e2-5ca0-4541-8f01-d20f7edbf27d.png)
   | 1x | A Side/B Side| 1x Small/Big |
| 2x Continuous   | 2x Continuous  | A Side/B Side Continuous| 1xPair Small/Big | 
| 10x Continuous | 10x Continuous  | 5xPair Continuous | 10xPair Small/Big


### 2.3 Suggested FDM Print Specifications

- Print in PLA
- 0.2mm layer height
- 0.5mm extrusion width
- print in 100% layers (no infill)


## 3.0 Modification & Open Source

In the event you encounter any different thicknesses of PCB, I have included the files neccesary for you to modify and produce your own versions of these shims in .SKP format as this project was modeled in in Sketchup Free.

If you would wish to use these as a basis for your own work kindly respect the open source licence and make derivatives of this work available to any who ask.
