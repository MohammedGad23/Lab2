# remove local branch
>> git branch -d(-D) dev\
>> git branch -d(-D) test\ 

# remove Remote branch 
>> git push origin :dev
>> git push origin :test

# checkout without commit 
>> will use git stash befor checkout branch
>> git stash 


# tages list 
>> git tag

# delete tags from local and remote 
>> local -> git tag -d v1.7
>> remote -> git push --delete origin v1.7

# Add image to README 

![Alt Text](addImage.jpg)
