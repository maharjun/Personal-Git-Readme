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

2. Merge Options -

   1. --no-commit
      
      This means that the merge will be performed and the results indexed but not committed. 
      This allows one to inspect and test the merge before committing
   
   2. --squash
      
      This means that the merge will be performed but all changes in the `Remote` Branch will
      be squashed together into a single commit and will not mix up the histories of the `Local`
      and `Remote` branch. However, this also means that the new merge commit will not contain
      as a parent, the commit of `Remote` branch that it merged with.
3. 
