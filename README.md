PS C:\Users\pc\OneDrive\Desktop\New folder> git init
Initialized empty Git repository in C:/Users/pc/OneDrive/Desktop/New folder/.git/
[master (root-commit) 0b5d59d] frist commit
 create mode 100644 index.html
PS C:\Users\pc\OneDrive\Desktop\New folder> git log
commit 0b5d59d8746cd133b0d7dd394389f7bb79943ff8 (HEAD -> master)
Author: khaled-m-hamza <khaled.m.hamza2001@gmail.com>
Date:   Fri Aug 30 17:28:38 2024 +0300

PS C:\Users\pc\OneDrive\Desktop\New folder> git switch div
Switched to branch 'div'
PS C:\Users\pc\OneDrive\Desktop\New folder> git commit -am "sec_com"
        index.js

nothing added to commit but untracked files present (use "git add" to track)
[div a5ae7c9] secound
 1 file changed, 1 insertion(+)
PS C:\Users\pc\OneDrive\Desktop\New folder> git branch test
PS C:\Users\pc\OneDrive\Desktop\New folder> git add sec.js
PS C:\Users\pc\OneDrive\Desktop\New folder> git commit -m "third"
[div 2bb6241] third
 1 file changed, 1 insertion(+)
 create mode 100644 sec.js
PS C:\Users\pc\OneDrive\Desktop\New folder> git remote add origin https://github.com/khaled-m-hamza/lab2.git
PS C:\Users\pc\OneDrive\Desktop\New folder> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/khaled-m-hamza/lab2.git'
info: please complete authentication in your browser...
Counting objects: 100% (3/3), done.
Compressing objects: 100% (2/2), done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/khaled-m-hamza/lab2.git
branch 'master' set up to track 'origin/master'.
Already on 'div'
PS C:\Users\pc\OneDrive\Desktop\New folder> git switch test
Switched to branch 'test'
PS C:\Users\pc\OneDrive\Desktop\New folder> git push origin master
Everything up-to-date
PS C:\Users\pc\OneDrive\Desktop\New folder> git switch master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
Switched to branch 'div'
PS C:\Users\pc\OneDrive\Desktop\New folder> git push origin
fatal: The current branch div has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin div

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\pc\OneDrive\Desktop\New folder> git push -u origin div
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Writing objects: 100% (6/6), 526 bytes | 105.00 KiB/s, done.
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'div' on GitHub by visiting:
remote:      https://github.com/khaled-m-hamza/lab2/pull/new/div
remote:
To https://github.com/khaled-m-hamza/lab2.git
 * [new branch]      div -> div
branch 'div' set up to track 'origin/div'.
Switched to branch 'test'
PS C:\Users\pc\OneDrive\Desktop\New folder> git push -u origin test
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/khaled-m-hamza/lab2/pull/new/test
remote:
To https://github.com/khaled-m-hamza/lab2.git
 * [new branch]      test -> test
branch 'test' set up to track 'origin/test'.
Switched to branch 'master'
Updating 0b5d59d..2bb6241
Fast-forward
 index.js | 1 +
 sec.js   | 1 +
 2 files changed, 2 insertions(+)
 create mode 100644 index.js
 create mode 100644 sec.js
PS C:\Users\pc\OneDrive\Desktop\New folder> git merge test
Already up to date.
PS C:\Users\pc\OneDrive\Desktop\New folder> git tag -a v1.7 -m "first tag"
PS C:\Users\pc\OneDrive\Desktop\New folder> git push origin v1.7
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 166 bytes | 83.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/khaled-m-hamza/lab2.git
 * [new tag]         v1.7 -> v1.7
PS C:\Users\pc\OneDrive\Desktop\New folder> 
