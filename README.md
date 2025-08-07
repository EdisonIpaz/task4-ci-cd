CI/CD Pipeline with GitHub Actions – Static Website

Project Overview
This project demonstrates a CI/CD pipeline for a static HTML site using GitHub Actions.  
When a change is pushed to the `main` branch, the pipeline:

- Runs HTML validation tests using HTMLHint.
- Simulates a build process.
- Deploys the contents to GitHub Pages automatically.

Technologies Used
- HTML
- GitHub Actions
- HTMLHint
- GitHub Pages

Setup Process

1. Create GitHub Repository
Initialize the repository and push local files.
git init
git remote add origin https://github.com/EdisonIpaz/task4-ci-cd.git
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main

2. GitHub Pages Setup
Go to Settings > Pages
Choose GitHub Actions as the deployment source

3. Workflow File
Create the file .github/workflows/ci-cd.yml.
The information in the .yml file can be viewed within the project.

4. Permissions
Make sure the repository is public.

Result
You can view the live site here:
https://edisonipaz.github.io/task4-ci-cd/
