# Session-3.1-assignment-rahul-sharma
Acagild Session-3.1

1. How to import SAS XPORT files into R with the foreign package?

Ans 1 -> 

library(foreign)

mydata <- read.xport("c:/mydata.xpt")

2. How to import SAS files into R with the Haven package?

Ans 2 ->

library(haven)

read_sas("mtcars.sas7bdat")

3. How to read Weka Attribute-Relation File Format (ARFF) files in R?

Ans 3 ->

read.arff(file)

4. How to read a heavy csv/tsv file using readr package?

Ans 4 ->

library(tidyverse)

mydata <- read_tsv("mtcars.txt")

mydata <- read_csv("mtcars.csv")
