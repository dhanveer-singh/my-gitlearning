
# What is Git?
Git is an open source, distributed version control system that helps developers collaborate on projects of any scale.Linus Torvalds, the developer of the Linux kernel, created Git in 2005 to help control the Linux kernel's development.

# Git Download and Installation
Git Download Link: https://git-scm.com/

<blockquote>
    Launch Git Bash after installation.
</blockquote>

# What is Git Bash?
Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience. Bash is an acronym for Bourne Again Shell. A shell is a terminal application used to interface with an operating system through written commands. Bash is a popular default shell on Linux and macOS. Git Bash is a package that installs Bash, some common bash utilities, and Git on a Windows operating system.

<p>Check version in Git Bash:<p/>
<code>git --version</code>

# Configure Git 
<p>Configuring user information used across all local repositories</p>
<blockquote>
If you want to use a different username or email address for a specific repository, run the git config command without the --global option from within the repository directory.
</blockquote>

<ol>
    <li>
        <b>How to set your global username configuration?</b><br>
        <code>git config --global user.name [username]</code> <br>
    </li>
     <li>
        <b>How to set your global email configuration?</b><br>
        <code>git config --global user.email [email]</code> <br>
    </li>
</ol>

# Verify Git configuration
The command below returns a list of information about your git configuration including user name and email.

<ol>
    <li>
        <b>How to check your Git configuration?</b><br>
        <code>git config --list</code> <br>
    </li>
</ol>

# Initialise Git inside your project

<ol>
    <li>
        <b>How to initialize/add a git repo in your project?</b><br>
        <code>git init</code>
    </li>
    <li>
        <b>Displays the state of the working directory and the staging area</b><br>
        <code>git status</code>
    </li>
     <li>
        <b>Create new file via gitbash</b><br>
        <code>touch [filename]</code>
    </li>
    <li>
        <b>How to remove .git repo from your project?</b><br>
        <code>rm -rf .git</code>
    </li>
</ol>

# Staging area
The staging area can be described as a preview of your next commit.

<ol>
     <li>
        <b>Add a file as it looks new to your next commit (stage)</b><br>
        <code>git add [filename]</code>
    </li>
    <li>
        <b>Add all files or new changes to the repository</b><br>
        <code>git add --a</code>
    </li>
    <li>
        <b>How to show list of folder and files?</b><br>
        <code>ls --lart</code>
    </li>
    <li>
        <b>Remove or untrack added file from staging-area</b><br>
        <code>git rm --cached [filename]</code>
    </li>
    <li>
        <b>Remove or Delete file from working directory</b><br>
        <code>git rm [filename]</code>
    </li>
</ol>

# Git Commit
It is used to record the changes in the repository. It is the next command after the git add. Every commit contains the index data and the commit message.

<ol>
    <li>
        <b>How to check origin URL of remote repo?</b><br>
        <code>git remote -v</code>
    </li>
    <li>
        <b>Commit your staged content as a new commit snapshot</b><br>
        <code>git commit -m “[descriptive message]”</code>
    </li>
    <li>
        <b>How to check history of commits?</b><br>
        <code>git log -p -[Number of commits]</code>
    </li>
</ol>

# Branch & Merge
Isolating work in branches, changing context, and integrating changes.

<ol>
    <li>
        <b>Create New Branch from master branch</b><br>
        <code>git branch [branchname] or git checkout -b [branchname]</code>
    </li>
    <li>
        <b>Check all existing branches</b><br>
        <code>git branch</code>
    </li>
    <li>
        <b>Switch to another branch</b><br>
        <a>git checkout [branchname]</code>
    </li>
</ol>

# Useful Links
<ol>
    <li>
        <b>This tool will describe commands</b><br>
        https://explainshell.com/
    </li>
   
</ol>
