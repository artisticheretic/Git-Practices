# Git-Practices :: Topics 

Basics -

1. What is Git? - Git is a VCS (Version Controlled System). Version control helps manage changes to code.
2. Repositories - A local / remote folder where the entire project is stored.
3. Branches - Branch is sort of a sub-folder within a repository. Branches other than the MAIN branch, typically contains features, or additional functionalities which may or may not be present in the MAIN branch.
4. Commits - A branch is made up of one or more sets of changes to files. We call these commits. If a branch represents a feature, a commit represents an implementation step. Selecting files to be added to a commit is called STAGING. And the changes which are commited go to the STAGING AREA.
5. Git Environment Setup.
6. Git Workflow.
7. Working Directory -> Git init (Git Initialization) -> Local Repo Is Created.
Fork Remote Repo -> Clone To Local Repo -> Create New Branch -> Checkout (Move) To New Branch -> Edit Files -> Add Files -> Review Changes -> Commit -> Push -> Pull Request To Add Changes To Main Branch Of The Original Repo (-> If everything looks good, original repo's author/admin can implement the changes in the code.) -> If there are mergle conflicts, these should be solved immediately.

Advanced -

1. Rebase - The process of moving or combining a sequence of commits to a new base commit. Generally, adding a feature branch's commits after the latest commits of the MAIN branch's commit.
2. Cherry-pick - Cherry picking is the act of picking a commit from a branch and applying it to another. Great to undo changes, when mixed with another command to delete the original commit.
3. Revert - We use when we want to take a previous commit and add it as a new commit, keeping the log intact.
4. Reset - We use when we want to move the repository back to a previous commit, discarding any changes made after that commit.
5. Amend - Used to modify the most recent commit.


////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


In this repo, there are multiple branches, conveniently named what the branch contains. For example - "Rebase-example" branch contains practical example of rebase with all the commit logs, and changes done.
