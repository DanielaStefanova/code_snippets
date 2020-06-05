#Init user
git config --global user.name "Daniela Stefanova"
git config --global user.email "d@mail.com"

#Init repository
// Go to an empty folder. Creates .git file
git init

#Get the current status of repository
git status

#Git add. You do this for new and modified files
git add
git add .  // It adds all changes made

#Git commit
git commit -m "Commit message"  // This is commit with message

#Git log
git log

#Git checkout
git checkout <commit-hash>  // <commit-hash> is a revision number - big code
git checkout master  // get back to the head
git checkout <branch-name>   // checkout of a branch (switch)

#Branches
git branch  // just list branches
git branch <branch-name> // creates branch with the given name

#Commit to main
git merge <branch-name>

#Overview of the process
git checkout master  //update
git branch myBranch
git checkout myBranch
/// do changes
git add .
git commit -m "I did some changes"
git checkout master  // switch to master
git merge myBranch

#GitHub
#Add existing repository to GitHub
git remote add origin https://github.com/Daniela/something.git  // origin is a name for the URL
git push -u origin master   // run it every time you want to get changes to GitHub
#Get changes from GitHub
git pull origin master

#Overview create new branch and push it to GitHub
git checkout -b relaxing
git add .
git commit -m "Add relaxing songs"
git push -u origin ralaxing

#Download a new repository from GitHub
// Got to an empty folder
git clone https://github.com/tralala/tralala.git

#Fork a repository
// Fork in the web page

#Workflow with public git repository
// Fork
// Clone
// Do changes
// Add
// Commit
// Push
// Pull request  from web page
// Wait for approval
// Merge
// Update my repository
git pull origin master
