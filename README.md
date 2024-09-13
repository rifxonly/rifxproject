mkdir nama-repo
cd nama-repo
echo "Hello World!" > index.html
git init
git add index.html
git commit -m "Initial commit"
git remote add origin https://github.com/username/username.github.io.git
git push -u origin master
