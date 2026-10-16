# Contributing

Thanks for adding a tip! Follow these steps.

1. **Fork** this repository (the Fork button, top right).
2. **Clone your fork**, not this repository:

   ```bash
   git clone https://github.com/<your-username>/level-2-git-tips.git
   cd level-2-git-tips
   git remote -v
   ```

3. **Make a branch:**

   ```bash
   git switch -c add-my-tip
   ```

4. **Add one file** at `tips/<your-github-username>.md`. Copy the format from
   [`tips/example.md`](tips/example.md). Use your GitHub username, not your full name.
5. **Commit and push to your fork:**

   ```bash
   git add tips/<your-github-username>.md
   git commit -m "Add tip about <topic>"
   git push -u origin add-my-tip
   ```

6. **Open a pull request.** Before you click Create, check:
   - **base repository** is this repository, and **base** is `main`
   - **head repository** is your fork, and **compare** is `add-my-tip`
7. **Describe your change** in a sentence or two: what you added and why it's useful.

## Rules

- Change only your own file. Don't edit other people's tips or this file.
- Keep it to one short tip.
- Don't include personal information.
