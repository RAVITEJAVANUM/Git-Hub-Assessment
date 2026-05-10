# Question 1: Project Initialization & First Push
1. Add New Folder
2. git init
3. Add new file app.py
4. git status
5. git add app.py
6. git status
7. git commit -m 'My first assessment commit'
8. git status
9. Create Remote repository
10. git remote add origin https://github.com/RAVITEJAVANUM/Git-Hub-Assessment.git
11. git remote -v
12. git push --set-upstream origin main

#### Configured Git username and email
<img width="800"  alt="image" src="https://github.com/user-attachments/assets/c87f7c4a-cea6-4efe-bfa1-8d0e45fef612" />

#### Initialized local Git repository
<img width="800"  alt="image" src="https://github.com/user-attachments/assets/dec6d282-c0d7-49eb-879b-1990e4ff0c85" />

#### Checked the current Git status
<img width="800" alt="image" src="https://github.com/user-attachments/assets/2a7d6ef8-8f81-4cc2-8b27-964f16720daf" />

#### Staged the file
<img width="800"  alt="image" src="https://github.com/user-attachments/assets/cf42ff7b-c025-4fd2-9adf-26d672b56479" />

#### Committed the code
<img width="800" alt="image" src="https://github.com/user-attachments/assets/60693c6b-31c3-4440-8992-57980248a12d" />

#### Added remote repository to local and verified the remote configuration
<img width="800"  alt="image" src="https://github.com/user-attachments/assets/2dfd64fd-c070-4816-a598-da0141da3adf" />

#### Pushed the local code to the remote repository
<img width="800" alt="image" src="https://github.com/user-attachments/assets/33540021-4bb4-44ca-b31a-1728dc98c10b" />

# Question 2: Working with Changes & History
1. Open app.py and add new functionality
2. git status
3. git diff
4. git add -p app.py
5. git commit -m 'Added new feature'
6. Make changes to the code
7. git add app.py
8. git commit -m 'Added new functionality to the previously added feature'
9. git log
10. git log --oneline

#### Check the changes made
<img width="800" height="265" alt="image" src="https://github.com/user-attachments/assets/e5f26faf-129f-46b5-a527-fa89f74ceba8" />

#### View the difference between new and old codes 
<img width="800" height="266" alt="image" src="https://github.com/user-attachments/assets/bd084fb6-1f48-4eaf-9244-16ca9100904d" />

#### Staged only specific changes
<img width="800" height="350" alt="image" src="https://github.com/user-attachments/assets/4535ac67-5dc7-4051-9b9e-d9fb7f16b5b7" />

#### Committed the new code
<img width="796" height="118" alt="image" src="https://github.com/user-attachments/assets/2130a850-6599-4a9b-be2a-b4b775c1e0cb" />

#### Staged all the changes 
<img width="800" alt="image" src="https://github.com/user-attachments/assets/32dddf58-bed1-4a85-895a-b37af7f0c87e" />

#### Commited the changes
<img width="800"  alt="image" src="https://github.com/user-attachments/assets/a3e07e1f-6ef5-4b80-8521-f8ab98337f70" />

#### Viewed full commit history
<img width="800"  alt="image" src="https://github.com/user-attachments/assets/52922e5c-1591-4749-a41d-c7ea96b9c26b" />

#### Viewed one-line history
<img width="800"
  alt="image" src="https://github.com/user-attachments/assets/4aca354a-50db-4f98-9815-41d4cf2c3715" />

# Question 3: Branching & Feature Development
1. git checkout -b feature-update
2. Add new Features to the code
3. git add app.py
4. git commit -m 'Added a new Feature-2'
5. git checkout main
6. git merge feature-update
7. git log --oneline
8. git branch -d feature-update (or) git branch --delete feature-update
9. git checkout -b dummy-feature
10. git add app.py
11. git commit -m 'Added new test feature'
12. git log --oneline
13. git checkout main
14. git branch --delete --forced dummy-feature (or) git branch -D dummy-feature

#### Created a new branch
- <img width="801" alt="image" src="https://github.com/user-attachments/assets/b7db26e4-580d-4a12-82df-904fe4571209" />

#### Switched to new branch 
<img width="800" alt="image" src="https://github.com/user-attachments/assets/daa74f9b-f320-4b8c-aa73-a3df48f6dda1" />

#### Added new features and staged the changes
<img width="800" alt="image" src="https://github.com/user-attachments/assets/6170004d-a8f6-413b-b9a1-4b0127d5e9d5" />

#### Committed the changes
<img width="800" alt="image" src="https://github.com/user-attachments/assets/4666452f-4f24-4f8f-ae4c-9780a8d5512d" />

#### Switched back to main branch
<img width="800"  alt="image" src="https://github.com/user-attachments/assets/8a9200e1-1448-41f8-b985-14a15ba51b2f" />

#### Merged the feature-update branch into main
<img width="801"  alt="image" src="https://github.com/user-attachments/assets/326db250-4a67-457e-9a41-d88a7132a1a9" />

#### Verified the changes merged or not
<img width="800" alt="image" src="https://github.com/user-attachments/assets/ef19355f-93f8-43db-a9e7-f596e2e94db7" />

#### Deleted the feature-update branch
<img width="800" alt="image" src="https://github.com/user-attachments/assets/d11cc4fb-6fd9-4b3f-a7ac-b52e36139b89" />

#### Created a dummy-feature branch, staged and committed the new changes
<img width="800" alt="image" src="https://github.com/user-attachments/assets/b47b6a4d-2c96-4fc2-8eda-22dcc4375079" />

#### Switched to the main branch and Force deleted the dummy branch
<img width="800" alt="image" src="https://github.com/user-attachments/assets/fddaf034-6457-4e0e-beab-11485e4e6a5d" />

# Question 4: Handling Errors (Stash, Reset, Revert)
1. Create a new file config.env
2. git status
3. git stash -u -m "Feature is inprogress"
4. git stash list
5. git stash pop
6. git add .
7. git commit -m 'New Feature-3 added'
8. Add new code changes
9. git add .
10. git commit -m 'New Feature-4 added'
11. git reset --hard head~1
12. Add new code changes
13. git add .
14. git commit -m 'New Feature-5 added'
15. git revert head
16. git log --oneline

#### Created a new file and stashed the changes
<img width="800" alt="image" src="https://github.com/user-attachments/assets/460735f8-2ee5-4c17-b75f-a6d2bcc8f9c0" />

#### Applied the stashed changes back 
<img width="800" alt="image" src="https://github.com/user-attachments/assets/35000d20-2fba-4578-8e09-8ba70d32bfaf" />

#### Staged and committed the changes
<img width="800" alt="image" src="https://github.com/user-attachments/assets/3d84955b-27c2-4d2f-89ac-67fcc2a24035" />

#### Added new code and committed the changes 
<img width="800" alt="image" src="https://github.com/user-attachments/assets/29f73a89-bec9-4e3c-b7f3-1f76d943719e" />

#### Resetted the last commit
<img width="800"  alt="image" src="https://github.com/user-attachments/assets/93bdb09f-fded-44ad-8806-095e20edeaff" />

#### Added new code again and committed the changes
<img width="800" alt="image" src="https://github.com/user-attachments/assets/15ffe1c0-63cf-46d9-be24-9140acf402d7" />

#### Reverted the last commit
<img width="800" alt="image" src="https://github.com/user-attachments/assets/4aa37004-c5e1-4772-bffa-a7068e42c429" />
