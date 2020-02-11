# Command line notes

Corey Schafer has a few very important videos related to the Command line. Check them out and take notes below.

## Linux/Mac Terminal Tutorial: Navigating your Filesystem
[Watch the Video](https://www.youtube.com/watch?v=j6vKLJxAKfw)

-> Navigating filesystem
   pwd (Print working directory)
   ls (list)
   cd (Change directory)
   ls -a (Hidden files)
   ls -l (list long form)
   ls -la (Combining options)
   <Relative paths>
   . (Current directory)
   .. (Parent directory)

## Linux/Mac Terminal Tutorial: Create, Copy, Move, Rename and Delete Files and Directories
[Watch the Video](https://www.youtube.com/watch?v=eoejHvAPDFs)

create: start with pwd 
        mkdir (file's name) ex) mkdir TestDir
        [cd TestDir]
        touch test_file.txt
        $test_file.txt will be created in a floder, TestDir
copy: use 'CP' command
      -> cp (file name that is copyed) (file name that is pasted)
move: use 'MV' command
      -> mv (file's name) (folder name that the file would be replaced)

rename: use 'MV' command
        -> mv (file name before changed) (file's new name)
move and rename at the same time:
        -> mv  (file's name) ../(file's new name)
delete: use 'RM' command
        -> rm (file name)

directories: man (something) ex) man cp, man rm

## Mac OS X Terminal Tutorial: Time-Saving Keyboard Shortcuts
[Watch the Video](https://www.youtube.com/watch?v=TXzrk3b9sKM)

Ctrl+a: move to beginning of the line

Ctrl+e: move to end of the line

option+,<- ->: move one word at a time

option+Click: move to click location

Ctrl+u: deldte everything before cursor

Ctrl+k: delete everything after the cursor

Tab: auto-complete

drag folder in the terminal as directly, then shows what are in folder.

command'fi': rerun, can see that the last command that it ran 

history: show all history

if you want to run the one at 5:27, instead of copying and pasting or retyping the whole thing out, just type in exclamation point 527 and it shows history that is run at 5:27

Ctrl+r: reverse search

Ctrl+l: clear screen

Cmd+k: clear scrillback
