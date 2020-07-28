---
title: 3D Printing a Tiki Torch Top
author: Kolton Bodnovich
date: '2020-07-27'
slug: 3d-printing-a-tiki-torch-top
categories: []
tags: []
image: img/portfolio/tiki_top/tiki_cover.jpg
showonlyimage: no
---

Designing and printing a replacement lid for my brother's tiki torches using my iPad and Ender 3 Pro.

<!--more-->

Earlier this month my brother, Karson, asked if I could use my new 3D printer to make a few tiki-torch lids because some of his were blown away during a storm. It seemed like a simple print to design - just an open ended cylinder - so I agreed to try making some *tiki-tops* for him. Karson came to visit from Chicago shortly after making his request, and he brought a tiki-torch canister/tiki-top so that I could get accurate dimensions for my design. 

![tiki canister with original lid](/portfolio/3d-printing-a-tiki-torch-top_files/tiki_og.jpg)

>  I used **Shapr3D** to create the designs for the tiki-tops. Shapr3D is a 3D CAD app for iPad and Apple Pencil. 

<img src="/portfolio/3d-printing-a-tiki-torch-top_files/shapr3d_logo.jpg" alt="Shapr3D logo" width="50%" height="50%"/>

I went through multiple designs before I had something that actually worked, then I played around a bit and designed a few that were more *aesthetically pleasing*. 

![TikiTop practice prints ](/portfolio/3d-printing-a-tiki-torch-top_files/tiki_0thru8_sm.jpg)

Karson took two tiki-tops with him when he returned to Chicago. A week later he asked if I could print tops for the rest of his tiki-torches, even the ones that still had their original tops. 

![](/portfolio/3d-printing-a-tiki-torch-top_files/bluetikis_all_ordered.jpg)
![](/portfolio/3d-printing-a-tiki-torch-top_files/bluetiki.gif)

### Major Factors to Consider 

The most important elements of this design were getting the **inner diameter** of the lid just right, and including something that you could **attach a string** to. 

Another factor to consider was the time it took to actually print the piece - a **shorter print time** is preferable over a longer one. There are *literally* hundreds of settings you can tweak for a 3D print, and many of them have an effect on print time. The two things I focused on were (1) increasing the speed of my printer nozzle and (2) reducing the amount of plastic needed for the print. You can reduce plastic by tinkering with wall thickness, infill percentage [^infill], support pieces [^support], and the overall height of the object.  

### Tiki-Tops 1 through 4

![TikiTops 0-4](/portfolio/3d-printing-a-tiki-torch-top_files/tiki_0_thru_4.jpg)

Tiki-Tops 1-4 were mainly attempts to find the correct diameter of the inside of lids so that it fit snuggly over the wick-holder. The tops needed to be snug around the base because that made it harder for them to get blown off.

##### Tiki 1

The design for *Tiki 1* was 43 mm tall: the same height as the original tiki-top. The outer diameter was 40 mm, and the inner diameter was 34 mm, which means the walls were 3 mm thick all the way around.

*Tiki 1* was too wide, but only by a couple milimeters. It also didn't have anything where you could attach a string. 

##### Tiki 2

To get the design for *Tiki 2*, I went back to the drawing board (my iPad) and drew another cap from scratch. I started by making the *outer diameter* 34 milimeters because I knew that Tiki 1's *inner diameter* was 34 milimeters, which was too big for the inside, but it might be a good size for the outside. 

The inner diameter was 30.8 mm, which made the walls 1.6 mm thick. I chose this thickness based on the size of the nozzle on my 3D printer. The nozzle is 0.4 mm wide, meaning that each little line of plastic it lays down is 0.4 mm. To print something 1.6 mm thick the nozzle would have to lay down 4 lines: 2 for the *inside shell*, and 2 for the *outside* (and no room for infill). I also reduced the overall height by 5 mm to cut some print time. 

while *Tiki 2's* walls were a nice thickness, there was a big seam up the side that I had to trim away. Worst of all, the piece was too narrow and didn't fit over the wick-base. 

##### Tiki 3

*Tiki 3* was mostly an experiment to see how thin I could make the walls (because less plastic = less print time). I made the walls 1mm thick all around by setting the outder diameter at 30 mm, and the inner at 28 mm. I knew that this would be too small for the tiki torch; I just wanted to do a small *quick* print to see what would happen. 

*Tiki 3* took somewhere around 15 minutes to print, which is an *absurdly* short print time in the 3D printing world. It had seams all around the outside, and considerable stringing on the inside. This was by far the worst print of the series, but it showed me how the shell and infill can interact when you try to print that thin using an average size (.4 mm) nozzle. 

##### Tiki 4



[^infill]: This refers to how *dense* the print will be. An infill of 0% will make an object that is hollow on the inside, while an infill of 100% will be solid. There is usually no reason to print with 100% infill because it requires considerably more plastic and time without improving the quality of the print. A common infill percentage in the 3DP community is 20%. 
[^supports]: Slicing software can add support structures to help with prints that have obscure shapes/angles or need help adhering to the print bed. Including supports in your print may increase quality, but it also increases plastic. 
[^slicing software]: I used Creality3D's slicing software for this project, but I have recently converted to using Ultimaker's *Cura* for all my slicing needs. 
