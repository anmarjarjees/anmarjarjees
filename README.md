### Hi there 👋 I am Anmar Jarjees, a Web Developer and Instructor with more than 10 years of experience in teaching and training different levels of students in various subjects and programs including:
- Web Development and Programming
- Introduction to Graphic Design
- Microsoft Office Applications
- Computer Hardware and Software

I am in process of keep uploading more samples of my previous and the coming code, assignments, and projects.

<!--
**anmarjarjees/anmarjarjees** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


### GitHub Quick Tips 
##### (Dear students, please refer to my two comprehensive pdf files about using Git, GitHub, and GitPod for more details and explinations)
### New Repo
You can start a new empty repo on GitHub by adding the essentials "README.md" and .gitignore, then you can clone it to your local machine. GitHub will use the "main" branch by default.
- To clone a repo (I used my repo as an example):
> git clone https://github.com/anmarjarjees/git-review.git

- To connect your local folder with your remote repo, my example:
> git remote add origin https://github.com/anmarjarjees/git-basic.git
- To download all the files that only exist in the remote repo:
> git pull origin master
<br> OR: <br>
> git pull origin main

NOTE: We need to pull the changes/differences in the main repo before pushing the local ones to avoid the conflict
- Add all your new/updated files to staging:
> git add .

- Commit your changes with the required text
> git commit -m "updating with initial code"

- Push/Upload your code to GitHub
> git push origin master

OR:
> git push origin main

- You can always check your repo status:
> git status

- You can also check your repo branch name:
> git branch

- in case you added (staged) all folders/files and forget to ignore some with .gitignore, and you need to unstage everything and start again, you can use "git restore --staged <file>..." to unstage [based on git comment]:
> git restore --staged <file>
OR for unstaging everything:
> git restore --staged *

Based on "git-scm.com" documenttation:<b>
Git version 2.23.0 introduced a new command: "git restore". It's basically an alternative to "git reset". From Git version 2.23.0 onwards, Git will use git restore instead of git reset for many undo operations.

### NOTES: 
- Make sure to upload the public code that you want to share into your default branch whether it's "main" or "master" for immediate and easy access
- You can select/set your default branch:
-- Go to "Settings"
-- Under the "Code and automation" section on the left sidebar, select/click "Branches"
-- Click the two opposite arrows icon to see the switching branch menu
-- Select the branch that you want to set as a default then click "Update"
-- Accept the warning of doing these changes "I understand, update the default branch"

### MARKDOWN Language:
For more refreshing about using Markdown language,
you can check the official documents of GitHub:
[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
