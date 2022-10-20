# HR-Attritition
(Employee Attrition prediction):[https://hr-attrition.herokuapp.com/]

conda create -p venv python==3.9 -y

conda activate venv/

pip install -r requirements.txt

To Add files to git `` git add .

OR

git add <file_name>


> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status

git status


To check all version maintained by git
git log


To create version/commit all changes by git
git commit -m "message"


To send version/changes to github
git push origin main


To check remote url

git remote -v

To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = ramdj81@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = hr-attrition


 BUILD DOCKER IMAGE

docker build -t <image_name>: .

