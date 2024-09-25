# Setting Up a Collaborative Repository with a Protected `main` Branch

## 1. Create a New Repository
First, create a new repository on GitHub.

## 2. Add Collaborators
Invite your team members to collaborate on the repository by going to the repository’s **Settings** > **Manage access** and adding collaborators.

## 3. Create a `stage` Branch
In the terminal of your project, create a new branch called `stage` for staging changes:
```bash
git checkout -b stage
git push origin stage

## 4. Merge Changes from the stage Branch into the main Branch
To merge the changes from the stage branch into the main branch, you can follow these steps

Switch to the main branch:
git checkout main

Pull the latest changes from the remote main branch:
git pull origin main

Merge the stage branch into the main branch:
git merge stage

Push the updated main branch back to the remote repository:
git push origin main
