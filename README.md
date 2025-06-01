This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

The paper the problemset is based on investigates the effect of military aid provided to law enforcement agencies in the US through the 1033 program on crime rates.

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("JonasGrueneberg/RTutorMilitarizationOfUsPolice")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorMilitarizationOfUsPolice)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorMilitarizationOfUsPolice")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorMilitarizationOfUsPolice",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
