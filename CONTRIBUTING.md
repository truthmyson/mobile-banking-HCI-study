# 📚 Contribution Guidelines: HCI Mobile Banking Project

Welcome to the team repository! To keep our project organized and avoid merge conflicts, please follow this step-by-step guide to submit your report sections. 

**Do NOT push directly to the `main` branch.** Everyone must work on their own branch.

---

## 📂 1. Repository Structure
To keep our repository organized, please ensure you save your files in the correct folders. If the folders do not exist yet, create them in your branch.

- `/reports/` - For individual Markdown or PDF reports.
- `/assets/` - For screenshots, wireframes, diagrams, and images.

---

## 🚀 2. Git Workflow Instructions

Follow these exact steps to submit your work. **Do not push directly to the `main` branch.**

### Step 1: Clone the Repository (First time only)
If you haven't downloaded the repository to your local machine yet, open your terminal and run:
```bash
git clone <YOUR_REPO_URL_HERE>
cd <YOUR_REPO_NAME>
```

### Step 2: Create a Task Branch
Before making any changes, you must create a new branch for the specific task you are assigned or it would be created for you. The naming convention is strictly required: `task-[IssueNumber]-[short-description]` (Use hyphens, no spaces).

```bash
# Example: If you are assigned to Issue #1 (User Research)
git checkout -b task-1-user-research

# Example: If you are assigned to Issue #2 (Login Screen Evaluation)
git checkout -b task-2-login-evaluation
```
(Note: If you and another member are assigned to the same task, coordinate so that only one person creates the branch first. The others can then run git checkout task-1-user-research to pull it down and work on it together).

---

### Step 3: Add Your Files and Commit
Write your report (see the Report Requirements section below). Once your files are ready, add them to Git and commit with a clear message.

```bash
# Add all your changes
git add .

# Commit your changes with a descriptive message
git commit -m "Add [Your Name]'s HCI usability analysis report"
```

### Step 4: Push to GitHub
Push your newly created task branch to the remote repository on GitHub.

```bash
# Example based on the branch name above
git push origin task-1-user-research
```

### Step 5: Create a Pull Request (PR)
1. Go to the repository on GitHub.com.
2. You will see a green button that says **"Compare & pull request"** for your recently pushed branch. Click it.
3. Add a brief description of what you contributed.
4. Assign a team member to review it, then click **"Create pull request"**.

---

## 📁 4. File Naming Conventions
When saving your files to push to the repo, please use the following naming format so we know whose work is whose:

- **Reports:** `Lastname_Firstname_HCI_Analysis.docx` (or `.pdf`)
- **Screenshots:** `Lastname_Firstname_Screen_Login.png`
- **Wireframes:** `Lastname_Firstname_Wireframe_Transfer.png`

---

## ⚠️ 5. Need Help?
If you get stuck with Git, do not panic and **do not force push**. Ask the team lead for help.

```
