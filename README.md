# ProyectoGit-Curso
Mi proyecto con Git Curso 

Ejecuciones Git Bash Durante el Curso- para recordar Procedimientos


Darlin@DESKTOP 12 ~
$ cls
bash: cls: command not found

Darlin@DESKTOP 12 ~
$ ls
'3D Objects'/
 AndroidStudioProjects/
 AppData/
'Configuración local'@
 Contacts/
 Cookies@
'Datos de programa'@
 Desktop/
 Documents/
 Downloads/
'Entorno de red'@
 Favorites/
 Impresoras@
 Links/
'Menú Inicio'@
'Mis documentos'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 OneDrive/
'OneDrive - UTESA'/
 Pictures/
 Plantillas@
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

Darlin@DESKTOP 12 ~
$ https://www.facebook.com/
bash: https://www.facebook.com/: No such file or directory

Darlin@DESKTOP 12 ~
$ pwd
/c/Users/Darlin

Darlin@DESKTOP 12 ~
$ cd desktop

Darlin@DESKTOP 12 ~/desktop
$ cd proyecto

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ ls
app.js  index.html

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git init
Reinitialized existing Git repository in C:/Users/Darlin/Desktop/Proyecto/.git/

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        app.js
        index.html

nothing added to commit but untracked files present (use "git add" to track)

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git add app.js

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   app.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git add index.html

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   app.js
        new file:   index.html


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   app.js
        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        style.css


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git add style.css

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   app.js
        new file:   index.html
        new file:   style.css


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Darlin@DESKTOP.(none)')

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git config --global user.email"darlintapia09@hotmail.com"

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git config --global user.name "Darlin"

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   app.js
        new file:   index.html
        new file:   style.css


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Darlin@DESKTOP.(none)')

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git config --global user.email "darlintapia09@hotmail.com"

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git config --global user.name "darlintc"

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   app.js
        new file:   index.html
        new file:   style.css


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git commit
[main (root-commit) 3e3a9d2] mi primer commit
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 app.js
 create mode 100644 index.html
 create mode 100644 style.css

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git log
commit 3e3a9d2145b88fcfca007fee6ac6b5dbcfe4712f (HEAD -> main)
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:01:38 2021 -0600

    mi primer commit

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
nothing to commit, working tree clean

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
nothing to commit, working tree clean

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git checkout -- index.html

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git diff
diff --git a/index.html b/index.html
index e69de29..32fb2fe 100644
--- a/index.html
+++ b/index.html
@@ -0,0 +1,10 @@
+<!DOCTYPE html>
+<html>
+ <head>
+    <meta charset="utf-8">
+    <title>Mi primera pagina</title>
+</head>
+ <body>
+
+ </body>
+</html>
\ No newline at end of file

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git add index.html

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git commit
[main 861e655] Ahora el index.html tiene codigo HTML
 1 file changed, 10 insertions(+)

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git log
commit 861e6559d628f9073e89caab7a39daed9ccb59b6 (HEAD -> main)
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:24:05 2021 -0600

    Ahora el index.html tiene codigo HTML

commit 3e3a9d2145b88fcfca007fee6ac6b5dbcfe4712f
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:01:38 2021 -0600

    mi primer commit

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test/

nothing added to commit but untracked files present (use "git add" to track)

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test/

nothing added to commit but untracked files present (use "git add" to track)

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git add .gitignore

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ status
bash: status: command not found

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        text


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        text


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        text


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore
        modified:   app.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        comit


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore
        modified:   app.js


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git add .app.js
fatal: pathspec '.app.js' did not match any files

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git add app.js

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        modified:   app.js

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git add .gitignore

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        modified:   app.js


Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git commit -m "he agregado un .gitignore"
[main 369d55d] he agregado un .gitignore
 2 files changed, 3 insertions(+)
 create mode 100644 .gitignore

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git brach
git: 'brach' is not a git command. See 'git --help'.

The most similar command is
        branch

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git branch
* main

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git checkout

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git branch login

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git branch
  login
* main

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git checkout login
Switched to branch 'login'

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git branch
* login
  main

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git status
On branch login
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        login/

nothing added to commit but untracked files present (use "git add" to track)

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git status
On branch login
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        autentificacion/
        login/

nothing added to commit but untracked files present (use "git add" to track)

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git add .

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git status
On branch login
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   autentificacion/index.js
        new file:   login/index.js


Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git commit -m "version alternativa con un login"
[login e0be7d9] version alternativa con un login
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 autentificacion/index.js
 create mode 100644 login/index.js

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git log
commit e0be7d944eba81819ef1f4db8e1b3a15ef2497d5 (HEAD -> login)
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 23:08:45 2021 -0600

    version alternativa con un login

commit 369d55de675067583fa77aff7d67fdc6776ef626 (main)
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:54:16 2021 -0600

    he agregado un .gitignore

commit 861e6559d628f9073e89caab7a39daed9ccb59b6
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:24:05 2021 -0600

    Ahora el index.html tiene codigo HTML

commit 3e3a9d2145b88fcfca007fee6ac6b5dbcfe4712f
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:01:38 2021 -0600

    mi primer commit

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git branch
* login
  main

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git checkout

Darlin@DESKTOP 12 ~/desktop/proyecto (login)
$ git checkout main
Switched to branch 'main'

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git branch
  login
* main

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git log
commit 369d55de675067583fa77aff7d67fdc6776ef626 (HEAD -> main)
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:54:16 2021 -0600

    he agregado un .gitignore

commit 861e6559d628f9073e89caab7a39daed9ccb59b6
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:24:05 2021 -0600

    Ahora el index.html tiene codigo HTML

commit 3e3a9d2145b88fcfca007fee6ac6b5dbcfe4712f
Author: darlintc <darlintapia09@hotmail.com>
Date:   Tue Oct 5 22:01:38 2021 -0600

    mi primer commit

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git remote add origin https://github.com/Darlintc/ProyectoGit-Curso.git

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ git push -u origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (10/10), 923 bytes | 153.00 KiB/s, done.
Total 10 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Darlintc/ProyectoGit-Curso.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ https://github.com/Darlintc/ProyectoGit-Curso.git
bash: https://github.com/Darlintc/ProyectoGit-Curso.git: No such file or directory

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ cd documentos
bash: cd: documentos: No such file or directory

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ cd c
bash: cd: c: No such file or directory

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ cd darlin
bash: cd: darlin: No such file or directory

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ pwd
/c/Users/Darlin/desktop/proyecto

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ cd desktop
bash: cd: desktop: No such file or directory

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ cd Users
bash: cd: Users: No such file or directory

Darlin@DESKTOP 12 ~/desktop/proyecto (main)
$ cd clone

Darlin@DESKTOP 12 ~/desktop/proyecto/clone (main)
$ https://github.com/Darlintc/ProyectoGit-Curso.git
bash: https://github.com/Darlintc/ProyectoGit-Curso.git: No such file or directory

Darlin@DESKTOP 12 ~/desktop/proyecto/clone (main)
$ git clone https://github.com/Darlintc/ProyectoGit-Curso.git
Cloning into 'ProyectoGit-Curso'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 10 (delta 1), reused 10 (delta 1), pack-reused 0
Receiving objects: 100% (10/10), done.
Resolving deltas: 100% (1/1), done.

Darlin@DESKTOP 12 ~/desktop/proyecto/clone (main)
$

