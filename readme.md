# Transferring between Repos
 
Transferring between repos is hard

Naming each repo a different name witin a 
convention can be confusing:
Protip: keep the names of the remotes
the same as the name as the repos

when trying to update a secondary repo with the date in the first:
1) push data to first repo (git push origin main)
2) change branch to branch on secondary repo (git checkout secondary)
3) pull data from main repo using git pull remote branch (git pull origin main)
4) add to staging (git add --all)
5) commit staging (git commit -m "text")
6) push to secondary remote (git push secondary secondary)
7) Debug



