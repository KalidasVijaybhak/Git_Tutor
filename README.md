# Git_Tutor
This repo will let you be able t use GitHub and git command line very easily. The tutorial is updated on a daily basis and and anyone can contribute be it new commands , real life git issues and solution, shortcuts, tricks etc. 

## Tip 3 Cloning a repository into local device
   git clone https:<area>//github.com/YOUR-USERNAME/YOUR-REPOSITORY 
   
   in the command line type this code inside the folder where you want to create a copy of the repo from github into your local machine
  

## Tip 2 To initialise a folder as a git repository
   inisde the folder type **git init**
   
   this will create a hidden folder containing all the necessaary info for the initialisation of the repository
   
   
## Tip 3 To know the current branch
    git symbolic-ref --short HEAD
     
or
   
    git branch 
     
or

    git branch --list 
     
or

    git rev-parse --abbrev-ref HEAD   // This should work with Git 1.6.3 or newer.

## Tip 4 To commit to a cloned repo(simple case)
   *Step 1:*
   
        git status  //  to check for those file which have been changed
   *Step 2:* 
   
        git add . //to add all those file with changes
   *Step 3:*  
   
        git add filename // to add only a specific file
   *Step 4:*  
   
        git commit -m "message"
   *Step 5:*  
        
        git push origin -u master
