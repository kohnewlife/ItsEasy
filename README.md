This is my collection of quick tutorials for popular developers' tools.  
I personally edit and summarize to keep the content as concise as possible.  
*(**Suggestions** are appreciated; **contributions** are more than welcomed)*

# **Linux**
```
1. Commands:
+ Navigation
./Documents
../../

Ctrl + c  
      universal Cancel
Ls [options] [location]
      list items
pwd 
      print working directory
cd 
      Change Directories 
File [path] 
      what type it is
man <command>
      manuals
man -k <search term> 
      search for all manual pages containing the given search term
'q' 
      quit
'/' <search term> enter
       search, 'n' for next 

+ File manipulation
mkdir [options] <Directory> 
      Creating a directory
rmdir [options] <Directory> 
      remove directory
'-p' 
      make parent directories as needed. 'mkdir -p test/butt'
'-v'
      it is doing. 'mkdir -pv test3/butt'
rm [options] <file> 
      remove a file
rm -r <directory> 
      Removing non empty Directories

touch [options] <filename>
      Creating a Blank File
cp [options] <source> <destination> 
      Copying a File 
(If the destination is to a file, it will create a copy of the source but name the copy the filename specified in destination. If we provide a directory as the destination then it will copy the file into that directory and the copy will have the same name as the source.)
cp -r <source> <destination> 
      Copying a Dir
mv [options] <source> <destination>
(mv foo2 backups/foo3 = We moved the directory foo2 into the directory backups and renamed it as foo3)
(mv barney backups/ = We moved the file barney into backups. As we did not provide a destination name, it kept the same name.)


2. Rules:
Case sensitive. No Undo. Tab for suggesting. 
Space
      'Holiday Photos' or Holiday\ Photos
Hidden 
      '.'   .file.txt  => to show hidden files: ls -a
shorthand
      ls -a,  ls -alh(combined)
longhand
      ls --all

3. Vi Text Editor
vi <file>
      start vi
cat <file>
      view small files
less <file>
      view big files     SpaceBar=forward a page;  b=back a page; q=quit
'i'
      insert
Esc
      escape
ZZ 
      Save and exit
:q!
      discard all changes, since the last save, and exit
:w
      save file but don't exit
:wq
      again, save and exit
```


# **Regex**

```
abc…	Letters
123…	Digits
\d	Any Digit
\D	Any Non-digit character
.	Any Character
\.	Period
[abc]	Only a, b, or c
[^abc]	Not a, b, nor c
[a-z]	Characters a to z
[0-9]	Numbers 0 to 9
\w	Any Alphanumeric character
\W	Any Non-alphanumeric character
{m}	m Repetitions
{m,n}	m to n Repetitions
*	Zero or more repetitions
+	One or more repetitions
?	Optional character
\s	Any Whitespace
\S	Any Non-whitespace character
^…$	Starts and ends
(…)	Capture Group
(a(bc))	Capture Sub-group
(.*)	Capture all
(abc|def)	Matches abc or def
```
