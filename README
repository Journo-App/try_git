This is the start of the Open Oakland Brigade's Github how-to for P2PU

(Pull changes if necessary first: git pull origin master)

##I. Start tracking your changes!##
There are multiple ways to start a new git repository and host a copy on github. One entails "cloning" from a github repo (making a local copy), another entails pushing a local copy in to a repository on github (in some cases, the github on repo may already exist, but below we describe to create one as well).

1. Sign up and log in to http://github.com/
1. Create repo in GitHub by selecting the "create new repo" button in the top-right corner menu of any github.com page.
    * We will copy to create a local repo (i.e. folders and git's history) that copies it, like this `try_git` repo  itself.
1. Go to the terminal and type: 
`mkdir ~/try_git` (you are making the local directory)
`cd try_git` (you are switching into that local directory)  or: `cd ~/try_git`
`git init` (you are initializing that local directory)
`touch README` (creating the README file in that local directory) 
1. Open the local repo (folder), find the README file and open it in your text editor and add info about the project 
1. Save; close README file 
    * Everything is still only on your computer (i.e. local) 
1. Commmit README to your local git repo: 
    * `git add README (this stages the changes)`
    * `git commit -m "first commit"`
1. Push your commit to Github: 
    * `git remote add origin https://github.com/username/reponame.git` (which would look like * this here: https://github.cm/Journo-App/try_git.git)
1. Then push the changes to Github: 
    * `git push -u origin master` 
        * Note "origin" and "master" are arbitrary names, but are conventional to make explaining git repos easier, see your remotes with `git remote -v` and see your branches with `git branch -v`

##II. Push an existing local repo to Github repo:##

1. `cd existing/git/repo` (replace whatever directories and name you have to locate your repo locally)
1. `git remote add origin https://github.com/username/reponame.git` (replace username and reponame appropriately as well)
1. `git push -u origin master`

##III. Change an existing file on the local repo and push to Github:##

Pull changes if necessary first: git pull origin master

1. Open the file (in this example it's called README) and make the changes. Save and close.
1. `git add README`
1. `git commit -m "the text you want to show up under your commit message that tells others what you've done"`
1. `git push -u origin master`
    * You should be prompted for your
    * Username: 
    * Password: 

##IV. BONUS: Edit a file from Github.com with Edit tab on file page.##

Then you have to pull down the changes to your remotely kept file to make sure they're in sync: 

1. make changes in the code and click the Commit Changes button at the bottom of the Github page
1. go into your terminal and type: 
    * `git pull origin master`

##V. To get what's in Github to your computer:##

1. Make sure you are in the right directory 
1. `git remote` (will show you any remote repos that your computer knows about)
1. `git remote add`

##VI. Cloning an existing Github repo (pulling down a copy of a Github repo)##

1. Find and copy the Github URL of the project you want to clone 
1. cd in the terminal to the directory you want to pull it down into, such as Documents
1. Paste in the terminal the Github URL you want to clone to your machine 
1. Git creates a directory by default that will be the XXXX.git in the URL (for example: http://github.com/username/reponame.git. The directory would be called reponame) BUT!
1. You can also rename the directory. For ex: reponame_myversion
1. Type (in the terminal) `ls -la` to see the folder that has been created on your machine in the directory you chose 
    * You will make changes and push them to the repo you want 

##? Alternative method: You have created a new repo -- test.git in this example -- in Github and have a local one too:##

1. `touch README.md` (***I am not sure why github's instructions put the .md at the end and other tutorials don't ***) 
1. `git init`
1. `git add README.md`
1. `git commit -m "first commit"`
1. `git remote add origin https://github.com/Journo-App/Test.git`
1. `git push -u origin master`
