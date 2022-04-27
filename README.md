# Starting New Repo | GIT (main)

Git is a version control system.
They are also called source code management tool.

SCCS (Source Code Control System)
RCS (Revision Control System)
CVS (Concurrent Version System)
SVN (Apache Subversion)
BitKeeper SCM
GIT (Distributed Version Control)

Git stores configuration at 3 places.

1. System (Program Files/Git/etc/gitconfig)

2. User ($HOME/.gitconfig)

3. Project (local to a project)

Commands
1. $ git config --system (System)
2. $ git config --global (User)
3. $ git config (Project)

Configurations we can set
1. git config --global user.name "Himanshu"
2. git config --global user.email "himanshucasillas@nothing.com"

"SPACE to get all in git config"

$ git config user.name (Shows user name)
 
$ git config --global core.editor "vim"

$ git config --global color.ui true

# Git Help

$git help COMAND_NAME
$git help cherry-pick


user@ ~/Desktop/git/.git (GIT_DIR!)
$ ls
COMMIT_EDITMSG  config       hooks/  info/  objects/
HEAD            description  index   logs/  refs/

## Commit Message
1. should be less than 50 characters. Commits are in present tens. 
#### GOOD/ BAD Examples
1. BAD - "Fix Typo"
2. GOOD - "Added Missing Hypen in index.html"
3. BAD - "Updated Login"
4. GOOD - "Changed User Authentication to use Blowfish"

## View Commits

###### $git log
###### $git log -n 5 (recent 5)
###### $git log --since=2020-01-01
###### $git log --until=2020-01-01
###### $git log --grep="Init" (Any commit which has Init at start.)







