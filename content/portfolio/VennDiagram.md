---
title: In Search of a New Venn Diagram
author: Kolton Bodnovich
date: '2020-06-02'
slug: new-venn-diagram
categories: []
tags: []
image: img/portfolio/VennDiagram/venn_cov.jpg
showonlyimage: no
weight: 7
draft: true
---

Can you make a Venn Diagram with more than 3 circles? What about a shape other than a circle? 

<!--more-->

The inspiration for this project came from my one of Strategy case studies in business school. Our professor began the case study by using a venn diagram to compare/contrast two subjects involved in the case we were reading. Eventually, a third party entered the mix so our professor drew an additional circle that overlapped with the two circles in the original diagram. Pretty soon a fourth party got involved but my professor said that we had to switch over to a different diagram because it was impossible to make a Venn Diagram using more than 3 circles. 

*********


### Challenging a Venn Diagram's 3-Circle Limit (2D)

At first I didnt believe him, because I could picture 4 overlapping circles in my head and everything seemed to work fine. But when I actually drew the figure I realized that there were some group interactions that weren't present. More specifically, the top left circle and the bottom right circle in the figure below do not have a section where only those shapes share an interection. 

![VennDiagram_4circle](/portfolio/VennDiagram_files/venn_4circle.png)*4 Circle Venn Diagram: 2D*

![Blue and Green Intersection](/portfolio/VennDiagram_files/venn_expl_fail.png)*Shaded: The intersection of Blue and Green*

![Blue Green and Yellow](/portfolio/VennDiagram_files/venn_expl_fail_yellow.png)*Yellow also intersects with Blue and Green in this region*

![Blue Green and Red](/portfolio/VennDiagram_files/venn_expl_fail_red.png)*Red intersects with Blue and Green as well, leaving no space in the model for and intersection of just Blue and Green*

Every intersection between these two groups also includes an intersection with one or both of the remaining two groups. 

*******

I could have stopped after confirming my professor's claim that a 4 circle diagram didn't work, but I was curious to see whether this applied to other shapes as well. Venn diagrams are commonly used when studying probability, and I thought it would be interesting find an alternate model that provided a way to study probability from a different perspective. 

### Exploring alternative shapes. (2D)

In addition to circles, I also gave triangles, rectangles, and squares a try. 

![VennTriangles](/portfolio/VennDiagram_files/venn_triangle_table.jpg)*4 Triangle Venn Diagram*
![Venn_bars](/portfolio/VennDiagram_files/venn_bars_square_star.jpg)*4 Rectangle Venn Diagram: Square and Star Layout*
![VennStarBar](/portfolio/VennDiagram_files/venn_bars_starred.jpg)*Analyzing the Interactions at the Center of the Star Layout* 
![Venn_squares_table](/portfolio/VennDiagram_files/venn_squares_table.jpg)*4 Square Venn Diagram: Random Layout*
![Venn Squares Grid Layout](/portfolio/VennDiagram_files/venn_squares_ordered.jpg)*4 Square Venn Diagram: Ordered Layout*

*********

### Challenging a Venn Diagram's 3-Circle Limit (3D)

My next thought was that maybe if you add another dimension and convert the diagram from 2D into 3D, then the 3-circle limitation would no longer apply. I started with the 2D drawing of a 4 circle venn diagram and created solids for the outermost sections. 

![spin3D GIF](/portfolio/VennDiagram_files/venn_spin3d.gif)*4 Circle Venn Diagram: 3D*

![VennDiagram 4 Circle 3D - Outer Layer](/portfolio/VennDiagram_files/venn_outer_level.png)*Outermost sections: No overlap between colors*

Then I moved one level inward and created objects to represent these intersections. At this level, each region is shared between two of the four original circles. 

![VennDiagram 3D 1st and 2nd levels](/portfolio/VennDiagram_files/venn_3D_levels1_2.png)*1st and 2nd Levels* 

This is what they look like without the outer level. Each of these *shield-shaped* objects has 2 convex faces and 2 concave faces. The convex faces indicate the colors of the circles that are present in that area, while the concave faces indicate the other two colors that are not present in that section. 

![VennDiagram 3D 2nd Layer only](/portfolio/VennDiagram_files/venn_3D_2nd_layer.png)*2nd Level*

I did the same thing for the third level. 

![VennDiagram 3D Levels 1-3](/portfolio/VennDiagram_files/venn_3d_levels_1thru3.png)*1st, 2nd, and 3rd level*

Each of these objects represents the intersection of 3 of the 4 original circles. 

![VennDiagram 3D 3rd Level](/portfolio/VennDiagram_files/venn_3d_3rd_level.png)*Only the 3rd Level*

And finally I created a solid for the middle intersection. 

![VennDiagram 3D All Levels](/portfolio/VennDiagram_files/venn_3d_all_levels.png)

This central region represents the intersection of all 4 regions. 

![VennDiagram 3D Centersection](/portfolio/VennDiagram_files/venn_3d_center.png)*Central Intersection of All Four Regions* 

The 3D version of the Venn Diagram failed for the same reason the 2D version did: it lacked a region where the two circles sitting opposite one another had an intersection without the other two circles also being present. 

### Conclusion

It appears my professor was correct: you can't create a Venn Diagram using more than 3 circles. Additionally, a Venn diagram cannot be created using a shape other than a circle: in both 2D and 3D. 

A potential solution might be to try making a 3D venn diagram using spheres rather than cylinders. This may provide the proper dimensions for all 4 regions to interact and have their intersections represented properly, like a traditional Venn Diagram. 

![](/portfolio/VennDiagram_files/venn_spin3d.gif)


