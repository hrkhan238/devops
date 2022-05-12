#DevOps

#To perform version control in git

#Create github account

#Create new repository

1. Create new folder
2. Create new file index.html in new folder
3. Right click and click Git Bash Here
4. Type git config --global user.name "YOUR USERNAME"
5. Type git config --global user.email "YOUR EMAIL"
6. Type git init
7. Type git add .
8. type git remote add origin https://github.com/yourusername/repositoryname.git
9. Type git commit "First commit"
10. Type git push --set-upstream origin master

#If error occured in step 10 then repeat step 4 and 5 by following changes

#git config credential.username "YOUR USERNAME"

#git config credential.username "YOUR EMAIL"



#To perform deployment of web application on GitHub

1. Follow all the above step
2. Go to your current repository ex. hrkhan238/devops
3. Click on setting
4. Inside setting, Click on pages
5. Select Branch as master and save

#Wait for some time then click on the link that will be generated sometime it takes time 


#To install and configure Docker in Ubuntu
1. Open terminal in Ubuntu
2. sudo apt update
3. sudo apt install -y docker.io
4. sudo systemctl enable --now docker
5. sudo usermod -aG docker $USER
6. docker --version


#To perform Deployment of web application on Docker

#Your github password will not work in Ubuntu
1. Go to GitHub setting in profile on top right
2. Click on Developers setting
3. Click on Personal access tokens
4. Click on Generate new token
5. Write something on note ex. my-key
6. Click only on repo rest will be selected
7. Click generate token

#Your token will be generated

#Copy your token before refreshing your page

Please follow this link for the rest

https://github.com/nouman-atac/docker_web_app


#To perform version control on Mercurial

1) hg (to check Mercurial is installed) / (hg config --edit) to change mercurial.ini

2) mkdir

3) cd repo

4) hg init (for .hg file to be installed in repo)

5) hg clone http://www.selenic.com/repo/hello myHello (Cloning file from Mercurial)

6) cd myHello

8) Now go back to repo by (cd ..)

9) hg clone myHello myHelloClone (you make a directory clone of myHello)

10) Now manually (GUI) go to myHelloClone and access the Hello.c file and make some changes

11) go back to cmd and go to cd myHelloClone and type hg status

12) hg diff (To check the changes made in it)

13) hg commit -m "My first version" hello.c (to commit the changes made earlier in the hello.c file)

14) hg push ..\myHello

15) now go to myHello folder using cd..

16) hg update (to update the changes done in myHello folder)

17) Now manually (GUI) go and check the Hello.c file in myHello. You can see the changes that were done in myHelloClone/Hello.c in myHello/Hello.c
