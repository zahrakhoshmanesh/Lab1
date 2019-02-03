## Lab 1

Course name: STAT 585

Team members: Zahra Khoshmanesh,Gani Agadilov,Oscar Aguilar

In this repository , we worked as a team on Lab 1 questions which are as follows:

#Building a book
The goal of this part of the lab is to build the html version of the 2nd edition for Hadley Wickham's book Advanced R Programming from a github repository.

Steps:

Clone the repository https://github.com/hadley/adv-r.
Open the R project in the repository in RStudio.
Navigate to the file index.Rmd and knit it.
The book will be available in html format as index.html
Deliverable (1): what is the last word in chapter 15? - You don't have to answer this question, if things don't work, but please answer the next one and see the next page.

Deliverable (2): Write a paragraph on the biggest problem you encountered when you were building the book, and how you managed to solve it.

#US weather stations
The National Climate Data Center at NOAA publishes information on temperature and precipation across a network of stations in the US.

The Data can be accessed through ftp at ftp://ftp.ncdc.noaa.gov/pub/data/ushcn/v2.5, a code book with a description of the data structure is available at ftp://ftp.ncdc.noaa.gov/pub/data/ushcn/v2.5/readme.txt

Download a copy of the file ushcn-v2.5-stations.txt.

Make yourself familar with the command read_fwf from package readr.

Use the codebook description for the stations file, extract all columns and bring them into the intended format (i.e. numbers are numbers)

Create a plot with ggplot2 to show latitude, longitude and elevation. Can you also include state information and time zone?

Deliverable: include the code necessary to read the file and to create the plot in README.Rmd. Assume the data is in the same folder as the README.Rmd file.




