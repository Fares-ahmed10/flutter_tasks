# flutter_tasks# OSC Flutter 2027 – Task Submissions 🚀

Welcome to the official **OSC Flutter 2027 Task Submission Repository!**

This repository is where you will submit your solutions to the tasks assigned during the Flutter track.

Please follow this guide carefully to make sure your submissions are organized and uploaded correctly.

---

## 📌 Table of Contents

- [Prerequisites](#-prerequisites)
- [Step 1: Clone the Repository](#-step-1-clone-the-repository)
- [Step 2: Navigate to the Task Folder](#-step-2-navigate-to-the-task-folder)
- [Step 3: Create Your Personal Folder](#-step-3-create-your-personal-folder)
- [Step 4: Add Your Solution](#-step-4-add-your-solution)
- [Step 5: Upload Your Submission](#-step-5-upload-your-submission)
- [Step 6: Verify Your Submission](#-step-6-verify-your-submission)
- [Common Problems](#-common-problems)
- [Submission Rules](#-submission-rules)

---

## 🛠 Prerequisites

Before getting started, make sure you have:

1. A GitHub account.
2. Git installed on your computer.
3. A code editor such as VS Code or IntelliJ IDEA.

Useful links:

- [Create a GitHub Account](https://github.com/signup)
- [Download Git](https://git-scm.com/downloads)
- [Git Documentation](https://git-scm.com/doc)

To verify that Git is installed, open your terminal and run:

```bash
git --version
```

If Git is installed correctly, you should see its version.

---

## 📥 Step 1: Clone the Repository

First, you need to download a local copy of this repository to your computer.

**1. Open this repository on GitHub.**

**2. Click the green `Code` button.**

**3. Copy the HTTPS URL.**

**4. Open your terminal** in the directory where you want to save the repository.

**5. Run the following command:**

```bash
git clone REPOSITORY_URL
```

Replace `REPOSITORY_URL` with the URL you copied.

For example:

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

**6. Enter the repository folder:**

```bash
cd REPOSITORY_NAME
```

Congratulations! You now have a local copy of the repository on your computer.

---

## 📂 Step 2: Navigate to the Task Folder

Inside the repository, you will find folders for the assigned tasks.

Navigate to the folder corresponding to the task you want to submit.

For example:

```text
OSC-Flutter-2027/
│
├── Task 01/
├── Task 02/
├── Task 03/
└── README.md
```

**Important:** Always make sure you are submitting your solution inside the correct task folder.

Do not create your personal folder directly in the repository root.

---

## 👤 Step 3: Create Your Personal Folder

Inside the task folder, create a new folder using your **Full Name**.

For example, if your name is Ahmed Mohamed:

```text
Task 01/
│
├── Ahmed Mohamed/
├── Sara Ali/
└── Mohamed Hassan/
```

You can create your folder manually using your file explorer or through the terminal.

Using the terminal:

```bash
mkdir "Your Full Name"
```

Then enter your folder:

```bash
cd "Your Full Name"
```

Replace `Your Full Name` with your actual full name.

**Please follow these rules:**

- Use your real full name.
- Keep your folder name clear and readable.
- Do not use someone else's folder.
- Do not upload your files directly into the task's main directory.

---

## 💻 Step 4: Add Your Solution

Now it's time to add your solution!

Place all the required files inside your personal folder.

For example, a Flutter task might look like this:

```text
Task 01/
│
└── Ahmed Mohamed/
    │
    └── my_flutter_app/
        ├── lib/
        ├── test/
        ├── pubspec.yaml
        ├── pubspec.lock
        └── README.md
```

### Important Notes for Flutter Projects

When submitting a Flutter project:

**Include:**
- `lib/`
- `test/` (if applicable)
- `pubspec.yaml`
- `pubspec.lock`
- Required assets and configuration files.
- Any additional files necessary to run your project.

**Do NOT include:**
- `build/`
- `.dart_tool/`
- Unnecessary IDE-generated files.
- Personal credentials, passwords, or API keys.

Make sure your project is properly organized and that your solution works before submitting it.

---

## 🚀 Step 5: Upload Your Submission

Once your solution is ready, you need to upload it to GitHub.

Open your terminal at the repository's root directory.

### 1. Check Your Changes

Run:

```bash
git status
```

This command shows the files you have added or modified.

### 2. Stage Your Submission

Run:

```bash
git add "Task Folder/Your Full Name/"
```

Replace the folder names with your actual task folder and full name.

This command prepares your files for the next step.

### 3. Commit Your Changes

Run:

```bash
git commit -m "Add Your Full Name - Task 01"
```

A commit is a saved snapshot of your changes.

Feel free to use a clear commit message that describes your submission.

### 4. Push Your Changes

Run:

```bash
git push origin main
```

This command uploads your committed changes to GitHub.

**Note:** If the repository uses a different default branch, replace `main` with the correct branch name.

If you are asked to authenticate, follow GitHub's authentication instructions.

### ⚠️ Important: Repository Access

Direct pushing requires write access to the repository.

If you receive a permission error, do not try to change repository settings or use someone else's account.

Contact the OSC Flutter team to get the correct submission instructions.

If the repository uses a Fork and Pull Request workflow, follow the instructions provided by the team instead.

---

## ✅ Step 6: Verify Your Submission

After pushing your changes:

1. Open the repository on GitHub.
2. Navigate to the correct task folder.
3. Find your personal folder.
4. Open it and check that all your files are there.
5. Make sure your latest changes have been uploaded.

If everything is visible on GitHub, your submission has been uploaded successfully!

---

## 🔧 Common Problems

Here are some common problems you might encounter and how to solve them.

### 1. `git: command not found`

**Problem:** Your terminal does not recognize the Git command.

**Solution:** Install Git from [git-scm.com](https://git-scm.com/downloads), then restart your terminal.

### 2. `fatal: destination path already exists`

**Problem:** A folder with the same repository name already exists.

**Solution:** Navigate to the existing repository folder instead of cloning it again.

```bash
cd REPOSITORY_NAME
```

### 3. `nothing to commit, working tree clean`

**Problem:** Git cannot find any new changes to commit.

**Solution:** Make sure you added your solution files inside the repository and that they are not ignored by Git.

Then run:

```bash
git status
```

### 4. Authentication or Permission Errors

**Problem:** GitHub refuses to accept your push.

**Solution:** Make sure you are authenticated with the correct GitHub account and that you have permission to push to the repository.

If you still cannot push, contact the OSC Flutter team.

### 5. `Updates were rejected because the remote contains work`

**Problem:** Someone has pushed new changes to the repository before you.

**Solution:** First, make sure your local changes are committed, then run:

```bash
git pull --rebase origin main
```

After resolving any conflicts, push again:

```bash
git push origin main
```

If you are unsure how to resolve a conflict, ask for help before proceeding.

### 6. Accidentally Submitted to the Wrong Folder

**Problem:** You uploaded your solution inside the wrong task directory.

**Solution:** Contact the OSC Flutter team for guidance before deleting or moving files, especially if your changes have already been pushed.

---

## 📋 Submission Rules

Please follow these rules to keep the repository clean and organized:

1. Every student must have their own personal folder inside each task directory.
2. Use your full name as your folder name.
3. Submit your solution inside the correct task folder.
4. Do not modify or delete other students' submissions.
5. Do not rename or delete existing task folders.
6. Do not upload unnecessary generated files or caches.
7. Make sure your solution works before submitting it.
8. Follow any additional instructions provided with each task.
9. Keep your commits clear and meaningful.
10. If you face any issues, ask the OSC Flutter team for help.

---

## 🎯 Final Note

We encourage everyone to submit their tasks on time and keep their code clean and organized.

Remember, the goal is not just to complete the tasks, but also to practice using Git and GitHub as part of your development journey.

**Happy Coding! 💙**

**OSC Flutter Team – 2027**