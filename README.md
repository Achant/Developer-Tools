### General

- [X] Artifact produced is a [gist](https://gist.github.com/) with a Markdown file containing links and text

### Use the Shell Like a Pro

- [X] Artifact contains a list of 5-10 of the commands you find most useful.

1.) cd - Used to change the directory the shell is in.
2.) clear - Used to clear the view of the shell.
3.) ls - Used to list all of the visible files in a directory.
4.) alias/export - Used to create shortcuts for commands/Used to export alias commands into a file.
5.) cp – Copy a File.
6.) mv – Move and Rename Files.
7.) [up-arrow], [down-arrow] - Display commands history.
8.) cat - Used to display the contents of a file.
9.) sort - Used to sort a file.
10.) rm - Used to permanently remove a file, without sending it to the trash.

 - [X] Extra useful commands.

11.) * - Technically not a command, but a useful way to select all of one set of files.
12.) nano - Used to edit a file within the shell.
13.) man – Display Command Manual Files.
14.) pwd – Print Working Directory.
15.) wget – Retrieve files from remote locations.
16.) grep – Search Files or Output.
17.) tail – Display End of a File.

### Level Up your Debugging

- [X] Artifact includes a list of 3+ debugging tools that you found especially useful

1.) console.log() - A great tool for initial debugging. Generally used as a test to see if something is running.
2.) Chrome/Firefox Developer Tools - A variety of tools useful in displaying information as well as a variety of other things. Some of its uses are displaying HTML Elements, running the Javascript line by line via breakpoints, and displaying the console.
3.) console.count() - A tool used to count the number of times something has run.
4.) console.clear() - A tool used to clear the console.
5.) console.assert() - A tool used to evaluate an expression, and then run a message.
6.) console.dir() - Displays an interactive listing of the properties of a specified object.
7.) Console.group() - Creates a new inline group.
8.) Console.error() - Outputs an error message.
9.) Console.exception() - An alias for error().
10.) Console.debug() - An alias for log().
11.) Console.warn() - Outputs a warning message.

### Get Good at Git and GitHub

- [X] Sandbox **GitHub repository** is created and linked to in the artifact
https://github.com/Achant/super-tiger.git
- [X] Sandbox repo includes a `.gitignore` file with at least a few patterns included
- [X] Sandbox repo has at least one **pull request**

Artifact contains the **git commands** you used to...
- [X] **clone** a remote repository
git clone https://github.com/Achant/oop-practice.git Developer Tools
- [X] **stage** and unstage files for commit
git add .
git rm .
- [X] create a **commit** with a **commit message**
git commit -m "new .gitignore added"
- [X] **amend** the most recent commit message
git commit --amend "new new .gitignore added"
- [X] create and delete **branches**
git checkout -b little-tiger
git branch -d little-tiger
- [X] **push** to a remote repository
git push
- [X] **pull** a **feature branch** from a remote repository
git branch --track origin/feature-branch
- [x] push a **local branch** to a specific remote branch
(Once the branch you want is selected.)
git push remote-branch little-tiger
- [X] **revert** files back to a specific commit
git revert little-tiger
- [X] **rebase** a branch onto master
(Once the branch you want is selected.)
git rebase master
git checkout master
git rebase little-tiger
- [X] interactively rebase using the `--interactive` flag to squash, rename, and reorder commits
git rebase -i little-tiger
- [X] move specific commits between different branches with the `cherry-pick` command
(Once the branch you want is selected.)
git cherry-pick little-tiger

### Type Faster and Better

- [X] Artifact cites your best WPM (words per minute) score from Typing.io
Doug: 40 WPM
Amine: 30 WPM

### Practice Pair Programming
1.) pairing in roles(driver & navigator)
2.) pairing on the same computer
3.) giving feedback at the end of each day

### Master your Editor

- [X] Artifact contains a list of 3+ features of your editor that you discovered
1.) Side by side viewing of projects.
2.) Project tree view available.
3.) Numerous packages and themes to customize your workspace.
4.) Command + D - selects multiple lines of the same text.
5.) Find and replace text.
6.) Command + T - (Fuzzy Finder) search for any file you want.
7.) Command + \ - View and open files in your current project.
9.) Command + Shift + P - (project-manager) Easy access and management to all your projects. Allows for project specific settings and options.

- [X] Artifact contains a list of your favorite editor plugins

1.) Package Installer - allows you to search for packages or themes and install them as needed. 
2.) Minimap - Displays a navigatable overview of your code.
3.) Color Picker - Displays a color wheel when choosing HTML colors.
4.) Pigments - Makes the HTML selecting a color display the color itself.
5.) git-plus: Ctrl + Shift + H - Shortcuts to common git actions without needing to switch to your terminal.
6.) merge-conflicts - A very helpful tool for finding, previewing, and resolving merge conflicts within your project.
7.) emmet: tab - Expand abbreviations by Tab key. It also one of my favorites because it saves me so much time typing my code.
8.) docblockr - Makes writing documentation faster by detecting the details of the function below it and autofilling much of the comment.
9.) linter - Visualizes and notifies you of errors within your project. It is probably one of the most helpful packages.
10.) autocomplete-modules - Autocompletes require/import statements for you by following the path you type and showing you the available files at that location.
11.) auto-update-packages - Updates your packages automatically by checking for updates at the interval defined in it's settings.
12.) Beautify - Beautifies your code
13.) simple-drag-drop-text - Highlight text to drag and drop it somewhere else in your code.
14.) highlight-selected - When you double click a word, it and every other matching word in the file becomes highlighted.


### Setup Homebrew and Install Some Packages

- [X] A `Brewfile` with your favorite Homebrew packages is linked from the artifact
https://github.com/hhhhhaaaa/Brewfile

### Stretch

### Make Your Own Dotfiles

- [ ] Dotfiles repo exists in your personal GitHub account
- [ ] Artifact includes link to dotfiles repo

### Build an Atom Package

- [ ] Installable Atom package is published as a repo on your personal GitHub account
- [ ] Artifact includes link to Atom package repo
