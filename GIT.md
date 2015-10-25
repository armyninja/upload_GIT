#How to upload to GIT
##First create the GIT on github by logging in to github at https://github.com/armyninja
## Next create the repository by clicking the "+" sign and following instructions.
## For this example, I am creating "gettingAndCleaningDataProject"

## Finally open Git on your computer "GIT Bash" and type in the below

## Move to the proper working directory for this example it is ~/Documents/R/GettingAndCleaningData_Project/Project (master)

## to see working directory use PWD, use CD to change directory, use cd.. to go back one level


$ PWD
#/c/Users/Dad/Documents/R/GettingAndCleaningData_Project/Project


$ git init

$ git remote add origin https://github.com/armyninja/gettingAndCleaningDataProject.git


$ ls
#Project.Rproj  UCI HAR Dataset  getdata_dataset.zip  tidy.txt


$ ls
# CodeBook.md    README.md        getdata_dataset.zip  tidy.txt
# Project.Rproj  UCI HAR Dataset  run_analysis.R

$ git add -A

$ git commit -m "Uploading Getting and cleaning data"

$ git config --global push.default matching

$ git push -u origin master
##Username for 'https://github.com': armyninja
##Password for 'https://armyninja@github.com':
