# HW3A Solution - Git and Version Control
## Part 1: Repository Cloning
I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo`.

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
- Repository URL: https://github.com/tdubz24/py4eda-work
- Output of `git remote -v`:
- The output of `git log --oneline`:

##Questions
###Reflections

*Question 1: Git Workflow Benefits* 
a. I would normally use my file explorer. I am new to git and github so this a new way of storing files and data for me

b. It would have been great to have for my labs during my undergrad so that you're able to more seamlessly share files and see changes. Kinda like onedrive or google drive.This would have kept everything as far as files in one place and we would have been able to see the changes eah person makes, although onedrive and google drive accomplish that as well. I think to me from what I've learned so far it's another flavor of those tools.

*Question 2: Repository Organization*

a. It's important because you can separate the files that you want people to have access to, to make changes and which ones you want for yourself or to have as read only. If you tried to put everything into one repsoitory then it's easy for things to get messy and organization to go out the door. Also, your files are subjet to editing by whomever

b. 

*Question 3: Commit Messages History*

a. It's more useful because you can see why there was an update made. That way when you open the file, you have an idea of where to go look for where you left off last or from whoever updated the file last. It's kind of like an audit trail. May need to find it again when a change is made to data or something of that nature

b. A good unit of work would 

*Question 1: The Three-Stage Model*

a.

b. You should commit wirte code to load data. The others are minor things and can wait. This is a good stopping point since code to load data is a key piece. Stagging gives you a chance to determine what all will go in to your commit, otherwise you'd go straight into pushing files and could be more prone to mistakes or accidents. You're able to stage the files that are completed and ready without having to push the ones that aren't.

c. Git status gives you a glimpse into the state of your repository. It lets you see if all of your files are up to date or if you need to pull data from an update such as if someone else made a change to something the night before. You'd then have the latest and greatest. I think you cn use git status at you leisure because it's a tool to help you be informed.

*Question 2: Local vs Remote Repositories*

a. 

b. It enables develpers to work from anywhere. They don't need a wireless or wired connection. Developers can have their own local copy of the repository and you can play around in the files without making permanent changes because you would have to commit them and then push those changes. So there's some fail safe there too.

c. git clone copies everything. git pull only brings in the latest and greatest of the files in the repositorty. Git push, well it pushes any commits or changes you have made to files in the repository

*Question 3: Porfessional Portfolio*

a. 

b. Repository is more professional and souly tied to you. Open source can be contaminated with other people's work that is not your own.

c. Continue to enhance and build on it. This can be a usefu way to not only develop skills but be a good way to showcase skills to potential employers or for larger scale prokects in industry. Good habits are to invest in yourself through saving your work to be viewed by others later. 



###Graduate Questions
