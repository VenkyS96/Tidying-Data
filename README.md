##Tools used to produce this project
- This project is built by `knirt` package instllled on RStudio with RMD (R Markdown) format.

- The  `run_analysis.md` and `codebook.md` files will be  automatically  produced by `run_analysis.Rmd` 

##Steps to produce this project

- Plsease see the details in `run_analysis.md` and `codebook.md`.

- Those files  contain the instructions and steps with R code embedded  to produce this project.

- The final tidy data is in `tidydata.txt`. It can be loaded by `Data<-read.table("tidydata.txt", sep=" ", head=TRUE)`

- The codebok is in `codebook.md` . It gives the descriptions of the variables in the data frame prouduced by this project.

##Steps to reproduce this project

-  Open Rstudio to open R  Markdown file  `run_analysis.Rmd` to build the Project , then `run_analysis.md` , `codebook.md` and 
  `tidydata.txt` will be produced.
  
-  Alterativley the R script `run_analysis.r` can be used  to build the Project, but it only produces the final tidy dataset in `tidydata.txt`

 
