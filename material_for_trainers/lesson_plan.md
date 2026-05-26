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

## 10:10 Break - 10'

## 10:20 🎦 Presentation - Collaborative Software Projects - 10'

[//]: # (TODO slides)

Present from [slides](https://tud365.sharepoint.com/:p:/r/sites/ResearchDataServices/_layouts/15/Doc2.aspx?action=edit&sourcedoc=%7B06a41ff9-049e-480e-a180-dbef81488b8c%7D&wdOrigin=TEAMS-MAGLEV.teamsSdk_ns.rwc&wdExp=TEAMS-TREATMENT&wdhostclicktime=1774444252296&web=1)

- Software Development lifecycle
- Collaborative software development
- Open vs closed collaboration
- Considerations in open collaboration for RSE
- When does collaborative development make sense?

## 10:30 Live Demo: Github issues and branching - 10'
- Create issues - participant teams create in the cloned template repo from earlier
- Explain workflow possibilities:
    - **Branching**
    - **Forking**

## 11:40 💪 Exercise: Branching Workflow - 20'

[//]: # (Consider a new template repo - probaby not necessary here)

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

## 11:30 💪 Exercise: Pull Requests - 15'

Exercise 2: [Pull Requests](../material_for_participants/exercises.md)

Exercise in which participants:

- Create pull requests for the issues above
- Merge the PRs, resolving any conflicts that emerge

## 11:45 Live Demo: Forking Workflow - 10'

Explain a forking strategy and demonstrate the workflow around forking, cloning, pushing and upstream pull requests

## 12:10 Exercise: Forking Workflow - 25'

Exercise 3: [Forking Workflow](../material_for_participants/exercises.md#3-forking-workflow)

## 12:35: Lunch Break - 60'

## 13:35: Presentation: Code Reviews - 7'

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

## 13:42 Live Demo: Code Reviews - 10'

Demonstrate code review based on pull request from previous section

## 13:52 Exercise: Code Reviews - 23;

Exercise 4.2: [Code Reviews](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L4-ex02.html)

1. [Author] Assign one or two team members as reviewers in your pull request (PR).
2. [Reviewer] Reviews, discuss, and suggest changes the pull request(s) following recommendation mentioned so far.
3. [Author] Make changes to PR based on the reviewer(s) suggestions, and updates the PR.
4. [Reviewer] Approves the PR.
5. [Author] Merges the PR into the repository after being approved for at least one reviewer.

## 14:15 Break - 10'

## 14:25 🎦 Presentation: CONTRIBUTING document - 10'

Discussi:
- Why contributing guidelines matter
- How they can help insure consistency, quality and easy review workflows
- The main components of a contributing guideline and adapting them depending on the project
- Why contributors should follow guidelines

## 14:35 💪 Exercise: Guidelines for Contributors - 10'

[//]: # (Shaved 5' off this to catch up from time glitch in precious session)

Exercise 4.3: [Guidelines for Contributors](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L4-ex03.html)

1. Working individually, use the CONTRIBUTING.md template provided in [manuGil/fair-code](https://github.com/manuGil/fair-code) to add contributing guidelines to the repository used for individual exercises.
2. Adapt the template to your repository as long as time allows it.

## 14:50 🎦 Presentation: Licenses and Citation - 10'

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

## 15:00  💪 Exercise: Choosing Licenses and Enabling Software Citation - 15'

Exercise 4.4: [Choosing Licenses and Enabling Software Citation](https://4turesearchdata-carpentries.github.io/GitCoDev/exercises/L4-ex04.html)

1. Use the Open Source Initiative license tool to pick an open source license of your choice: https://opensource.org/licenses
2. Add a LICENSE file to your remote repository. Check the [GitHub documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) to know how to add a license file. If you have to, edit the license file to include auhtors name, year, etc.
3. Use this tool to generate a CITATION file and add it to your remote repository:
    - Search the Internet for: cffinit

## 15:15 Break 10'

## 15:25 Presentation: CI & CD - 10'

- Introduction to tests
- Running tests locally
- Importance of automated testing in collaborative workflow: accept changes from others safely, without breaking your code
- Introduction to Continuous Integration (CI) and Continuous Deployment (CD)
- CI: automatically running tests on new code changes to ensure they don't break existing functionality
- CD: automatically deploying code changes to production after passing tests

Type along: automate tests using Github actions. Show how to set up a simple workflow that runs tests on every pull request.

Aspects of both code quality control (Lint-style checks) and unit and regression tests can be run automatically. Live applications can also be deployed in response to actions on the repository. 

Provide a demo of CI & CD tasks using Github actions, showing tests both passing and failing in response to a PR.

## 15:55 Exercise: Full Cycle Workflow - 45'



## 16:20 Summary and Key Points / Q&A - 15'

## 16:45 Feedback - 5'

## 16:45 Goodbye