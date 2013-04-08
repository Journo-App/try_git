This is the start of the Open Oakland Brigade's Github how-to for P2PU

Pull changes if necessary first: git pull origin master

I. 1. Create repo in GitHub and then a local repo (i.e. folder) that mirrors it, like, for this purpose: try_git (BUT! your local folder can have a different name than your Github repo)
2. go to the terminal and type: 
mkdir ~/try_git (you are making the local directory) 
cd try_git (you are switching into that local directory)  or: cd ~/try_git 
git init (you are initializing that local directory)
touch README (creating the README file in that local directory) 
3. Open the local repo (folder), find the REAME file and open it in your text editor and add info about the project 
4. Save; close README file 
Everything is still only on your computer (i.e. local) 
5. Commmit README to Github repo: 
* git add README (this stages the changes) 
* git commit -m "first commit" 
6. Push your commit to Github: 
* git remote add origin https://github.com/username/reponame.git (which would look like * this here: https://github.cm/Journo-App/try_git.git)
7. Then push the changes to Github: 
8. git push -u origin master 

II. To push an existing local repo to Github repo: 
cd existing_git_repo (whatever the name of is replaces existing_git-repo)
git remote add origin https://github.com/username/reponame.git 
git push -u origin master 

III. To make changes to an existing file on the local repo and push to Github: 
Pull changes if necessary first: git pull origin master
1. Open the file (in this example it's called README) and make the changes. Save and close 
2. git add README
3. git commit -m "the text you want to show up under your commit message that tells others what you've done" 
4. git push -u origin master
Username: 
Password: 
 
IV. You can also edit a file from Github by clicking the Edit tab on the file page. 
Then you have to pull down the changes to your remotely kept file to make sure they're in sync: 
1. make changes in the code and click the Commit Changes button at the bottom of the Github page
go into your terminal and type: 
2. git pull origin master

V. To get what's in Github to your computer: 
1. Make sure you are in the right directory 
2. git remote (will show you any remote repos that your computer knows about)
3. git remote add 

VI. Cloning an existing Github repo (pulling down a copy of a Github repo)
1. Find and copy the Github URL of the project you want to clone 
2. cd in the terminal to the directory you want to pull it down into, such as Documents
3. Paste in the terminal the Github URL you want to clone to your machine 
4. Git creates a directory by default that will be the XXXX.git in the URL (for example: http://github.com/username/reponame.git. The directory would be called reponame) BUT!
5. You can also rename the directory. For ex: reponame_myversion
6. Type (in the terminal) ls -la to see the folder that has been created on your machine in the directory you chose 
You will make changes and push them to the repo you want 

? Alternative method: You have created a new repo -- test.git in this example -- in Github and have a local one too: 
1. touch README.md (***I am not sure why github's instructions put the .md at the end and other tutorials don't ***) 
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git remote add origin https://github.com/Journo-App/Test.git
6. git push -u origin master
