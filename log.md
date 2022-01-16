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

Now I would like to dive into my thoughts on python virtual environments. From my understanding it is important to use virtual environments because package versions can change which can impact how to use that package and if you install & update packages in your global environment projects that rely on the old version may not work.

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
### Day 4: Thursday January 6th - Back to Python 🐍

**Progress**: I made lots of progresss on the Intro to Python Programming course I am currently taking on EdX. I just finished chapter 3.3 on loops. Below are couple answers to some problems that I am proud of the solution I came up with on my own. 

```python 
#Coding Problem 3.3.15 (Advanced)
for i in range (1,len(mystery_string)+1):
    print(mystery_string[:i])

#Coding Problem 3.3.16 (Advanced)
count = 0
for index, char in enumerate(mystery_string):
    if char == "c":
        if mystery_string[index:index+3] == "cat":
            count += 1
print(count) 
```

**Thoughts**: Things finally feel like they are starting to click. I truly feel that I am able to code now. I have been off and on about programming for awhile now but lately I feel like I am really understanding how things work. The key for me was to keep at it. 

I can't express enough how much help this #100DaysOfCode challenge has been helping. For one it really holds me accountable. Secondly, I have find it very helpful to write about what I am learning. It makes me think about what I learned & that helps reenforce those concepts I learned. Looking forward to keep on keeping on.

Below are some other resources/articles that I checked out today. 

