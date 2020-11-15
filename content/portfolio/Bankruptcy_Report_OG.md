---
date: "2016-11-05T19:41:01+05:30"
draft: false  
image: img/portfolio/bank/bank_choro_2.png
showonlyimage: false
title: Liquidation Nation
weight: 4
---

Using R Programming to analyze more than 1 million bankruptcy cases from 2001-2019  


<!--more-->

![](/portfolio/Bankruptcy_Report_OG_files/bank_choro_2.png)

_____

**CHALLENGE**

**OUTCOME**
_____


### BACKGROUND

I came up with the idea for this project after finding a report made by the Department of Justice (DOJ) that covered every bankruptcy case that had closed between 1994 and 2000. The report, published in 2001, had all sorts of statistics and charts summarizing various aspects of these cases. While the report was informative, it only included cases up to the year 2000; a report on bankruptcy cases closed in the 21st century  report of this nature was never published again, the DOJ The DOJ annually published bankruptcy datasets, but   published the data No similar report was ever published However, the DOJ   and of   of bankruptcy datasets on the Department of Justice's website as well as a report from 2001 that summarized bankruptcy activity between 1994 and 2000. The dataset    as well as a number of  that had closed since 2001. Essentially, the dataset included every asset case that had closed during the 21st century, totalling just under 1 million cases. 

In addition to the data, I also found a report that provided a summary of bankruptcy from 1994 - 2000.

[The original report](https://www.justice.gov/ust/eo/private_trustee/library/chapter07/docs/assetcases/Publicat.pdf), published by the DOJ in 2001, had dozens of charts, some of which are shown below. 

<img src="/portfolio/1w_bankruptcy_files/og_report_grid.PNG" alt="Charts from the original 2001 report" width="600px" height="600px"/>


The DOJ has not published a similar report since 2001, and I wanted to see if I could use the data I found and my skills in R programming to recreate the report. 

Here are the goals I had for this project:

1. Use R programming to create a new report that contained the same charts as the original report but used data from 2001-2018 rather than 1994-2000.
2. Learn the basics of RMarkdown so that I could publish the report. 
3. Update some of the charts to display the data in a way that made it easier for the reader to understand. 
4. Create interactive and dynamic versions of charts to make the report more engaging for the viewer. 

To avoid making this post unbearably long I decided to include only a portion of the new report in this post. Check out my github to see the full list of RMarkdown files containing the updated pages of the report as well as the code I used to generate them. While I was able to recreate much of the report, there was some data that was necessary to make certain charts that I was unable to find and therefore, some charts from the original report are not in my recreated version. 

> DISCLAIMER: The report I've created is in no way associated with the Department of Justice.

<img src="/portfolio/1w_bankruptcy_files/B1_old_vs_new.PNG" alt="FIG_B1_old_vs_new" width="600px" height="300px"/>

<img src="/portfolio/1w_bankruptcy_files/A3_old_vs_new.PNG" alt="FIG_A3_old_vs_new" width="600px" height="300px"/>

<img src="/portfolio/1w_bankruptcy_files/B4_old_vs_new.PNG" alt="FIG_B4_old_vs_new" width="600px" height="300px"/>

[Click here to my version of the updated report](https://rpubs.com/Kojobo/bankruptcy)

[Click here to see upgraded interactive charts](https://rpubs.com/Kojobo/567371)

## Getting Started 

### Retrieving and Cleaning the Data 

The first task in making this report was assembling all of the bankruptcy data into a single data frame. This turned out to be a much larger challenge than I initially anticipated. The DOJ has published data on Chapter 7 bankruptcy annually since 2001. A screenshot of the page is shown below, and the actual site  can be accessed by clicking this [LINK](https://www.justice.gov/ust/bankruptcy-data-statistics/chapter-7-trustee-final-reports). 

<img src="/portfolio/Bankruptcy_files/bankruptcy_data_site.PNG" alt="DOJ CH7 Data page" width="600px" height="600px"/>

Over the nearly two decades that this data has been published, not only have the layout and naming conventions of these data tables changed, the file formats have changed as well. An RMarkdown file laying out all the steps I took to retreive and reformat the data can be found on my github account. 



