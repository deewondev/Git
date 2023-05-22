# Git

Basic Git command line codes for Github

It enables you to be able to connect from github to your local directory and vice versa

…or create a new repository on the command line
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/deewondev/repository_name.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin https://github.com/username/repository_name.git
git branch -M main
git push -u origin main