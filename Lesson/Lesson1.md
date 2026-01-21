## What are Git and GitHub?

### Git

**Git** is a version control system.

In simple terms, Git:

* Keeps a complete history of your files
* Lets you save checkpoints (called **commits**)
* Allows you to safely go back to earlier versions

Think of Git as:

> **Track Changes + unlimited undo + timestamps + authorship**

Official site: [https://git-scm.com/](https://git-scm.com/)

---

### GitHub

**GitHub** is an online platform that hosts Git repositories.

GitHub allows you to:

* Store your work securely online
* Share it with collaborators
* Control who can view or edit your files
* Review comments and feedback in one place

Think of GitHub as:

> **Google Drive + version history + collaboration**

Official site: [https://github.com/](https://github.com/)

Documentation:
[https://docs.github.com/en/get-started/git-basics](https://docs.github.com/en/get-started/git-basics)

---

## 1. Why use GitHub for academic work?

GitHub is commonly used for:

* Thesis drafts
* Code and analysis scripts
* Figures and supplementary material
* Collaborative feedback from supervisors

Key benefits:

* No more files like `final_v3_revised_REALfinal.docx`
* Clear record of what changed and when
* One single **source of truth** for your work
* Supports **private repositories** (nothing is public unless you choose)

---

## 2. Accounts and tools you need (one-time setup)

You will install three things:

1. A **GitHub account**
2. **Git** (installed locally on your computer)
3. **Visual Studio Code (VS Code)**

---

## 3. Create a GitHub account

1. Go to: [https://github.com/](https://github.com/)
2. Click **Sign up**
3. Choose a username (this will be visible to collaborators)
4. Use an email address you check regularly

No payment is required.

---

## 4. Install Git on your computer

Git runs in the background and keeps track of file versions.

### macOS

1. Open **Terminal**
2. Run:

   ```bash
   git --version
   ```
3. If Git is not installed, macOS will prompt you to install it

Alternatively, download Git from:
[https://git-scm.com/download/mac](https://git-scm.com/download/mac)

---

### Windows

1. Download Git from:
   [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Run the installer
3. Accept the default options

---

### Linux

Use your package manager, for example:

```bash
sudo apt install git
```

---

### Verify installation

After installation, confirm Git is available:

```bash
git --version
```

---

## 5. Install Visual Studio Code (VS Code)

VS Code is a free, user-friendly editor that integrates Git.

Download from:
[https://code.visualstudio.com/](https://code.visualstudio.com/)

Why VS Code?

* No command-line required for basic Git usage
* Built-in Git support
* Works for text, documents, and code

After installation:

* Open VS Code
* No extensions are required for now

---


## 6. Configure Git (recommended first-time setup)

Git needs to know who you are so changes are correctly attributed.

### Check existing global configuration

```bash
git config --global --list
```

Look for:

* `user.name`
* `user.email`

---

### Set your name (if not already set)

```bash
git config --global user.name "Your Full Name"
```

---

### Set your email (should match GitHub account email)

```bash
git config --global user.email "your.email@example.com"
```

---

### (Optional) Set default branch name

```bash
git config --global init.defaultBranch main
```

---

### Verify configuration

```bash
git config --global user.name
git config --global user.email
```

---

### Key reassurance

* This setup is done **once per computer**
* You can change these values later if needed
* Nothing here makes your work public

---

**You are now ready to start using Git and GitHub.**
