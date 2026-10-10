# Code Review Assignment 1 Instructions

Fork the repository, add your assignment files, open a pull request (PR), and **@mention your assigned peer reviewer in a PR comment**.

## 1. Fork the repository

Open [the class repository](https://github.com/ucsc-cse-242/assignment1-code-reviews), click **Fork**, and then **Create fork** under your GitHub account.

## 2. Add you Assignment1 Code: choose one option

### Option A: Use the command line

With Git installed, replace `YOUR-USERNAME` with your GitHub username and run:

```bash
git clone https://github.com/YOUR-USERNAME/assignment1-code-reviews.git
cd assignment1-code-reviews
git switch -c assignment1-submission
```

Complete the assignment and check your code. Then commit and push your files, replacing `path/to/your-file` with the actual file path(s):

```bash
git add path/to/your-file
git commit -m "Complete assignment 1"
git push -u origin assignment1-submission
```

### Option B: Upload directly on GitHub

You do not need to install Git or clone the repository for this option.

1. Complete the assignment on your computer and check your code.
2. Open **your fork** on GitHub.
3. Click the branch dropdown (usually **main**), type `assignment1-submission`, and choose **Create branch**.
4. On that branch, select **Add file → Upload files** and upload your assignment files.
5. Enter a commit message, such as `Complete assignment 1`, and click **Commit changes**. If prompted, commit directly to `assignment1-submission`.

You can also edit files directly on GitHub using the pencil icon and commit your changes to the same branch.

## 3. Open a pull request

After completing either option:

1. Open your fork and click **Compare & pull request**. If you do not see it, select **Pull requests → New pull request**, then **compare across forks** if needed.
2. Check that the PR compares these repositories and branches:

   | Setting | Select |
   | --- | --- |
   | Base repository | `ucsc-cse-242/assignment1-code-reviews` |
   | Base branch | `main` |
   | Head repository | Your fork |
   | Compare branch | `assignment1-submission` |

3. Check the diff, enter a title such as `Assignment1: Your Name`, and briefly describe your work and how you checked it.
4. Click **Create pull request**.

## 4. Tag your peer reviewer

On your PR's **Conversation** tab, post a comment like this:

```text
@REVIEWER-USERNAME My assignment is ready for your code review.
```

Replace `REVIEWER-USERNAME` with your assigned reviewer's GitHub username, with no space after `@`, and click **Comment**. **The @mention must appear in a posted PR comment.**

If you make revisions after receiving feedback, push or upload them to the same branch; your PR will update automatically. Follow the assignment's Canvas submission requirements as well.

For help, see GitHub's guides to [pull requests from forks](https://docs.github.com/en/pull-requests/how-tos/create-pull-requests/creating-a-pull-request-from-a-fork) and [@mentions](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#mentioning-people-and-teams).
