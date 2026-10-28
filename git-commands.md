# 1. Initialize a Git Repository

Create a new local Git repository:

```bash
git init
```

This creates the hidden `.git` directory used by Git to store repository history and configuration.

---

# 2. Rename the Default Branch to Main

```bash
git branch -M main
```
---

# 3. Connect the Repository to GitHub

Add the GitHub repository as the remote named `origin`:

```bash
git remote add origin <repository-url>
```
Verify the configured remote:

```bash
git remote -v
```

---

# 4. Check Repository Status

```bash
git status
```
---

# 5. View the Current Branch

```bash
git branch --show-current
```
---

# 6. View Local Branches

```bash
git branch
```
The `*` represents the currently checked-out branch.

---

# 7. View Local and Remote Branches

```bash
git branch -a
```
This displays both local branches and remote-tracking branches.

---

# 8. Create branch

Create and switch to it:

```bash
git switch -c dev
```
Older Git syntax:

```bash
git checkout -b dev
```
---
# 9. Switch Between Branches

Switch to `main`:

```bash
git switch main
```
---
# 10. View Commit History

Full history:

```bash
git log
```

Compact history:

```bash
git log --oneline
```
---
# 11. Release tag command:

```bash
git tag -a v1.0.0 -m "First stable release"
```

Push:

```bash
git push origin v1.0.0
```
---
