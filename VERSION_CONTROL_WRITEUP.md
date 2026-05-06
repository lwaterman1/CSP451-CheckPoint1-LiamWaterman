# Version Control Systems, Understanding Git and GitHub

## Introduction to Version Control

Version control is an important tool in software development. It helps track changes made to files over time and allows developers to save different versions of their work. This makes it easier to manage projects, fix mistakes, and work in an organized way.

Git is a version control system used by developers around the world. It saves project changes in checkpoints called commits. Each commit records what changed, who made the change, and when the change was made. This creates a full history of the project.

## How Version Control Tracks Changes

Git tracks changes by creating commits. A commit is a saved version of the project at a specific point in time. Each commit includes a short message explaining what was updated.

This helps developers understand the history of a project. For example, if new code creates a problem, the team can look at earlier commits to find where the issue started. They can then fix the problem or return to a working version.

This makes project management easier and keeps work organized.

## Three Collaboration Benefits with Examples

### 1. Better teamwork

Git allows multiple people to work on the same project at the same time.

For example, one developer can work on a homepage while another developer works on a login page. Both can complete their work separately and combine it later.

### 2. Easier review of changes

Git records each update clearly.

For example, a commit message like `feat: add login page` explains what was added. Team members can review updates and understand project progress.

This improves communication and keeps work clear.

### 3. Easy recovery from mistakes

Git makes fixing mistakes simple.

For example, if code breaks a website, developers can go back to an earlier version that worked properly.

This saves time and protects work.

## Git's Backup and Recovery

Git stores project history in a hidden folder called `.git`. This folder keeps commits, branches, and project settings.

Git is also distributed, which means every copy of the project contains the full history. This creates a backup in more than one place.

Git also includes recovery tools such as:

- `git revert`
- `git reset`
- `git reflog`

These tools help recover lost work or undo mistakes.

## Difference Between Git and GitHub

| Git | GitHub |
|-----|--------|
| Version control tool | Online hosting platform |
| Runs on a computer | Runs on the web |
| Works offline | Used online |
| Tracks file changes | Stores and shares projects |
| Handles commits and branches | Supports collaboration tools |

Git is used to track project changes.

GitHub is used to store Git projects online and help teams work together.

## Conclusion

Version control is a key part of software development. It helps developers track changes, work together, and recover from mistakes. Git is a strong version control tool, and GitHub makes sharing and collaboration easier. Together, they improve the way software projects are built and managed.