---
date: "2016-11-05T19:41:01+05:30"
draft: false
image: img/portfolio/bank/bank_port_profile.PNG
showonlyimage: false
title: Liquidation Nation
weight: 1
---

An updated report on Chapter 7 Bankruptcy in the US from 2001-2018
<!--more-->

## Background on the Project 

In law school I completed a course called "Debtor Creditor Law" which focused a great deal on the  bankruptcy system in the United States. 

While conducting research for an assignment in this class, I came across a wealth of bankruptcy data on the Department of Justice's website. In addition to the data, there was also a report published in 2001 by the DOJ that provided a summary of bankruptcy in the US from 1994 - 2000. 

[Click here to see the original report.](https://www.justice.gov/ust/eo/private_trustee/library/chapter07/docs/assetcases/Publicat.pdf)

The DOJ has not published a similar report since 2001, but the Department has bankruptcy data from 2000 to the present readily available on their website.

Here are the goals I had for this project:

1. Use R programming to create a new report that contained the same charts as the original report but used data from 2001-2018 rather than 1994-2000.
2. Learn the basics of RMarkdown so that I could publish the report. 
3. Update some of the charts to display the data in a way that made it easier for the reader to understand. 
4. Create interactive and dynamic versions of charts to make the report more engaging for the viewer. 

While I was able to recreate many of the charts and statistics found in the original report, there was some data that was necessary to make certain charts that I was unable to find and therefore, some charts from the original report are missing from my recreated version. 

> DISCLAIMER: The report I've created is in no way associated with the Department of Justice. 

## Getting Started 

### Retrieving and Cleaning the Data 

The first task in making this report was assembling all of the bankruptcy data into a single data frame. This turned out to be a much larger challenge than I initially anticipated. The DOJ has published data on Chapter 7 bankruptcy annually since 2001. A screenshot of the page is shown below, and the actual site  can be accessed by clicking this [LINK](https://www.justice.gov/ust/bankruptcy-data-statistics/chapter-7-trustee-final-reports). 

<img src="/portfolio/Bankruptcy_files/bankruptcy_data_site.PNG" alt="DOJ CH7 Data page" width="600px" height="600px"/>

Over the nearly two decades that this data has been published, not only has the layout and naming conventions of these data tables changed, the file formats have changed as well. An RMarkdown file laying out all the steps I took to retreive and reformat the data can be found on my github account. 

### Recreating the Charts and Graphics 

After collecting and cleaning the data, I began working my way through the report. Page by page, I recalculated all of the statistics and recreated the charts.The original report is nearly 50 pages and has over 20 charts, so to avoid making this post unbearably long I decided to include only a portion of the pages in this post. Check out my github to see the full list of RMarkdown files containing the updated pages of the report as well as the code I used to generate them. 

