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
30/09/2025
* How to use a rasberry pie

07/10/2025
* Recap of what was done yesterday: [Binary stuff](https://github.com/Akhabue72/COM304_FOUNDATION_1/blob/main/sessions/session2/docs/binaryArithmetic.md)
* Logic gates

## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

* To access the git folder I have locally through git would be "cd C:\Gitrepos"
* To check which folder I'm in, I input "pwd" and then it just displays it
* To access the Computing foundation folder through git would be " cd COM304_Foundation_1/"
* Small tip: You can autocomplete the destination if the path name is unique enough by pressing TAB (thanks craig)
* To update igni (I'll just call them igni (my laptop) and pheas (the web version) from now on) with changes I made on pheas, I have to make sure that I'm in the right folder, and then input "git pull", which will pull all changes i made on pheas into igni.
* I can use "git status" to check whether igni is up to date with pheas
* When I make changes on igni, and want to push it to pheas, I need to "git add --all" to add all the changes together, then I "git commit -m" to do something (?) which will then ask for my identity if this is the first time I'm doing this from my device. Once the commit is ready, I then "git push", which requires my personal access token, and if all goes well, the changes I made on igni will get put on pheas (I'll look into all the new terms and stuff in a bit)
* How to make a personal acces token: Settings, Developer Settings, Personal access tokens (from there just follow the steps. I already made one and I don't remember the other steps after)
* A personal access token is essentially just a very long password that you use every time you "push"

* [link to the instructions for Installing a rasberry Pi](https://github.com/Akhabue72/COM304_FOUNDATION_1/blob/main/sessions/session1/docs/InstallingRaspberryPI.md)
* The connections consist of: Power cable, keyboard, mouse, Internet thingie, Hdmi cable
* Ping is something engineers use to check whether there is a response from the network (measured in "ms")

* We skipped past the basic stuff (I already know it anyway)
* Half adder is essentially just a NAND + AND gate [Half Adder Sim](https://simulator.io/board/A0MeGe4pvm/1)
* A full adder is 2 NAND + 2 AND + 1 NOT gates [Full Adder Sim](https://simulator.io/board/CZ0EsxYPgm/1)
* A full adder is used for adding stuff together [Adder calc](https://simulator.io/board/JIxRlrtGhm/1)
* 
### Research

#### CD
* "cd" is used to refer to "Change Directory", so whenever I say "cd C:\Gitrepos", I'm telling git to change my directory to "Gitrepos" in my C drive
Apparently, there's varyations to this command, such as 
* "cd .." to go up one directory level
* "cd ~" to go to the home directory
* "cd /" to go to the root directory
* "cd" by itself also goes back to the home directory



## Exercises and results

I got git working
Shaun and I (mainly shaun) got the rasberry pi working

## Summary of learning
* I now know how to use github (or atleast the basics)
* I now can set up a rasberry pi, but I'm not too sure about actually using one
