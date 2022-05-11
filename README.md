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
1. Go to setting in profile on top right
2. 
https://github.com/nouman-atac/docker_web_app
