# IE-Q3-HW1
The Third Q of the Internet Engineering First Home Work




## Forgot add few changes in previous Commit
In this situation we can use --amend for change the previous commit files
<br>
<code>
  git commit --amend
</code>
<br>
 (or we can have new message for Modified commit)
<code>
git commit --amend -m "The Commit content"
</code>


## For delete file from all where
We can delete with use this command 
<br>
<code>
  git filter-branch --index-filter "git rm -rf --cached --ignore-unmatch path_to_file" HEAD
</code>


that use the path of file that you want to delete in path_to_file
![Screenshot (52)](https://user-images.githubusercontent.com/66215461/138945221-fd94a1d6-c11b-4cb0-a1d1-316866cfe0bd.png)


## For Share that cannot be pushed right away
We can Share files with firends withoutbe pushed right away 
<br>
<code>
git diff > filename.patch
</code>

and we can download with
<br>
<code>
git apply filename.patch
</code>


## For Have a commit from other branch :)

<br>
<code>
git cherry-pick <commit-hash> 
</code>

and for rest of the other branch merge
<br>
<code>
git rebase other-branch
</code>
