## 09:00 Land - 10'
☕ Coffee/tea 

## 09:10 Installation check, housekeeping - 10'
- ✅ Roll call + 🤝 Code of Conduct
- 🖥 Did everyone install Git and have a Github account? 
- 🙋Getting help (🆘 red  ✅ green stickers)

## 09:20 Icebreaker - 5'
A short icebreaker from [resources document](https://tud365.sharepoint.com/:w:/r/sites/ResearchDataServices/Gedeelde%20documenten/Training/Research_Software_Training/lesson_plans/resources/resources.docx?d=waea671d7fc6a46d5b5c068fc19f41940&csf=1&web=1&e=f2QYgy)

## 09:25 🎦 Introduction - 20'
- 🎦 Introduce the subject of collaborative development using [slides](https://tud365.sharepoint.com/:p:/r/sites/ResearchDataServices/Gedeelde%20documenten/Training/Research_Software_Training/lesson_plans/resources/Collaborative%20Software%20Development.pptx?d=w06a41ff9049e480ea180dbef81488b8c&csf=1&web=1&e=1seegV)
- Why collaborative 🤝 software development
- Review remote operations (clone / pull / push)
- Git hosting options: Github / Gitlab / Others

## 09:45 Live Demo: Setting Up - 25'
- Install SSH key
- Publish local repo to github
  - Create local repo in candidates' location of choice
- Explore Github GUI
- Collaborating

## 10:10 💪 Exercise - 10'

[//]: # (TODO refine choice about template repo)

Exercise 3.1: [Clone a repository and make a contribution](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L3-ex01.html)
- Excessive commit concurrency
- pull-then-push workflow
- Why we want to use a branching workflow

## 10:20 Break - 10'

## 10:30 🎦 Presentation - Collaborative Software Projects - 10'

[//]: # (TODO slides)

Present from [slides](https://tud365.sharepoint.com/:p:/r/sites/ResearchDataServices/_layouts/15/Doc2.aspx?action=edit&sourcedoc=%7B06a41ff9-049e-480e-a180-dbef81488b8c%7D&wdOrigin=TEAMS-MAGLEV.teamsSdk_ns.rwc&wdExp=TEAMS-TREATMENT&wdhostclicktime=1774444252296&web=1)

- Software Development lifecycle
- Collaborative software development
- Open vs closed collaboration
- Considerations in open collaboration for RSE
- When does collaborative development make sense?

## 10:40 💪 Exercise - Roles and Responsibilities - 15'

[//]: # (I don't think this will take 15')

Exercise 3.2: [Roles and Responsibilities](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L3-ex02.html)
- Set up a team with
    - Owner
    - Administrator
    - Collaborator(s) (1+ May include owner & admin)
    - Reviewer(s) (0+ May include collaborators)
- Name the team

## 10:55 Live Demo: Github issues and branching - 10'
- Create issues - participant teams create in the cloned template repo from earlier
- Explain workflow possibilities:
    - **Branching**
    - **Forking**

## 11:05 💪 Exercise: Branching Workflow - 20'

[//]: # (Consider a new template repo - probaby not necessary here)

Exercise 3.3: [Branching Workflow](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L3-ex03.html)

1. [Administrator] Creates a repository using [this template](https://github.com/the-magnificents/collab-branching).
2. Administrator] Invites all team members to the team’s repository as collaborators.
3. [Team] Read the TODO.md file and each member choses one task for the next step.
4. [Collaborator] each member opens an issue for the chosen task.
5. [Collaborator] each member uses the branching model to complete the chosen task.
6. [Collaborator] each member commits and pushs changes to the team’s repository.

## 11:25 Break - 10'

## 11:35 Live Demo: Pull Requests - 10'
Explain pull requests and demonstrate the workflow around creating, reviewing and merging

## 11:45 💪 Exercise: Pull Requests - 15'

Exercise 3.4: [Pull Requests](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L3-ex04.html)

1. [Collaborators] create a pull request for their own branch. Give your pull request a meaning name, and a short and clear description.
2. Are there any conflicts? Resolve them using the GitHuB GUI. Ask for help if you need to.
3. [Collaborators] Merge the pull request to the main branch using the method of their choice.
4. [Collaborators] Check the main branch to confirm that your changes have been merged.

## 12:00 Live Demo: Forking Workflow - 10'

[//]: # (TODO: some visual aids would probably help here!!)

Explain a forking strategy and demonstrate the workflow around forking, cloning, pushing and upstream pull requests

## 12:10 💪 Exercise: Forking Workflow - 20'

Exercise 3.5: [Forking Workflow](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L3-ex05.html)

Working in teams, apply FAIR principles to a Git repository using a [FAIR software checklist](https://tu-delft-dcc.github.io/docs/software/fair_software/checklist.html).

1. [Administrator] creates a repository for the team using the [collab-faircode template repository](https://github.com/the-magnificents/collab-faircode). Name the team’s repository as -faircode
2. [Team] Go thru the Fair software checklist and assign one item from the list to each team member. The chosen item will become tasks for the team members to work on.
3. [Collaborators] open an issue in the team’s repository about the chosen item. Describe the task for each item in the issue.
4. [Collaborators] Fork the team’s repository to their accounts.
5. [Collaborators] Clone their forks onto thier local machine, work on their issues, and push changes to their forks.
6. [Collaborators] Make a pull request from their forks to the base repository (team’s repostory), main branch.

## 12:30: 🧆🥗 Lunch Break - 60'

## 13:30: 🎦 Presentation: Code Reviews - 10'

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

## 13:40 Live Demo: Code Reviews - 10'

Demonstrate code review based on pull request from previous section

## 13:50 💪 Exercise: Code Reviews - 20;

Exercise 4.2: [Code Reviews](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L4-ex02.html)

1. [Author] Assign one or two team members as reviewers in your pull request (PR).
2. [Reviewer] Reviews, discuss, and suggest changes the pull request(s) following recommendation mentioned so far.
3. [Author] Make changes to PR based on the reviewer(s) suggestions, and updates the PR.
4. [Reviewer] Approves the PR.
5. [Author] Merges the PR into the repository after being approved for at least one reviewer.

## 14:10 Break - 10'

## 14:20 🎦 Presentation: CONTRIBUTING document - 10'

Discussi:
- Why contributing guidelines matter
- How they can help insure consistency, quality and easy review workflows
- The main components of a contributing guideline and adapting them depending on the project
- Why contributors should follow guidelines

## 14:30 💪 Exercise: Guidelines for Contributors - 10'

[//]: # (Shaved 5' off this to catch up from time glitch in precious session)

Exercise 4.3: [Guidelines for Contributors](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L4-ex03.html)

1. Working individually, use the CONTRIBUTING.md template provided in [manuGil/fair-code](https://github.com/manuGil/fair-code) to add contributing guidelines to the repository used for individual exercises.
2. Adapt the template to your repository as long as time allows it.

## 14:40 🎦 Presentation: Licenses and Citation - 10'

Explain and discuss the importance of software licenses and software citation for software.

### Open Source Licenses
- Importance of OS licenses in context of FAIR
- Permissive (MIT, Apache, BSD) vs copyleft (GPL) licenses
- If no license specified, cannot use
- Why software, data & digital content are different (eg why you don't use CC licenses for software)
- TU Delft research software policy and guidelines

### Software Citation
Explain how citations files are used to provide information about the software and its authors, and how they can be used to generate citations in different formats. In GitHub, for example, the citation file is called CITATION.cff citation file can be used to generate citations in different formats, such as BibTeX, APA, and MLA.

Provide a demo on how to create .cff files using this [CFFInit Tool](https://citation-file-format.github.io/cff-initializer-javascript/)

## 14:50  💪 Exercise: Choosing Licenses and Enabling Software Citation - 15'

Exercise 4.4: [Choosing Licenses and Enabling Software Citation](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L4-ex04.html)

1. Use the Open Source Initiative license tool to pick an open source license of your choice: https://opensource.org/licenses
2. Add a LICENSE file to your remote repository. Check the [GitHub documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) to know how to add a license file. If you have to, edit the license file to include auhtors name, year, etc.
3. Use this tool to generate a CITATION file and add it to your remote repository:
    - Search the Internet for: cffinit

## 15:05 Break 10'

## 15:15 🎦 Presentation: CI & CD - 10'

## 15:25 💪 Exercise: Full Cycle Workflow - 45'

## 16:10 Summary and Key Points / Q&A - 15'

## 16:25 Feedback - 5'

## 16:30 Goodbye