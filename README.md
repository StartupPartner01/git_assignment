# Git Assignment - StartupPartner01

a. What is an issue?
an issue is a feature that allows users to track and discuss problems, enhancements, tasks, or ideas related to a repository. Issues serve as a way to communicate and collaborate on specific topics within a project. 

b. What is a pull request?
A pull request (PR) is a feature in GitHub that facilitates code review and collaboration between team members or contributors on a Git repository. It's essentially a request to merge changes from one branch into another, typically from a feature branch into the main branch (such as main or master)

c. How do I open up a pull request?
On the GitHub repository page, click on the "Pull requests" tab, then click the green "New pull request" button. Select the base branch (the branch you want to merge your changes into) and the compare branch (the branch with your changes).

d. Give me a step by step guide on how to add someone to your repository.
Navigate to Repository Settings:
Go to the GitHub repository page where you want to add a collaborator.
Click on the "Settings" tab located near the top-right corner of the repository page.
Access Collaborators Settings:
In the Settings sidebar, select the "Manage access" or "Collaborators & teams" option. This will take you to the Collaborators settings page.
Add Collaborator:
In the "Collaborators" section, you'll find a field labeled "Collaborators".
Begin typing the GitHub username or email address of the person you want to add as a collaborator.
Select Collaborator:
GitHub will auto-complete the username or email address as you type. Once you see the correct user, click on their name to select them.
Invite Collaborator:
After selecting the collaborator, click on the "Add collaborator" or "Invite" button next to their name. This will send an invitation to the selected user.
Confirm Invitation (if needed):
If the collaborator is not yet a member of the repository's organization, GitHub may prompt you to confirm the invitation by entering your password or re-authenticating.
Notification Sent:
Once the invitation is sent, GitHub will notify the collaborator via email and/or GitHub notification.
Collaborator Accepts Invitation:
The collaborator will receive the invitation and can choose to accept it. They can do this by clicking on the invitation link in the email or by navigating to the repository's Collaborators settings page on GitHub.
Access Granted:
Once the collaborator accepts the invitation, they will gain access to the repository and its associated resources based on the permissions you've granted.


e. What is the difference between git and GitHub?
Git is a version control system for tracking changes in code locally. GitHub is a web-based platform providing hosting and collaboration features for Git repositories. Git operates locally, while GitHub is an online service for remote repository hosting and collaboration. Git manages version control, branching, and merging. GitHub adds features like pull requests, issue tracking, and project management on top of Git.

f. What does git diff do?

git diff is a command used to show the difference between the changes in your working directory and the staging area (if you've staged changes using git add), or between the staging area and the last commit (if you haven't staged any changes). It displays the line-by-line differences between files, highlighting additions, deletions, and modifications. This command helps you review changes before committing them and understand what modifications you've made to your code.

g. What is the main branch?

The main branch, also commonly referred to as the default branch or primary branch, is the primary line of development in a Git repository. It often serves as the baseline for the project's history and typically represents the most stable version of the codebase. In many repositories, the main branch is named either main or master.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
Pushing changes directly to the main branch is generally not recommended, especially in collaborative projects or environments where code stability and review are important.
