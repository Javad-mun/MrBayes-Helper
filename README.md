# MrBayes-Helper
Assists to extract useful information from MrBayes output files  
  
In this repository I prepared an R code which get a *pstat* file and returns two files.

- A log file in CSV format which contains NT for each position. It can detect positions which have more than one posibble NT and mark them. Aslo, it returns the probabilities of such positions so the user can investigate them.

- A text file which has the results based on the log file.


Try it here:  
https://seyedjavad.shinyapps.io/MrBayes-Helper/
