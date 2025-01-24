user@DESKTOP-88F2675 MINGW64 ~ (master)
$ cd C:\Users\Saeed younedi\my-project
bash: cd: too many arguments

user@DESKTOP-88F2675 MINGW64 ~ (master)
$ git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --[no-]verbose    be more verbose
    -q, --[no-]quiet      be more quiet
    --[no-]progress       force progress reporting
    --[no-]reject-shallow don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --checkout            opposite of --no-checkout
    --[no-]bare           create a bare repository
    --[no-]mirror         create a mirror repository (implies --bare)
    -l, --[no-]local      to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    --hardlinks           opposite of --no-hardlinks
    -s, --[no-]shared     setup as shared repository
    --[no-]recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --[no-]recursive ...  alias of --recurse-submodules
    -j, --[no-]jobs <n>   number of submodules cloned in parallel
    --[no-]template <template-directory>
                          directory from which templates will be used
    --[no-]reference <repo>
                          reference repository
    --[no-]reference-if-able <repo>
                          reference repository
    --[no-]dissociate     use --reference only while cloning
    -o, --[no-]origin <name>
                          use <name> instead of 'origin' to track upstream
    -b, --[no-]branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --[no-]upload-pack <path>
                          path to git-upload-pack on the remote
    --[no-]depth <depth>  create a shallow clone of that depth
    --[no-]shallow-since <time>
                          create a shallow clone since a specific time
    --[no-]shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --[no-]single-branch  clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --tags                opposite of --no-tags
    --[no-]shallow-submodules
                          any cloned submodules will be shallow
    --[no-]separate-git-dir <gitdir>
                          separate git dir from working tree
    --[no-]ref-format <format>
                          specify the reference format to use
    -c, --[no-]config <key=value>
                          set config inside the new repository
    --[no-]server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --[no-]filter <args>  object filtering
    --[no-]also-filter-submodules
                          apply partial clone filters to submodules
    --[no-]remote-submodules
                          any cloned submodules will use their remote-tracking branch
    --[no-]sparse         initialize sparse-checkout file to include only files at root
    --[no-]bundle-uri <uri>
                          a URI for downloading bundles before fetching from origin remote


user@DESKTOP-88F2675 MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/user/.git/

user@DESKTOP-88F2675 MINGW64 ~ (master)
$ git odd
git: 'odd' is not a git command. See 'git --help'.

The most similar command is
        add

user@DESKTOP-88F2675 MINGW64 ~ (master)
$ git odd . C:/Users/user/.git/
git: 'odd' is not a git command. See 'git --help'.

The most similar command is
        add

user@DESKTOP-88F2675 MINGW64 ~ (master)
$ git commit -m "Initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'user@DESKTOP-88F2675.(none)')

user@DESKTOP-88F2675 MINGW64 ~ (master)
$ git remote add origin https://github.com/danie1837030/my-project.git

user@DESKTOP-88F2675 MINGW64 ~ (master)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/danie1837030/my-project.git'

user@DESKTOP-88F2675 MINGW64 ~ (master)
$ echo "# my-projects" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/daniel837030/my-projects.git
git push -u origin main
Reinitialized existing Git repository in C:/Users/user/.git/
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'user@DESKTOP-88F2675.(none)')
error: remote origin already exists.
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/danie1837030/my-project.git'

user@DESKTOP-88F2675 MINGW64 ~ (main)
$ git remote add origin https://github.com/daniel837030/my-projects.git
git branch -M main
git push -u origin main
error: remote origin already exists.
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/danie1837030/my-project.git'

user@DESKTOP-88F2675 MINGW64 ~ (main)
$ git commit --amend -m "3rd commit"
fatal: You have nothing to amend.

user@DESKTOP-88F2675 MINGW64 ~ (main)
$ git log --oneline
fatal: your current branch 'main' does not have any commits yet

user@DESKTOP-88F2675 MINGW64 ~ (main)
$
