h1 Git commands and procedures for the best workflow EVER
---

h2 Commands:

- git status                 --> Shows how is your directory in vim's terms.
- git log --oneline          --> Shows all commits that contributed to the current branch.
- git add file.txt           --> Adds this file to current commit.
- git add .                  --> Add all files to current commits (even untracked files).
- git checkout -- file.txt   --> Remove changes on this file in relation to last commit.
- git remote --verbose       --> List the remote repositories. 
- git checkout -b feature_1  --> Create a new branch and goes to it.
- git branch --verbose       --> List branches in the repository.

- extra:
	- vim ~/.zshrc       --> Configure file in the home directory.


h2 Procedures:

+---------------------------------------------------------------------------------------------+
|                                                                                             |
|                                                                                             |
|                                                                                             |
|               |yuri-almeid/feature_2|--c--c--c-M--c                                         |
|               /                               /    \                                        |
|              / |felipejoribeiro/feature_1|--c--c--c \                                       |
|             /     /                                \ \                                      |
|            /     /                                  \ \                                     |
|     |upstream/production|----------------------------M-M---                                 |
|        /                                                                                    |
|       /                                                                                     |
|---|upstream/master|---                                                                      |
+---------------------------------------------------------------------------------------------+

