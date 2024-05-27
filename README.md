Creating a Pull Request
1.Fork the Repository: If you haven’t already, fork the repository you want to contribute to.
This creates a copy of the repository under your account.
2.Clone Your Fork: Clone your forked repository to your local machine using the git clone
command.
git clone <repository_URL>
3.Create a Branch: Create a new branch to work on your changes. It’s good practice to create
a separate branch for each feature or issue you’re addressing.
git checkout -b <branch_name>
4.Make Changes: Make the necessary changes to the codebase on your local branch.
5.Commit Changes: Once you’ve made your changes, commit them to your local repository
with descriptive commit messages.
git add .
git commit -m "Description of changes"
6.Push Changes: Push your local branch to your forked repository on the Git hosting platform.
git push origin <branch_name>
7.Create Pull Request: Navigate to your forked repository on the Git hosting platform and click
on the “Pull Request” button.
8.Select Branches: Choose the branch you pushed your changes to in your fork as the
“compare” branch, and the original repository’s branch you want to merge into as the “base”
branch.
9.Review Changes: Provide a title and description for your pull request, summarizing the
changes you made. You can also include any relevant context or details.
Template For Pull Request
1. Please give clear description and fill all the needed fields in the PR template below
2.Provide all the test report and results for the PR. It is mandatory. Otherwise,
your PR may get rejected without any review/discussion
3. If the PR is incomplete/in progress, please add [WIP] at the beginning of the PR title.
4. Provide the link to the issue and other relevant files related to the PR
-->
**What type of PR is this?**
> Uncomment only one ` /kind <>` line, hit enter to put that in a new line, and remove
leading whitespace from that line:
>
> /kind new feature
> /kind bug fix
> /kind cleanup
> /kind revert change
> /kind design
> /kind documentation
> /kind enhancement
**What this PR does / why we need it**:
**Which issue(s) this PR fixes**:
<!--
*Please provide the issues number or link.
Usage: `Fixes #<issue number>`, or `Fixes (paste link of issue)`.
-->
Fixes #
22BCAA54 Basics of Open Source Demystified Lab Record
Kristu Jayanti College (Autonomus) 14
**Test Report Added?**:
> Uncomment only one ` /kind <>` line, hit enter to put that in a new line, and remove
leading whitespace from that line:
> /kind TESTED
> /kind NOT-TESTED
**Test Report**:
<!--
*Please provide the test report link (public accessible, screen shot or copy paste the test report,
or add the testing details
