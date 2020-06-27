---
date: "2016-11-05T20:22:08+05:30"
draft: false
image: img/portfolio/AF/sixsigma.png
showonlyimage: false
title: Six Sigma with Abercrombie & Fitch 
weight: 2
---

A six sigma project I completed to earn my Green belt. 

<!--more-->

Six Sigma is a business philosophy and improvement methodology that uses performance metrics to achieve systematic continuous improvement. It utilizes data and statistical tools to align organizational strategic goals with the needs of the customer to achieve the highest level of customer satisfaction. 

In Spring 2019 I collaborated with a team of fellow MBA students and Abercrombie & Fitch associates to complete a six sigma project and earn my green belt. The main focus of the project was to improve the accuracy of machine measurements during the intake process, which would ultimately reduce the occurrence of machine errors in outbound packaging process. Improving machine performance reduced the need for human intervention and enabled employees to focus on value added activities.

The first task for our team was to observe the entire process for receiving, sorting, packaging, and shipping SKUs out to A&F Branches across the country. After observing each of these steps, we created a work flow diagram to document each phase in the process. 

![AF_workflow][3]

[Click this link to see a description of each phase of the process](https://rpubs.com/Kojobo/AFprocessmap)

Here are some examples of the errors my team was tasked with reducing: 

### Overfills (aka Close to Edits)

This type of error would occur when the system incorrectly recorded item volumes to be smaller than they were in reality. For example, an order of 10 sweaters might have been packed tightly into the 100 cubic unit box from the supplier, so each sweater is assigned 10 cubic unit. However, when the sweaters are removed from the box, they expanded considerably to 25 cubic units. When the sorting system drops 6 sweaters into an outbound box, it 'thinks' that 60/100 available units are used, but in reality 150/100 units are used, and the box is overfilled. 

![Close to Edit][1]

When this happens, an employee must come and manually stop the chute and tell the system that the box is full. Then they need to move some of the SKUs into a new box so that they can properly close the original box.

### Underfills

This type of error occurs when the system mistakenly measures an item as being larger than it is in reality. For example, a box of 20 swimsuits comes in a 100 cubic box from the supplier. The system assigns a volume of 5 units to each swimsuit, but in reality each swimsuit is 3 units. When the sorting system drops 20 suits into an outbound box, it will trigger the chute to close because it 'thinks' that the box is full. In reality, only 60/100 available units have been used, so there are 40 units of space still available in the current box. 

![Underfilled Box][2]

When this happens, an employee must come and push a button on the chute to let the system know that it can still drop another item into the box. The employee may have to push this button several times before the box is actually full. 

Here is a graphic I created to better portray the idea of an underfill. 

<img src="/portfolio/2w_AF_sixsig_files/dead_space_exampleScenario.png" alt="deadspace_underfill" width="600px" height="450px"/>

### Other Graphics 

Here is a chart I made to show the breakdown of the volume in incoming boxes. The green bars indicate the actual volume of the SKUs in the box, while the gray and tan boxes indicate the portion of the box that is air and cardboard, respectively. These values were found by taking a sample of incoming boxes and measuring the contents of each box. 

<img src="/portfolio/2w_AF_sixsig_files/Dead_space_graphic.png" alt="deadspace_graphic " width="600px" height="450ps"/>

This chart shows provides an analysis of the chutes and CTEs throughout the year. The spikes indicate when the most errors occur in the process. 

<img src="/portfolio/2w_AF_sixsig_files/chute_analysis.jpg" alt="chute_analysis" width="600px" height="450px"/>

I also created an interactive and scalable application for the A&F team. Unfortunately I am not able to post this application because it contained confidential information. 

[1]: /img/portfolio/AF/AF_CTE.jpg
[2]: /img/portfolio/AF/AF_underfill.jpg
[3]: /img/portfolio/AF/AF_WorkFlow.PNG
