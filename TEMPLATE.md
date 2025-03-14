## Cherry-picking a Commit from Another Repository

If you want to cherry-pick a commit from a different repository, follow these steps!

### 1. Add the remote repository:

```bash
git remote add student-hub https://github.com/MrImmortal09/student-hub.git
```

### 2. Fetch the changes:

```bash
git fetch student-hub
```

### 3. Cherry-pick the commit:

```bash
git cherry-pick a8633b1df549c983d294e3e2572f294568b19f87
```

### 4. Push the changes (if needed):

```bash
git push origin <your-branch>
```

Replace `<your-branch>` with your actual branch name. If there are conflicts, resolve them and continue:

```bash
git cherry-pick --continue
```

Now your commit is applied to your repo! 🚀

