# **Git Fundamentals Cheat Sheet**  
🚀🔥
## **1️⃣ Getting Started with Git**  
### **Why Use Git?**  
✅ Track changes and maintain version history.  
✅ Collaborate seamlessly with others.  
✅ Work offline and sync when needed.  

### **Basic Terminal Navigation**  
| **Command** | **Description** |
|------------|-------------|
| `ls` | List directory contents. |
| `cd <directory>` | Change to a specific directory. |

### **Initializing a Git Repository**  
| **Command** | **Description** |
|------------|-------------|
| `git init <repo-name>` | Create a new Git repository. |
| `cd <repo-name>` | Navigate into the repository. |

### **Tracking and Committing Files**  
| **Command** | **Description** |
|------------|-------------|
| `git add <file>` | Stage a specific file. |
| `git add .` | Stage all modified files. |
| `git commit -m "message"` | Commit staged changes with a message. |

---

## **2️⃣ Understanding How Git Stores Data**  
### **Git’s Data Structure**  
🔹 **Commit** → A snapshot of changes with metadata.  
🔹 **Tree** → Tracks file names and locations.  
🔹 **Blob** → Compressed file contents.  

### **Viewing Version History**  
| **Command** | **Description** |
|------------|-------------|
| `git log` | Show commit history. |
| `git log --since="YYYY-MM-DD"` | Show commits after a specific date. |
| `git log --until="YYYY-MM-DD"` | Show commits before a specific date. |
| `git show <commit-hash>` | View details of a specific commit. |

---

## **3️⃣ Comparing Changes in Git**  
| **Command** | **Description** |
|------------|-------------|
| `git diff report.md` | Show changes between an unstaged file and the latest commit. |
| `git diff --staged report.md` | Show changes between a staged file and the latest commit. |
| `git diff <commit1> <commit2>` | Compare differences between two commits. |
| `git diff HEAD~1 HEAD~2` | Compare the last two commits. |

---

## **4️⃣ Undoing Changes in Git**  
| **Command** | **Description** |
|------------|-------------|
| `git revert HEAD` | Revert the last commit (creates a new commit). |
| `git revert HEAD --no-edit` | Revert without opening an editor. |
| `git revert HEAD -n` | Revert without committing immediately. |
| `git checkout HEAD~1 -- report.md` | Restore a file to its previous state from the last commit. |
| `git restore --staged report.md` | Unstage a single file (move it back to the working directory). |
| `git restore --staged` | Unstage all files. |

---
