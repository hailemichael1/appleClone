# appleClone

## Project Overview
This project is a clone of Apple's homepage, built collaboratively by our team to practice front-end development and Git version control workflows. The project is broken down into several sections, each of which represents different parts of the Apple website. Every team member works on their assigned section and contributes to the repository via branches.

## Folder Structure
The project is organized as follows:
- **index.html**: The main HTML file containing the structure of the page.
- **CSS/**: This folder contains the main stylesheet(s) for the project.
  - `style.css`: The main CSS file to style the website.
- **images/**: All images used in the project are stored here.
- **js/**: Contains JavaScript files for any dynamic behavior.

## How to Set Up Locally
To set up and work on this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hailemichael1/appleClone.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd appleClone
   ```
3. **Open `index.html` in your browser** to view the current state of the project.

## Collaboration Guidelines
- Each team member works on a separate branch based on their assigned section (e.g., `header`, `footer`).
- **Branch Naming Convention**: Use clear and descriptive names like `header`, `footer`, `macbook-banner`, etc.
- **Frequent Commits**: Make small, frequent commits with clear commit messages to track progress effectively.
- **Pull Requests**: After completing your task, create a pull request for your branch and request a code review from the team leader.

## Sections Breakdown
Each member is responsible for the following sections:
1. **Header** (branch: `header`)
2. **Footer** (branch: `footer`)
3. **First section** (MacBook Pro banner)
4. **Second section** (iPhone 11 Pro banner)
5. **Third section** (iPhone 11 banner)
6. **Fourth section – Left** (Watch Series 5)
7. **Fourth section – Right** (Card is Here)
8. **Fifth section – Left** (Apple TV+)
9. **Fifth section – Right** (AirPods Pro)
10. **Sixth section – Left** (MacBook Pro)
11. **Sixth section – Right** (The new iPad)

## Working on Your Task
1. Create a branch for your assigned task:
   ```bash
   git checkout -b <branch-name>
   ```
2. After completing your work, commit and push the changes:
   ```bash
   git add .
   git commit -m "Completed <section name>"
   git push origin <branch-name>
   ```

3. **Before pushing**, make sure to pull the latest changes from the `main` branch to avoid conflicts:
   ```bash
   git pull origin main
   ```

4. Once your task is complete and you’ve tested it locally, create a pull request for code review and merge.

## Conflict Resolution
If two or more members edit the same file, there may be a **merge conflict**. Resolve conflicts by discussing the changes with your teammates and agreeing on the final content before merging.

## Reverting Changes
If something breaks after merging a pull request, the team can revert to a previous stable version using:
```bash
git revert <commit-hash>
```

## Best Practices
- Keep your commits small and frequent to make it easier to track and review changes.
- Test your changes locally before pushing them to the remote repository.

## License
This project is for educational purposes only.
