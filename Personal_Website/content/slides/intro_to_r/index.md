---
authors: []
categories: []
date: "2019-06-05T00:00:00Z"
slides:
  highlight_style: dracula
  theme: black
summary: An introduction to R coding language.
tags: []
title: Intro to R
---

# What is R?  

- Ross Ihaka and Robert Gentleman  
- 2000
- Object-oriented  
- Statistical analyses  
- Data visualization (publication quality figures)
- Free, open source
- Active user community that contributes packages
- Interpreted

---

## RStudio

- Base R
- An integrated development environment (IDE)
- Runs R
---
## Basic Code Syntax

```r
x <- 1
x = 1
function(arg1, arg2, arg3)

# Comments
```
---
## Data Structures

- Numeric  
- Integer  
- Character  
- Factor  
- Vectors  
- Matrix  
- Array  
- Dataframe  
- Tibble  
- List  
---
## Installing Packages

```r
install.packages("package")

#Notice the use of " " when installing but not when calling it
library(package)
require(package)
```
---
## Working directory

```r
getwd()
list.files(pattern = ".csv")
iris <- read.csv("iris.csv")
```
---
## Indexing

```r
vector[1]
dataframe[row, col]
df[ ,col] #all rows
df[row, ] #all columns
list[[]]
list[[]][row, col] #for dataframes in a list
which()
```
---
## Loops

- For loops  
- While loops

```r
for(i in 1:10){
  some function(i)
}

while(i in x){
  some function(i)
}
```
###### _i_ is the iterator, it has no real significance and can be named anything you like. It is recommended to name it based on what you are using it to loop through to make your code easier to follow. 
---
## Logic

- if( )    
- ifelse( )  
- is.___( )  
- == or !=  
- TRUE (T) or FALSE (F)
 
---
## Best Practices for Coding 

- use spaces between arguments  
- use the <- for assignment instead of  = 
- use #comments to annotate your code!




