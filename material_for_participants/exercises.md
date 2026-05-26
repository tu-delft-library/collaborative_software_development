# Exercises

Some exercises to practice our skills through the day:

## 1. Branching workflow

As a Team, work on the following coding taks using a **branching** workflow.

#### Exercise prep

- In your team of 3 - 5 people, assign roles and responsibilities to each member:
   - One project owner
   - One administrator
   - One or more collaborators. Project owners and administrators can also be collaborators.
   - Zero or more reviewers. Collaborators can also be reviewers.
 - [Administrator] Create an exercise repository called branching-workflow-exercise by generating from a template using this template: https://github.com/tu-delft-library/recipe-book-template 
 - [Administrator] Invite all team members to the team's repository as collaborators.
 - Share the link to the newly created repository with your group.

#### Exercise tasks [All Team Members]:

    - Clone the repository to your local machine (if you haven’t already).
    - Choose a recipe you would like to change.
    - Open an issue on github for the change you would like to make.
    - Create a new branch in your local repository for the change you want to make. Name the branch something descriptive of the change you are making.
    - Make a change to the recipe book on the new branch and in the commit cross-reference the issue you opened. 
    - Push the branch to GitHub.


## 2. Pull Requests

Working as a team, merge the changes made in the previous exercise into the main branch of the team’s repository.

#### Exercise tasks

1. [Collaborators] Create a pull request for your own branch. Give your pull request a meaningful name, and a short and clear description that references the issue you raised in the previous exercise.
2. [Team] Are there any conflicts? Resolve them using the GitHuB GUI. Ask for help if you need to.
3. [Collaborators] Merge the pull request to the main branch using the method of their choice.
4. [Collaborators] Check the main branch to confirm that your changes have been merged.

## 3. Forking Workflow

This exercise is based on the [Code Refinery's forking workflow exercise](https://coderefinery.github.io/git-collaborative/forking-workflow/#exercise)

#### Exercise prep

1. **The maintainer**: Creates an exercise repository called `forking-workflow-exercise` by generating from a template using this template: https://github.com/tu-delft-library/recipe-book-template 

In this case we do not add collaborators to the repository (this is the point of this exercise).

2. **The maintainer**: Shares the link to the newly created repository with your group.

3. **Learners in exercise team**: Fork the newly created repository (the one created by the maintainer) and then clone your fork. 

4. **The maintainer**: Forks the neighboring team’s repository and clones the fork to their local machine. This is to ensure that the maintainer can also practice the forking workflow and experience the process from the perspective of a contributor.


#### Exercise tasks:

1. Open an issue in the upstream exercise repository where you describe the change you want to make. Take note of the issue number.

2. Clone your fork of the repository to your local machine (if you haven’t already).

3. Create a new branch in your local repository for the change you want to make. Name the branch something descriptive of the change you are making.

4. Make a change to the recipe book on the new branch and in the commit cross-reference the issue you opened.

5. Push the branch to your fork on GitHub.

6. Open a pull request from your branch in your fork to the main branch of the upstream exercise repository. In the pull request description, reference the issue you opened in the upstream repository.

7. Team leaders will merge the pull requests. (Check this: During the review, pay attention to the automated test step (here for demonstration purposes, we test whether the recipe contains an ingredients and an instructions sections).

8. After few pull requests are merged, update your fork with the changes.

9. Check that in your fork you can see changes from other people’s pull requests.


## 4. Code Reviews

Working in teams. Practice reviewing code in pull requests created in the previous exercise. Names between `[]` indicate who in the team should engage in each activity.

1. [Author] Assign one or two team members as reviewers in your pull request (PR).
2. [Reviewer] Reviews, discuss, and  suggest changes the pull request(s) following recommendation mentioned so far.
3. [Author] Make changes to PR based on the reviewer(s) suggestions, and updates the PR.
4. [Reviewer] Approves the PR.
5. [Author] Merges the PR into the repository after being approved for at least one reviewer.

## 5. Guidelines for Contributions

1. Working individually, use the `CONTRIBUTING.md` template provided in https://github.com/manuGil/fair-code to add **contributing guidelines** to the very repository used in Lessons 1 and 2. 
2. Adapt the template to your repository as long as time allow it.

## 6. Choosing Licenses and Enabling Software Citation

Working individually. Add a license and citation files to the repository used in Lesson 1 and 2.
1. Use the Open Source Initiative license tool to pick an open source license of your choice: https://opensource.org/licenses
2. Add a `LICENSE` file to your remote repository. Check the [GitHub documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) to know how to add a license file. If you have to, edit the license file to include auhtors name, year, etc.
3. Use this tool to generate a CITATION  file and add it to your remote repository: 
    - Search the Internet for: `cffinit` 

    ## 7. Full-cycle collaborative workflow

    ***TBD based on Coderefinery lesson***