# Contributing to JobBuddy
> We are thrilled that you are interested in contributing to our JobBuddy Discord Bot for Coden!
No worries if you are a first-timer contributing to this project or to open-source in general.
Let's break it down into bite-size steps for you!

## Table of Contents
* [Step 0: Are you a Codenian?](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/.github/CONTRIBUTING.md#step-0-are-you-a-codenian)
* [Step 1: Fork the project](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/.github/CONTRIBUTING.md#step-1-fork-the-project)
* [Step 2: Find an issue](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/.github/CONTRIBUTING.md#step-2-find-an-issue)
* [Step 3: Create a branch](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/.github/CONTRIBUTING.md#step-3-create-a-branch)
* [Step 4: Work on the issue assigned](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/.github/CONTRIBUTING.md#step-4-work-on-the-issue-assigned)
* [Step 5: Commit](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/.github/CONTRIBUTING.md#step-5-commit)
* [Step 6: Push it to your forked branch](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/.github/CONTRIBUTING.md#step-6-push-it-to-your-forked-branch)
* [Step 7: Make a Pull Request (PR)](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/.github/CONTRIBUTING.md#step-7-make-a-pull-request-pr)

### Step 0: Are you a Codenian?
* Click [here](https://github.com/CodenCommunity/Support/issues/new?assignees=LeeRenJie&labels=Join+Coden+GitHub&template=join-coden-github.md&title=Join+Coden+on+GitHub) to be a member of Coden on GitHub to contribute to any in-house projects.
* Click [here](https://discord.gg/rSKKKZEnVn) to join us in our Discord Server and meet the rest of the community!
Once you are on GitHub and Discord, move on to step 1

---

### Step 1: Fork the project
* Fork this Repository. This will create a Local Copy of this Repository on your Github Profile.
![fork](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/assets/pic1_fork.png)

<ul>
  <li>Add the forked repository to your computer directory:</li>
  <blockquote>

```
$ git clone https://github.com/<your-username>/Coden.github.io 
    
# This is a comment, change **repo_name** in the following to your repository name
$ cd repo_name 
    
$ git remote add upstream https://github.com/CodenCommunity/Coden.github.io
```
  </blockquote>
</ul>
  
---

### Step 2: Find an issue
* Take a look at the Existing Issues or create your **own** Issues!  
* Wait for the Issue to be assigned to you after which you can start working on it.  
* Note : Every change in this project should/must have an associated issue.
![issue](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/assets/pic2_find_issue.png)
  
---
  
### Step 3: Create a branch
<ul>
  <li>Create a new branch in your computer directory. Use its name to identify the issue you are addressing.</li>
  <blockquote>
    
```
# This is a comment, change **branch_name** in the following to the name of issue you are addressing
$ git checkout -b branch_name
```
  </blockquote>
  <li>OR you can create the branch in Github as shown here:</li>
  
![branch](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/assets/pic3_branch.png)
  
<blockquote>
    
```
# After you create the branch here, remember to update it in your computer directory
$ git pull
$ git checkout branch_name
```
  </blockquote>
</ul>

---
  
### Step 4: Work on the issue assigned
* Work on the issue(s) assigned to you.   
* Add all the files/folders needed.  
* After you've made changes or made your contribution to the project add changes to the branch you've just created by using terminal:  
```  
# To add all new files to branch Branch_Name  
$ git add .  

# To add only a few files to Branch_Name
$ git add <some files>
```
- Using GitHub
![upload_file](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/assets/pic4_upload_file.png)

---

### Step 5: Commit
* You are suggested to use Conventional Commits in your commit message to ease other contributors reading the documentation, read [here](https://www.conventionalcommits.org/en/v1.0.0/)
* To commit give a descriptive message for the convenience of reviewer by using terminal:  
```
# This message get associated with all files you have changed  
$ git commit -m "message"  
```
- Using GitHub
![commit](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/assets/pic5_commit.png)
---
  
### Step 6: Push it to your forked branch
* Push your changes to the forked branch
```
git push
```
* You should see something like this in your Github after pushing:
![push](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/assets/pic6_push.png)
---
  
### Step 7: Make a Pull Request (PR)
* Go to your repository in browser and click on compare and pull requests. Then add a title and description to your pull request that explains your contribution.
![pull_request](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/assets/pic7_create_pull.png)
* AND compare the forked branch with the main branch
![compare](https://github.com/Michelle-Lohwt/Coden.github.io/blob/branch1/assets/pic8_compare_repo.png)

---
  
Need more help?
Take a look at some resources below:
* [Forking a Repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)  
* [Cloning a Repo](https://help.github.com/en/desktop/contributing-to-projects/creating-an-issue-or-pull-request)  
* [How to create a Pull Request](https://opensource.com/article/19/7/create-pull-request-github)  
* [Getting started with Git and GitHub](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)  
* [Learn GitHub from Scratch](https://lab.github.com/githubtraining/introduction-to-github)
* [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

Admin note:
* Feel free to ask clarification from us. It always takes time to understand and learn. So, do not worry at all. We know you have got this!💪
