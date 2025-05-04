
HQ@DESKTOP-NQPLIN1 MINGW64 ~ (master)
$ mkdir learn_git
mkdir: cannot create directory ‘learn_git’: File exists

HQ@DESKTOP-NQPLIN1 MINGW64 ~ (master)
$ cd learn_git

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ touch third.txt

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git init
Reinitialized existing Git repository in C:/Users/HQ/learn_git/.git/

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git add third.txt

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git commit -m "adding third.txt"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HQ@DESKTOP-NQPLIN1.(none)')

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git log
fatal: your current branch 'master' does not have any commits yet

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ touch fourth.txt

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git add fourth.txt

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git commit -m "adding fourth.txt"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HQ@DESKTOP-NQPLIN1.(none)')

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ rm third.txt

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git add .

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git commit -m "removing third.txt"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HQ@DESKTOP-NQPLIN1.(none)')

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git log
fatal: your current branch 'master' does not have any commits yet

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git config --global core.pager cat

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git config --global --list
gui.recentrepo=C:/Users/HQ
core.pager=cat

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   fourth.txt


HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git commit -m "adding fourth.txt"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HQ@DESKTOP-NQPLIN1.(none)')

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git status
bash: $'\302\226git': command not found

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   fourth.txt


HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git add .

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   fourth.txt


HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git commit -m "adding fourth.txt"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HQ@DESKTOP-NQPLIN1.(none)')

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-regex]
    --get-all             get all values: key [value-regex]
    --get-regexp          get values for regexp: name-regex [value-regex]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value_regex]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-regex]
    --unset-all           remove all matches: name [value-regex]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --path                value is a path (file or directory name)

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)


HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ ^C

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git config  --global user.email "bradfordottun@gmail.com"

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git config  --global user.name "bradford"

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   fourth.txt


HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git commit -m "adding fourth.txt"
[master (root-commit) bab4ca4] adding fourth.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fourth.txt

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ echo "# ayo" >> README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/koseunti/ayo.git
git push -u origin main
HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git init
Reinitialized existing Git repository in C:/Users/HQ/learn_git/.git/

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory.

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git commit -m "first commit"
[master c1709b6] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (master)
$ git branch -M main

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (main)
$ git remote add origin https://github.com/koseunti/ayo.git

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (main)
$ git push -u origin main
fatal: HttpRequestException encountered.
   An error occurred while sending the request.
Username for 'https://github.com':
remote: No anonymous write access.
fatal: Authentication failed for 'https://github.com/koseunti/ayo.git/'

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (main)
$ git add .

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (main)
$ git commit -m "adding images.png"
[main 67b22ec] adding images.png
 6 files changed, 1 insertion(+)
 create mode 100644 MINGW64__c_Users_HQ_learn_git 5_4_2025 3_24_14 PM.png
 create mode 100644 MINGW64__c_Users_HQ_learn_git 5_4_2025 3_27_12 PM.png
 create mode 100644 MINGW64__c_Users_HQ_learn_git 5_4_2025 3_27_25 PM.png
 create mode 100644 MINGW64__c_Users_HQ_learn_git 5_4_2025 3_27_39 PM.png
 create mode 100644 MINGW64__c_Users_HQ_learn_git 5_4_2025 3_27_59 PM.png

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (main)
$ git status
On branch main
nothing to commit, working tree clean

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main


HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (main)
$ git remote add origin https://github.com/koseunti/ayo.git
fatal: remote origin already exists.

HQ@DESKTOP-NQPLIN1 MINGW64 ~/learn_git (main)
$
