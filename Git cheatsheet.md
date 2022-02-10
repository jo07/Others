## Create new git remote

You know how to create the token, once you have done that, execute the following

    git remote remove origin                                           # To remove preexisting remote named origin
    git remote add origin https://[TOKEN]@github.com/[USER]/[REPO]     # Use the token, your username and the repo the remote is                                                                          # being created for
    git push origin main                                               # if you want to push to main branch
    
    
## Create a .gitignore file

You go to the folder and open the terminal there. Then you type

    touch .gitignore
That's a tada


## Write to .gitignore file

We echo the commands. Make sure your terminal is currently at the folder where .gitignore file is 

    echo ".ipynb_checkpoints" >> .gitignore
    
That's another tada!!!