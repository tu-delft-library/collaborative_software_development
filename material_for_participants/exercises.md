# Exercises

Some exercises to practice our skills through the day:
## 1. Clone a repository and make a contribution

Please perform the following tasks individually.

1. Clone the Check-in repository via SSH.
1. Make a copy of the file `check-in/template.md` in the same directory; give it an anonymous name, ex. `<name-initials><3-last-digits-phone>.md`
1. Open your copy of `template.md` and add something to the lists in the file.
1. Commit your changes, and push them to the remote repository. You might experience difficulties doing that, follow the suggestions given by Git.
1. Reflect on the difficulties you faced, and how we might avoid them.

💡 Tip: 

While completing this exercise, Git may warn you that you have to pull changes before pushing your contribution. 
This is expected and is part of the reason for what we will learn *next* in the class, but please do ask for help if you need it.

## 2. Roles and Responsibilities 

Please perform the following tasks.

1. Make teams of 3 or 4 people. You will work together during group exercises.
2. Assign roles and responsibilities to each member; your team should have:
    - One project owner
    - One administrator
    - One or more collaborators. Project owners and administrators can also be collaborators.
    - Zero or more reviewers. Collaborators can also be reviewers.
3. Choose a name for the team.

## 3. Branching workflow

As a Team, work on the following coding taks using a **branching** workflow.

1. [Administrator] Creates a repository using [this template](https://github.com/the-magnificents/collab-branching)
2. [Administrator] Invites all team members to the team's repository as collaborators.
3. [Team] Read the `TODO.md` file and each member choses one task for the next step.
4. [Collaborator] each member opens an issue for the chosen task.
5. [Collaborator] each member uses the branching model to complete the chosen task.
6. [Collaborator] each member commits and pushs changes to the team's repository.

## 4. Pull Requests

Working as a team, merge the changes made in the previous exercise into the main branch of the team’s repository.

1. [Collaborators] create a pull request for their own branch. Give your pull request a meaning name, and a short and clear description.
2. Are there any conflicts? Resolve them using the GitHuB GUI. Ask for help if you need to.
3. [Collaborators] Merge the pull request to the main branch using the method of their choice.
4. [Collaborators] Check the main branch to confirm that your changes have been merged.

## 5. Forking Workflow

This exercise is based on the [Code Refinery's forking workflow exercise](https://coderefinery.github.io/git-collaborative/forking-workflow/#exercise))

#### Exercise prep
Maintainer (team lead):

- Create an exercise repository called forking-workflow-exercise by generating from a template using this template: https://github.com/tu-delft-library/recipe-book-template 

- In this case we do not add collaborators to the repository (this is the point of this exercise).

- Share the link to the newly created repository with your group.

Learners in exercise team: Fork the newly created repository (the one created by the maintainer) and then clone your fork. 

#### Exercise tasks:

    - Open an issue in the upstream exercise repository where you describe the change you want to make. Take note of the issue number.
    - Clone your fork of the repository to your local machine (if you haven’t already).
    - Create a new branch in your local repository for the change you want to make. Name the branch something descriptive of the change you are making.
    - Make a change to the recipe book on the new branch and in the commit cross-reference the issue you opened. 
    - Push the branch to your fork on GitHub.
    - Open a pull request from your branch in your fork to the main branch of the upstream exercise repository. In the pull request description, reference the issue you opened in the upstream repository.
    - Team leaders will merge the pull requests. For individual participants, the instructors and workshop organizers will review and merge the pull requests. During the review, pay attention to the automated test step (here for demonstration purposes, we test whether the recipe contains an ingredients and an instructions sections).
    - After few pull requests are merged, update your fork with the changes.
    - Check that in your fork you can see changes from other people’s pull requests.

## 6. Code Reviews

Working in teams. Practice reviewing code in pull requests created in the previous exercise. Names between `[]` indicate who in the team should engage in each activity.

1. [Author] Assign one or two team members as reviewers in your pull request (PR).
2. [Reviewer] Reviews, discuss, and  suggest changes the pull request(s) following recommendation mentioned so far.
3. [Author] Make changes to PR based on the reviewer(s) suggestions, and updates the PR.
4. [Reviewer] Approves the PR.
5. [Author] Merges the PR into the repository after being approved for at least one reviewer.

## 7. Guidelines for Contributions

1. Working individually, use the `CONTRIBUTING.md` template provided in https://github.com/manuGil/fair-code to add **contributing guidelines** to the very repository used in Lessons 1 and 2. 
2. Adapt the template to your repository as long as time allow it.

## 8. Choosing Licenses and Enabling Software Citation

Working individually. Add a license and citation files to the repository used in Lesson 1 and 2.
1. Use the Open Source Initiative license tool to pick an open source license of your choice: https://opensource.org/licenses
2. Add a `LICENSE` file to your remote repository. Check the [GitHub documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) to know how to add a license file. If you have to, edit the license file to include auhtors name, year, etc.
3. Use this tool to generate a CITATION  file and add it to your remote repository: 
    - Search the Internet for: `cffinit` 

## 9. Full-cycle collaborative workflow

***TBD based on Coderefinery lesson***