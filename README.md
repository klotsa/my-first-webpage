# my-first-webpageLast login: Mon Mar 13 13:39:03 on ttys000
epicodus-7:~ Guest$ cd desktop
epicodus-7:desktop Guest$ ls
cookie-recipe		goodbye1		my-first-webpage
goodbye			hello-world
epicodus-7:desktop Guest$ cd my-first-webpage/
epicodus-7:my-first-webpage Guest$ ls
my-first-webpage.html
epicodus-7:my-first-webpage Guest$ git init
Reinitialized existing Git repository in /Users/Guest/Desktop/my-first-webpage/.git/
epicodus-7:my-first-webpage Guest$ git add my-first-webpage.html
epicodus-7:my-first-webpage Guest$ git-pair-commit -m "first webpage"
Committing under anatoliy@
On branch master
nothing to commit, working directory clean
epicodus-7:my-first-webpage Guest$ git pair ak jl
NOTE: Overriding global user.name setting with local.
global: user.name klotsa
local:  user.name Anatoliy Klots and Jason Lazzuri
NOTE: Overriding global user.email setting with local.
global: user.email klots@uw.edu
local:  user.email anatoliy+jason@
local:  user.initials ak jl
epicodus-7:my-first-webpage Guest$ git-pair-commit -m "first webpage"
Committing under jason@
On branch master
nothing to commit, working directory clean
epicodus-7:my-first-webpage Guest$ git add my-first-webpage.html
epicodus-7:my-first-webpage Guest$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   my-first-webpage.html

epicodus-7:my-first-webpage Guest$ git remote add ak https://github.com/klotsa/my-first-webpage.git
epicodus-7:my-first-webpage Guest$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   my-first-webpage.html

epicodus-7:my-first-webpage Guest$ git log
commit d3eed790284e8aa93ddf0a9a9aac02566241f262
Author: Anatoliy Klots and Jason Lazzuri <jason@>
Date:   Mon Mar 13 13:49:31 2017 -0700

    add final official html elements:Doctype, head, title, body

commit b3557d00037399b80a864c60b1cb1335d74636fb
Author: Anatoliy Klots and Jason Lazzuri <jason@>
Date:   Mon Mar 13 13:44:43 2017 -0700

    add lists elements

commit d30220e95e0c049a68a63c67fd17d7e6668f12e2
Author: Anatoliy Klots and Jason Lazzuri <jason@>
Date:   Mon Mar 13 13:39:57 2017 -0700

    test commit

commit d17e9738a1e093510f496927273345b6f5f5c012
Author: Anatoliy Klots and Jason Lazzuri <jason@>
Date:   Mon Mar 13 13:33:09 2017 -0700

    add paragraph
:...skipping...
commit d3eed790284e8aa93ddf0a9a9aac02566241f262
Author: Anatoliy Klots and Jason Lazzuri <jason@>
Date:   Mon Mar 13 13:49:31 2017 -0700

    add final official html elements:Doctype, head, title, body

commit b3557d00037399b80a864c60b1cb1335d74636fb
Author: Anatoliy Klots and Jason Lazzuri <jason@>
Date:   Mon Mar 13 13:44:43 2017 -0700

    add lists elements

commit d30220e95e0c049a68a63c67fd17d7e6668f12e2
Author: Anatoliy Klots and Jason Lazzuri <jason@>
Date:   Mon Mar 13 13:39:57 2017 -0700

    test commit

commit d17e9738a1e093510f496927273345b6f5f5c012
Author: Anatoliy Klots and Jason Lazzuri <jason@>
Date:   Mon Mar 13 13:33:09 2017 -0700

    add paragraph
~
epicodus-7:my-first-webpage Guest$ git push ak master 
Username for 'https://github.com': klotsa
Password for 'https://klotsa@github.com': 
Counting objects: 12, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (8/8), done.
Writing objects: 100% (12/12), 1.33 KiB | 0 bytes/s, done.
Total 12 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/klotsa/my-first-webpage.git
 * [new branch]      master -> master
epicodus-7:my-first-webpage Guest$ 
