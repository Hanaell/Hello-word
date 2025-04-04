Reinitialized existing Git repository in /home/karle.eyang@Digital-Grenoble.local/.git/
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ ls
 anaconda3   Downloads   Music      snap               Videos
 Desktop     Karl        Pictures   Templates          vmware
 Documents   monprojet   Public    'Untitled Folder'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ <!DOCTYPE htlml>
bash: !DOCTYPE: event not found
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ <head> <title> hello worlf<title>
bash: syntax error near unexpected token `<'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ </body>
bash: syntax error near unexpected token `newline'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ git add index.html
fatal: pathspec 'index.html' did not match any files
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ cd monprojet
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git config --global user.name "Blaire Wol"
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git config -- global user.email "hanaelleeyang.gmail.com"
error: key does not contain a section: global
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ^C
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git config --global user.email hanaelleeyang.gmail.com
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git init
Reinitialized existing Git repository in /home/karle.eyang@Digital-Grenoble.local/monprojet/.git/
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ pwd
/home/karle.eyang@Digital-Grenoble.local/monprojet
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ls
index.html
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add index.html
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add index.html style.css
fatal: pathspec 'style.css' did not match any files
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git commit -m " ajout du fichier html de base"
[master (root-commit) 1364226]  ajout du fichier html de base
 1 file changed, 13 insertions(+)
 create mode 100644 index.html
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add readme.txt
fatal: pathspec 'readme.txt' did not match any files
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add --all
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   readme .txt

