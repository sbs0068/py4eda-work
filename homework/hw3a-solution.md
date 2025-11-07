# HW3A Solution - Git and Version Control

## Part 1: Repository Cloning

I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to `~/insy6500/class_repo`.

### Key Commands Used

- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections

## Part 2: Portfolio Repository Creation

I created my personal course repository with:

- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes

### Understanding Git Workflow

The three-stage workflow:

1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`

## Part 3: GitHub Publishing

Successfully published repository to GitHub:

- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub

### The Remote Connection

My local repository is now connected to GitHub:

- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)

### Details

Complete this section with details from your setup:

- Repository URL: https://github.com/sbs0068/py4eda-work/tree/main
- Output of `git remote -v`: origin  https://github.com/sbs0068/py4eda-work.git (fetch)
origin  https://github.com/sbs0068/py4eda-work.git (push)
- The output of `git log --oneline`:ab6eaa3 (HEAD -> main, origin/main) Add hw3a solution document
f79accf Initial commit: Add README and .gitignore

##Question 1

###Reflections

#### a.) 
Before implementing git I typically performed version control by 
simply saving copies of my documents/scripts with updated version numbering at the the. 
1. One advantage of git is that it saves a continuous stream of all of my saved states for easy access. 
2. If I revert a git file to an older version it still saves my progress and I can restore it if needed. 
3. Git allows me to add comments to my new versions when I save them, so that I remember what exactly I did.

#### b.) 
Git's commit history would have been valuable when working on Stochastic OR case studies. 
These case studies were often very long and required multiple iterations to get right. Git would have made testing much easier because it would provide a log of what I had tried as well as 
allowing easy access to revert changes.  

##Question 2

###Reflections 

##### a.)
Keeping the repositories seperate is importatn because the very reason we are
making repositories is to stay organized. If the repoositories were merged it would
be hard to seperate my work from class documents. If everything were in one file names
would conflict as well.

#### b.) 
I think the most basic way is to create folders for each class in my respository
and within those folders have generic subfolders for projects, assignments, and
references. Group projects would probably be stored in their own repositiores 
and I would clone it into my records when completed.

##Question 3

###Reflections

####a. 
Output:
$ git log --oneline
689baa5 (HEAD -> main, origin/main) Complete Part 3 documentation
ab6eaa3 Add hw3a solution document
f79accf Initial commit: Add README and .gitignore
(base)
The "Add hw3a...structure" message is much more useful than simply "update." THis is because it gives information on what was changed at this iteration
of the code. So if needed I would know where to revert to. If I needed to 
view what my original document looked like or if something goes wrong in the
future I would be able to restore this without starting from scratch. 

####b.)

A good unit of work to commit is anytime any meaningful progress is saved. 
Even if it is just a few lines or a single funciton written it is important 
to save and document your work. For instance, what if you only have time to 
do a very small amount at a time. If you never save because there is "not enough"
to make it worth it you would never save at all. Furthermore, if you do have time
routinly saving every soo often i.e. 15 or 30 minutes prevents data loss in the event of a crash.


