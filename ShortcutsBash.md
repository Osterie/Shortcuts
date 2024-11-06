=======================

* Normal
* !Heavily Used
* ?Frequent
* *Less Used
* //Useless
* TODO

=======================

# ----------------LINUX (BASH COMMANDS)--------------------

## ----------General-------

* ?Display Linux Process - top

* ?Interactive Process Viewer


## ------List Files----------

* ! List All Files And Directories In Current Directory - ls

Color codes:
- Blue: Directory
- Green: Executable or recognized data file
- Cyan (Sky Blue): Symbolic link file
- Yellow with black background: Device
- Magenta (Pink): Graphic image file
- Red: Archive file
- Red with black background: Broken link

* ! List Directory Tree - tree directory

* ? -R :  List Files In Sub-directories Aswell


## ------Directory-------------

* ! Navigate to root directory - cd /

* ! Navigate to HOME directory - cd OR cd ~

* ? Find Path Of Current Working Directory - pwd

## ------Create, Change And Read Files (cat)---------

* ! CTRL + D - SAVES TEXT WRITTEN WITH cat

* ! Create A New Empty File - touch filename.filetype

* ? Create A New File (And Write) - cat > filename.filetype

* ? Read A File - cat filename.filetype

* ? Change All Text In File - echo "text" > text.txt

* ? Append Text To File - echo "text" >> text.txt

* *Read A File, Reverse Order - tac filename.filetype


## * ?---------COPY FILES AND DIRECTORIES (cp)----------

* ? Copy File(s) To Sub-Directory - cp file (file file file) file-directory

* ! Copy File Content To File In Same Directory - cp file1 file2

* ! Copy Entire Directory - cp -R Directory/ToBe/Copied Directory/ToBe/Copied/To


## * ?-------MOVE OR RENAME FILES/DIRECTORIES----------

(Current Directory)
* ? Rename A File - mv old_filename new_filename

* ? Move A File - mv filename Path/To/New/Directory


## * ?------------Directories------------

* ! Create Directory - mkdir directoryfirst/directorsecond
 -p or -parents : Create A Directory Between Directories : music/2020/other creates 2020
 Also Creates Multiple Direcrories 1/2 Creates 1 And 2

 -v Prints A Message For Each Created Directory

* ! Create Directory With Multiple Subdirectories and Subdirectories With Subdirectories - mkdir -p htg/{articles/{new,rewrites},images,notes,done}
//* ?mkdir -p directory/{sub1, 2, 3, 4, 5, ...}


* ! Remove Empty Direcotry - rmdir direcotry
-p : Remove Direcotry And Ancestors (rmdir -p a/b/c removes a, b, c)


---------------FILES---------------------

* ! Remove Files Within Directory - rm filename : Multiple - rm file1 file2 file3 :

* ? Remove Files With Certain Filetyp - rm *.txt

-r : Delete Directory And All Files Within
-d : Works Just Like rmdir
-i : Confirmation For Deletion

* ? File Size - du

* ? Archive File/Directory - tar -cvf name.tar Directory/path OR Directory/File name

* ? Extract Archived File/Directory - tar xvf ----------||--------------------------


-------------------LOCATE FILES AND IN FILES------------------

* ? Locate File From Database System - locate filename (word1*word2 For Multiname File)

* ? Locate File Within Specific Directory - find

* ? Locate Words In File - grep word file.tupe


---------------TROUBLESHOOTING----------------

* ? Check If Network And Host Is Reachable - ping google.com


-------------LOOPS-------------------

* !for x in (1..10); do (SOMETHING $x); done


------------------------------

* !---------Alias----------

To create permanent aliases, open ~/.bashrc (use nano)
Go to the bottom and add the alias.
Write $ source ~/.bashrc

* !------------------------

* !Shutdown - shutdown.exe /s (after 1 mins gracefull, /t for instant)
* Math- expr

mnt/c

mv (MOVE/RENAME)

cp (COPY)

rm (REMOVE)

nano (TEXT EDITOR FILER MAN KAN BRUKE NOTEPAD TIL)

Ctrl + X (OM Q IKKE FUNGERER, BRUKES TIL Å EXITE)

ADMIN (su OR sudo or sudo bash (makes new terminal in admin))

apt-get update (UPDATE REPOSITORY (GET LIST OF UPDATES))

(TRENGER BARE BRUKE APT)
apt-get upggrade (UPGRADES)

apt-get install (INSTALL APPS)

more  press h for help

python3 twitter.py >vg.html (DET SOM HADDE KOMMET I TERMINAL)

python3 twitter.py >vg.html >> appender

ln -s symbolsk link

ls -la

man (MANUAL)