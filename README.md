# BUS 212A Lab 0B

Name: Chieloka Mbaji
Date: September 22nd, 2026

## Purpose
This repository demonstrates that workflows can be reproduced and committed to a different repository in GitHub. It is also used to create a repository that should be easily readable by another analyst. 

## Structure
README.md serves as an explanation of the folder and the command line instructions used to create the repository. 
.gitignore is the file that is used to protect private and sensitive documents. It tells GitHub not to commit certain files to the repository. 
src/ serves as a folder to contain the Python script.
outputs/ is a folder for the text output of the Python script. 

## How To Run
python src/hello_analytics.py > outputs/lab0b_output.txt

## Verified Output
A text output file is created. In the file, I checked that the output matched the code that was typed into the Python script. 

## Privacy And .gitignore
The .gitignore file filters tracking. It does not remove what has already been committed. It cannot decide whether something has been lawfully committed or not. 
Information that shouldn't be publicly committed includes sensitive datasets and passwords. 

## Version Note
git commit -m "Add reproducible Lab 0B workflow"
The commit records the message above, as well as the files in the Lab 0B folder. 


## AI Use Note
AI was used in order to check the syntax for creating a .gitignore file. 