# Rock the ladle build
The files found in this repo are auto generated and should not be edited directly. That being said if all else fails "YOLO"    
The source files are found in https://github.com/digitalcake/rocktheladle whitch is a middle man app. 

## Setup source files steps.    
1: fork https://github.com/digitalcake/rocktheladle   
2: Follow steps to run middleman https://middlemanapp.com/    
3: compile changes. The compiled version is saved in the build folder which is also a git submodule whos remote points to this repo. 

*** It should be noted that the github pages are based on the gh-pages branch. 

## Steps to deploy changes to the site. 
1: Git push the branch 'gh-pages' with the contents of the build folder    
  * if step 1: fails and or is too dificult for you to figure out you can clone ("fork") this repo and make edits directly and create pr for that.     
2: Changes will take effect with in a few miniuts after a deploy has been made given the correct branch has been pushed to. 

