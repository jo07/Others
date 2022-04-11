<h2 style="font-weight: normal">Create new git remote</h1>
You know how to create the token, once you have done that, execute the following

    git remote remove origin                                           # To remove preexisting remote named origin
    git remote add origin https://[TOKEN]@github.com/[USER]/[REPO]     # Use the token, your username and the repo the remote is                                                                          # being created for
    git push origin main                                               # if you want to push to main branch
    
    
<h2 style="font-weight: normal">Create a .gitignore file</h1>
You go to the folder and open the terminal there. Then you type

    touch .gitignore
That's a tada



<h2 style="font-weight: normal">Write to .gitignore file</h1>
We echo the commands. Make sure your terminal is currently at the folder where .gitignore file is 

    echo ".ipynb_checkpoints" >> .gitignore
    
That's another tada!!!

<h2 style="font-weight: normal">Undoing Your Last Commit (That Has Not Been Pushed)</h1>
You reset it.
    git reset --soft HEAD~

Now go make another mistake to try reset again.



<h2 style="font-weight: normal">Reverting it back</h1>
You reset it.
    git revert head

I don't dissapoint when it comes to mistakes