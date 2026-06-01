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

Exercise goal: Practice the forking workflow, which is a common workflow for contributing to open source projects where you don't have write access to the original repository.


### Exercise prep

Each team assigns one person as the project owner. 

1. **Project owner**: Creates an exercise repository called `forking-workflow-exercise` by generating from a template using this template: https://github.com/tu-delft-library/recipe-book-template. To create the repository from a template, the project owner clicks on the "use the template" button on the template repository page, fills in the repository name and other details, and creates the repository. See this [link](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) for more details on how to create a repository from a template. 

**IMPORTANT**: In this case the project owner does not add collaborators to the repository. This is the point of this exercise.

2. **Project owner**: Shares the link to the newly created repository with their group. This repository will henceforth be called the `upstream repository`. 

3. **Rest of the team members**: Fork the upstream repository to their own GitHub accounts. This can be done by navigating to the upstream repository on GitHub and clicking on the "Fork" button in the top right corner of the page. This will create a copy of the upstream repository in each team member's GitHub account, which is called a "fork". Each team member will have their own forked repository that they can work on independently. Check that you can see the forked repository in your GitHub account after forking with a URL like this: `https://github.com/<your-username>/forking-workflow-exercise`

4. **Team members**: Clone your fork to your computer (`git clone <url-of-your-forked-repository>`).

4. **Project owner**: Forks the neighboring team’s project owner's repository and clones the fork to their local machine. This is to ensure that the project owner can also practice the forking workflow and experience the process from the perspective of a collaborator.

### Exercise tasks:

At this stage everyone has a forked copy of the upstream repository on their GitHub account and a local clone of their forked repository on their machine. Now we will practice contributing changes to the upstream repository using the forking workflow.

1. Open an issue in the upstream exercise repository (the original repository created by the project owner) where you describe the change you want to make, for example, add a new recipe or modify an existing one. Take note of the issue number. Make sure you open the issue in the upstream repository and not in your fork.

2. Go to your clone of your forked repository on your local machine. **IMPORTANT** make sure you are on the right clone. To check this, run `git remote -v` in your terminal and it should show the URL of your forked repository (`https://github.com/<your-username>/forking-workflow-exercise`).

3. Create a new branch for the change you want to make (`git checkout -b <branch-name> main`) where `<branch-name>` is a descriptive name for the branch, for example `add-recipe-xyz` or `fix-recipe-xyz`.

4. Make a change to the recipe book on your branch and commit the changes (`git commit -m "Your commit message"`) and in the commit message cross-reference the issue you opened. For example, if the issue number is 5, you can write in your commit message: "Fixes #5: Add recipe for XYZ". 

5. Push the branch to your fork on GitHub (`git push origin <branch-name>`). Check whether the branch is visible in your fork on GitHub.

6. Open a pull request from your branch in your fork to the main branch of the upstream exercise repository. This can be done through the GitHub web interface by navigating to your forked repository, switching to the branch you just pushed, and clicking on the "Compare & pull request" button. In the pull request description, reference the issue you opened in the upstream repository. For example, you can write: "This pull request addresses issue #5 by adding a recipe for XYZ". 

7. The project owner will merge the pull requests one be one.

8. After the project owner merges a few pull requests, your fork will be out of sync with the upstream repository. To get the latest changes from the upstream repository, you need to update your fork with the latest changes from the upstream repository. This can be done using the button `sync fork` in the GitHub web interface of your forked repository. This will ensure that your fork is up to date with the latest changes from the upstream repository.

9. After updating your fork, check that in your fork you can see changes from other people’s pull requests.


## 4. Code Reviews

Exercise goal: Working in teams. Practice reviewing code in pull requests created in the previous exercise. 
Continue working on the same repository as in the previous exercise.

### Exercise prep 
Continue working on the same repository as in the previous exercise (`forking-workflow-exercise` repository)


### Exercise tasks

1. Go to your local clone of your forked repository and create a new feature branch and one or few commits making changes to a recipe. In these commits, change something in a recipe, but also deliberately introduce a typo or a mistake which we will want to fix during the code review.

2. Push your branch to your fork on GitHub (`git push origin <branch-name>`)

3. Open a pull request from your feature branch towards the main branch of the upstream repository. In the pull request description, reference the issue you opened in the previous exercise and describe the changes you made in the pull request. For example, you can write: "This pull request addresses issue #5 by modifying the recipe for XYZ".

4. Add a reviewer to your pull request. The reviewer can be a teammate or the project owner. To do this, go to the pull request page on GitHub, click on the "Reviewers" section on the right side of the page, and select a reviewer from the list of collaborators. The reviewer will receive a notification about the pull request and can then review the changes you made.

5. As a reviewer to somebody else’s pull request, ask for an improvement and also directly suggest a change for the small typo. (Hint: suggestions are possible through the GitHub web interface, view of a pull request, “Files changed” view, after selecting some lines. Look for the “±” button.)

6. As the pull request submitter, respond to the review comments and make the necessary changes to address the comments. For the small typo, accept the suggested change directly in the GitHub web interface. For other comments, make the necessary changes in your local repository on your machine, commit the changes, and push the changes to your fork on GitHub. This will automatically update the pull request with your new commits.

7. After the reviewer approves the pull request, the project owner will merge the pull request to the main branch of the upstream repository. 


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

This exercise integrates many of the skills you have learned today and lets you practice using Github Actions to automate software tests.

For this part of the course, we use the exercise [CodeRefinery Full-cycle collaborative workflow](https://coderefinery.github.io/testing/full-cycle-ci/#). Please see details of the exercise there.


(To do: Add instructions for Step 2: Run test locally uisng pytest)


## Where to go from here

- This example was using Python but you can achieve the same automation for R or Fortran or C/C++ or other languages
- This workflow is very useful for collaborators who work on the same code and it works both for
  [centralized](https://coderefinery.github.io/git-collaborative/02-centralized/) and
  [forking](https://coderefinery.github.io/git-collaborative/03-distributed/) workflows - have a look at this
  [alternative exercise](./full-cycle-ci) to see how that works.
- GitHub Actions has a [Marketplace](https://github.com/marketplace?type=actions) which offer wide range of automatic workflows
- On GitLab use [GitLab CI](https://about.gitlab.com/product/continuous-integration/)
- For Windows builds you can also use [Appveyor](https://www.appveyor.com)
