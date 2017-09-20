This repo uses Git LFS ("Large File Storage"). It's required to use files bigger
than 100MB with GitHub.

To activate it in your own repo, create a .gitattributes file like the one
provided here, listing the file extensions you'd like to host with Git LFS.

If you're using the latest version of GitHub Desktop, you already have Git LFS
support and don't need to do anything else:  
https://desktop.github.com/

Optionally, to set up your system to use Git LFS from the command line, go here:
https://git-lfs.github.com/

Two important things to be aware of:  
1. Git LFS files can't be downloaded from the GitHub website. You have to use
another client, like the GitHub Desktop app or the command line tools.

2. Hosting a large (> 1GB) repo on GitHub may incur bandwidth charges, even if
you're on a free plan. If you're not the repo's owner, you won't be charged--but
if you plan to make extensive use of Git LFS, coordinate with your collaborators
in advance and default to keeping your repos private.
