# GitDemo2025
This is a Demo for Git &amp; Github class

# Author 
Sudesh Dhangada


## Why Git May Not Recognize Code Changes

If Git is not recognizing your code changes, consider the following:

- **File Not Tracked:** Make sure the file is added to Git using `git add <filename>`.
- **No Actual Changes:** Ensure you have saved your changes. Unsaved edits won't be detected.
- **.gitignore File:** Check if your file is listed in `.gitignore`, which prevents Git from tracking it.
- **Line Endings:** Sometimes, only line endings change (CRLF vs LF), which may not be obvious.
- **Staging Area:** If you've already staged changes, use `git status` to see what's pending commit.

Use `git status` to check the current state and `git diff` to view changes.