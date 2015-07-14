# Personal-Git-Readme

## Basic

### Branch related
1. Create Branch -
   
        git branch <BranchName>
   
2. Push branch for the first time
   
        git push -u origin <BranchName>
   
3. Push branch to another repo
   
        git push <Url/Remote> [+]<LocalBranchName>:<RemoteBranchName>
   
   the optional `+` sign is in order to force the push even if it is not fast-forward

### Merge Related
1. Merge Branches - 
   
   In order to merge branch `Remote` into branch `Local`, we perform the following command
        git checkout <LocalBranchName>
        git merge <RemoteBranchName>

2. Merge 
