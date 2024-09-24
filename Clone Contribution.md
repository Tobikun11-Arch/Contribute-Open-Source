# Contribution Guidelines

## Cloning the Stage Branch

1. **Create a Folder for the Contribution Project**
   - Navigate to your desired directory and create a folder for your project.

2. **Clone the Repository**
   ```bash
   git clone -b stage --single-branch "https://github.com/username/repository.git"

3. Change Directory 
    cd path/to/your/repo

4. Checkout the Stage Branch
    *git checkout stage  (remove * always)

5. Pull the Latest Changes
    Always pull the latest changes before making any modifications:
    *git pull origin stage

6. Install Project Dependencies
    Run the following command in the terminal to install all packages:
    *npm install

7. Start the Project
    *npm run dev


## Creating a New Branch for Your Task

1. Create a New Branch
    Before making changes, create a new branch named after the task you're assigned (e.g., scrum-17):
    *git checkout -b scrum-17
    This command will create and switch you to a new branch named scrum-17, based on the stage branch.

2.5 Existing branch
    before pushing a new update, *git pull origin *branchname

2. Make Your Changes        
    You can now modify the code as needed.


## Pushing Your Changes

1. Stage Your Changes
    *git add .

2. Commit Your Changes
    *git commit -m "SCRUM-17: Brief description"

3. Push Your Branch to the Remote Repository
    *git push origin scrum-17


## Creating a Pull Request

1. Navigate to the Repository on GitHub
    After pushing your branch, go to the repository (the project you cloned).

2. Open the Pull Request
    Look for the "Compare & pull request" button that appears after your push.

3. Fill in the Pull Request Details
    Title: Change the title from the default (e.g., "scrum-17") to something more descriptive, such as:
    SCRUM-17: Implemented NotFound page

    Description: In the description box, explain what you've done in this PR:
    Mention the task (SCRUM-17) and describe the changes you made.
    Include any issues or blockers, such as problems with the SiteHeader.
    Example:
    **Task:** SCRUM-17  
    **Description:**
    - Implemented the NotFound page.
    - Encountered an issue with the SiteHeader, so I added some comments to explain the problem.

4. Request Reviewers (if applicable)
    If your project requires code review, assign reviewers as necessary.

5. Create the Pull Request
    Once everything is filled out, click the green "Create pull request" button.


TIPS:
If you push code and create a PR, you can modify the file again and push it, and the changes will be reflected in your PR.