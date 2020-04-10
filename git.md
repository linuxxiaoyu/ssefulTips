### init

git init [*repository*]



### add

git add [*file, path ...*]



### branch

git branch -d *branch*

git branch -D *branch*



### cat-file

git cat-file -t

git cat-file -p



commit, tree, blob



### checkout

git checkout -b *newBranch*

git checkout [*file*]



### clone

git clone --bare [file://]*src.git* *des.git*



### commit

git commit -m '*msg*'

~~git commit -am '*msg*'~~

git commit --amend



### config

git config [--list] [--global, --local, --system]

git config [--global, --local, --system] user.name '*userName*'

git config [--global, --local, --system] user.email '*userEmail*'



### diff

git diff [--cached] [*file, path ...*]

git diff [*branch1*] [*branch2*] [*file*]

git diff [*commit1*] [*commit2*] [*file*]





### log

git log [--oneline] [--graph] [--all]



### mv

git mv



### push

git push *name*

git push --set-upstream *name* [*branch*]





### remote

git remote -v

git remote add *name* *url*

git remote remove *name*



### rebase

git rebase -i [--root] [HEAD~*n*] [HEAD^^^^] []

git rebase --continue



pick

reword

squash



### reset

git reset HEAD [*file*]

~~git reset --hard~~





### rm

git rm [*file*]



### stash

git stash [apply] [pop] [list] [clear] [drop]



### status

git status 



### switch

git switch *branch*