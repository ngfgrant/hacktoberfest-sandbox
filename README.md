# Hacktoberfest Sandbox


# How to Contribute

- "Fork" this repository
- "Clone" your fork
- Add the "upstream" remote so you can update from the main project `git remote add upstream https://github.com/ngfgrant/hacktoberfest-sandbox.git`
- Create a branch `git checkout -b your-branch-name`
- Make the change to docs/index.html
- Stage your changes with `git add docs/index.html`
- Commit your staged changes with `git commit` this will open up a text editor on the top line of the editor write your commit message, save and quit.
- Push your changes to your remote fork with `git push -u origin your-branch-name`
- Go to GitHub and view your fork you should be able to open up a Pull Request (make sure the pull request target is this repo `ngfgrant/hacktoberfest-sandbox`. The output from the last step should also give you a link to go to to open up a Pull Request.
- Once open you should see your Pull Request open on this repo!


If your PR has conflicts with the main repo you will need to rebase

- Get the changes from the main project but don't merge them `git fetch upstream`
- Now update your branch `git rebase upstream/master` or `git merge upstream/master`

Congratulations!
