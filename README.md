# phase-0-gps-1

git clone git@github.com:abruckman/phase-0-gps-1.git
ls
cd phase-0-gps-1
git checkout -b session1
touch awesome_page.md
git add awesome_page.md
git commit -m "made awesome_page.md"
git checkout master
git merge master
git merge session1
git push origin master
git checkout -b add-command-log
start README.md