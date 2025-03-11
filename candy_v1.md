# Candy V1
Made by: @outdatedcandy92

Repository: [https://github.com/Outdatedcandy92/CandyV1](https://github.com/Outdatedcandy92/CandyV1)

### Total Hours: 11

- ✅I have a 3D printer or will be getting one before March 21st

---

## Overview:


Desired Specs-

- 300x300x250 build volume
- Uses Klipper
- 0.1mm resolution
- multi-color (maybe)
- raspi 4 controller
- timelapse feature
- tangle detection

 

## Day 1 (3rd Feb, 2025)

Did preliminary research on polar printers and how they work

- Want something like this by Joshua [https://www.youtube.com/watch?v=VEgwnhLHy3g](https://www.youtube.com/watch?v=VEgwnhLHy3g)
- Instead of the tool head moving on the X-Axis I'm thinking of the moving the whole bed if possible???
- Did a little bit of researching about 3D printer parts

I want this thing to be able to fit on my shelf/desk, build volume doesn’t really matter i just want to make it

### Time Elapsed: 1 Hrs

## Day 2 & 3 (4th-5th Feb, 2025)

- Created a project timeline and set up deadlines
- worked on formatting this markdown file and writing a description for this project

I was thinking about how printing with a rotational bed would work, like how much should i rotate to get to a set coordinate on a Cartesian plane.

- Studied about polar coordinates and how they really work.
- Turns out its very easy to convert Cartesian coordinates to polar ones.

Below is the maths for how it works for a point (x,y) on a Cartesian plane. 

1. Find linear position (r) of the bed by using Pythagoras theorem
    
    [![\\ r^{2}=\sqrt{x^{2}+y^{2}}](https://latex.codecogs.com/svg.latex?%5C%5C%20r%5E%7B2%7D%3D%5Csqrt%7Bx%5E%7B2%7D%2By%5E%7B2%7D%7D)](#_)    

    

2. Find angle of the bed (θ) using trigonometry (use Sin/Cos/Tan based on the quadrant of the coordinates). here we assume its in the 1st quadrant
    
    [![\\ \theta = \cot(\frac{y}{x})](https://latex.codecogs.com/svg.latex?%5C%5C%20%5Ctheta%20%3D%20%5Ccot(%5Cfrac%7By%7D%7Bx%7D))](#_)

    

Polar coordinates are (r,θ)

- I still have no idea what parts I'm gonna use

### Time Elapsed: 2 Hrs

## Day 4-6 (8th-10th March, 2025)

 ### March break grind starts!!

##### March 8th
I decided to scrap my previous idea of a polar printer, while it is a cool idea I feel like it wouldn't really be that functional.
So now instead of building a polar printer I'm thinking of making a Cartesian style printer with a build volume of at least 300x300x300mm. This idea seems more functional and feels like something I would actually use on a daily basis. I currently own a Bambu A1 mini so having a bigger build volume is really something I want.

##### March 9th-10th
I spent majority of my time on picking out the parts i wanted. It was really hard to get stuff under the budget. After a lot of considerations I decided to get rid of the heatbed 
as I'll only be printing in PLA, which saved me about $60CAD. Getting rid of the heatbed helped me stay under the buget and gave me a little extra wiggle room for adding more parts.

I also decided to rethink about how many gantry was gonna be. My original idea was something like an H-Bot design but after some thinking I decided to scrap that idea because then the toolhead would be heavy and since im moving on smooth rods this might cause some issue, I did some more research and came across the cross-styled gantry but again it had the same problem of having a overall heavy toolhead. After a lot of consideration and research I decided to go with a corexy design, this would make the belt system a lot more complex but allow for a lighter and balanced printhead.

Over the past 3 days I've worked on my parts list and BOM and I've almost finished my BOM (just have a few misc parts and wires left)
[BOM](https://docs.google.com/spreadsheets/d/10UROUA1rVFZyfdf39kwov9C5ffhGzZl1vPd_-cW53OE/edit?usp=sharing)


### Time Spent:  8 hours

