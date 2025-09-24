# Contributing to UI Training Curriculum

This guide will help you understand the proper workflow, branch structure, and best practices to ensure a smooth collaboration.

---

## 1. Branching Strategy

Each participant should work on their own branch for the assigned week:

- Branch naming convention: `week-01-yourname`
- Always start your branch from `master`.
- Do not push directly to `master`.

---

## 2. Weekly Workflow

1. **Create your branch** for the week.
2. **Complete tasks** listed in `tasks.md` for that week.
3. **Add your project code** inside the `project/` folder of the corresponding week.
4. **Commit your changes** frequently with clear messages.

---

## 3. Commit Guidelines

- Write clear, descriptive commit messages using the following format: 
``` txt
[CODE] FULL DESCRIPTION
```
Where `XXX` is a three-letter code representing the type of change.

### Commit Type Codes

| Code | Meaning | Description |
|------|--------|-------------|
| DEV  | Development | Adding new features or developing functionality |
| FIX  | Bug Fix | Fixing bugs or issues in the code |
| DOC  | Documentation | Changes in documentation, README, or comments |
| TST  | Test | Adding or modifying tests |
| REF  | Refactor | Code restructuring or cleanup without changing behavior |
| CFG  | Config | Changes in configuration, setup, or build files |
| CHG  | Change | General or minor changes not covered by other types |
| PER  | Performance | Performance improvements or optimizations |
| ADD  | Add | Adding a new file to project |
| DEL  | Delete | Deleting a file from project |

- Examples:  
  - ✅ `[DEV] Add login form component`  
  - ✅ `[FIX] Correct validation logic for registration form`  
  - ✅ `[DOC] Update README with project instructions`  
  - ❌ `[DEV] stuff done` (too vague) 
  - ❌ `Update project login` (not in format)

- Use present tense: `Add`, `Fix`, `Update`.
- Keep commits focused: one logical change per commit.

---

## 4. Pull Requests (PRs)

- Open a PR from your branch to `main` when your daily's tasks are complete.
- Include a checklist in the PR description referencing tasks in `tasks.md`:

```markdown
- [ ] Task 1
- [ ] Task 2
- [ ] Task 3
```

- Assign the mentor (or reviewer) for feedback.
- Address requested changes and update your branch until approved.
- Merge only after approval.

---

## 5. Code Quality & Best Practices

- Follow clean coding practices and coding conventions.
- Maintain consistent indentation and formatting.
- Add comments when necessary to explain complex logic.
- Organize project files according to the folder structure.

---

## 6. Communication

- Use PR comments for questions or explanations.
- Be responsive to feedback.
- Ask for clarification if a task or feedback is unclear.

---

## 7. General Guidelines

- Respect deadlines and maintain weekly progress.
- Keep your code self-contained within your weekly folder.
- Use external resources responsibly; always cite if necessary.
- Focus on learning and applying best practices.

---

Following this guide ensures that your learning process is structured, transparent, and effective for both you and your mentor.
