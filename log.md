# 100 Days Of Code - Log

<!--- This what was originally in the log file. I am going to keep it as a reference for markdown syntax.
### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)
**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.
**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.
**Link to work:** [Calculator App](http://www.example.com)
### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)
**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.
**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.
**Link(s) to work**: [Calculator App](http://www.example.com)
### Day 1: June 27, Monday
**Today's Progress**: I've gone through many exercises on FreeCodeCamp.
**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.
**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)-->
### Day 1: Monday January 3rd 2021 - The Beginning🐍

**Today's Progress**: I went through the SQL & Python exercises on W3Schools. I also checked out HackerRank & Exercism. Lastly, I made some progress on the Introduction to Python Programming course I am taking on Edx. Currently I am on the loops chapter 3.3. Below is are some code snippets from that class for some problems I had to solve. 
 
 ```python
 #3.3.5 Coding Excercise 1
 for i in range(1,measures+1):
    for j in range(1,beats_per_measure+1):
        print(j)
 
 #3.3.5 Coding Excercise 2
line_counter = 0 
while line_counter < lines_of_sanity:
    for i in lyrics:
        print(i)
        line_counter += 1
print("MAKE IT STOP") 
 ```

**Thoughts**: I am excited to began my #100DaysOfCode journey. Two main skills I want to focus on is Python & SQL. I may also learn a little bit about Web Dev (HTML,CSS,JS). I have a learning plan created on Trello (See attached link below). I plan on mixing in resources like CodeWars, HackerRank to get additional practice.

**Links**
1. [W3Schools](https://my-learning.w3schools.com/)
2. [HackerRank](https://www.hackerrank.com/TheRealTHill)
3. [Excercism](https://exercism.org/profiles/TylerHillery)
4. [CodeWars](https://www.codewars.com/users/TylerHillery)
5. [Trello Learning Plan](https://trello.com/b/z8s7uGR0/data-science-self-learning-journey)
6. [Intro To Python Programming](https://www.edx.org/professional-certificate/introduction-to-python-programming)
---
### Day 2: Tuesday January 4th 2021 - Linux & Bash 🐧

**Today's Progress**: Today took a weird turn & I fell down a rabbit hole of learning linux and bash. I installed the windows linux subsystem and started playing around in the terminal. Below are some common commands in Linux. 

```bash
# pwd print working directory 
# cd change directory 
# cd .. go up one directory
# cd ~ goes to home dir (you can do cd ~/documents to go directly to documents folder
# ls list contents in current directory
# mkdir make directory
# clear clears out the terminal
# touch create file 
# nano filename.filetype opens nano text editor
# cat display file contents
```

**Thoughts**: I have heard that linux and bash are good things to learn about if you want to get into data engineering & when I get interested in a topic I like to really take advantage of that feeling / urge and dive right in. I feel that it is okay to jump around to different topics when self learning. I really enjoy learning on my own opposed to in a structured environment because I can dive into what interests me at any given time opposed to be trapped into whatever class you are currently enrolled in. Getting use to the terminal & CLI I think is something that can really separate from others because I feel it is a skill that is often overlooked. 

**Links**
- [Linux Tutorial](https://www.youtube.com/watch?v=cBokz0LTizk)
- [Bash in 100 Seconds](https://www.youtube.com/watch?v=I4EWvMFj37g)
- [Best Web Dev Setup?](https://www.youtube.com/watch?v=-atblwgc63E)
- [WSL Set Up Guide](https://fireship.io/lessons/windows-10-for-web-dev/)
- [Diff between Terminal,Console,Shell & Command Line](https://www.youtube.com/watch?v=hMSByvFHOro&t=516s)
---
### Day 3: Wednesday January 5th 2021 - Git, venv, 2022 Become-a-Dev Challenge & some PyGitHub 📦

**Today's Progress**: I discovered the interesting world of python virtual environments and git today. I worked through several tutorials on YouTube to learn more about git and venv. I will list some common code snippets for both below and attached links to the resources I used to learn about these topics. From now on I will be updating the log.md file on a local machine and pushing the changes to my remote repo. 

Two other things that I was able to work on was learning about PyGitHub and the 2022 Become-a-Dev challenge. PyGitHub is a python library that allows interaction with the GitHub API. The 2022 Become-a-Dev challenge was created by Quincy Larson who founded Free Code Camp. There are 5 steps
1. Max out your stats in Learn ToCode RPG
2. Start #100DaysOfCode
3. Complete the freeCodeCamp Relational Database Certification
4. Publish 3 tutorials on your Hashnode blog 

Steps 1 & 2 look interesting to me and I plan on utilizing these resources during my #100DaysOfCode challenge. 

**Thoughts**: Git was something that I always struggle wrapping my head around. Knowing how to use git is going to be such a crucial part of my professional career I felt it was vital that I start using it on my projects, even this one! Here are the steps I took to work on this repo on my local machine.

 ```bash 
git clone https://github.com/TylerHillery/100-days-of-code.git #clone remote repo to local machine
git checkout -b Day3 #Created a new branch to record day 3 journal
code log.md #open file in vs code to edit
git status #shows which files are staged and not stage
git reset filename #unstage change
git add #add changes to staging area. Use a "." to add all changes
git commit -m "describe commit" #commit changes to branch current on
git stash -u #save all changes without committing 
git stash pop #bring back those changes
git merge branch #merge branch. Use --squash flag to put all commits into one.
git remote add origin #Connect local repo to remote repo 
git push origin branch #push changes to remote repo
git branch -d branch #delete branch
```
Writing markdown files in vs code is nice because I have the [Code Spell Checker](https://github.com/streetsidesoftware/vscode-spell-checker) extension installed to help with typos. Also if you hit ```Ctrl+Shift+V``` in vs code you can preview your markdown file. I like to split screen the preview file with the raw file so I can watch my changes be rendered in real time. 

**Git Resources**
- [Git it? How to use Git and Github by Fireship](https://www.youtube.com/watch?v=HkdAHXoRtos)
- [Git explained in 100 seconds by Fireship](https://www.youtube.com/watch?v=hwP7WQkmECE&t=4s)

Now I would like to dive into my thoughts on python virtual environments. From my understanding it is important to use virtual environments because package versions can change which can impact how to use that package and if you install & update packages in your global environment projects that rely on the old version. 

```python
#Using WSL with Ubuntu distro
pip list # This command will list out packages installed in the environment you are currently in. 
sudo pip install virtualenv #venv does not come with WSL so had to install virtualenv
virtualenv -p python3 venv #creates virtual environment called venv
source venv/bin/activate #activates the environment
pip freeze #formats the packages so there put into requirements.txt file
deactivate #to get out of venv
rm -rf venv/ #delete venv

#powershell 
Set-ExecutionPolicy Unrestricted #need to run this command to be able to run activate.ps1
python -m venv venv #creates virtual environment in powershell
.\venv\scripts\activate.ps1 #activates the environment
pip freeze #formats the packages so there put into requirements.txt file
deactivate #to get out of venv
rm .\venv -Recurse -Force #delete venv 

#git bash 
& 'C:\Program Files\Git\bin\sh.exe' --login #enter in powershell to launch git bash in windows terminal
python -m venv venv #create virtual environment 
source venv/scripts/activate #activate environment 
pip freeze > requirements.txt #formats the packages so there put into requirements.txt file
deactivate #to get out of venv
rm -rf venv/ #delete venv
```

After this experience of using the WSL and the git bash terminal I think it is going to be easier for me to just use the git bash terminal unless I really need linux for something. This way I can still learn bash. If you are using a virtual environment in vs code make sure to open the command palette ```CTRL+SHIFT+P``` and select _Python: Select Interrupter_. Also make sure to add venv/ to .gitignore file.

**VENV Resources**
- [Python Tutorial: VENV (Linux)](https://www.youtube.com/watch?v=Kg1Yvry_Ydk)
- [VS Code Setting up python venv](https://www.youtube.com/watch?v=-nh9rCzPJ20&t=2137s)

Lastly to wrap it up I am going to talk a little bit about PyGitHub. It was my first experience ever writing code that interacts with and API. It was cool to see how it works. Below is a code snippet I got from the docs that allowed me to update a file on my repo. 

```python
pip install PyGitHub #First created a venv and installed PyGithub
from github import Github

g = Github("API KEY")

repo = g.get_repo("TylerHillery/100-days-of-code")
contents = repo.get_contents("log.md")
repo.update_file(contents.path, "more test", "This is a test",contents.sha, branch="master")
```
Shortly after I ran this I realized that this does not just add "This is a test" at the bottom of the file it replaces the whole thing. The "more test" parameter was the title of the commit. Lesson learned.

**Additional Resources**
- [PyGithub Docs](https://pygithub.readthedocs.io/en/latest/index.html)
- [Take the 2022 Become-a-Dev Challenge](https://www.freecodecamp.org/news/2022-become-a-dev-new-years-resolution-challenge/)
---