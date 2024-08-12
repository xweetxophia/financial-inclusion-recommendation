Microsoft Windows [Version 10.0.22631.3880]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Sophia\Desktop\learn_git>git init
Initialized empty Git repository in C:/Users/Sophia/Desktop/learn_git/.git/

C:\Users\Sophia\Desktop\learn_git>git add .

C:\Users\Sophia\Desktop\learn_git>git commit -m "adding third.txt"
[master (root-commit) fd9c74d] adding third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

C:\Users\Sophia\Desktop\learn_git>git log 
commit fd9c74daedd16b1a56abe4882c203213ff5d3065 (HEAD -> master)
Author: unknown <sophieoelvis@gmail.com>
Date:   Mon Aug 12 12:02:21 2024 +0100

    adding third.txt

C:\Users\Sophia\Desktop\learn_git>git add fourth.txt

C:\Users\Sophia\Desktop\learn_git>git commit -m "adding fourth.txt"
[master b907b12] adding fourth.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fourth.txt

C:\Users\Sophia\Desktop\learn_git>git add . 

C:\Users\Sophia\Desktop\learn_git>git commit -m "removing third.txt"
[master 9f7d220] removing third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 third.txt

C:\Users\Sophia\Desktop\learn_git>git log 
commit 9f7d220d250fe9162325c888ca5308815aa080a5 (HEAD -> master)
Author: unknown <sophieoelvis@gmail.com>
Date:   Mon Aug 12 12:05:08 2024 +0100

    removing third.txt

commit b907b122b079b01217bb4514d423cf20367cec46
Author: unknown <sophieoelvis@gmail.com>
Date:   Mon Aug 12 12:03:57 2024 +0100

    adding fourth.txt

commit fd9c74daedd16b1a56abe4882c203213ff5d3065
Author: unknown <sophieoelvis@gmail.com>
Date:   Mon Aug 12 12:02:21 2024 +0100

    adding third.txt

C:\Users\Sophia\Desktop\learn_git>git config --global core.pager "cat"

C:\Users\Sophia\Desktop\learn_git>git config --global --list 
user.email=sophieoelvis@gmail.com
core.pager=cat

C:\Users\Sophia\Desktop\learn_git>
