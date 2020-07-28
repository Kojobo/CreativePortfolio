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

Karson took three tiki-tops with him when he returned to Chicago. A week later he asked if I could print tops for the rest of his tiki-torches, even the ones that still had their original tops. 

![](/portfolio/3d-printing-a-tiki-torch-top_files/bluetikis_all_ordered.jpg)
![](/portfolio/3d-printing-a-tiki-torch-top_files/bluetiki.gif)

### Major Factors to Consider 

The most important elements of this design were getting the **inner diameter** of the lid just right, and including something that you could **attach a string** to. 

Another factor to consider was the time it took to actually print the piece - a **shorter print time** is preferable over a longer one. There are *literally* hundreds of settings you can tweak for a 3D print, and many of them have an effect on print time. The two things I focused on were (1) increasing the speed of my printer nozzle and (2) reducing the amount of plastic needed for the print. You can reduce plastic by tinkering with wall thickness, infill percentage [^infill], support pieces [^support], and the overall height of the object.  

### Tiki-Tops 1 through 4

![TikiTops 0-4](/portfolio/3d-printing-a-tiki-torch-top_files/tiki_0_thru_4.jpg)

Tiki-Tops 1-4 were mainly attempts to find the correct diameter of the inside of lids so that it fit snuggly over the wick-holder. The tops needed to be snug around the base because that made it harder for them to get blown off.

#### Tiki 1
###### Print Time: 97 minutes
###### Plastic: 5.45 meters

The design for *Tiki 1* was 43 mm tall: the same height as the original tiki-top. The outer diameter was 40 mm, and the inner diameter was 34 mm, which means the walls were 3 mm thick all the way around.

*Tiki 1* was too wide, but only by a couple milimeters. It also didn't have anything where you could attach a string. 

#### Tiki 2
###### Print Time: 64 minutes
###### Plastic: 3.51 meters

To get the design for *Tiki 2*, I went back to the drawing board (my iPad) and drew another cap from scratch. I started by making the *outer diameter* 34 milimeters because I knew that Tiki 1's *inner diameter* was 34 milimeters, which was too big for the inside, but it might be a good size for the outside. 

The inner diameter was 30.8 mm, which made the walls 1.6 mm thick. I chose this thickness based on the size of the nozzle on my 3D printer. The nozzle is 0.4 mm wide, meaning that each little line of plastic it lays down is 0.4 mm. To print something 1.6 mm thick the nozzle would have to lay down 4 lines: 2 for the *inside shell*, and 2 for the *outside* (and no room for infill). I also reduced the overall height by 5 mm to cut some print time. 

while *Tiki 2's* walls were a nice thickness, there was a big seam up the side that I had to trim away. Worst of all, the piece was too narrow and didn't fit over the wick-base. 

#### Tiki 3
###### Print Time: 45 minutes 
###### Plastic: 1.95 meters

*Tiki 3* was mostly an experiment to see how thin I could make the walls (because less plastic = less print time). I made the walls 1mm thick all around by setting the outder diameter at 30 mm, and the inner at 28 mm. I knew that this would be too small for the tiki torch; I just wanted to do a small *quick* print to see what would happen. 

*Tiki 3* took somewhere around 45 minutes to print, which is an *absurdly* short print time in the 3D printing world. It had seams all around the outside, and considerable stringing on the inside. This was by far the worst print of the series, but it showed me how the shell and infill can interact when you try to print that thin using an average size (.4 mm) nozzle. 

#### Tiki 4
###### Print Time: 102 minutes
###### Plastic: 5.55 meters

*Tiki 4* was first top to actually fit [^fit]. I finally discovered the *perfect* inner diameter (28.98 mm) that made the cap fit so snuggly I could invert the canister and it wouldn't fall off. It took longer to print than the previous 3 designs, and also used the most plastic. This was mainly due to the 5 mm thick walls and the high infill percentage. 


### Tiki-Tops 5 through 8

Now that I had figured out the correct dimensions to get a proper fit I needed to incorporate something into the design for attaching a string. I realized that the object could have any shape and would still fit properly as long as the inner diameter was set to 28.98 mm.

![tiki5-8](/portfolio/3d-printing-a-tiki-torch-top_files/tiki_5_thru_8.jpg)

#### Tiki 4.5 

This tiki-top features a *divot* or *notch* near the top end which was intended to hold a string in place. This tiki-top never made it to the printer though because I realized that there was no way to create the "ledge" created by the divot without adding supports of some kind. I couldn't find a way to add the necessary supports without disrupting the design - so I scrapped it. 

![](/portfolio/3d-printing-a-tiki-torch-top_files/tiki_4.5.PNG)

#### Tiki 5
###### Print Time: 87 minutes
###### Plastic: 4.87 meters

