# Lesson 3: Fix the Readme File

We've got a bad bug that needs fixing, so I'm going to show you how to do that using the GitHub Workflow. You'll learn how to do some new things on GitHub, and afterwards we'll go over _why_ you did it that way. But for now, just follow my instructions. :smiley:

In GitHub, all our code lives in a Repository, or "repo". You can find the name of the repository that you're in at the top of the page. The name is a link that will take you to the main codebase of the repository.

![Repo Name](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/repo-name.png)

The `README.md` file is a file that sits in the main directory of a repo. It's another way we use to communicate with each other. The `README.md` file should include everything we need to get the repo running on our local computers. 

I've included the text we want in the README below. Add the text to the README file, commit it to a new branch called `readme-bugfix` (**this is very important!**), then submit a pull request for the changes.

Once you've finished this lesson, I'll create a new `learning` issue and assign it to you. You'll need to go there to learn more about why we did things this way.

---
If you need help, just @-mention me below asking for help and I'll send you a more detailed, image-based tutorial for how to do this. Again, keeping this issue open in its own tab while you do the work will make getting feedback and looking at the task list easier.


## Instructions

- Edit the README file, replacing the current text with the text below.
- [ ] Commit the file to a new branch called `readme-bugfix`.
- [ ] Create a pull request, include the text `fixes #3`.
- [ ] Once I comment with a :+1:, merge the PR.
- [ ] Delete the branch.
- Go to the main page of the repo to see your new README file in action.


COMMENT 1

```
This is the content of the README file.

* Right now this is just a blank repo.
* As we build more lessons, there will be more information in it.
* But every repo needs a README file, so this is ours.
```


USER COMMENTS W/ `HELP`

Sure thing `@user`! I wanted to push you because you'd learned the rest so quickly, but this trips everyone up the first time they try it. What you need to do is follow the instructions below.

1. Click on the repo name.  
  ![Repo Name](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/repo-name.png)
2. Click on the `README.md` file.  
  ![Readme File](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/readme-file.png)
3. Click on the edit button (it's a pencil).  
  ![Edit Icon](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/edit-icon.png)
4. Copy and paste the above text into the edit screen.  
  ![Edit Screen](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/edit-screen.png)
5. Add a commit title and message, or just use the default ones.
6. Click on the "create a new branch" button.
7. Name the branch `readme-bugfix`.  
  ![Create a New Branch](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/new-branch.png)
8. Propose the file change. This will take you to a new PR screen.
9. In the comment section of the PR, include the text `fixes #3`. This tells the PR that it is associated with this issue.
10. Create the pull request.  
  ![Create PR](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/create-pr.png)
11. Wait for the teacher to comment on your PR. 
12. Once they've given you the thumbs up, click "merge the pull request", and confirm the merge.  
  ![Merge PR](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/merge-pr.png)
13. Delete the branch.  
  ![Delete Branch](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/delete-branch.png)
14. Come back to this issue by clicking on the "#3" in the comment from earlier. This issue should be closed, because of the `fixes` tag.
15. Confirm that the issue is closed and all the boxes are checked above, then go to the Issues View and look for the new `leanring`-labeled issue I've created and assigned to you. 

Once you do, I'll tell you a bit more about _why_ we do things this way. 


USER COMMITS TO MASTER--REVERT README TO ORIGINAL STATE

Hey `@user`. I saw that you committed to `master` instead of creating a new branch. That's actually a bit of a problem, but it's OK! Everyone makes mistakes, and GitHub makes it really easy to revert them.

We try to never commit directly to `master` because that code immediately shows up to users. We want to make sure to have multiple people look at it before our users see it.

I've reverted the change to master. Follow the steps below to commit to a new branch.

4. Copy and paste the above text into the edit screen of the `README.md` file.  
  ![Edit Screen](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/edit-screen.png)
5. Add a commit title and message, or just use the default ones.
6. Click on the "**create a new branch**" button.
7. Name the branch `readme-bugfix`.  
  ![Create a New Branch](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/new-branch.png)
8. Propose the file change. This will take you to a new PR screen.
9. In the comment section of the PR, include the text `fixes #3`. This tells the PR that it is associated with this issue.
10. Create the pull request.  
  ![Create PR](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/create-pr.png)
11. Wait for the teacher to comment on your PR. 
12. Once they've given you the thumbs up, click "merge the pull request", and confirm the merge.  
  ![Merge PR](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/merge-pr.png)
13. Delete the branch.  
  ![Delete Branch](https://raw.githubusercontent.com/1point618/codename-exemplar/master/img/delete-branch.png)
14. Come back to this issue by clicking on the "#3" in the comment from earlier. This issue should be closed, because of the `fixes` tag.
15. Confirm that the issue is closed and all the boxes are checked above, then go to the Issues View and look for the new `leanring`-labeled issue I've created and assigned to you. 

Once you do, I'll tell you a bit more about _why_ we do things this way.  



USER SUBMITS PR CORRECTLY

-- make comments from `pr1_bugediting.md`


USER MERGES PR and DELETES BRANCH

Great job `@user`! That was a lot of help for us, and a lot to learn for you. Let's take a step back and learn more about what you just did. The steps you took are called **The GitHub Workflow**, and they are a very important part of how we do work on GitHub. 

In the next lesson, we're going to take a step back and learn more about the GitHub Workflow and why we use it. When you're read, go to teh new issue I just created and assigned to you called **Lesson 3: The GitHub Workflow**. You'll have the chance to read up on it, then we'll go through it again to add a new feature to our website.

CREATE ISSUE #8 from `i4_feature-flow.md`