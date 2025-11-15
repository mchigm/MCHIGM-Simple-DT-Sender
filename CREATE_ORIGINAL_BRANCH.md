# Creating the Original Branch

This document explains how to create the public 'Original' branch for this repository.

## Automated Method (Recommended)

A GitHub Actions workflow has been created to automatically create the 'Original' branch.

### Steps:
1. Go to the Actions tab in the GitHub repository: https://github.com/mchigm/MCHIGM-Simple-DT-Sender/actions
2. Click on "Create Original Branch" workflow in the left sidebar
3. Click the "Run workflow" button on the right side
4. Select the branch to run from (typically 'main' or current branch)
5. Click the green "Run workflow" button
6. Wait for the workflow to complete (should take less than a minute)

The workflow will:
- Create a new branch named 'Original' from commit `086cbfe` (the base merge commit)
- Push it to the remote repository
- Make it publicly available

## Manual Method

If you prefer to create the branch manually, you can run these commands locally:

```bash
# Fetch all commits
git fetch --all

# Create the Original branch from the base commit
git checkout -b Original 086cbfe065994cc757311d5555ecbed2ee934101

# Push it to the remote repository
git push -u origin Original
```

## Branch Details

- **Branch Name**: Original
- **Base Commit**: 086cbfe065994cc757311d5555ecbed2ee934101
- **Commit Message**: "Merge pull request #1 from mchigm/copilot/add-files-to-main"
- **Purpose**: Preserve the original state of the repository

Once created, the 'Original' branch will be publicly visible on GitHub.
