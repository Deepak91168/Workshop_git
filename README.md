## GIT/GIT-HUB WORKSHOP

<hr>
<li>
Do not jump Directly over Solution use the following hints and try to do it Yourself!

<li>You are required to make changes only in <strong>Test</strong> folder rest should be untouched.
<hr>

# Task

0. Fork and Clone the Repository.

    `git clone https://github.com/<YOUR_USERNAME>/Workshop_git.git`

    Note: You can clone anywhere you want but prefer Desktop for first time.

![alt text for screen readers](/images/clone.png "Clone")

1. Add a file in <strong>TEST</strong> Folder with File Name: <strong>Firstname_rollno.fileextension</strong>. 

    (Eg: Deepak_20bcs102.pdf, Deepak_20bcs102.txt, Deepak_20bcs102.py, Deepak_20bcs102.cpp etc)

2. You can add anything Inside the file (Eg: Code Script, Your Name, Class, Roll etc).

3. Make A seperate Branch (Branch Name: Roll No.).

    `git branch <BRANCH_NAME>`

4. After Adding the file into TEST folder stage the changes using 

    `git add .`

    And now you are ready to commit the changes.

    `git commit -m "<MyCommit_RollNo.>"`

4. Push Changes into Your Branch.

    `git push origin <BRANCH_NAME>`

    While Pushing the Changes...... You will be asked for

    Username: git_username
    Passwork: access_token

5. Now Open GitHub website and open the Above repo you will be able to see the option for creation of pull request. Click over <strong>Compare and pull Request</strong>.

![alt text for screen readers](/images/PR.png "Compare and Pull request")

Now ! write something

![alt text for screen readers](/images/write.png "Write Final Commit Msg")

6. Final Step After writing commit message click over <strong>Create Pull Request</strong>.

![alt text for screen readers](/images/final.png "Create Pull request")

Note: You will not get the option for Merge Pull Request as you are not owner of the repo.

<hr>

# Have a look over Changes
Test Folder Added and updated Readme.md

![alt text for screen readers](/images/applied-changes.png "Changes")
