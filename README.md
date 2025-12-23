Level 1: Introduction to Git Commits
* A **commit** represents a snapshot of the project at a point in time.
* Each new commit points to the previous commit.
* The `main` branch automatically moves forward with each commit.
<img width="1913" height="906" alt="Screenshot 2025-12-17 110624" src="https://github.com/user-attachments/assets/5fcf0873-1928-401b-b08d-5c8aba3d74a3" />

### 🛠 Commands Used

```bash
git commit -m "My new commit"
git commit -m "My new commit"
```



Level 2: Branching in Git



* Branches allow working on features or fixes independently.
* `git branch` creates a new branch.
* `git checkout` switches to that branch.
* Multiple branches can point to the same commit initially.
<img width="1917" height="889" alt="Screenshot 2025-12-17 113029" src="https://github.com/user-attachments/assets/63b55166-a2c5-44fe-bda0-96177984a8d3" />

### 🛠 Commands Used

```bash
git branch bugfix
git checkout bugfix
```

Level 3: Merging in Git
<img width="1910" height="919" alt="Screenshot 2025-12-23 104719" src="https://github.com/user-attachments/assets/0761136e-a553-414a-8161-5768a192fc41" />
### 🛠 Commands Used
```bash
git branch bugfix
git checkout bugfix
git commit
git checkout main
git commit
git merge bugfix
```

Level 4: Rebase introduction
<img width="1919" height="902" alt="Screenshot 2025-12-23 121909" src="https://github.com/user-attachments/assets/fe598b6e-b559-4ce9-a9c0-9e16d1408360" />

### 🛠 Commands used
```bash
git checkout -b bugfix
git commit
git checkout main
git commit
git checkout bugfix
git rebase main
```


