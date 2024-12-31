# TITLE 

***

**Citation:** We are in the process of writing a manuscript and will include a citation here when it is available. 

## 1. Overview


## 2. Requirements
We used the following software, R packages, and data to complete our analysis.

### 2.1 Software and R Packages
1. Download the following software: 
- [R](https://cran.r-project.org/bin/windows/base/)
- [RStudio](https://www.rstudio.com/products/rstudio/download/#download) or another R graphical user interface
2. Run the following code in R to install the following packages:
- These required packages are needed to run our code. 
	```installation	
	install.packages(c(''rio','tidyverse','janitor','broom'), dependencies = TRUE)
	```
3. We used the following versions of software and packages:
- **Software**:
	- *R:* _____ ("_____")
	- *RStudio:* _____ ("_____")
- **Packages**:
	- *`rio`*: _____
	- *`tidyverse`*: _____ 
	- *`janitor`*: _____
	- *`broom`*: _____ 

### 2.2 Data
We used the following data: 
- _____
- _____

Our final analytical dataset `_____.RDS` can be found in [`data/processed`](_____).

- We have included a data dictionary `_____-DD.xlsx` in the same folder.

## 3. Code and Instructions
We used the following code to complete our analysis: 

- `code/clean_data.R`: Merge, clean, and prepare analytical dataset.
- `code/fit_models.R`: Complete analyses.
- `code/create_tables_figs.R`: Create tables and figures for our analysis.

## 4. Cloning this Repository with RStudio
Below are steps to clone this repository to your local device with RStudio. Please refer to this [link](https://resources.github.com/github-and-rstudio/) for more information about using git in RStudio.

1. On top this page, click on `Code` and copy the link to this git repository (starts with https://github.com/...).
2. Open RStudio.
3. In RStudio, click on `File` &rarr; `New Project...` &rarr; `Version Control` &rarr; `Git`.
4. Under "Repository URL", paste the link of the git repository.
5. Under "Project directory name", name your project directory.
6. Under "Create project as subdirectory of:", select the folder in which you would like your project directory to be located.
7. Click on `Create Project` when you are done to clone your repository! This should take a minute or two to complete.

## 5. Grant Information
This research was supported by grants from the ______, National Institutes of Health (Grants: #_____).