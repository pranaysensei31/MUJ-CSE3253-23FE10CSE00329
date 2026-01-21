# Git Workflow Documentation

## 1. GitFlow vs GitHub Flow
### GitFlow
- Uses multiple long-running branches like main, develop, release, feature, hotfix.
- Best for large projects with planned releases.

### GitHub Flow
- Uses short-lived feature branches + pull requests into main.
- Best for continuous delivery and small fast-moving teams.

## 2. When to use Rebase vs Merge
### Rebase
- Used to maintain a clean linear commit history.
- Best before merging feature branch into develop/main.

### Merge
- Preserves complete history including branch structure.
- Best when you want to record exact merge points.

## 3. Commit Message Conventions
- Use short meaningful messages.
- Examples:
  - "Added login.html and auth.js"
  - "Fixed merge conflict in styles.css"
  - "Hotfix: critical bug fix"

## 4. Pull Request Template
### Title
[Feature/Bugfix/Hotfix] Short description

### Description
- What changes were made?
- Why were the changes needed?

### Testing
- How was it tested?
- Screenshots/output if needed.

### Checklist
- [ ] Code compiles/runs
- [ ] No unnecessary files committed
- [ ] Proper commit messages
