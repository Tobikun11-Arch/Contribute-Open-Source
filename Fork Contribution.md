# Contributing to an Open-Source Project on GitHub

## 1. Find an Open-Source Project on GitHub

### Search for a Project
You can search for projects using **Next.js** and **TypeScript** on GitHub by using the following query:

```
nextjs typescript language:TypeScript
```

If you're looking for a specific type of project, you can refine your search. For example:

```
nextjs typescript e-commerce language:TypeScript
```

Once you find a project you're interested in, select it.

### 2. Fork the Repository
Click the **Fork** button at the top right of the repository page to create a copy of the repository in your own GitHub account.

### 3. Set Up Your Local Environment
Make a folder for your contribution project and open that folder in Visual Studio Code.

In the terminal, run the following command to clone the repository:

```
git clone https://github.com/your-username/repository-name.git
```

Make sure to use the link from your forked repository.

After cloning, navigate to the cloned folder:

```
cd repository-name
```

### 4. Create a New Branch
In the terminal of the cloned project, create a new branch:

```
git checkout -b branchname (example: tobibranch)
```

### 5. Install Dependencies
Run the following command to install all dependencies:

```
npm install
```

### 6. Make Your Changes
Make the necessary changes to the codebase. These changes could include fixing a bug, adding a feature, improving documentation, or enhancing tests. Always ensure your code follows the project's guidelines and passes all tests.

### 7. Stage and Commit Your Changes
Once you’ve made your changes, you need to stage and commit them. Before committing, check the modified files with:

```
git status
```

Then stage your changes:

```
git add .
```

Commit your changes with a brief description:

```
git commit -m "Brief description of the change"
```

Push your changes to your branch:

```
git push origin branchname (example: tobibranch)
```

### 8. Open a Pull Request (PR)
After pushing your changes, open a Pull Request to the original repository to propose your changes.

#### Steps:
1. Go to the original repository on GitHub.
2. You’ll see a message about your recently pushed branch, along with a button to **Compare & pull request**. Click it.
3. Add a title and description explaining your changes.
4. Submit the Pull Request.

### 9. Participate in the Review Process
Once your Pull Request is submitted, maintainers and other contributors will review it. They might suggest improvements or request changes. Be open to feedback and make any necessary revisions.

### To update your PR with changes:
1. Make changes in your local branch.
2. Stage, commit, and push them to the same branch:

```
git add .
git commit -m "Address feedback"
git push origin branchname (example: tobibranch)
```

Additional:
If there are new changes added to the main branch and you want to pull those changes into your feature branch before making further modifications, you can follow these steps:

git checkout branchname (example: tobibranch)
git fetch origin
git merge origin/main   //if the repo is using master instead of main change it to master
git add .
git commit -m "Resolved merge conflicts with main" 