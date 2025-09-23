[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 2

## Topics covered
*What topics were covered in this session*

* Finished the history of computers
* Setting up git for windows
* What a personal access token is and how to use it
* What SSH Keys are and how to use them(?)

## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

* To access the git folder I have locally through git would be "cd C:\Gitrepos"
* To check which folder I'm in, I input "pwd" and then it just displays it
* To access the Computing foundation folder through git would be " cd COM304_Foundation_1/"
* Small tip: You can autocomplete the destination if the path name is unique enough by pressing TAB (thanks craig)
* To update igni (I'll just call them igni (my laptop) and pheas (the web version) from now on) with changes I made on pheas, I ave to make sure that I'm in the right folder, and then input "git pull", which will pull all changes i made on pheas into igni.
* I can use "git status" to check whether igni is up to date with pheas
* When I make changes on igni, and want to push it to pheas, I need to "git add --all" to add all the changes together, then I "git commit -m" to do something (?) which will then ask for my identity if this is the first time I'm doing this from my device. Once the commit is ready, I then "git push", which requires my personal access token, and if all goes well, the changes I made on igni will get put on pheas
* How to make a personal acces token: Settings, Developer Settings, Personal access tokens (from there just follow the steps. I already made one and I don't remember the other steps after)
* A personal access token is essentially just a very long password that you use every time you "push"

__Research__
CD
* "cd" is used to refer to "Change Directory", so whenever I say "cd C:\Gitrepos", I'm telling git to change my directory to "Gitrepos" in my C drive
Apparently, there's varyations to this command, such as 
* "cd .." to go up one directory level
* "cd ~" to go to the home directory
* "cd /" to go to the root directory
* "cd" by itself also goes back to the home directory



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*



## Summary of learning
*What did you learn through these exercises*
