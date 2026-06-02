## 09:00 Land - 10'
☕ Coffee/tea 

## 09:10 Installation check, housekeeping - 10'
- ✅ Roll call + 🤝 Code of Conduct
- 🖥 Did everyone install Git and have a Github account? 
- 🙋Getting help (🆘 red  ✅ green stickers)
- The concept of this course:
  - Less new tech material
  - More "bringing it together" in good practice
  - Working in groups to share experience and skills

## 09:20 Icebreaker - 5'
A short icebreaker from [resources document](https://tud365.sharepoint.com/:w:/r/sites/ResearchDataServices/Gedeelde%20documenten/Training/Research_Software_Training/lesson_plans/resources/resources.docx?d=waea671d7fc6a46d5b5c068fc19f41940&csf=1&web=1&e=f2QYgy)

## 09:25 Introduction - 20'
- Introduce the subject of collaborative development using [slides](https://tud365.sharepoint.com/:p:/r/sites/ResearchDataServices/Gedeelde%20documenten/Training/Research_Software_Training/lesson_plans/resources/Collaborative%20Software%20Development.pptx?d=w06a41ff9049e480ea180dbef81488b8c&csf=1&web=1&e=1seegV)
- Why collaborative 🤝 software development
- Review remote operations (clone / pull / push)
- Git hosting options: Github / Gitlab / Others

## 09:45 Live Demo: Setting Up - 25' 

- git config
- Test SSH key
  - ssh -T git@github.com 
- Install SSH key
  - ssh-keygen -t ed25519 -C [email address]
  - No passphrase
  - cat ~/.ssh/id_ed25519.pub
  - Install in github
  - Test again
- ~~Publish local repo to github~~
  - ~~Create local repo in candidates' location of choice~~
- Explore Github GUI
- Create initial repo on github from recipe book template  
- Clone to local
- Collaborating

## 10:10 Break - 10'

## 10:20 Presentation - Collaborative Software Projects - 10'


Present from [slides](https://tud365.sharepoint.com/:p:/r/sites/ResearchDataServices/_layouts/15/Doc2.aspx?action=edit&sourcedoc=%7B06a41ff9-049e-480e-a180-dbef81488b8c%7D&wdOrigin=TEAMS-MAGLEV.teamsSdk_ns.rwc&wdExp=TEAMS-TREATMENT&wdhostclicktime=1774444252296&web=1)

- Software Development lifecycle
- Collaborative software development
- Open vs closed collaboration
- Considerations in open collaboration for RSE
- When does collaborative development make sense?
- Roles and Responsibilities in the team

## 10:30 Live Demo: Github issues and branching - 10'
- Add collaborators (i.e. co-trainer) to demo repository in github
- Create issues - participant teams create in the cloned template repo from earlier
  - Navigate to repo in github
  - Click on 'Issues'
  - Click 'New Issue' and follow workflow
- Explain workflow possibilities:
    - **Branching**
    - **Forking**

## 11:40 Exercise 1: Branching Workflow - 20'


Exercise 1: [Branching Workflow](../material_for_participants/exercises.md)

Exercise in which participants:

- Assign team roles
- Create a repository from a template
- Clonee the repository
- Assign issues to themselves for changes
- Make changes locally
- Commit and push changes to github

## 11:10 Break - 10'

## 11:20 Live Demo: Pull Requests - 10'
Explain pull requests and demonstrate the workflow around creating, reviewing and merging

## 11:30 Exercise 2: Pull Requests - 15'

Exercise 2: [Pull Requests](../material_for_participants/exercises.md)

Exercise in which participants:

- Create pull requests for the issues above
- Merge the PRs, resolving any conflicts that emerge

## 11:45 Live Demo: Forking Workflow - 40'

- Motivation and learning goals [2 min]
   - Scenario: When you don't have permissions to push to the original repository, or when you want to contribute to a project without being a collaborator

- [Demo] Failed push to a repository to explain why forking is necessary in some cases [5 min]
    - [Preparation] The co-instructor creates a repository named `forking-workflow-demo` using the [recipe-book template](https://github.com/tu-delft-library/recipe-book-template) and does not add the lead instructor as a collaborator. To create the repository from a template, the co-instructor clicks on the "use the template" button on the template repository page, fills in the repository name and other details, and creates the repository. See this [link](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) for more details on how to create a repository from a template. 
    - The co-instructor then shares the link to the newly created repository with the lead instructor. 
    - The lead instructor wishes to contribute a new recipe, so they clone the repository to their local machine, creates a new branch, adds the new recipe, commits the changes, and tries to push the changes to the original repository on GitHub. However, since the lead instructor does not have write access to the original repository, the push is rejected by GitHub.
    - The lead instructor then explains why the push was rejected and introduces the concept of forking as a solution to this problem.

- [Demo] Forking workflow demo [15 min]
    - The lead instructor demonstrates the forking workflow by forking the `forking-workflow-demo` repository from the previous step to their own GitHub account, cloning the forked repository to their local machine, creating a new branch, adding a new recipe, committing and pushing the changes to their fork on GitHub, and then creating a pull request from their branch in their fork to the main branch of the upstream `forking-workflow-demo` repository. 
    - The lead instructor then explains each step of the process and highlights important concepts such as upstream repository, remote, origin, fork, and pull request.

- [Slides] Explain clone vs fork and forking workflow [10 min]
    - Terminlogies: Upstream repository, remote, origin, fork, pull request  

- Summarize forking workflow [3 min]

- Q&A [5 min]

- Explain exercise goals [5 min]
    - Explain generating from template (like a cookiecutter) to create a new repository for the exercise. 
    

## 12:20 Exercise 3: Forking Workflow - 25'

Exercise 3: [Forking Workflow](../material_for_participants/exercises.md#3-forking-workflow)

## 12:45 Lunch - 60'

## 13:45 Q&A Forking workflow and summary - 10'

- When should you use the forking workflow vs the branching workflow?
- Questions? 

## 13:55 Code Reviews - 5'

- Why Code Reviews?
    - Sharing knowledge
    - Spreading ownership
    - Unifying development practices
    - Quality control
- Best Practices:
    - Do
        - Give constructive feedback
        - Communicate clearly
    - Don't
        - Make huge, omnibus PRs
        - Spend time won what you can automate
        - Be hostile to individuals


## 14:00 Live Demo: Code Reviews - 10'

[Preparation]
- Lead instructor creates a new repository named `code-review-demo` using the recipe book template as per the instructions for the code review exercise. 
- The co-instructor forks [this repository](https://github.com/niketagrawal/demo-code-review) and clones the fork to their local machine.
- The co-instructor follows the steps mentioned in the [code review exercise](../material_for_participants/exercises.md#4-code-reviews): creates a new branch, makes changes to the recipe book, commits and pushes the changes to their fork and creates a pull request from their branch in their fork to the main branch of the upstream `code-review-demo` repository. 

[Demo] The lead instructor reviews the pull request, providing feedback and requesting changes. The co-instructor makes the requested changes, pushes them to their fork, and the lead instructor merges the pull request.

- Explain exercise goals and instructions


## 14:10 Exercise 4: Code Reviews - 20'

Exercise 4: [Code Reviews](../material_for_participants/exercises.md#4-code-reviews)


## 14:30 Break - 10'


## 14:40 Presentation: CONTRIBUTING document - 10'

Discussion:
- Why contributing guidelines matter
- How they can help insure consistency, quality and easy review workflows
- The main components of a contributing guideline and adapting them depending on the project
  - What kinds of contribution are welcome?
  - Who may contribute?
  - How to fit into the community of contributors?
  - How to report bugs?
  - How to suggest features?
  - How to document
  - Relevant standards
- Why contributors should follow guidelines
  - Conssitency
  - Collegiality
  - Process and product quality

## 14:50 Exercise 5: Guidelines for Contributors - 10'

Exercise 5: [Guidelines for Contributors](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L4-ex03.html)

1. Working individually, use the CONTRIBUTING.md template provided in [manuGil/fair-code](https://github.com/manuGil/fair-code) to add contributing guidelines to the repository used for individual exercises.
2. Adapt the template to your repository as long as time allows it.

## 15:00 Presentation: Software Licenses and Software Citation - 20'

Explain and discuss the importance of software licenses and software citation for software.

Copyright inheres in creative work automatically. IP created in the course of our work belongs to the employer (except ... see TU Delft policy below). Copyrighted material may not be reproduced without permission.

*So* if you don't apply a license to your code, nobody else may use or adapt it. And you may not use or adapt any other matrial without a license.

### Open Source Licenses
- Importance of OS licenses in context of FAIR
- Permissive (MIT, Apache, BSD) vs copyleft (GPL) licenses
- If no license specified, cannot use
- Why software, data & digital content are different (eg why you don't use CC licenses for software)
- TU Delft research software policy and guidelines

### Software Citation
Explain how citations files are used to provide information about the software and its authors, and how they can be used to generate citations in different formats. In GitHub, for example, the citation file is called CITATION.cff citation file can be used to generate citations in different formats, such as BibTeX, APA, and MLA.

Provide a demo on how to create .cff files using this [CFFInit Tool](https://citation-file-format.github.io/cff-initializer-javascript/)

## 15:20 Exercise 6: Choosing Licenses and Enabling Software Citation - 15'

Exercise 4.4: [Choosing Licenses and Enabling Software Citation](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L4-ex04.html)

1. Use the Open Source Initiative license tool to pick an open source license of your choice: https://opensource.org/licenses
2. Add a LICENSE file to your remote repository. Check the [GitHub documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) to know how to add a license file. If you have to, edit the license file to include auhtors name, year, etc.
3. Use this tool to generate a CITATION file and add it to your remote repository:
    - Search the Internet for: cffinit

## 15:35 Break 10'


## 15:45 Presentation: Automated Testing - 45'

Note: Content of this demo and the exercise is based on the [Code Refinery's Automated Testing lesson](https://coderefinery.github.io/testing/continuous-integration/), adapted to fit the context of this workshop.

- Introduction [2 min]
    - So far we learned how to collaborate on software development projects productively and efficiently. Despite following good practices for collaborating in software development, it is still possible to accidentally introduce bugs while developing software collaboratively. This is where automated testing can help us.

- [Demo] Motivation and looking together at an automated testing workflow in action [15 min]
    - Where does automated testing fit in the collaborative software dev workflow?
        -  Instructor answers this question by showing how automated testing setup in the exercise repository is implemented and how it works. 
    - Show what we are working towards and how are we going to get there?
        - The recipe-book respotory implementes a automated test that checks if the recipe files have Ingredients and Instructions sections. The instructor shows how this test is implemented, where the .yml file that defines the automated testing workflow is located, and how the test is run automatically when a pull request is created.   
        - Show green tick symbol in exercise repo and make commits to fail and then pass the tests to show how it works in practice.
        - Break down concepts: Automated testing = Testing + automation
        - Building blocks: test (check_recipes.py), .yml file, putting it all together

- Introduction to testing [5 min]
    - Experimental scientist and instrument calibration analogy for software tests (Source: [Code Refinery testing lesson](https://coderefinery.github.io/testing/motivation/#untested-software-can-be-compared-to-uncalibrated-detectors))
    - Questions to participants about their experience with testing
        - Where would you start adding a test in an existing project?
        - How and when do you test?

- [Demo] Examples of tests [15 min]
    - Instructor shows two examples on how to write tests: adding two numbers, farenheit to celsius converter (sourced from Code Refinery testing lesson). This is a demo, not a type along. The instructor needs a working python setup on their computer, and prepares the files for this demo using the examples mentioned in the Code Refinery testing lesson https://coderefinery.github.io/testing/motivation/. We cover two examples here: adding two numbers (basic example) and converting farenheit to celsius (asserting floating point numbers)
    - Explain the structure of a test, how to run tests locally, and how to interpret the results. 
    - Briefly mention pure and impure functions and how testing impure functions can be more complex. We do not go into details of test design for different types of fucntions. 
    - Refer learners to the testing section of resources.md for more examples of tests for impure functions. It is not in the scope of this course to go into details of test design for various types of functions, but the goal is to give participants a sense of what tests look like, how they can be used to check the correctness of code, and how does automated testing fits in the collaborative software development workflow. 
    - Running tests locally using pytest
        - Create a python virtual environment using venv or conda, activate it, and install pytest using pip. Then run the tests using the command `pytest` in the terminal.
        - Modifying code to make tests fail and then fixing the code to make the tests pass again

- Explain exercise goals and instructions [5 min]

- Q&A [5 min]

## 16:20 Exercise 7: Implementing Continuous Integration - 35'

Exercise 5: [Implementing Continuous Integration](../material_for_participants/exercises.md#5-implementing-continuous-integration)


## 16:55 Summary and Key Points / Q&A - 15'

- Branching workflow or forking workflow?
- Code reviews, roles, and responsibilites
- Automated testing 

Where to go from here?
- Check resources.md for more code examples, reading material, and inspiration on the topcis covered in this course.
- Explore GitHub respositories of your favorite open source software projects to see how they implement collaborative software development, code reviews, contributing guidelines, and automated testing. You can learn a lot from just reading the commit messages, pull request description and how other review code, and their CI setup.
- DCC open office hours: If you have any questions related to implementing the concepts taught in this course in your projects, you are welcome to attend the open office hours where you can discuss your questions with me or one of my colleagues. See this link for more information and for making an appointment https://www.tudelft.nl/digital-competence-centre/services/code-data-office-hours


## 17:10 Feedback - 5'


## 17:15 End