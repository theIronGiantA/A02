# A02 | Webstorm/Git/Github Tutorial

Step 1: Install WebStorm
- Download WebStorm from JetBrains website: https://www.jetbrains.com/webstorm/
- Install the right Webstorm according to your operating system like windows or mac os, etc.

Step 2: Install Git
- Download Git from https://git-scm.com/downloads.
- Use default settings once you install Git.
- Check if Git was installed correctly by putting git --version in a terminal.

Step 3: Create a GitHub Account
- Go to https://github.com/.
- Create an account.
- Make a new repository by pressing "New" under the Repositories tab.

Step 4: Make Sure Git runs correctly with Webstorm
- Open WebStorm, after which thoroughly proceed to each of File > Settings > Version Control > Git.
- Guarantee that WebStorm  detects Git. Or, manually set the Git executable path.
- Click "Test" to verify the entire configuration. This checks all settings.

Step 5: CLoning Process
- In WebStorm, go to File > New > Project. Then select 'from Version Control'.
- After choosing Git, carefully enter the GitHub repository URL.
- After choosing a directory for project storage, select "Clone".

Step 6: Making Changes
- Open your project in WebStorm.
- After a file is modified, save the changes.
- Highlight the changed files then click Commit.
- Before clicking Commit, enter a commit message that means something.

Step 7: Push Changes to Github
- To push after a commit, click VCS > Git > Push.
- After choosing the remote repository and branch, click "Push".

Step 8: Fetch & Pull Changes
- Click VCS, then Git, then Fetch to check for remote updates.
- Use VCS > Git > Pull to download and merge all updates into your local branch.

Step 9: Branch & Merge
- Go to VCS > Git > Branches > New Branch to create a new branch.
- Switch branches by using the Branches menu.
- Branches are merged through VCS > Git > Merge Changes.

Step 10: Merge Conflicts
- WebStorm will point out the conflicting files. This will occur if there is a merge conflict.
- Open the file after reviewing the changes and resolving conflicts manually.