**Links** 
- [The Odin Project](https://www.theodinproject.com/)
- [Replit](https://replit.com/)
- [Free Code Camp Game](https://freecodecamp.itch.io/learn-to-code-rpg)
- [FCC Data Science Curriculum (Super Exciting!)](https://www.freecodecamp.org/news/building-a-data-science-curriculum-with-advanced-math-and-machine-learning/)
- [FCC Relation DB Course](https://www.freecodecamp.org/news/how-to-run-freecodecamps-relational-databases-curriculum-using-docker-vscode-and-coderoad/)
- [FCC's future which is awesome](https://www.freecodecamp.org/news/free-accredited-bachelors-degrees-in-computer-science-how-do-we-get-there/)
---
### Day 5: Friday January 7th - Web Development, htmx & APIs 🕸️ 

**Progress**: Lots of progress was made on day 5. I dipped my toes into learning more about how the web works & other concepts such as APIs & htmx. I will think some of the resources and tutorials I started today. 

**Thoughts**: Learning about web development has been fun. My reason for wanting to learn more about web development is because I want to build my own portfolio website. Also I feel that it would make a for a great project to work on during my #100DaysOfCode. I am a big fan of the [Jamstack](https://jamstack.org/) which is all about pre-rendering by generating the HTML on build opposed to server side rendering which generates the HTML on demand. This makes it easy to deploy the site onto a content deliver network (CDN) like Github Pages or Netlify. Also, I plan on using a static site generator called [Pelican](https://docs.getpelican.com/en/latest/) which is a tool that generates HTML pages based on raw data from templates (A template is a reusable format for web content; developers use templates to avoid writing the same formatting over and over.) and given content source (e.g. markdown files).I am looking forward to following this [tutorial](https://shahayush.com/categories/pelican-for-website-creation/) to get my website started. Stay tuned! 

Well that is enough about the jamstack, what the heck is htmx and why was I learning about it? Well I came across htmx because I heard allows you to write less javascript. I have nothing against javascript but being a fairly new programming & python I'm not really at a point yet where I really want to start branching out to other languages and learning front end frameworks like react. I enjoy python and I want to use it as much as possible when I can. 

A quote from [htmx.org](https://htmx.org/)
>htmx allows you to access AJAX, CSS Transitions, WebSockets and Server Sent Events directly in HTML, using attributes, so you can build modern user interfaces with the simplicity and power of hypertext

This intrigued me because when static sites may not be enough for a web app I am trying to accomplish. I think using htmx for my front end could be very beneficial because it allows my to write the back end in a python web framework (flask, django or fastapi) and keep the front end in HTML and CSS without having to worry about javascript. 

Lastly, while I was researching about web development the term API was coming up a lot. While I get high level that API stands for application programming interface and this is what allows a user to communicate with different applications, I didn't understand how they work. Especially because htmx was encouraging building APIs that deliver HTML opposed to JSON & I kept hearing about GraphQL and how it enables users to request specific data. This led me to a great tutorial called [Python API Development](https://www.youtube.com/watch?v=0sOvCWFmrtA). I have been working through this tutorial so far and I am learning a lot. Looking forward to picking it up again tomorrow. 

**Links**:
- [What is the Jamstack?](https://jamstack.org/what-is-jamstack)
- [htmx course](https://training.talkpython.fm/courses/htmx-flask-modern-python-web-apps-hold-the-javascript)
- [htmx - Clean, Dynamic HTML pages](https://www.youtube.com/watch?v=4wjqsPtj2QY)
- [Dynamic HTML with htmx](https://devmode.fm/episodes/dynamic-html-with-htmx#2318)
- [RESTful APIs in 100 seconds](https://www.youtube.com/watch?v=-MTSQjw5DrM&t=176s)
---
### Day 6: Saturday January 8th - Python Functions ➕

**Progress**: Completed chapter 3.4 for the Intro to Python Programming on functions.

**Thoughts**: This was a really helpful chapter for me because functions are one thing I've struggled implementing in my programs. I find the using functions helps with DRY code. Below is an example of one of the problems I had to solve. 

```python 
#3.4.6 Coding Exercise 1
def snowed_in(temperature, weather, is_celsius = True):
    if is_celsius:
        is_freezing = temperature < 0
    else:
        is_freezing = temperature < 32
        
    if is_freezing or weather == "snowy":
        return True
    else:
        return False
```

Also, the reason for me taking this course is to strength my application to GaTech's Master of Science in Analytics program. After I finish up the the Intro to Python Programming certificate I will submit my application! Today I even looked into the courses and created a course schedule. (I really brought this up just because I wanted to see how to add an image in markdown.)

<img src="https://i.imgur.com/Cnb1dY9.jpg" width="400"/>

**Links**
- [Python String Formatting](https://docs.python.org/3/library/stdtypes.html#printf-style-string-formatting)
---
### Day 7: Sunday January 9th - More Python Functions 

**Progress**: Worked on the problem set for chapter 3.4 functions. 

**Thoughts**: I completed the chapter yesterday but at the end of every chapter there is a problem set with about 25 questions. Half of them are coding, the other half is multiple choice or fill in the blank. So far I have been impressed the course. 

---
### Day 8: Monday January 10th - Error Handling

**Progress**: Made some progress on chapter 3.5 Error handling. 

```python 
try:
    print(10/mystery_value)
except ZeroDivisionError:
    print("Can't divide by zero")
except:
    print("Not possible")

```

**Thoughts**: I can see how important error handling can be when writing a program. You never want the user to see the program crash so if you can anticipate errors ahead of time and have a plan for them it's going to make the user experience a lot better. Standard format for error handling is ```Try-Catch-Finally``` python uses ```Try-Except-Else-Finally```

---
### Day 9: Tuesday January 11th - Day 14: Sunday January 16th 

I know it has been awhile since I updated my log.md but I promise I still have been coding. The reason I haven't had the time to update the log is actually because of coding & I am excited to share what I have been working on. 

**Progress**: 
### **I launched my personal website 🌐**.
This has been something I wanted to do for so long now. It was also one of my 2022 new years resolutions & I am excited to say it's live. So please check out [www.tylerhillery.com](https://www.tylerhillery.com) & let me know what you think! 

There are a few reasons I wanted to build this website. 

1. Creating the website itself was a great way to improve upon my Python, Git, Markdown, HTML & CSS skills. 
2. A place where I can showcase future projects.
3. Somewhere where I can write about what I am learning, my thoughts on the data landscape. 
4. Post tutorials & other learning resources. 

I used Pelican a static site generator to help build the site. The website is also based on the Flex theme with some custom CSS of my own. You can checkout the repo for the website [here](https://github.com/TylerHillery/TylerHillery.github.io).

I can't express enough how important project are in developing technical skills. i highly recommend when you get a base foundation in whatever skill your learning to put it to the test & build *something*. You may struggle, I sure did, but that's okay! Those are the times that really help develope those skills. 

Also, I completed [Computing in Python II: Control Structures](https://www.edx.org/course/computing-in-python-ii-control-structures) in the [Intro to Python Programming Certificate](https://www.edx.org/professional-certificate/introduction-to-python-programming?index=product&queryID=338370f2779087494d5e00a23e8e47ac&position=2). I hoping to finish this certificate shortly so I can officially submit my graduate application. 

<img src="https://i.imgur.com/61smhlO.jpg" width="400"/>

___
