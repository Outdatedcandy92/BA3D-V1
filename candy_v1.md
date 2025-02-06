# 4-Axis 3D Printer

Made by: @outdatedcandy92

Repository: [https://github.com/Outdatedcandy92/CandyV1](https://github.com/Outdatedcandy92/CandyV1)

Total Hours: 3

- ✅I have a 3D printer or will be getting one before March 21st

---

## Overview:

CandyV1 is my attempt at making a 4-axis polar printer. It would work by having a rotational C-axis for the bed and a rotational B-axis on the extruder, additionally the plan is to have the bed move linearly in the Y-axis.

Desired Specs-

- Polar printer + rotating toolhead
- Uses Klipper
- 0.1mm resolution
- multi-color (maybe)
- raspi 4 controller
- build volume: doesn’t really matter
- timelapse feature
- tangle detection

 

## Day 1 (3rd Feb, 2025)

Did preliminary research on polar printers and how they work

- Want something like this by Joshua [https://www.youtube.com/watch?v=VEgwnhLHy3g](https://www.youtube.com/watch?v=VEgwnhLHy3g)
- Instead of the toolhead moving on the X-Axis I'm thinking of the moving the whole bed if possible???

![image.png](https://cloud-rhn74wi57-hack-club-bot.vercel.app/0image.png)

- Did a little bit of researching about 3D printer parts

I want this thing to be able to fit on my shelf/desk, build volume doesn’t really matter i just want to make 

### Time Elapsed: 1 Hrs

## Day 2 & 3 (4th-5th Feb, 2025)

- Created a project timeline and set up deadlines
- worked on formatting this markdown file and writing a description for this project

I was thinking about how printing with a rotational bed would work, like how much should i rotate to get to a set coordinate on a cartesian plane.

- Studied about polar coordinates and how they really work.
- Turns out its very easy to convert cartesian coordinates to polar ones.

Below is the math for how it works for a point (x,y) on a cartesian plane. 

1. Find linear position (r) of the bed by using pythagoras theorem
    
    [![\\ r^{2}=\sqrt{x^{2}+y^{2}}](https://latex.codecogs.com/svg.latex?%5C%5C%20r%5E%7B2%7D%3D%5Csqrt%7Bx%5E%7B2%7D%2By%5E%7B2%7D%7D)](#_)    r^{2}=\sqrt{x^{2}+y^{2}}

    

1. Find angle of the bed (θ) using trigonometry (use Sin/Cos/Tan based on the quadrant of the coordinates). here we assume its in the 1st quadrant
    
    [![\\ \theta = \cot(\frac{y}{x})](https://latex.codecogs.com/svg.latex?%5C%5C%20%5Ctheta%20%3D%20%5Ccot(%5Cfrac%7By%7D%7Bx%7D))](#_)

    

Polar coordinates are (r,θ)

- I still have no idea what parts im gonna use

### Time Elapsed: 2 Hrs
