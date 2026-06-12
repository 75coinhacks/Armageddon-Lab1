Lab 1 — Branching, Git, & Python Collaboration Objective 
The goal of this lab is to practice team-based Git workflows while building a simple,  functional Python console application. Emphasis is placed on branching discipline,  collaboration, and merge integration, not application complexity. 
Example repository: https://github.com/rossislike/2025dec22 
Scenario: 
You are working in a GitHub repository for a small Python project. Your goal is to clone the  repository, create a feature branch, make code changes, update documentation, and push your  work. Along the way, you will intentionally create common Git mistakes so you can recognize  and understand how to mitigate them in real projects. 
Technical Requirements 
Repository Setup 
● Create a brand-new GitHub repository from scratch (no templates). ● Repository must include: 
○ .README.md 
○ .gitignore (appropriate for Python) 
○ At least 2 Python files (.py) per student
Git Workflow Requirements 
Round 1: Happy Path 
In this round you will demonstrate a base understanding of GitOps by successfully  merging multiple branches back into main without any issues. In tech, the Happy Path  scenario is one in which no errors or issues present themselves.  
Each team member must: 
1. Clone the repository locally 
2. Create their own Git branch 
○ Naming convention (recommended): 
feature/<firstname>-function 
3. Write at least two Python files with the following code concepts  implemented 
○ Static and dynamic variables 
○ User input 
○ File creation 
○ Conditional Logic 
4. Commit their work to their branch 
5. Push their branch to GitHub 
6. Open a Pull Request (PR) 
7. Participate in resolving merge conflicts (if any) 
No one should push directly to main except through Pull Requests. 
Round 2: Exception Path 
In this round you will demonstrate an intermediate understanding of GitOps by manually  creating scenarios that require mitigation and then taking the steps to resolve them  before merging back into the main branch. In tech, the Exception Path scenario are  those in which errors or exceptions and arise. In order for the for the scenario to  complete successfully, additional steps, troubleshooting, or error-handling must be  utilized. 
I. Stage Unwanted Files
Intentionally create extra files that should not be committed, such as: 
- notes.txt 
- debug.log 
- test_output.tmp 
Then stage all files in the directory. Run a git status to verify that all files in the  directory, including extraneous files have been staged. You must remove  these staged files before pushing your second batch of Python files to the  main branch. 
Deliverable:  
You must keep these files in the local directory tied to your GitHub repo  without committing or pushing them. Capture screenshots of your console and  add them to a nested subdirectory labeled “1.2.1_Visuals” 
Hint: Unwanted staged files can be removed from the staging area without  deleting them locally. This is usually handled with Git restore or reset  commands. The key idea is that the staging area is separate from the working  directory. 
II. Missing Commit message 
Run a git commit command without adding a commit message This will create a downstream error that you will then need to resolve.  
Deliverable:  
You must resolve the empty commit message before pushing to your  branch. Capture screenshots of your console commands and add them to  a nested subdirectory labeled “1.2.2_Visuals” 
Hint: Use a CLI-based text editor tool to manually add commit message 
III. Create a Merge Conflict 
To create a merge conflict there must be incompatible or overlapping code  differences to a file that exists on the repo. To accomplish this, you may  make changes to one of the files from round 1 or create a new shared file  across the group repo. 
Deliverable:  
You must resolve the merge conflicts to overcome errors that will be  thrown when you empty to push the updated code to your branch. Capture 
screenshots of your console commands and add them to a nested  subdirectory labeled “1.2.3_Visuals” 
Application Requirements 
● Must be console-based (CLI) 
● Must execute via: 
python app.py 
● Application purpose is open-ended 
○ Examples: 
■ Calculator 
■ Quiz game 
■ Text-based menu 
■ File utility 
● Must demonstrate: 
○ Function calls between files or modules 
○ Conditional Logic 
○ Variables (Both dynamic and static) 
○ Basic user input/output 
○ Clean code structure 
Deliverables 
● GitHub repository link 
● Evidence of: 
○ Multiple branches 
■ 2 Separate branches and re-merges into main for each group member ○ Multiple contributors
○ Pull Requests 
● Final merged working application on main 
Evaluation Criteria 
Area Weight Proper Git branching 30% Individual contribution 25% Successful merge to main 25% 

Application runs without  errors 
 20%
