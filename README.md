# PLPBasicGitAssignment
Setting Up Your Git Repository
1. Local Folder Setup:
Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").
Open a terminal or command prompt and navigate to the created folder.
2. Git Initialization:
Initialize a new Git repository in your local folder.
bash
Copy code
git init
3. Connecting to GitHub:
Link your local repository to the GitHub repository you created in Task 1.
bash
Copy code
git remote add origin <repository-url>
Replace <repository-url> with the actual URL of your GitHub repository.
Making Changes and Pushing to GitHub
4. Create a File:
Inside your local folder, create a new text file (e.g., hello.txt).
Add a simple text message (e.g., "Hello, Git!").
5. Committing Changes:
Stage the changes.
bash
Copy code
git add hello.txt
Commit the changes.
bash
Copy code
git commit -m "Add hello.txt with a greeting"
6. Pushing to GitHub:
Push the committed changes to your GitHub repository.
bash
Copy code
git push -u origin main
Verification and Submission
7. Verification:
Visit your GitHub repository in a web browser and confirm that the hello.txt file and commit message are visible.