*Tiki 5's* design was made using the Loft feature in Shapr3D. It has an hourglass shape so that a string can be tied around the top without sliding off. 

#### Tiki 6
###### Print Time: 93 minutes
###### Plastic: 5.24 meters 

After using the Loft tool in Shapr3D to create *Tiki 5*, I wanted to play around with it a bit more, which is how I came up with *Tiki 6*. Instead of using regular circles like in *tiki 5*, I used octagons. Each octagon in the stack was raised 10 mm, then rotated by 10 degrees: this created the neat spiral effect. *Tiki 6* was definitely my favorite design in the series, but it lacked any sort of mechanism to attach a string. 

I used a modified version of this design to make the full set of tiki-tops Karson requested later on. The design is essentially the same - the only difference is that I added a small loop at the top for the string. 

![BlueTiki](/portfolio/3d-printing-a-tiki-torch-top_files/bluetikis.jpg)

### Tiki 7 
###### Print Time: 70 minutes
###### Plastic: 3.23 meters

*Tiki 7* is basically a hybrid of *Tiki 5* and *Tiki 6*: it has the same coke-bottle shape as *Tiki 5* and the octagonal spiral pattern from *Tiki 6*. The very top edge is slightly beveled to remove the sharp edge like in *tiki 5*. This print was surprisingly strong considering that it was one of the quickest prints and required the least amount of plastic. Although *Tiki 7* met all the necessary criteria, it looked a little weird - almost like melted ice cream. 

### Tiki 8
###### Print Time: 137 minutes
###### Plastic: 7.32 meters

*Tiki 8* was initially an attempt at designing a top that looked like an actual Tiki head. After multiple unsuccessful tries I scrapped the tiki head idea and used whatever I had to come up with this *art-deco* look. The nice features about *tiki-8* were that it was very heavy and had a solid loop for holding a string. Karson really liked this loop feature and requested that I include it in the design when I printed the full set of tiki-tops. I essentially took this loop element and merged it with the design for *tiki 6* to come up with the final design.

![ArtdecoTiki](/portfolio/3d-printing-a-tiki-torch-top_files/tiki8_front.jpg)
![ArtDecoTiki2](/portfolio/3d-printing-a-tiki-torch-top_files/tiki8_side.jpg)

### The Final Tiki Top Design 
#### Printing a Matching Set

As previously mentioned, my brother Karson really liked the tiki-tops I made for him using my 3D printer - he liked them so much that he asked if I could print enough for all of the tiki-torches on his balcony. The other reason why he wanted to replace all the original caps was because they were made of some sort of thin, porous wood (possibly Balsa) and they would absorb the tiki fluid. aside from making the tops look wet and unsightly, this was somewhat of a fire hazard.

He initially requested that I print 10 tops using the design for *tiki 8*, but this was only because he liked the loop hope feature. I didn't want to use *tiki 8* for these tops because (1) I thought that it looked bulky and ugly when I saw it on the tiki torch out on his patio (2) it required a large amount of plastic and had a very long print time. So instead of using one of the previous designs I merged our favorite parts from all of them into one. 

![](/portfolio/3d-printing-a-tiki-torch-top_files/tiki10.gif)
![](/portfolio/3d-printing-a-tiki-torch-top_files/bluetikis_all_ordered.jpg)
![](/portfolio/3d-printing-a-tiki-torch-top_files/bluetikis_all.jpg)

> Sidenote: I purchased a new color of plastic filament after Karson went back to Chicago - that's why these caps are all blue and the initial series of caps are all gray.

Before I created the final design, I tried to create a loop that meshed well with the spiral pattern. The loop I came up with was too small and too thin (3mm) which meant that it was likely to break during use. The edge of the loop was also very pointy, and I preferred something smoother. 

![](/portfolio/3d-printing-a-tiki-torch-top_files/bluetiki_wronghole.jpg)

All-in-all the final tiki-top design took a little over an hour (70 min) to print, and required 5.86 meters of plastic. The design itself took less than five minutes to create in Shapr3D. I was able to get the entire set printed over the course of a single day. 




















[^infill]: This refers to how *dense* the print will be. An infill of 0% will make an object that is hollow on the inside, while an infill of 100% will be solid. There is usually no reason to print with 100% infill because it requires considerably more plastic and time without improving the quality of the print. A common infill percentage in the 3DP community is 20%. 
[^support]: Slicing software can add support structures to help with prints that have obscure shapes/angles or need help adhering to the print bed. Including supports in your print may increase quality, but it also increases plastic. 
[^slicing software]: I used Creality3D's slicing software for this project, but I have recently converted to using Ultimaker's *Cura* for all my slicing needs. 
[^fit]: Wooo!
