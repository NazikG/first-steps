git clone https://gitlab.com/NazikG/StartGit.git
cd StartGit
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
cd existing_folder
git init
git remote add origin https://gitlab.com/NazikG/StartGit.git
git add .
git commit -m "Initial commit"
git push -u origin master
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.com/NazikG/StartGit.git
git push -u origin --all
git push -u origin --tags




git pull - вигрузка з сервера
git push -u origin master - загрузка на сервер
touch фаил - создать фаил 
git branch "название" - создать ветку
git checkout "название" -  переход на ветку
git stash код - загрузка сохранения
git commit -m "коментарий" - сохранение