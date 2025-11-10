# Terminal commands learned
Yes. For **Day 2 (Git + GitHub setup)** you must remember these core commands — they’re the foundation of all version control work.

---

### **1. Local repository basics**

| Action          | Command                           | Meaning                                           |
| --------------- | --------------------------------- | ------------------------------------------------- |
| Initialize repo | `git init`                        | Start tracking version history in current folder. |
| Check status    | `git status`                      | Show new/modified files.                          |
| Add files       | `git add filename` or `git add .` | Stage files for commit.                           |
| Commit          | `git commit -m "message"`         | Save staged changes locally.                      |
| View history    | `git log --oneline`               | List commits.                                     |

---

### **2. Remote connection**

| Action          | Command                       | Meaning                            |
| --------------- | ----------------------------- | ---------------------------------- |
| Add remote link | `git remote add origin <URL>` | Connect local repo to GitHub.      |
| View remotes    | `git remote -v`               | Verify remote URLs.                |
| Rename branch   | `git branch -M main`          | Set main branch name.              |
| Push code       | `git push -u origin main`     | Upload local commits to GitHub.    |
| Pull updates    | `git pull`                    | Download and merge remote changes. |

---

### **3. Configuration**

| Command                                            | Purpose                 |
| -------------------------------------------------- | ----------------------- |
| `git config --global user.name "kai"`              | Set commit author name. |
| `git config --global user.email "you@example.com"` | Set commit email.       |
| `git config --list`                                | View current config.    |

