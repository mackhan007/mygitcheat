For me.


git init
git add README.md
git add .
git commit -m "first commit"
git remote add origin $url // git remote set-url origin $url
git push -u origin master // git push -f origin master

// create repo from terminal and add current dir as main dir
gh repo create Todo-ios --public --source=.
