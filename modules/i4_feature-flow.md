BOT CREATES THIS LESSON, gives is learning label, and assigns to user, once they've completed the bugfix lesson.

#Lesson 3: The GitHub Workflow

Let's dig into the GitHub Workflow so that you can help us add a feature to our website. This will give you both a conceptual understanding of how GitHub works, as well as experience using the GitHub Workflow with a team.

To start off, [open this link in a new tab](https://guides.github.com/introduction/flow/) to read up on the GitHub Workflow. Pay special attention to the sections on Branches, Commits, and Pull Requests. We're using the Branching workflow, so don't worry about the references to the Forking workflow.

Now that you've read it, did some of it seem familiar? When fixing the bug, you did all these steps, although they were crammed together. You created a branch and committed to it at the same time, you went directly to creating a pull request, then I commented on the PR, and you merged it successfully. We didn't need to deploy it to production, because I could view the README right on GitHub, which is what I did to verify that what you'd done was correct.

The flow we went through, creating a branch and committing to it at the same time, really only works for small fixes that you want to merge right away. For longer projects where we'll have multiple commits, we'll want to create a new branch first, then commit the various files to that branch.

Enough talk, let's get started! Go to the Issue View and assign yourself the Issue called **Users should be able to email us if they want to get in touch**. In that Issue, we'll discuss the work that needs to get done in order to get the new feature up and running.

This issue will stay here as a repository for everything you've learned so far. You can go through the comments below to find resources on Issues, Commits, Branches, and more. Go ahead and leave it open or close it, it's up to you—either way you'll be able to come back to it to review the work you've done.


COMMENT 1

# Issues

Issues are one of the primary ways people communicate on GitHub. An issue can represent a bug, a feature, a discussion, or anything else. 

Issues can be assigned to users so everyone knows who is responsible for that issue.

Issues can be labeled. This lets you see what each issue pertains to. It also lets you quickly search through the issues by label.

You can use [markdown](https://help.github.com/articles/markdown-basics/) to format issues to make them easier to read.

To learn more about issues, [go here](https://guides.github.com/features/issues/).


COMMENT 2

# Branches

Branching is an essential part of the way that we work on GitHub. Rather than having everyone write code to the same place, we create branches for each piece of work, commit code there, then merge them into the main branch once they're done.

Branches should have descriptive names so that you know what work is getting done on which branch. By convention, the main branch is usually called `master` on GitHub projects. When you see people talking about master, they're just talking about a specific branch. 


COMMENT 3

# Commits

A commit is a saved chunk of work. You can only save one file per a commit when using the GitHub Web Interface, but a commit may have multiple or even partial files when using other Git interfaces. 

When saving a commit, you should include a commit message. This is a description of the work that you did so that if others want to look at it, they can more easily figure out what changed.


COMMENT 4

# Pull Requests

A Pull Request is how you communicate about wanting to merge a branch into the main branch. Once you've made the commits you need to a branch, you create a Pull Request (or PR as most people call it) to compare it to the master branch. By convention, you should wait for at least one other person to give you a thumbs up and permission to merge it. Then you should merge it yourself so that if anything isn't working right, you're there to fix it. 

Pull Requests allow comments just like Issues do. You can also associate a PR with a specific Issue to make it easy to jump back and forth between the two. Often a PR is created in response to a specific Issue. 

Pull Requests also allow you to look at all the commits that are a part of that PR, and to make comments inline on the files that were changed. This is a great way to offer specific feedback on the new code, or to ask questions about the implementation. There is no ambiguity about what you're asking about or recommending.

Finally, you can continue to make commits to the branch that is associated with the PR while it is open, and it will update that PR. Because of this, sometimes teams will open PRs very early in the development process, so that they can communicate with each other while they work on the branch. Others will wait until they think the code is finished, so the PR is about making sure there are no bugs left to squash. Either way is a valid way of working.

For a tutorial on how to create and use PRs to their full effect, [go here](https://help.github.com/articles/using-pull-requests/).