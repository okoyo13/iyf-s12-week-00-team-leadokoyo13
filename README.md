# Team Knowledge Base — Week 0

A collaborative knowledge base created by our three-person team during IYF Season 12 Week 0. Each team member contributes a short section about a tool, programming language, or study technique we use, such as VS Code shortcuts, Git and GitHub, and spaced repetition. This repository also gives us practical experience with the branch, pull request, code review, and merge workflow that we will use throughout the semester.

## okoyo13 — VS Code Tips
<!--okoyo13 will add this section here-->

Visual Studio Code (VS Code) is a powerful code editor that helps developers write, edit, and manage code efficiently. It provides useful keyboard shortcuts, such as **`Ctrl + S`** to save files, **`Ctrl + C`** to copy text, **`Ctrl + V`** to paste text, **`Ctrl + Z`** to undo changes, and **`Ctrl + /`** to comment or uncomment a line of code. You can also use **`Alt + Shift + F`** to format your code and make it easier to read.
### Essential VS Code Keyboard Shortcuts

The following keyboard shortcuts help developers work faster and more efficiently in Visual Studio Code on Windows.

| Keyboard Shortcut  | Function                              |
| ------------------ | ------------------------------------- |
| `Ctrl + S`         | Save the current file                 |
| `Ctrl + C`         | Copy selected text                    |
| `Ctrl + V`         | Paste copied text                     |
| `Ctrl + X`         | Cut selected text                     |
| `Ctrl + Z`         | Undo the last action                  |
| `Ctrl + Y`         | Redo the last action                  |
| `Ctrl + A`         | Select all content                    |
| `Ctrl + F`         | Find text in the current file         |
| `Ctrl + H`         | Find and replace text                 |
| `Ctrl + /`         | Comment or uncomment a line           |
| `Shift + Alt + F`  | Format the current document           |
| `Ctrl + Shift + P` | Open the Command Palette              |
| `Ctrl + P`         | Quickly open a file                   |
| `` Ctrl + ` ``     | Open or close the integrated terminal |

**Tip:** Practice these shortcuts regularly to improve your speed and productivity when coding.


### Using the Integrated Terminal

VS Code has an integrated terminal that allows you to run commands without leaving the editor. For example, you can use `node --version` to check whether Node.js is installed or `node app.js` to run a JavaScript file named `app.js`.

### Writing HTML Faster

When writing HTML, you can use **Emmet** by typing `!` in an HTML file and pressing `Tab` or `Enter`, depending on your settings, to generate the basic HTML boilerplate automatically.

### Useful Extensions

You can improve your coding experience by installing extensions such as **Live Server** for previewing web pages in a browser, **Prettier** for formatting code, and **ESLint** for identifying potential JavaScript errors.

### Organizing Your Projects

Keep your projects organized by using meaningful file names, such as `index.html`, `style.css`, and `script.js`. Save your work regularly using `Ctrl + S` and group related files into clearly named folders.

### Working with Git and GitHub

You can use the **Source Control** panel in VS Code to track changes, create commits, and synchronize your work with GitHub. This makes it easier to collaborate with other developers and manage project versions.

**Tip:** Practice using keyboard shortcuts, keep your code organized, and explore useful extensions to become more productive in VS Code.
## Description
The README lists GitLens (and Prettier) as favourite extensions, but the repo does 
not recommend them to contributors. When a teammate clones the project and opens 
it in VS Code, they get no prompt to install these tools, leading to inconsistent 
editor setups across the team.

## Steps to Reproduce
1. Clone the repo on a fresh machine
2. Open the folder in VS Code
3. Observe that no "recommended extensions" notification appears

## Expected Behavior
VS Code should prompt the user to install Prettier and GitLens when the workspace 
is opened for the first time.

## Actual Behavior
No `.vscode/extensions.json` file exists in the repo, so no recommendations are shown.

## Suggested Fix
Create a `.vscode/extensions.json` file at the repo root with the following content:

```json
{
  "recommendations": [
    "esbenp.prettier-vscode",
    "eamodio.gitlens"
  ]
}
```

## Wilfred-Mutuma — Git & Github
<!--Wilfred-Mutuma will add this section here-->

Git is a version control system that helps developers track changes
in their code. It allows us to create branches, make commits, and
work on different features without changing the main project.
GitHub allows developers to store Git repositories online and
collaborate with other developers through pull requests and reviews.

### Useful Git Commands

- `git clone` — downloads a repository
- `git status` — shows the current repository status
- `git add` — stages changes
- `git commit` — saves changes
- `git push` — uploads changes to GitHub
- `git pull` — downloads the latest changes

### Git and GitHub Collaboration Workflow

Follow these steps when contributing to our team repository.

#### 1. Create a Branch

Create a separate branch for your work instead of making changes directly to the `main` branch. Give your branch a meaningful name related to your task.

#### 2. Make Your Changes

Edit the necessary files in your branch. Check your changes carefully before submitting them.

#### 3. Commit Your Changes

A commit records the changes you have made. Write a clear commit message describing your work.

#### 4. Push Your Branch

Push your branch to GitHub so your teammates can access your changes.

#### 5. Open a Pull Request

Create a pull request to propose merging your branch into `main`. Explain what you changed and link the related GitHub Issue.

#### 6. Review the Pull Request

Ask another teammate to review your pull request. The reviewer should check the changes and leave comments or approve the work.

#### 7. Merge the Pull Request

After the required review and approval, merge the pull request into `main`. Resolve any requested changes before merging.

#### 8. Close the Related Issue

Include `Closes #10` in the pull request description when the pull request addresses Issue #10. GitHub will automatically close the issue when the pull request is merged into the repository's default branch.

#### Team Collaboration Rules

* Work on your own branch.
* Use clear commit messages.
* Review teammates' pull requests respectfully.
* Resolve conflicts before merging.
* Keep the `main` branch stable.

### Pull Request Checklist

Before submitting a pull request, make sure you:

* [ ] Created a branch for your work.
* [ ] Made and checked your changes.
* [ ] Used a clear commit message.
* [ ] Explained your changes in the pull request description.
* [ ] Requested a review from a teammate.
* [ ] Addressed review comments before merging.


## Javandaizy85-commits — Study Techniques
<!--Javandaizy85-commits will add this section here-->
I use simple study techniques that help me remember HTML and computer skills. My techniques are Active Recall (typing tags from memory), Spaced Repetition (revising every 2 days), Pomodoro (25 min work / 5 min break), and Teaching friends  I use VS Code, GitHub mobile app and YouTube.
