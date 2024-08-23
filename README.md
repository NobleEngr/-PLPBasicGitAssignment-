# -PLPBasicGitAssignment-
Day 4 Assignment(Hands on)

**STEPS TAKEN**

Task 1: Repository Setup
  1. Log in to your GitHub account. If you don’t already have a GitHub account, sign up at github.com.
  2. Create a New Repository: After you log in to your GitHub account, click on “New” Repository, you can find this button on your GitHub dashboard or by clicking the "+" icon in the top-right corner and selecting "New repository". 
  3. Configure Repository Settings:
     - Choose a name for your repository. This should be descriptive of the project. (I used **"PLPBasicGitAssignment"**)
     - Description (Optional): Add a brief description of what your repository will contain. {I used Day 4 Assignment(Hands on)}
     - Public vs. Private: (i) Public: Anyone can see this repository, making it ideal for open-source projects. (ii) Private: Only you and people you invite can access the repository, suitable for private or work-related projects. (I used public)
     - Initialize with a README (Optional): A README file is a good starting point for your repository, providing an overview of the project.(I initialized with README file)
     - Add .gitignore (Optional): Choose a .gitignore template to exclude certain files or directories (e.g., system files, environment files) from being tracked by Git.(I chose to ignore VisualCode)
     - Choose a License (Optional): Select an open-source license (like MIT, GPL) if you’re planning to make your project public. This dictates how others can use, modify, and distribute your code.(I used MIT license)
  4. Create the Repository: Click the "Create repository" button to finalize the setup.

Task 2: Local Setup
  - after launching command prompt on my machine, i navigated to my desired folder using command prompt lines
  - I created a new folder in the desired path using command prompt on windows (**mkdir <folder_name>**)
  - i navigated to the new folder using **cd <folder_name>**

Task 3: Git Initialization
  - i initialized Git using **git init**

Task 4: Connecting to GitHub
  - i linked my local repository to the GitHub repository i created using **git remote add origin <My_Repository_URL>**

Task 5: Making Changes
  - i created a text file in my local repository using **echo "Hello, Git!" > hello.txt**

Task 6: Committing Changes
  - i staged the changes using **git add hello.txt**
  - i committed the changes using **git commit -m "Add hello.txt with a greeting"**

 Task 7: Pushing to GitHub
   - i pushed the changes to my GitHub repository using **git push -u origin <branch_name>**.(my branch name is **master**)

Task 8: Verification
  - i visited my GitHub repository in my web browser to verify the changes.
