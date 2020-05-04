git init
git add readme.txt
git commit -m "first commit"
git remote add origin https://github.com/GeekQ007/learngit.git
git push -u origin master
#get remote repos
git clone https://github.com/GeekQ007/learngit.git newname
git status -s 
#s refers to short
#git log show commit history of a branch
git log --oneline --number
git log --oneline --graph
git log --oneline branch1 ^branch2 
#belong to branch1 not to branch2
#show diff of unstaged changes
git diff
git reset HEAD filename
#github add repos
curl -u zqwang https://api.github.com/repos -d {"name":"name of repose"