(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git commit -m " Hello Ma belle"
[master b03e603]  Hello Ma belle
 1 file changed, 1 insertion(+)
 create mode 100644 readme .txt
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git commit -a
Aborting commit due to empty commit message.
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git  a- -m " merci"
git: 'a-' is not a git command. See 'git --help'.

The most similar command is
	am
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git log
commit b03e603c7dbc16f6bacd3b4de4528a853abede80 (HEAD -> master)
Author: Blaire Wol <hanaelleeyang.gmail.com>
Date:   Fri Apr 4 10:47:28 2025 +0200

     Hello Ma belle

commit 1364226880f2b53d575debf293ab1b9b3d1c4a1b
Author: Blaire Wol <hanaelleeyang.gmail.com>
Date:   Fri Apr 4 09:49:11 2025 +0200

     ajout du fichier html de base
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git command -help
git: 'command' is not a git command. See 'git --help'.
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git help --all
See 'git help <command>' to read about a specific subcommand

Main Porcelain Commands
   add                     Add file contents to the index
   am                      Apply a series of patches from a mailbox
   archive                 Create an archive of files from a named tree
   bisect                  Use binary search to find the commit that introduced a bug
   branch                  List, create, or delete branches
   bundle                  Move objects and refs by archive
   checkout                Switch branches or restore working tree files
   cherry-pick             Apply the changes introduced by some existing commits
   citool                  Graphical alternative to git-commit
   clean                   Remove untracked files from the working tree
   clone                   Clone a repository into a new directory
   commit                  Record changes to the repository
   describe                Give an object a human readable name based on an available ref
   diff                    Show changes between commits, commit and working tree, etc
   fetch                   Download objects and refs from another repository
   format-patch            Prepare patches for e-mail submission
   gc                      Cleanup unnecessary files and optimize the local repository
   gitk                    The Git repository browser
   grep                    Print lines matching a pattern
   gui                     A portable graphical interface to Git
   init                    Create an empty Git repository or reinitialize an existing one
   log                     Show commit logs
   maintenance             Run tasks to optimize Git repository data
   merge                   Join two or more development histories together
   mv                      Move or rename a file, a directory, or a symlink
   notes                   Add or inspect object notes
   pull                    Fetch from and integrate with another repository or a local branch
   push                    Update remote refs along with associated objects
   range-diff              Compare two commit ranges (e.g. two versions of a branch)
   rebase                  Reapply commits on top of another base tip
   reset                   Reset current HEAD to the specified state
   restore                 Restore working tree files
   revert                  Revert some existing commits
   rm                      Remove files from the working tree and from the index
   scalar                  A tool for managing large Git repositories
   shortlog                Summarize 'git log' output
   show                    Show various types of objects
   sparse-checkout         Reduce your working tree to a subset of tracked files
   stash                   Stash the changes in a dirty working directory away
   status                  Show the working tree status
   submodule               Initialize, update or inspect submodules
   switch                  Switch branches
   tag                     Create, list, delete or verify a tag object signed with GPG
   worktree                Manage multiple working trees

Ancillary Commands / Manipulators
   config                  Get and set repository or global options
   fast-export             Git data exporter
   fast-import             Backend for fast Git data importers
   filter-branch           Rewrite branches
   mergetool               Run merge conflict resolution tools to resolve merge conflicts
   pack-refs               Pack heads and tags for efficient repository access
   prune                   Prune all unreachable objects from the object database
   reflog                  Manage reflog information
   remote                  Manage set of tracked repositories
   repack                  Pack unpacked objects in a repository
   replace                 Create, list, delete refs to replace objects

Ancillary Commands / Interrogators
   annotate                Annotate file lines with commit information
   blame                   Show what revision and author last modified each line of a file
   bugreport               Collect information for user to file a bug report
   count-objects           Count unpacked number of objects and their disk consumption
   diagnose                Generate a zip archive of diagnostic information
   difftool                Show changes using common diff tools
   fsck                    Verifies the connectivity and validity of the objects in the database
   gitweb                  Git web interface (web frontend to Git repositories)
   help                    Display help information about Git
   instaweb                Instantly browse your working repository in gitweb
   merge-tree              Perform merge without touching index or working tree
   rerere                  Reuse recorded resolution of conflicted merges
   show-branch             Show branches and their commits
   verify-commit           Check the GPG signature of commits
   verify-tag              Check the GPG signature of tags
   version                 Display version information about Git
   whatchanged             Show logs with differences each commit introduces

Interacting with Others
   archimport              Import a GNU Arch repository into Git
   cvsexportcommit         Export a single commit to a CVS checkout
   cvsimport               Salvage your data out of another SCM people love to hate
   cvsserver               A CVS server emulator for Git
   imap-send               Send a collection of patches from stdin to an IMAP folder
   p4                      Import from and submit to Perforce repositories
   quiltimport             Applies a quilt patchset onto the current branch
   request-pull            Generates a summary of pending changes
   send-email              Send a collection of patches as emails
   svn                     Bidirectional operation between a Subversion repository and Git

Low-level Commands / Manipulators
   apply                   Apply a patch to files and/or to the index
   checkout-index          Copy files from the index to the working tree
   commit-graph            Write and verify Git commit-graph files
   commit-tree             Create a new commit object
   hash-object             Compute object ID and optionally create an object from a file
   index-pack              Build pack index file for an existing packed archive
   merge-file              Run a three-way file merge
   merge-index             Run a merge for files needing merging
   mktag                   Creates a tag object with extra validation
   mktree                  Build a tree-object from ls-tree formatted text
   multi-pack-index        Write and verify multi-pack-indexes
   pack-objects            Create a packed archive of objects
   prune-packed            Remove extra objects that are already in pack files
   read-tree               Reads tree information into the index
   symbolic-ref            Read, modify and delete symbolic refs
   unpack-objects          Unpack objects from a packed archive
   update-index            Register file contents in the working tree to the index
   update-ref              Update the object name stored in a ref safely
   write-tree              Create a tree object from the current index

Low-level Commands / Interrogators
   cat-file                Provide contents or details of repository objects
   cherry                  Find commits yet to be applied to upstream
   diff-files              Compares files in the working tree and the index
   diff-index              Compare a tree to the working tree or index
   diff-tree               Compares the content and mode of blobs found via two tree objects
   for-each-ref            Output information on each ref
   for-each-repo           Run a Git command on a list of repositories
   get-tar-commit-id       Extract commit ID from an archive created using git-archive
   ls-files                Show information about files in the index and the working tree
   ls-remote               List references in a remote repository
   ls-tree                 List the contents of a tree object
   merge-base              Find as good common ancestors as possible for a merge
   name-rev                Find symbolic names for given revs
   pack-redundant          Find redundant pack files
   rev-list                Lists commit objects in reverse chronological order
   rev-parse               Pick out and massage parameters
   show-index              Show packed archive index
   show-ref                List references in a local repository
   unpack-file             Creates a temporary file with a blob's contents
   var                     Show a Git logical variable
   verify-pack             Validate packed Git archive files

Low-level Commands / Syncing Repositories
   daemon                  A really simple server for Git repositories
   fetch-pack              Receive missing objects from another repository
   http-backend            Server side implementation of Git over HTTP
   send-pack               Push objects over Git protocol to another repository
   update-server-info      Update auxiliary info file to help dumb servers

Low-level Commands / Internal Helpers
   check-attr              Display gitattributes information
   check-ignore            Debug gitignore / exclude files
   check-mailmap           Show canonical names and email addresses of contacts
   check-ref-format        Ensures that a reference name is well formed
   column                  Display data in columns
   credential              Retrieve and store user credentials
   credential-cache        Helper to temporarily store passwords in memory
   credential-store        Helper to store credentials on disk
   fmt-merge-msg           Produce a merge commit message
   hook                    Run git hooks
   interpret-trailers      Add or parse structured information in commit messages
   mailinfo                Extracts patch and authorship from a single e-mail message
   mailsplit               Simple UNIX mbox splitter program
   merge-one-file          The standard helper program to use with git-merge-index
   patch-id                Compute unique ID for a patch
   sh-i18n                 Git's i18n setup code for shell scripts
   sh-setup                Common Git shell script setup code
   stripspace              Remove unnecessary whitespace

User-facing repository, command and file interfaces
   attributes              Defining attributes per path
   cli                     Git command-line interface and conventions
   hooks                   Hooks used by Git
   ignore                  Specifies intentionally untracked files to ignore
   mailmap                 Map author/committer names and/or E-Mail addresses
   modules                 Defining submodule properties
   repository-layout       Git Repository Layout
   revisions               Specifying revisions and ranges for Git

Developer-facing file formats, protocols and other interfaces
   format-bundle           The bundle file format
   format-chunk            Chunk-based file formats
   format-commit-graph     Git commit-graph format
   format-index            Git index format
   format-pack             Git pack format
   format-signature        Git cryptographic signature formats
   protocol-capabilities   Protocol v0 and v1 capabilities
   protocol-common         Things common to various protocols
   protocol-http           Git HTTP-based protocols
   protocol-pack           How packs are transferred over-the-wire
   protocol-v2             Git Wire Protocol, Version 2

External commands
   lfs

See 'git help <command>' to read about a specific subcommand

Main Porcelain Commands
   add                     Add file contents to the index
   am                      Apply a series of patches from a mailbox
   archive                 Create an archive of files from a named tree
   bisect                  Use binary search to find the commit that introduced a bug
   branch                  List, create, or delete branches
   bundle                  Move objects and refs by archive
   checkout                Switch branches or restore working tree files
   cherry-pick             Apply the changes introduced by some existing commits
   citool                  Graphical alternative to git-commit
   clean                   Remove untracked files from the working tree
   clone                   Clone a repository into a new directory
   commit                  Record changes to the repository
   describe                Give an object a human readable name based on an available ref
   diff                    Show changes between commits, commit and working tree, etc
   fetch                   Download objects and refs from another repository
   format-patch            Prepare patches for e-mail submission
   gc                      Cleanup unnecessary files and optimize the local repository
   gitk                    The Git repository browser
   grep                    Print lines matching a pattern
   gui                     A portable graphical interface to Git
   init                    Create an empty Git repository or reinitialize an existing one
   log                     Show commit logs
   maintenance             Run tasks to optimize Git repository data
   merge                   Join two or more development histories together
   mv                      Move or rename a file, a directory, or a symlink
   notes                   Add or inspect object notes
   pull                    Fetch from and integrate with another repository or a local branch
   push                    Update remote refs along with associated objects
   range-diff              Compare two commit ranges (e.g. two versions of a branch)
   rebase                  Reapply commits on top of another base tip
   reset                   Reset current HEAD to the specified state
   restore                 Restore working tree files
   revert                  Revert some existing commits
   rm                      Remove files from the working tree and from the index
   scalar                  A tool for managing large Git repositories
   shortlog                Summarize 'git log' output
   show                    Show various types of objects
   sparse-checkout         Reduce your working tree to a subset of tracked files
   stash                   Stash the changes in a dirty working directory away
   status                  Show the working tree status
   submodule               Initialize, update or inspect submodules
   switch                  Switch branches
   tag                     Create, list, delete or verify a tag object signed with GPG
   worktree                Manage multiple working trees

Ancillary Commands / Manipulators
   config                  Get and set repository or global options
   fast-export             Git data exporter
   fast-import             Backend for fast Git data importers
   filter-branch           Rewrite branches
   mergetool               Run merge conflict resolution tools to resolve merge conflicts
   pack-refs               Pack heads and tags for efficient repository access
   prune                   Prune all unreachable objects from the object database
   reflog                  Manage reflog information
   remote                  Manage set of tracked repositories
   repack                  Pack unpacked objects in a repository
   replace                 Create, list, delete refs to replace objects

Ancillary Commands / Interrogators
   annotate                Annotate file lines with commit information
   blame                   Show what revision and author last modified each line of a file
   bugreport               Collect information for user to file a bug report
   count-objects           Count unpacked number of objects and their disk consumption
   diagnose                Generate a zip archive of diagnostic information
   difftool                Show changes using common diff tools
   fsck                    Verifies the connectivity and validity of the objects in the database
   gitweb                  Git web interface (web frontend to Git repositories)
   help                    Display help information about Git
   instaweb                Instantly browse your working repository in gitweb
   merge-tree              Perform merge without touching index or working tree
   rerere                  Reuse recorded resolution of conflicted merges
   show-branch             Show branches and their commits
   verify-commit           Check the GPG signature of commits
   verify-tag              Check the GPG signature of tags
   version                 Display version information about Git
   whatchanged             Show logs with differences each commit introduces

Interacting with Others
   archimport              Import a GNU Arch repository into Git
   cvsexportcommit         Export a single commit to a CVS checkout
   cvsimport               Salvage your data out of another SCM people love to hate
   cvsserver               A CVS server emulator for Git
   imap-send               Send a collection of patches from stdin to an IMAP folder
   p4                      Import from and submit to Perforce repositories
   quiltimport             Applies a quilt patchset onto the current branch
   request-pull            Generates a summary of pending changes
   send-email              Send a collection of patches as emails
   svn                     Bidirectional operation between a Subversion repository and Git

Low-level Commands / Manipulators
   apply                   Apply a patch to files and/or to the index
   checkout-index          Copy files from the index to the working tree
   commit-graph            Write and verify Git commit-graph files
   commit-tree             Create a new commit object
   hash-object             Compute object ID and optionally create an object from a file
   index-pack              Build pack index file for an existing packed archive
   merge-file              Run a three-way file merge
   merge-index             Run a merge for files needing merging
   mktag                   Creates a tag object with extra validation
   mktree                  Build a tree-object from ls-tree formatted text
   multi-pack-index        Write and verify multi-pack-indexes
   pack-objects            Create a packed archive of objects
   prune-packed            Remove extra objects that are already in pack files
   read-tree               Reads tree information into the index
   symbolic-ref            Read, modify and delete symbolic refs
   unpack-objects          Unpack objects from a packed archive
   update-index            Register file contents in the working tree to the index
   update-ref              Update the object name stored in a ref safely
   write-tree              Create a tree object from the current index

Low-level Commands / Interrogators
   cat-file                Provide contents or details of repository objects
   cherry                  Find commits yet to be applied to upstream
   diff-files              Compares files in the working tree and the index
   diff-index              Compare a tree to the working tree or index
   diff-tree               Compares the content and mode of blobs found via two tree objects
   for-each-ref            Output information on each ref
   for-each-repo           Run a Git command on a list of repositories
   get-tar-commit-id       Extract commit ID from an archive created using git-archive
   ls-files                Show information about files in the index and the working tree
   ls-remote               List references in a remote repository
   ls-tree                 List the contents of a tree object
   merge-base              Find as good common ancestors as possible for a merge
   name-rev                Find symbolic names for given revs
   pack-redundant          Find redundant pack files
   rev-list                Lists commit objects in reverse chronological order
   rev-parse               Pick out and massage parameters
   show-index              Show packed archive index
   show-ref                List references in a local repository
   unpack-file             Creates a temporary file with a blob's contents
   var                     Show a Git logical variable
   verify-pack             Validate packed Git archive files

Low-level Commands / Syncing Repositories
   daemon                  A really simple server for Git repositories
   fetch-pack              Receive missing objects from another repository
   http-backend            Server side implementation of Git over HTTP
   send-pack               Push objects over Git protocol to another repository
   update-server-info      Update auxiliary info file to help dumb servers

Low-level Commands / Internal Helpers
   check-attr              Display gitattributes information
   check-ignore            Debug gitignore / exclude files
   check-mailmap           Show canonical names and email addresses of contacts
   check-ref-format        Ensures that a reference name is well formed
   column                  Display data in columns
   credential              Retrieve and store user credentials
   credential-cache        Helper to temporarily store passwords in memory
   credential-store        Helper to store credentials on disk
   fmt-merge-msg           Produce a merge commit message
   hook                    Run git hooks
   interpret-trailers      Add or parse structured information in commit messages
   mailinfo                Extracts patch and authorship from a single e-mail message
   mailsplit               Simple UNIX mbox splitter program
   merge-one-file          The standard helper program to use with git-merge-index
   patch-id                Compute unique ID for a patch
   sh-i18n                 Git's i18n setup code for shell scripts
   sh-setup                Common Git shell script setup code
   stripspace              Remove unnecessary whitespace

User-facing repository, command and file interfaces
   attributes              Defining attributes per path
   cli                     Git command-line interface and conventions
   hooks                   Hooks used by Git
   ignore                  Specifies intentionally untracked files to ignore
   mailmap                 Map author/committer names and/or E-Mail addresses
   modules                 Defining submodule properties
   repository-layout       Git Repository Layout
   revisions               Specifying revisions and ranges for Git

Developer-facing file formats, protocols and other interfaces
   format-bundle           The bundle file format
   format-chunk            Chunk-based file formats
   format-commit-graph     Git commit-graph format
   format-index            Git index format
   format-pack             Git pack format
   format-signature        Git cryptographic signature formats
   protocol-capabilities   Protocol v0 and v1 capabilities
   protocol-common         Things common to various protocols
   protocol-http           Git HTTP-based protocols
   protocol-pack           How packs are transferred over-the-wire
   protocol-v2             Git Wire Protocol, Version 2

External commands
   lfs
(END)
   mailinfo                Extracts patch and authorship from a single e-mail message
   mailsplit               Simple UNIX mbox splitter program
   merge-one-file          The standard helper program to use with git-merge-index
   patch-id                Compute unique ID for a patch
   sh-i18n                 Git's i18n setup code for shell scripts
   sh-setup                Common Git shell script setup code
   stripspace              Remove unnecessary whitespace

User-facing repository, command and file interfaces
   attributes              Defining attributes per path
   cli                     Git command-line interface and conventions
   hooks                   Hooks used by Git
   ignore                  Specifies intentionally untracked files to ignore
   mailmap                 Map author/committer names and/or E-Mail addresses
   modules                 Defining submodule properties
   repository-layout       Git Repository Layout
   revisions               Specifying revisions and ranges for Git

Developer-facing file formats, protocols and other interfaces
   format-bundle           The bundle file format
   format-chunk            Chunk-based file formats
   format-commit-graph     Git commit-graph format
   format-index            Git index format
   format-pack             Git pack format
   format-signature        Git cryptographic signature formats
   protocol-capabilities   Protocol v0 and v1 capabilities
   protocol-common         Things common to various protocols
   protocol-http           Git HTTP-based protocols
   protocol-pack           How packs are transferred over-the-wire
   protocol-v2             Git Wire Protocol, Version 2

External commands

See 'git help <command>' to read about a specific subcommand

Main Porcelain Commands
   add                     Add file contents to the index
   am                      Apply a series of patches from a mailbox
   archive                 Create an archive of files from a named tree
   bisect                  Use binary search to find the commit that introduced a bug
   branch                  List, create, or delete branches
   bundle                  Move objects and refs by archive
   checkout                Switch branches or restore working tree files
   cherry-pick             Apply the changes introduced by some existing commits
   citool                  Graphical alternative to git-commit
   clean                   Remove untracked files from the working tree
   clone                   Clone a repository into a new directory
   commit                  Record changes to the repository
   describe                Give an object a human readable name based on an available ref
   diff                    Show changes between commits, commit and working tree, etc
   fetch                   Download objects and refs from another repository
   format-patch            Prepare patches for e-mail submission
   gc                      Cleanup unnecessary files and optimize the local repository
   gitk                    The Git repository browser
   grep                    Print lines matching a pattern
   gui                     A portable graphical interface to Git
   init                    Create an empty Git repository or reinitialize an existing one
   log                     Show commit logs
   maintenance             Run tasks to optimize Git repository data
   merge                   Join two or more development histories together
   mv                      Move or rename a file, a directory, or a symlink
   notes                   Add or inspect object notes
   pull                    Fetch from and integrate with another repository or a local branch
   push                    Update remote refs along with associated objects
   range-diff              Compare two commit ranges (e.g. two versions of a branch)
   rebase                  Reapply commits on top of another base tip
   reset                   Reset current HEAD to the specified state
   restore                 Restore working tree files
   revert                  Revert some existing commits
   rm                      Remove files from the working tree and from the index
   scalar                  A tool for managing large Git repositories
   shortlog                Summarize 'git log' output
   show                    Show various types of objects
   sparse-checkout         Reduce your working tree to a subset of tracked files
   stash                   Stash the changes in a dirty working directory away
   status                  Show the working tree status
   submodule               Initialize, update or inspect submodules
   switch                  Switch branches
   tag                     Create, list, delete or verify a tag object signed with GPG
   worktree                Manage multiple working trees

Ancillary Commands / Manipulators
   config                  Get and set repository or global options
   fast-export             Git data exporter
   fast-import             Backend for fast Git data importers
   filter-branch           Rewrite branches
   mergetool               Run merge conflict resolution tools to resolve merge conflicts
   pack-refs               Pack heads and tags for efficient repository access
   prune                   Prune all unreachable objects from the object database
   reflog                  Manage reflog information
   remote                  Manage set of tracked repositories
   repack                  Pack unpacked objects in a repository
   replace                 Create, list, delete refs to replace objects

Ancillary Commands / Interrogators
   annotate                Annotate file lines with commit information
   blame                   Show what revision and author last modified each line of a file
   bugreport               Collect information for user to file a bug report
   count-objects           Count unpacked number of objects and their disk consumption
   diagnose                Generate a zip archive of diagnostic information
   difftool                Show changes using common diff tools
   fsck                    Verifies the connectivity and validity of the objects in the database
   gitweb                  Git web interface (web frontend to Git repositories)
   help                    Display help information about Git
   instaweb                Instantly browse your working repository in gitweb
   merge-tree              Perform merge without touching index or working tree
   rerere                  Reuse recorded resolution of conflicted merges
   show-branch             Show branches and their commits
   verify-commit           Check the GPG signature of commits
   verify-tag              Check the GPG signature of tags
   version                 Display version information about Git
   whatchanged             Show logs with differences each commit introduces

Interacting with Others
   archimport              Import a GNU Arch repository into Git
   cvsexportcommit         Export a single commit to a CVS checkout
   cvsimport               Salvage your data out of another SCM people love to hate
   cvsserver               A CVS server emulator for Git
   imap-send               Send a collection of patches from stdin to an IMAP folder
   p4                      Import from and submit to Perforce repositories
   quiltimport             Applies a quilt patchset onto the current branch
   request-pull            Generates a summary of pending changes
   send-email              Send a collection of patches as emails
   svn                     Bidirectional operation between a Subversion repository and Git

Low-level Commands / Manipulators
   apply                   Apply a patch to files and/or to the index
   checkout-index          Copy files from the index to the working tree
   commit-graph            Write and verify Git commit-graph files
   commit-tree             Create a new commit object
   hash-object             Compute object ID and optionally create an object from a file
   index-pack              Build pack index file for an existing packed archive
   merge-file              Run a three-way file merge
   merge-index             Run a merge for files needing merging
   mktag                   Creates a tag object with extra validation
   mktree                  Build a tree-object from ls-tree formatted text
   multi-pack-index        Write and verify multi-pack-indexes
   pack-objects            Create a packed archive of objects
   prune-packed            Remove extra objects that are already in pack files
   read-tree               Reads tree information into the index
   symbolic-ref            Read, modify and delete symbolic refs
   unpack-objects          Unpack objects from a packed archive
   update-index            Register file contents in the working tree to the index
   update-ref              Update the object name stored in a ref safely
   write-tree              Create a tree object from the current index

Low-level Commands / Interrogators
   cat-file                Provide contents or details of repository objects
   cherry                  Find commits yet to be applied to upstream
   diff-files              Compares files in the working tree and the index
   diff-index              Compare a tree to the working tree or index
   diff-tree               Compares the content and mode of blobs found via two tree objects
   for-each-ref            Output information on each ref
   for-each-repo           Run a Git command on a list of repositories
   get-tar-commit-id       Extract commit ID from an archive created using git-archive
   ls-files                Show information about files in the index and the working tree
   ls-remote               List references in a remote repository
   ls-tree                 List the contents of a tree object
   merge-base              Find as good common ancestors as possible for a merge
   name-rev                Find symbolic names for given revs
   pack-redundant          Find redundant pack files
   rev-list                Lists commit objects in reverse chronological order
   rev-parse               Pick out and massage parameters
   show-index              Show packed archive index
   show-ref                List references in a local repository
   unpack-file             Creates a temporary file with a blob's contents
   var                     Show a Git logical variable
   verify-pack             Validate packed Git archive files

Low-level Commands / Syncing Repositories
   daemon                  A really simple server for Git repositories
   fetch-pack              Receive missing objects from another repository
   http-backend            Server side implementation of Git over HTTP
   send-pack               Push objects over Git protocol to another repository
   update-server-info      Update auxiliary info file to help dumb servers

Low-level Commands / Internal Helpers
   check-attr              Display gitattributes information
   check-ignore            Debug gitignore / exclude files
   check-mailmap           Show canonical names and email addresses of contacts
   check-ref-format        Ensures that a reference name is well formed
   column                  Display data in columns
   credential              Retrieve and store user credentials
   credential-cache        Helper to temporarily store passwords in memory
   credential-store        Helper to store credentials on disk
   fmt-merge-msg           Produce a merge commit message
   hook                    Run git hooks
   interpret-trailers      Add or parse structured information in commit messages
   mailinfo                Extracts patch and authorship from a single e-mail message
   mailsplit               Simple UNIX mbox splitter program
   merge-one-file          The standard helper program to use with git-merge-index
   patch-id                Compute unique ID for a patch
   sh-i18n                 Git's i18n setup code for shell scripts
   sh-setup                Common Git shell script setup code
   stripspace              Remove unnecessary whitespace

User-facing repository, command and file interfaces
   attributes              Defining attributes per path
   cli                     Git command-line interface and conventions
   hooks                   Hooks used by Git
   ignore                  Specifies intentionally untracked files to ignore
   mailmap                 Map author/committer names and/or E-Mail addresses
   modules                 Defining submodule properties
   repository-layout       Git Repository Layout
   revisions               Specifying revisions and ranges for Git

Developer-facing file formats, protocols and other interfaces
   format-bundle           The bundle file format
   format-chunk            Chunk-based file formats
   format-commit-graph     Git commit-graph format
   format-index            Git index format
   format-pack             Git pack format
   format-signature        Git cryptographic signature formats
   protocol-capabilities   Protocol v0 and v1 capabilities
   protocol-common         Things common to various protocols
   protocol-http           Git HTTP-based protocols
   protocol-pack           How packs are transferred over-the-wire
   protocol-v2             Git Wire Protocol, Version 2

External commands
   lfs
...skipping...
   mailsplit               Simple UNIX mbox splitter program
   merge-one-file          The standard helper program to use with git-merge-index
   patch-id                Compute unique ID for a patch
   sh-i18n                 Git's i18n setup code for shell scripts
   sh-setup                Common Git shell script setup code
   stripspace              Remove unnecessary whitespace

User-facing repository, command and file interfaces
   attributes              Defining attributes per path
   cli                     Git command-line interface and conventions
   hooks                   Hooks used by Git
   ignore                  Specifies intentionally untracked files to ignore
   mailmap                 Map author/committer names and/or E-Mail addresses
   modules                 Defining submodule properties
   repository-layout       Git Repository Layout
   revisions               Specifying revisions and ranges for Git

Developer-facing file formats, protocols and other interfaces
   format-bundle           The bundle file format
   format-chunk            Chunk-based file formats
   format-commit-graph     Git commit-graph format
   format-index            Git index format
   format-pack             Git pack format
   format-signature        Git cryptographic signature formats
   protocol-capabilities   Protocol v0 and v1 capabilities
   protocol-common         Things common to various protocols
   protocol-http           Git HTTP-based protocols
   protocol-pack           How packs are transferred over-the-wire
   protocol-v2             Git Wire Protocol, Version 2

External commands
   lfs
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git branch  hello-word-image
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git branch
  hello-word-image
* master
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git checkout hello-word-image
M	index.html
Switched to branch 'hello-word-image'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git status
On branch hello-word-image
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add --a
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git status
On branch hello-word-image
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html

(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git status
On branch hello-word-image
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	Images_SW_illustration_16.jpg

(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git commit -m "Added image to Hello World"
[hello-word-image 98c8acf] Added image to Hello World
 1 file changed, 3 insertions(+)
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ls
 Images_SW_illustration_16.jpg   index.html  'readme .txt'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git checkout master
Switched to branch 'master'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ^C
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git checkout  -b emergency-fix
Switched to a new branch 'emergency-fix'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git branch -d emergency-fix
error: cannot delete branch 'emergency-fix' used by worktree at '/home/karle.eyang@Digital-Grenoble.local/monprojet'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git merge hello-wordl-image
merge: hello-wordl-image - not something we can merge
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add ^C
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add Images_SW_illustration_16.jpg
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git checkout master
A	Images_SW_illustration_16.jpg
Switched to branch 'master'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git branch hello-word-image
fatal: a branch named 'hello-word-image' already exists
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add -- all
fatal: pathspec 'all' did not match any files
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git commit -m " aed nex image"
[master cd6387c]  aed nex image
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Images_SW_illustration_16.jpg
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git checkout master
Already on 'master'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git merge hello-word-image
Merge made by the 'ort' strategy.
 index.html | 3 +++
 1 file changed, 3 insertions(+)
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git add codepyth.py
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ls
 codepyth.py   Images_SW_illustration_16.jpg   index.html  'readme .txt'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote add https://github.com/Hanaell/Hello-word.git
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote add https://github.com/Hanaell/Hello-word.git
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git clone https://github.com/Hanaell/Hello-word.git
Cloning into 'Hello-word'...
warning: You appear to have cloned an empty repository.
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git pull origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ls
 codepyth.py   Hello-word   Images_SW_illustration_16.jpg   index.html  'readme .txt'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ cd
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ git remote add originhttps://github.com/Hanaell/Hello-word.git
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ git remote add origin https://github.com/Hanaell/Hello-word.git
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ git push -- set-upstream origin master
error: src refspec origin does not match any
error: src refspec master does not match any
error: failed to push some refs to 'set-upstream'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ git remote set-url origin git@github.com:Hanaell/Hello-word.git
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ git push --set-upstream origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:Hanaell/Hello-word.git'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ git push --set-upstream origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:Hanaell/Hello-word.git'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ git pull origin main
The authenticity of host 'github.com (140.82.121.3)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ cd
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~$ cd monprojet/
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote add origin https://github.com/Hanaell/Hello-word.git
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git push --set-upstream origin master
Username for 'https://github.com': karle-hanaelle.eyang@le-campus-numerique.fr
Password for 'https://karle-hanaelle.eyang%40le-campus-numerique.fr@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/Hanaell/Hello-word.git/'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ssh-keygen -t ed25519 -C "your_email@example.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/home/karle.eyang@Digital-Grenoble.local/.ssh/id_ed25519): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/karle.eyang@Digital-Grenoble.local/.ssh/id_ed25519
Your public key has been saved in /home/karle.eyang@Digital-Grenoble.local/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:Z/bzPAQO7Qjhx25D6gecQMHe8sw3WPUoWQvp1pWQhME your_email@example.com
The key's randomart image is:
+--[ED25519 256]--+
|     ... ..=oo . |
|      o . E + o  |
|     o o + B =   |
|      + + @ * .  |
|       BS@+* .   |
|        X+B.o .  |
|       . + oo.   |
|        . .  +.  |
|         .    o. |
+----[SHA256]-----+
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ssh-keygen -t ed25519 -C "your_email@example.com"^C
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ssh-keygen -t ed25519 -C "karle-hanaelle.eyang@le-campus-numerique.fr"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/home/karle.eyang@Digital-Grenoble.local/.ssh/id_ed25519): 
/home/karle.eyang@Digital-Grenoble.local/.ssh/id_ed25519 already exists.
Overwrite (y/n)? ^C
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ ^C
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ cat ~/.ssh/id_ed25519.pub 
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIMcda287XrVA+Q0U/QmFl0+IIMeN0f442yLBNUaCU/GB your_email@example.com
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote add origin https://github.com/Hanaell/Hello-word.git
error: remote origin already exists.
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote origin
error: unknown subcommand: `origin'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --[no-]verbose    be verbose; must be placed before a subcommand

(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote remove origin
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote add origin https://github.com/Hanaell/Hello-word.git
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git branch -M main
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git push -u origin main
Username for 'https://github.com': ^[[A^[[A^[[A^[[D
Password for 'https://%1B%5BA%1B%5BA%1B%5BA%1B%5BD@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/Hanaell/Hello-word.git/'
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote remove origin
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git remote add origin git@github.com:Hanaell/Hello-word.git
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git branch -M main
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ git push -u origin main
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 8 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (14/14), 662.10 KiB | 6.76 MiB/s, done.
Total 14 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), done.
To github.com:Hanaell/Hello-word.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
(base) karle.eyang@Digital-Grenoble.local@GIT-L16:~/monprojet$ 


