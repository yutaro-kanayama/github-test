# github-test
echo "# github-test" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/yutaro-kanayama/github-test.git

git push -u origin master

git pull origin master
