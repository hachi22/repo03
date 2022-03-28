# Repositorio 03

Mi primer ejercicio con ramas

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (main)
$ git commit -m "primer commit"
[main (root-commit) 6804a27] primer commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (main)
$ git branch adrian28032022

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (main)
$ git checkout adrian28032022
Switched to branch 'adrian28032022'

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (adrian28032022)
$ git commit -am "Texto introducido"
[adrian28032022 b877ef8] Texto introducido
 1 file changed, 3 insertions(+)

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (adrian28032022)
$ git checkout main
Switched to branch 'main'

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (main)
$ git merge adrian28032022
Updating 6804a27..b877ef8
Fast-forward
 readme.md | 3 +++
 1 file changed, 3 insertions(+)

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (main)
$ git branch adrian28032022 -d
Deleted branch adrian28032022 (was b877ef8).

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (main)
$ git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 465 bytes | 465.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/hachi22/repo03.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

taller2@DESKTOP-FOU2B3E MINGW64 ~/desktop/repo03 (main)
$
