Step-by-Step Instructions
Step 1: Create a Public Repository on GitHub
Log in to your GitHub account.

In the top-right corner, click the + icon and select New repository.

Fill in the repository details:

Repository name: web-development-practice (or match your local folder name).

Description: A brief note like "My web development practice assignments".

Visibility: Select Public (required for submission).

Important: Leave all boxes unchecked (Do not add a README, .gitignore, or license, since you already have a local repository).

Click Create repository.

Step 2: Connect Your Local Repository to GitHub
Open your terminal inside your project folder (web-development-practice) and run the commands provided by GitHub under the section "…or push an existing repository from the command line":

Bash
# 1. Ensure your branch is named 'main'
git branch -M main

# 2. Link your local repo to your GitHub remote repository 
# (Replace YOUR_USERNAME with your actual GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/web-development-practice.git

# 3. Push your local files to GitHub for the first time
git push -u origin main
Step 3: Add a New File and Push a Second Commit
To fulfill the requirement of adding a new file and making a second push, let's create a README.md file:

Bash
# 1. Create a README file
echo "# Web Development Practice Repository" > README.md

# 2. Stage and commit the new file
git add README.md
git commit -m "docs: add README.md project overview file"

# 3. Push the new commit to GitHub
git push
Step 4: Verify on GitHub
Refresh your repository page on GitHub ([https://github.com/YOUR_USERNAME/web-development-practice](https://github.com/YOUR_USERNAME/web-development-practice)).

Verify that all your files (including index.html and README.md) are visible.

Click on the Commits link near the top of the file list to verify that both of your commits show up correctly.

Submission
Your submission requirement is the link to your public GitHub repository.

It will look like this:[https://github.com/YOUR_USERNAME/web-development-practice](https://github.com/YOUR_USERNAME/web-development-practice) (just replace YOUR_USERNAME with your real GitHub handle!)