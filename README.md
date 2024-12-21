# Learnable

1 - Version control: is a system that tracks changes to code over time, allowing multiple people to collaborate, revert to previous versions, and manage project history efficiently, often using tools like Git.


2 - Difference between Git And GitHub
Git: is a distributed version control system that tracks changes in files locally on your machine, allowing you to manage and collaborate on code. 
GitHub: is a cloud-based platform that hosts Git repositories online, providing collaboration tools like pull requests, issue tracking, and code review. GitHub allows developers to share, store, and manage code remotely, enabling easy collaboration across teams. 
In short, Git is the tool, while GitHub is the service that hosts and manages Git repositories.

3 - Alternative to Github
- GitLab
- BitForge
- SourceForge

4 - Difference Between GitFetch and GitPull
Git fetch: downloads updates from the remote repository but doesn’t apply them to your local branch, allowing you to review changes first while, git pull: combines `git fetch` and `git merge`, downloading updates and immediately merging them into your current branch. Use `git fetch` for controlled updates and `git pull` for immediate synchronization.

5 - Git rebase: rewrites commit history by moving your branch’s changes to the latest commit of another branch, creating a cleaner history. It avoids merge commits.  
Command: git rebase <branch-name>  
example:  git rebase develop

6 - Git cherry-pick: copies a specific commit from one branch and applies it to another, without merging the entire branch. It’s useful for selecting only the needed changes.  
Command: git cherry-pick <commit-hash>
