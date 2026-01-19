# Git & GitHub Onboarding – 1-Page Quick Start

**Audience:** First-time Git/GitHub users (scientists, researchers)

**Goal:** Connect a local folder to an existing GitHub repository, add files, and push changes safely.

---

## Golden Rule (Read This First)

> **If a GitHub repository already exists, always CLONE it first.**
> This avoids missing branches, conflicts, and confusion.

---

## Option A (Recommended): Clone an Existing GitHub Repository

### 1. Clone the repository

```bash
git clone https://github.com/username/repo-name.git
```

What this does automatically:

* Downloads the repository
* Sets the remote (`origin`)
* Creates the correct local branch (`main` or `master`)
* Pulls existing files (e.g. README)

---

### 2. Move into the project folder

```bash
cd repo-name
```

---

### 3. Check status

```bash
git status
```

You should see:

> On branch main (or master)

---

### 4. Add your files

Copy or create files inside the folder:

* thesis drafts
* documents
* code
* figures

---

### 5. Stage changes

```bash
git add .
```

---

### 6. Commit changes

```bash
git commit -m "Add initial project files"
```

---

### 7. Push to GitHub

```bash
git push
```

✅ Your files are now online.

---

## Option B (Only if you did NOT clone)

Use this **only** if you already have a local folder and the GitHub repo exists.

### 1. Initialise Git locally

```bash
git init
```

---

### 2. Add the remote repository

```bash
git remote add origin https://github.com/username/repo-name.git
```

*(This command shows no output when successful.)*

---

### 3. Fetch remote history

```bash
git fetch origin
```

---

### 4. Create a local branch from the remote

```bash
git checkout -b main origin/main
```

(Use `master` instead of `main` if required.)

---

### 5. Add, commit, and push files

```bash
git add .
git commit -m "Add initial project files"
git push -u origin main
```

---

## Common Beginner Confusions (Normal!)

* `git remote add` showing no output → **this is normal**
* `git branch` shows nothing → **you need a commit first**
* Remote branches don’t appear → **run `git fetch`**

---

## Mental Model (Remember This)

* **Clone** → Download + connect
* **Commit** → Save a snapshot
* **Push** → Upload your snapshot
* **Fetch** → See what exists remotely

---

## Best Practice Summary

✔ Clone if the repo exists
✔ Commit often with clear messages
✔ Keep `main` clean
✔ One repo = one source of truth

---

**That’s it. You now know enough Git to work confiden
