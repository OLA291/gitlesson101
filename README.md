# Gitlesson101
This lesson explains how to push code from your local environment to GitHub, a remote repository, highlighting the distributed aspects of Git.  
## Download gitbash  
- https://git-scm.com/downloads
## Configure gitbash  
- git config --global user.name  
- git config --global user.email  
## Configure environment  
- mkdr myresume  
- cd myresume  
- touch index.html  
- git init  
## Clone your repository  
- git remote add origin url (this should be the url from your created repo-use https)
## Push to github  
- git status
- git add index.html
- git commit -m "Create index.html"
- git push origin master
## Convert your file to github pages  
- Navigate to the settings tap of your repository
- from the genal section locate pages
- from the deploymant and build section select your your brach document and click save
- wait for a minute or more, then refresh the page to retrive the github pages for the file 
