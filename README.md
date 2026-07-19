### Hello, my name is Anmar Jarjees
I am a Technical Instructor and .NET Full-Stack Developer with 15+ years of experience in software development, web technologies, and programming education.
My focus is building practical applications using C#, ASP.NET Core, databases, and modern web technologies, while helping learners understand real-world software development practices.

Throughout my teaching career, I have delivered courses covering:
- Web Development and Computer Programming
- Object-Oriented Programming and Software Design
- Database Development
- Full-Stack Web Technologies
- Programming Frameworks and Development Tools
- Introduction to Graphic Design and Multimedia
- Microsoft Office Applications for Advanced Accounting and Office Administration
- Computer Hardware and Basic Networking

I regularly update my repositories with new projects, improvements to existing code samples, and educational resources created from my teaching and continuous learning experiences. Some projects are ongoing and continue to evolve as I explore new technologies and development practices.

A quote that reflects my approach to learning and professional growth:
  > "Give me six hours to chop down a tree and I will spend the first four sharpening the axe." **by Abraham Lincoln**

### Tech Stack
- **Languages:** C#, Java, JavaScript, TypeScript, Python, PHP, C++, SQL
- **Backend:** ASP.NET Core, MVC, REST APIs, Node.js, Express, Django
- **Frontend:** HTML5, CSS3, JavaScript, TypeScript, Vue.js, Bootstrap
- **Databases:** SQL Server, MySQL, MongoDB
- **Cloud & Tools:** Microsoft Azure, Git, GitHub, Visual Studio, VS Code, Postman

### Beyond Coding
Music has always been an important part of my life. I enjoy playing keyboard and guitar and participating in different church choirs.
Music continues to inspire my creativity, listening skills, patience, and collaboration, qualities that also influence my approach to software development and teaching.

### Connect With Me
- [Portloflio](https://www.anmarjarjees.com/)
- [LinkedIn](https://www.linkedin.com/in/anmarjarjees/)

---
---

### GitHub Quick Tips 
##### (Dear students, please refer to my two comprehensive PDF files about using Git, GitHub, and GitPod for more details and explanations)
### New Repository (repo)
You can start a new empty repository on GitHub first by adding the essentials: a 'README.md' and a '.gitignore' file. Then, you can clone it to your local machine. By convention, repository names should use all lowercase letters and separate words using dashes (-). GitHub will use the 'main' branch by default.
- To clone a repository (I used my repository as an example):
> git clone https://github.com/anmarjarjees/git-review.git

- To connect your local folder with your remote repository (my example):

Make sure that Git is initialized within the current folder:
> git init

Then:
> git remote add origin https://github.com/anmarjarjees/git-basic.git
- To download all the files that only exist in the remote repo:
> git pull origin main
- To list (view) the remote repo(s) (GitHub, Heroku, etc.) of your current local project, you can type:
>	git remote -v

NOTE: We need to pull the changes/differences in the main online repository before pushing the local ones to avoid any conflicts.
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

# Main Branch and Master Branch:
GitHub creates the repository with a single branch. This first branch in the repository is the default branch. The default branch is the branch that GitHub displays when anyone visits your repository. By default, GitHub names the default branch *"main"* in any new repository.

When we do the other way by first creating/converting a local folder into a git repo "git init" and then adding an empty GitHub repo later to upload (push) our files, Git will use the "master" branch to be the default one, but we should always use "main" as the default main branch. To avoid naming our branch with "master" we need to use this command:  

  > git branch -M main

GitHub will remind us by listing the following commands when we create an empty repo which are the steps to do locally:
  > git init

  > git add README.md
  
  > git commit -m "first commit"
  
  > git branch -M main
  
  > git remote add origin https://github.com/anmarjarjees/git-first-way.git
  
  > git push -u origin main

…or push an existing repository from the command line
  
  > git remote add origin https://github.com/anmarjarjees/git-first-way.git
  
  > git branch -M main
  
  > git push -u origin main

Notice that **-u** flag for **"upstream"** creates a tracking reference for every branch that you successfully push onto the remote repository. According to Git:

*"For every branch that is up to date or successfully pushed, add upstream (tracking) reference, used by argument-less git-pull[1] and other commands"*.

Example:
instead of:
  > git pull origin main
 we can just use:
  > git pull

If you added (staged) all folders/files and forget to ignore some with .gitignore, and you need to unstage everything and start again, you can use "git restore --staged <file>..." to unstage [based on Git documentation]:
> git restore --staged <file>
<br> OR for unstaging everything:<br>
> git restore --staged *

Based on "git-scm.com" documentation:<b>
Git version 2.23.0 introduced a new command: "git restore". It's an alternative to "git reset". From Git version 2.23.0 onwards, Git will use git restore instead of git reset for many undo operations.

### Branch NOTES: 
- Make sure to upload the public code that you want to share into your default branch whether it's "main" or "master" for immediate and easy access
- You can select/set your default branch:
-- Go to "Settings"
-- Under the "Code and automation" section on the left sidebar, select/click "Branches"
-- Click the two opposite arrows icon to see the switching branch menu
-- Select the branch that you want to set as a default then click "Update"
-- Accept the warning of doing these changes "I understand, update the default branch"
  
 #### NOTE: 
 You can open any link in a new tab using either of the following ways:
- Hold down the CTRL Key in Windows or the COMMAND key on Mac then click it
- Right-click the link and choose 'Open Link in New Tab' or 'Open Link in New Window' from the context menu.

### MARKDOWN Language:
For more refreshing about using Markdown language,
- You can check the official documents on GitHub:
[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- You can check the extended syntax: [Markdown Guide](https://www.markdownguide.org/extended-syntax/)

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
