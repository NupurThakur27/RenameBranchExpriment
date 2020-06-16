# RenameBranchExpriment

##Creating a new Branch
>git checkout -b nupur

##Renaming `nupur` branch to `nupurthakur`

>git branch -m nupur nupurthakur         # Rename branch locally

>git push origin :nupur                 # Delete the old branch

>git push --set-upstream origin nupurthakur   # Push the new branch, set local branch to track the new remote

