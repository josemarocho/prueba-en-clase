REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto
$ git init
Initialized empty Git repository in C:/Users/REDES/Documents/proyecto/.git/

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ code .

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        inex.html/

nothing added to commit but untracked files present (use "git add" to track)

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git add .

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   inex.html/index.html


REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git commit -m "mi primer commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'REDES@DESKTOP-IPSDPAH.(none)')

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   inex.html/index.html


REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git config--global user name "josemarocho"
git: 'config--global' is not a git command. See 'git --help'.

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git config --globalusername "josemarocho"
error: unknown option `globalusername'
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git config --global username "josemarocho"
error: key does not contain a section: username

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git config --global use.name.emailjosemarocho@example.com

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   inex.html/index.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    inex.html/index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html


REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git add .

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html


REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git commit -m "mi primer commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'REDES@DESKTOP-IPSDPAH.(none)')

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git config --global user.name prueba

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git config --global user.name "prueba"

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git config --global user.email prueba@gmail.com

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git user.name
git: 'user.name' is not a git command. See 'git --help'.

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git commit -m "mi primer commit"
[master (root-commit) 16c5bdb] mi primer commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git add .

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git status
On branch master
nothing to commit, working tree clean

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git commit -m "mi segundo commit"
On branch master
nothing to commit, working tree clean

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git commit -m "mi segundo commit"
On branch master
nothing to commit, working tree clean

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git remote add origin https://github.com/josemarocho/prueba-en-clase.git

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (master)
$ git branch -M main

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$ git push -u origin main






REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$ git config --global user.name "josemarocho"

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$ git config --global user.email josemarocho123@gmail.com

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$ git remote add origin https://github.com/josemarocho/prueba-en-clase.git
error: remote origin already exists.

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$ git branch -M main

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 206 bytes | 206.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/josemarocho/prueba-en-clase.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

REDES@DESKTOP-IPSDPAH MINGW64 ~/Documents/proyecto (main)
$
