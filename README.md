# Git_Tutor
This repo will let you be able t use GitHub and git command line very easily. The tutorial is updated on a daily basis and and anyone can contribute be it new commands , real life git issues and solution, shortcuts, tricks etc. 

## Tip 1 Cloning a repository into local device
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
## Tip 5

        git status
    
   Show the current working tree status(that is it dilsplay all those files which in which changes hae occured)

## Tip 6 To update local repo if chnages in remote repo exist(most simple case)
	git pull --rebase origin master

   With the above command we can update the local repo with the changes of the remote branch to local branch

##Tip 7 Know the local email address git is associated with
	git config --global user.email

   



# SOLUTIONS TO VARIOUS ISSUES
 >This section will give the best possible solution from various solutions from the web which I feel solved the problem
	
## Commits not showing up on GitHub contributions graph.
 > Solution: https://medium.com/@soufianerafik/commits-not-showing-up-on-github-contributions-graph-c3b539ad42a1