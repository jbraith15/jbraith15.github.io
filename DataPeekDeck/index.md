---
title: "Data Peek"
author: "Joan Braithwaite"
highlighter: highlight.js
output: pdf_document
job: Data Scientist
knit: slidify::knit2slides
mode: selfcontained
hitheme: default
subtitle: Application Overview
framework: io2012
widgets:
- mathjax
- quiz
- bootstrap
--- 

## Data Peek Application:

 <img width=400px height=600px src="../01/assets/img/PG2.PNG"></img> 
  
### Key Controls:

 * File selector: select and upload a csv file
 * Slider: select the number of rows to display in the table.
 * Output: application shows some rows of data along with a summary.

--- 

## Data Peek Operation:

### User Input:
* Select a csv file from file system.

### Application Output:

* Table with 10 rows of Data (default).
* Summary details of the File contents.

### Reactivity:

* User can change the number of rows to display using the 
  slider and submit.
  

--- 
## Data Peek Application showing user selection:  

  <img width=500px height=600px src="../01/assets/img/PG3.PNG"></img> 

--- 


## Example of running code in Slidify Presentation:


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```


