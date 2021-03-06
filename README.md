# DataBootCampHW
Gabe Antonio homework.
# DataBootCampHW
My repo to house homework for the UCB Data Bootcamp. 

# Simplifying GitHub & GitLab

### Change to your home directory
```
cd ~/
```
### Simpliftying GitHub & GitLabfor GitHub and GitLab
```
mkdir GitHub
mkdir GitLab
```
### Clone the GitLab (course materials) repo
```
cd GitLab
git clone https://ucb.bootcampcontent.com/UCB-Coding-Bootcamp/UCBER201805DATA2-Class-Repository-DATA.git
```
### Navigate back up a directory
```
cd ..
```
### Clone the GitHub (submit homework) repo
```
cd GitHub
git clone https://github.com/<username>/DataBootCampHW.git
```
## How to get the latest files from GitLab (course materials)?
### Navigate to the repo's folder
```
cd ~/GitLab/UCBER201805DATA2-Class-Repository-DATA
```
### Will check to see if there are any new files you don't have or updates to files you already have 
```
git pull 
```
From here you can check the changes, if any, and manually inspect those updated files.
## How to submit my homework to GitHub?

After you have created a new homework file, manually copy it and paste it in the GitHub repo file created to hold your homework
### Navigate to the repo's folder
```
cd ~/GitHub/<REPO-NAME>
```
### Run a sync first, for good measure
```
git pull 
```
### Then add the files you want to push to GitHub
NOTE: using ./* gives you every file (*) in the current (.) 
```
directory (/)
git add ./*
```
### Now commit the files to be added with a comment
```
git commit -m "Updating the repo with the latest files"
```
### Now submit the files
```
git push 
```
Verify the files are there by checking GitHub web interface.
