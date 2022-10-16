# gitlearning
This repo is a part of learning about Git and Github

<h2>Git Download and Installation</h2>
Git Download Link: https://git-scm.com/

To check git version: git --version

<h2>Setup</h2>
<p>Configuring user information used across all local repositories</p>
<ol>
    <li>
        <b>#Username/email and Password setup</b><br>
        <code>git config --global user.name [username]</code> <br>
        <code>git config --global user.email [email]</code> <br>
        <code>git config --global user.password [password]</code>
    </li>
</ol>

<h2>Initialise git inside your project</h2>
<ol>
    <li>
        <b>#Initialize an existing directory as a Git repository</b><br>
        <code>git init</code>
    </li>
    <li>
        <b>#show all folder and files List</b><br>
        <code>ls --lart</code>
    </li>
    <li>
        <b>#Displays the state of the working directory and the staging area</b><br>
        <code>git status</code>
    </li>
    <li>
        <b>#Create new file via gitbash</b><br>
        <code>touch [filename]</code>
    </li>
    <li>
        <b>#Add a file as it looks new to your next commit (stage)</b><br>
        <code>git add [filename]</code>
    </li>
    <li>
        <b>#Add all files or new changes to the repository</b><br>
        <code>git add --a</code>
    </li>
    <li>
        <b>#Remove or untrack added file from staging-area</b><br>
        <code>git rm --cached [filename]</code>
    </li>
    <li>
        <b>#Remove or Delete file from working directory</b><br>
        <code>git rm [filename]</code>
    </li>
    <li>
        <b>#Commit your staged content as a new commit snapshot</b><br>
        <code>git commit -m “[descriptive message]”</code>
    </li>
</ol>

<h2>Branch & Merge</h2>
<p>Isolating work in branches, changing context, and integrating changes</p>
<ol>
    <li>
        <b>#Create New Branch from master branch</b><br>
        <code>git branch [branchname] or git checkout -b [branchname]</code>
    </li>
    <li>
        <b>#Check all existing branches</b><br>
        <code>git branch</code>
    </li>
    <li>
        <b>#Switch to another branch</b><br>
        <code>git checkout [branchname]</code>
    </li>
</ol>
