echo "# blist1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M blist
git remote add origin https://github.com/seohyd/blist1.git
git push -u origin blist
