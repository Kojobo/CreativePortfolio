---
date: "2016-11-05T20:22:08+05:30"
draft: false
image: img/portfolio/AF/sixsigma.png
showonlyimage: false
title: Earning my Six Sigma Green Belt with Abercrombie & Fitch  
weight: 5
---

An overview of the six sigma project I completed to earn my Green Belt. 

<!--more-->

In Spring 2019 I was on a team that collaborated with Abercrombie & Fitch to complete a six sigma project[^six] and earn my green belt. The project's primary goal was to reduce the time employees spent correcting machine errors during the outbound packaging process in the main distribution center (DC1). Reducing this need for human intervention would enable employees to dedicate more time on value added activities.

Our four-person team consisted of three fellow MBA students and myself. We made weekly visits throughout the semester to DC1, the company's largest and busiest distribution center. Every item sold by any A&F store in the United States passed through DC1.

### Defining the Process 

After meeting with A&F's associates to define the project's scope, our team's first task was to determine the path a typical SKU took through DC1. After taking a guided tour of the facility, we determined the process had five steps. I used my iPad to create a work flow diagram illustrating each of the five steps. 

![AF_workflow][3]

1. Boxes from suppliers are loaded onto conveyor belts.
2. Scanner takes box dimensions and assigns volume to items in the box.
3. Items are removed from their box, and loaded onto conveyor belt.
4. Items drop from conveyor belt into chutes. 
5. Boxes are sealed and transferred to outbound shipping dock.

[Click this link to see a description of each phase of the process](https://rpubs.com/Kojobo/AFprocessmap)

### Understanding the Problem: Overfills and Underfills 

The problem we aimed to fix occurred during step 4 of the process. At the bottom of each chute is an empty box: the volume of the box is hard-coded into the software used by the sorting system. When an item is dropped from the belt into the box, the software deducts that item's volume from the box's initial volume. More items drop into the box until the system determine that the box was full. The system then disables that particular chute to prevent anymore items from dropping into the box until an employee comes to replace the full box with an empty one. 

For this system to operate properly, it needs to have precise volume measurements for each of the items being dropped into the box. When the system has *incorrect* measurements, its calculations are also incorrect, and the chutes will be disabled at the wrong time.  

Here are some examples of the errors my team was tasked with reducing: 

#### Overfills (aka Close to Edits)

Overfills occur when an item's reported volume is *smaller* than its actual volume.

For example, a sweater is assigned a volume of 10 cubic units when in reality, its 25 cubic units. When the sorting system drops 6 sweaters into an outbound box, it calculates that 60 units (6 x 10) of space are used, but in reality, 150 units (6 x 25)are used. If the box has an initial volume of 100 cubic units, the box has already been overfilled by 50 units, but the chute remains open because the system believes that it has 40 units of space left to add more items.  

![Close to Edit][1]

When this happens, an employee must come disable the chute by telling the system the box is full. Then they transfer some items into a new box so that they can properly close the original box. Every item transferred from the original box into a new box must be scanned so the system can account for their volumes. This was referred to as a '*Close to Edit*' (CTE) because the chute needed to be closed, and the contents of the box needed to be edited. Depending on the number of items that need to be transferred, correcting an overfill can require a considerable amount of time. 

We were able to quantify the impact of overfills because the system collected data on every CTE. This made it possible to detect items that were likely to cause overfills, and determine seasonal trends.   

### Underfills

Underfills occur when the system mistakenly measures an item as being larger than it is in reality.

For example, the system assigns a volume of 5 units to a swimsuit, but in reality, each swimsuit is 3 units. When the sorting system drops 20 suits into an outbound box, it will disable the chute because its calculations indicate that 100 units (20 x 5) are in the box. In reality, the box has only 60 units (3 x 20), and 40 units of space are still available.

![Underfilled Box][2]

Underfills are handled differently than overfills. Each chute has a button that, when pressed, lets the system know that the box isn't full yet. The chute reopens, but is disabled again after a *single* item is dropped into the box. If the box still is not full, the button can be pushed again, allowing for another item to be added. In some cases, the button is pushed several times before the box is actually full. 

I created this graphic to illustrate the idea of an underfill. 

<img src="/portfolio/2w_AF_sixsig_files/dead_space_exampleScenario.png" alt="deadspace_underfill" width="600px" height="450px"/>

The impact of underfills was almost impossible to quantify because the system didn't keep track of when a button was pressed on any of the chutes. After surveying employees we gained some insight on which items typically caused underfills as well as the season underfills occurred more frequently. This information was useful, but it did not provide us with any method for gauging the impact of our efforts to improve the process.  

### Other Graphics 

Here is a chart I made to show the breakdown of the volume in incoming boxes. The green bars indicate the actual volume of the SKUs in the box, while the gray and tan boxes indicate the portion of the box that is air and cardboard, respectively. These values were found by taking a sample of incoming boxes and measuring the contents of each box. 

<img src="/portfolio/2w_AF_sixsig_files/Dead_space_graphic.png" alt="deadspace_graphic " width="600px" height="450ps"/>

This chart shows provides an analysis of the chutes and CTEs throughout the year. The spikes indicate when the most errors occur in the process. 

<img src="/portfolio/2w_AF_sixsig_files/chute_analysis.jpg" alt="chute_analysis" width="600px" height="450px"/>

I also created an interactive and scalable application for the A&F team. Unfortunately I am not able to post this application because it contained confidential information. 

[^six]: Six Sigma is a business improvement methodology that uses performance metrics to achieve systematic continuous improvement. It utilizes statistical tools to align an organization's strategic goals with the needs of the customer to achieve the highest level of customer satisfaction.

[1]: /img/portfolio/AF/AF_CTE.jpg
[2]: /img/portfolio/AF/AF_underfill.jpg
[3]: /img/portfolio/AF/AF_WorkFlow.PNG
