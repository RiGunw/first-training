…to create a new repository on the command line

use cd to go to the folder we want
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/RiGunw/EduworkTraining.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/RiGunw/EduworkTraining.git
git branch -M main
git push -u origin main

…or to add change on existing files
git add .
git commit -m "add some blablabla"
git push origin main