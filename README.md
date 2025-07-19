## 🧠 **Git & GitHub Learning Roadmap**

### 🔰 1. **Git Basics (Core Concepts)**

| Concept      | Description                                        |
| ------------ | -------------------------------------------------- |
| `git init`   | Initialize a local Git repository                  |
| `git clone`  | Copy a repository from GitHub                      |
| `git status` | Check current status of working directory          |
| `git add`    | Stage changes for commit                           |
| `git commit` | Save changes to the repository                     |
| `git log`    | View commit history                                |
| `.gitignore` | Ignore specific files/folders from version control |

---

### 🌿 2. **Branching & Merging**

| Concept                      | Description                                    |
| ---------------------------- | ---------------------------------------------- |
| `git branch`                 | List, create, or delete branches               |
| `git checkout`               | Switch branches or restore files               |
| `git switch`                 | Modern way to switch branches                  |
| `git merge`                  | Merge one branch into another                  |
| Merge Conflicts              | Handle and resolve code conflicts during merge |
| Fast-forward vs. 3-way Merge | Understand different types of merges           |

---

### 🔁 3. **Remote Repositories (GitHub Integration)**

| Concept           | Description                             |
| ----------------- | --------------------------------------- |
| `git remote`      | Manage connections to remote repos      |
| `git push`        | Upload local commits to remote repo     |
| `git pull`        | Fetch + merge from remote repo          |
| `git fetch`       | Get changes from remote without merging |
| `origin`          | Default name of remote repo             |
| Tracking branches | Set up upstream tracking for branches   |

---

### 🧪 4. **Undoing Changes & Resetting**

| Concept       | Description                           |
| ------------- | ------------------------------------- |
| `git restore` | Restore files to last commit or stage |
| `git reset`   | Unstage or roll back commits          |
| `git revert`  | Create a new commit to undo changes   |
| `HEAD`        | Refers to current commit pointer      |
| `git stash`   | Temporarily save uncommitted changes  |

---

### 🧰 5. **GitHub Features**

| Concept           | Description                             |
| ----------------- | --------------------------------------- |
| Repositories      | Store and organize your codebase        |
| Commits & History | View detailed commit history            |
| Issues            | Track bugs or feature requests          |
| Pull Requests     | Propose changes, request reviews        |
| Fork              | Copy a repo to your account             |
| GitHub Actions    | CI/CD automation for testing/deployment |
| Projects          | Kanban-style task management            |
| Discussions       | Collaborate and discuss code ideas      |

---

### 🤝 6. **Collaboration Workflow**

| Workflow Step       | Tool                                       |
| ------------------- | ------------------------------------------ |
| Branching strategy  | `feature/*`, `bugfix/*`, `main`, `develop` |
| Code review         | Pull Requests                              |
| Syncing forked repo | `git remote add upstream` + `fetch`        |
| Squash and merge    | Clean commit history                       |
| Rebase  **            | Linear history (advanced)                  |
| Tags & Releases     | Create versioned releases                  |

---

### 🧙 7. **Advanced Git**

| Concept     | Description                                      |
| ----------- | ------------------------------------------------ |
| Git rebase  | Re-apply commits on top of another base          |
| Cherry-pick | Apply a single commit from another branch        |
| Submodules  | Embed another Git repo inside your repo          |
| Hooks       | Automate tasks (pre-commit, post-merge)          |
| Git bisect  | Find the commit that introduced a bug            |
| Reflog      | View history of HEAD movements (undo disasters!) |

---

### 🔒 8. **Security & Access**

| Concept                  | Description                             |
| ------------------------ | --------------------------------------- |
| SSH Keys                 | Secure GitHub authentication            |
| Personal Access Tokens   | GitHub authentication (for CLI & CI)    |
| Collaborator Permissions | Read, write, admin levels               |
| Branch Protection Rules  | Prevent force push or unreviewed merges |

---
