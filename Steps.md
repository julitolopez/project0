Instructions: Upload to  https://github.com/me50/julitolopez.git
on a branch called web50/projects/2020/x/0

Steps:
1) cd to project0 :status done

2) initialize git with command git init :status done

3) create a new remote for project0 (since origin remote repository is
  https://github.com/julitolopez/project0.git)
  command: git remote add CS50 https://github.com/me50/julitolopez.git :status pending

  You can check the remotes defined for the repository with: git remote -v

4) When project0 is ready, create a new branch, command:
  git branch web50/projects/2020/x/0 :status pending

5) Move the HEAD to the new branch, command: git checkout web50/projects/2020/x/0 :status pending

6) From the new branch, Push project0 repository to the new CS50 remote with command:
  git push <remote> <branch> -> git push CS50 web50/projects/2020/x/0 :status pending

    if upstream branch were not yet created, add -u in the command line:
    git push -u CS50 web50/projects/2020/x/0
