# Biol-812 Assignment

1. When should you use Git for a project?
- When you want to keep track of your changes in code
- For collaboration with different people
- To be able to revert to older versions

2. What kind of files/info should be saved in a Git repository? What types of files/info should not be included in a Git repo?
- Included 
    - code scripts
    - text files
- Not included
    - large files
    - private information

3. What are the commands to undo a commit?
``` 
git revert [commitID]
``` 

4. One of your repositories is in a “detached HEAD” state. How do you fix this?

```
git checkout master
```

5. Your boss has no idea what Git is or why you are using it. Explain the pros / cons of using Git for your research project. Explain the pros / cons of hosting your project in a public (or private) repository on Github/Bitbucket/Gitlab/etc.

Pros 
- Useful for backing up code
- keep track of what was modified and I can revert if code doesn't work

Cons
- takes time to learn Git
- Git will not back up extremely large files easily

Why host on Github
- another place to keep back up
- can collaborate with other people

Why not hot on Github
- repository is public unless made private 
