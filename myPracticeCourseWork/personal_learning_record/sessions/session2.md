[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 2

## Topics covered

22/09/2025
* Finished the history of computers 
* Setting up git for windows
* What a personal access token is and how to use it
* What SSH Keys are and how to use them(?)

29/09/2025
* Computer components

07/10/2025
* Recap of what was done yesterday: [Binary stuff](https://github.com/Akhabue72/COM304_FOUNDATION_1/blob/main/sessions/session2/docs/binaryArithmetic.md)
* Logic gates

13/10/2025
* Revision pretty much
* I now have a general to do list on my laptop [here](https://github.com/users/Akhabue72/projects/1)


## Personal Notes and research following this session
#### Github
* To access the git folder I have locally through git would be "cd C:\Gitrepos"
* To check which folder I'm in, I input "pwd" and then it just displays it
* To access the Computing foundation folder through git would be " cd COM304_Foundation_1/"
* Small tip: You can autocomplete the destination if the path name is unique enough by pressing TAB (thanks craig)
* To update igni (I'll just call them igni (my laptop) and pheas (the web version) from now on) with changes I made on pheas, I have to make sure that I'm in the right folder, and then input "git pull", which will pull all changes i made on pheas into igni.
* I can use "git status" to check whether igni is up to date with pheas
* When I make changes on igni, and want to push it to pheas, I need to "git add --all" to add all the changes together, then I "git commit -m" to do something (?) which will then ask for my identity if this is the first time I'm doing this from my device. Once the commit is ready, I then "git push", which requires my personal access token, and if all goes well, the changes I made on igni will get put on pheas (I'll look into all the new terms and stuff in a bit)
* How to make a personal acces token: Settings, Developer Settings, Personal access tokens (from there just follow the steps. I already made one and I don't remember the other steps after)
* A personal access token is essentially just a very long password that you use every time you "push"

#### Logic Gates (?)
* We skipped past the basic stuff (I already know it anyway)
* Half adder is essentially just a NAND + AND gate [Half Adder Sim](https://simulator.io/board/A0MeGe4pvm/1)
* A full adder is 2 NAND + 2 AND + 1 NOT gates [Full Adder Sim](https://simulator.io/board/CZ0EsxYPgm/1)
* A full adder is used for adding stuff together [Adder calc](https://simulator.io/board/JIxRlrtGhm/1)
### Research

#### CD
* "cd" is used to refer to "Change Directory", so whenever I say "cd C:\Gitrepos", I'm telling git to change my directory to "Gitrepos" in my C drive
Apparently, there's varyations to this command, such as 
* "cd .." to go up one directory level
* "cd ~" to go to the home directory
* "cd /" to go to the root directory
* "cd" by itself also goes back to the home directory

#### Git
* "git" is used to refer to the version control system itself (github)
* "git add" track these file changes and **add** them to the staging area
* "git commit" permanently save the staged changes to the repository's history
* "git push" push my local commits up to the remote server (github)
* "git clone" clone a remote repo to my local machine
* "git status" show me the current status of my repo





## Exercises and results

I got git working

[That Painful 4 bit excercise](https://github.com/Akhabue72/COM304_FOUNDATION_1/blob/main/sessions/session2/docs/booleanAlgebraAndLogicGates.md)
* The answer to making it count down is: Just make it negative!
* <img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/2f3ebacd-ea19-4c8f-b365-c74a0c938a87" />
* <img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/264ec550-9ca0-49ff-9dee-490833788924" />



## Summary of learning
* I now know how to use github (or atleast the basics)
* I understand the composition of the adders
