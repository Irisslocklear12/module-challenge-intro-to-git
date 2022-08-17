## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? -Git is a DevOps tool used for source code management (version control system) it is used to track changes in the source code, enabling multiple developers to work together on non-linear development 
2. What is the difference between Git and GitHub? -Git is a version control system that let you manage and keep track of your source code history.
-GitHub is a cloud-based hosting system that lets you manage Git respositories.
3. Why do we create a branch? -Git branches are created to order to isolate specific Git commits from the rest of your main Git history.
4. What is the purpose of a Pull Request? -To initiate the process of intergration new code changes into the main project respository.
5. What is the command you can use to switch between branches? -The git switch - command to undo any changes you make and return to your previous branch. If you instead want to keep your changes and continue from here, you can use git switch -c <new-branch-name> to create a new branch fromthis point.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? -git fetch updates your remote-tracking branches. -git merge join two or more development histories together. -git pull bring a local branch up to date with its remote version, while also updating your other remote tracking branches.
7. What is a merge conflict? -Merge conflict is an event that occurs when Git is unable to automatically resolve differences in code between two commits.
8. How do you resolve a merge conflict? -open it and make any necessary changes, after editing the file, you can use the git add a command to stage the new merged content, then create a new commit with the help of the git commit command, git will create a new merge commit to finalize the merge.
