# Script for v0.1 of the new project.

## Project set-up. 
We need a repo that looks like [this](https://github.com/1point618/exemplar-project/).

* Create 6 new issues.
* Create 2 new labels: "learning" (gold) and "feature" (light green). 
* Label the issues with learning or feature as necessary.

* Stuff not in the current repo but needed:
* Create a new branch w/ new content on that branch.
* Create a PR for that branch into master.

## Things the bot needs to be able to do while interacting with the user:
* Make comments on issues created by the project set-up.
* Make comments on issues created by the bot after set-up.
* Make comments on issues and PRs created by the USER.
* Update issues and comments to new text.
* Revert a commit made to master.
* Assign an issue to the user.
* Create a new issue.
* Assign a label to an issue.

## Things we need to be able to verify:
* The text in a user-comment (keyword search?).
* Whether the bot was @-mentioned in a comment / PR.
* The label assigned to an issue.
* The label assigned to multiple issues.
* The user assigned to an issue.
* The text of a PR.
* Which branch a commit was made to.
* A label was assigned to the wrong issue(s).
* An issue was assigned the wrong label.
* A user was assigned to the wrong issue.
* A group of actions were all completed (regardless of order).


## Lesson 1: Using Issues to Communicate

Hi @user! Welcome to the team.

I'm Brienne, your new manager. Today I'll be onboarding you to GitHub. GitHub is where we manage our projects and store our code and content. You'll be up and running in no time.

This is an issue, which we use to communicate about the project on GitHub. To get started, type a comment below. @-mention me by typing the `@` symbol followed by my user name so I get pinged when you do.


```
### USER Makes a comment w/ @mention
### Bot posts this comment below:
```
Great job! @-mentions are used to tag people into converations so that they know you're talking about them and want their input. A person will receive a notification when you @-mention them.

Now, on the right, assign this issue to yourself and label it with the gold `learning` label. I'll keep track of your progress in this comment. If you're not sure if you did it right, just check here to see if I checked the box or not.

- [ ] Assign self.
- [ ] Add `learning` label.

```
### USER assigns self to issue
### Bot updates above comment to include check mark.
```

```
### User adds the learning label
### Bot updates the comment to include check mark.
```

```
### USER has performed both actions
### Bot adds the following comment in-line.
```
Great job @user!

We use issues for all sorts of communications, including reporting bugs, requestiong new features, open-ended discussions about our site, and tracking the development of the site. An issue can be assigned to someone so that they know that they "own" the issue and the work that it will take to complete it. We label issues so that we can more easily search through them. You can also use [markdown](https://help.github.com/articles/markdown-basics/) to format issues—that's how I made those sweet check boxes and that link. 

There's one more thing to learn about Issues, then we can move on. Close this issue below, then click on the "Issues" icon to the right, then go to the other issues named **Lesson 2: Managing Issues**. 

```
### USER has closed issue.
### Bot assigns Issue #2 to user.
```

## Lesson 2: Managing Issues

Great job so far. You weren't lying about being a fast learner in your interviews, were you? :wink:

Next, we're going to have you perform some batch actions on issues. I'll keep track of them here, and you'll be able to see your progress from within the Issues view, just look next to the title of this Issue.

## Progress

- [x] Look at Issue View
- [ ] From the Issue View, assign the green label `feature` to all the unlabeled issues.
- [ ] Assign the issue with both the red `bug` and gold `learning` label to yourself. 

---

If you get stuck on any of these tasks, the [Mastering Issues GitHub Guide](https://guides.github.com/features/issues/) should have all the info you need to collect them. You can also come back here, and I'll give you feedback on what you've done so far. 

Once the status bar hits 100%, go ahead and close this Issue like you did the last one, and then click through to the bug Issue that you assigned to yourself.

```
### USER ONLY ASSIGNS SOME ISSUES W/ FEATURE LABEL
### Bot comments:
```
Hey @user, looks like you didn't assign all the unlabeled issues like I asked. If you use the check boxes in the Issues View, you can assign multiple issues with the same label at the same time. I'd recommend doing it that way.

```
### USER ASSIGNS Label to the wrong issue.
### Bot comments:
```
Hey @user, make sure you add the label to the right issues.

```
### USER ASSIGNS THE WRONG LABEL
### Bot comments:
```
Hey @user, make sure you assign those issues with the `feature` label. I've removed the label you assigned, try it again.

```
### USER ASSIGNS WRONG ISSUE
### Bot comments:
```
Hey @user, make sure to assign the issue with both the `bug` and `learning` labels to yourself. It's the one called "Fix the readme file".

```
### USER assigns the labels correctly
### Bot updates OP to include check box.
```

```
### USER assigns self to the correct issue
### Bot updates OP to include check box.
```

```
### USER completes both tasks.
### Bot comments:
```
Great job @user! Now close this issue and go to the Bug issue that you just assigned to yourself.


## Fix the Readme File

The readme.md file is a file that sits in the main directory of a repo. It's another way we use to communicate with each other. The readme.md file should include everything we need to get the repo running on our local computers. 

I've included the text we want in the readme below. Add the text, commit it to a new branch (**this is very important!**), then submit a pull request for the changes.

## Progress

- [ ] Edit readme file w/ correct stuff.
- [ ] Commit the file to a new branch called "readme-bugfix".
- [ ] Create a pull request, include the text `fixes #3`.
- [ ] Once they comment w/ a :+1:, merge the PR.
- [ ] Delete the branch.

---

Once you've finished this lesson, I'll create a new `learning` issue and assign it to you, you'll need to go there to learn more.

If you need help, just @-mention me below asking for help and I'll send you a more detailed tutorial for how to do this. 

```
Set-up has already commented:
```

## COMMENT 1

```
This is the content of the readme file.

It should be markdown.

* Expose the students to markdown.
* They'll learn what it is later.
```

```
### USER COMMENTS W/ `HELP`, `Tell me more`, etc
### Bot comments:
```

Sure thing @user! I wanted to push you because you'd learned the rest so quickly, but this trips everyone up the first time they try it. What you need to do is follow the instructions below.

1. Click on the repo name.
2. Click on the readme.md file.
3. Click on the edit button (it's a pencil).
4. Copy and paste the above text into the edit screen.
5. Add a commit title and message, or just use the default ones.
6. Click on the "create a new branch" button.
7. Name the branch `readme-bugfix`.
8. Propose the file change. This will take you to a new PR screen.
9. In the comment section of the PR, include the text `fixes #3`. This tells the PR that it is associated with this issue.
10. Create the pull request.
11. Wiat for the teacher to comment on your PR. 
12. Once they've given you the thumbs up, click "merge the pull request", and confirm the merge.
13. Delete the branch.``
14. Come back to this issue. It should be closed, because of the `fixes` tag.

Once you do, I'll tell you a bit more about _why_ we do things this way. It's called the GitHub Workflow and it's a pretty important part of how we work.

```
### USER edits readme and commits to new branch
### Bot updates first two check boxes.
```

```
### USER commits to master
### Bot reverts commit
### Bot comments:
```
It's really important not to commit to master, but to create a new branch when you commit. Otherwise you might over-write production code. I'll revert that commit and we'll try gain from the beginning. Make sure to commit to a branch this time.

```
### USER commits to a branch named something other than readme-bugfix
### Bot comments
```
You named the branch something other than what we wanted, but we'll just move forward with that for now.

```
### USER creates new PR including message w/ `fixes #3`
### Bot comments ON THAT PR
```
Looks good @user! :+1:

```
### USER doesn't include `fixes` tag.
### Bot comments ON PR + on issue
```
Hey, don't forget to include `fixes #3` in the comments of the PR. Go ahead and create a comments saying that so that it connects the right comment to the right PR.

```
### USER merges the PR
### Bot updates check box
```

```
### USER deletes branch
### Bot updates check box
```

```
### USER completes all tasks
### Bot creates a new issue w/ specific label, assignee, and text.
```