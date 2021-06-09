  # Demo

In order to learn how to upload Programs to Github, I used this video:
https://www.youtube.com/watch?v=RGOj5yH7evk
During the video some commands where different between Mac/Linux & Windows, so here you can find the equivalent commands for 
terminal in Windows. 
Also, if you want to use the commands like in the video, then its better if you use `Gitbash` which should be already installed in your desktop, just type the windows icon and search it.


## Commands I've used in Terminal

`git ls-files`(Windows) `git la -la` (Linux/Mac)

to show the documents inside the File.


`cls` (Windows) `clear` (Linux/Mac)

to clear / clean the Terminal

## Git commands

By order of use, first I have `status`, in order to see wich files have been modified and if the modifications have been uploaded.

`git status`
to check the status of the files if are modified or not.

In order to upload the modification, we will use `add` and there are two ways of using it:

`git add [name of document]`
to add modifications in a specific file or...

`git add .` 
to add modification in all the documents.

After that we can ``status`` use again and the name of the file now should be green.
Now we are ready to commit, to "save the changes".

`git commit -m "Name for the modification (up to you)" -m "Any comment about it"` here the first `-m "Name"` is obligatory in order to save it, but the order one (the comment) you can skip it.

Then we are ready to upload it in Github, for this we use:

`git push` after this one, we can reaload Github in the Navigator and chanes will appear.

###### important note: if is the first time using ``git`` then is necesary to set a `SSH KEY`
https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent 

Here is the info and is better using ``Git Bash`` for the commands.

`git config --global user.email "you@example.com"` used to set your account in Github and be able to sync.
Also can use `git config --global user.name "github_username"` so use Username instead of email.