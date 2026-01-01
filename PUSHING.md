# Pushing this repo to GitHub

This workspace already has your commits locally on the `work` branch. To push them to GitHub:

1. Make sure your changes are committed:
   ```bash
   git status
   git add <files>
   git commit -m "Your message"
   ```
2. Add the GitHub remote (only needed once). Replace the URL with your repository:
   ```bash
   git remote add origin https://github.com/<your-user>/<your-repo>.git
   ```
   If the remote exists but is wrong, update it with `git remote set-url origin <url>`.
3. Push the current branch and set upstream:
   ```bash
   git push -u origin work
   ```
   After the first push, you can use `git push` for subsequent updates.

You can run these commands directly in this terminal; a browser is not required except to create a pull request after pushing.
