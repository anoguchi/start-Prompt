# PROMPT - Command Line

## Primeiros comandos
`cd` : change directory  
`dir` : display a list of files  
`dir *.png` : display only png files  
`dir folder\nestedfolder\teste` : display files inside that directory  
`dir /a` : display a list of files and hidden files  
`cls` : clear screen  
`start` : start new command line window  
`mkdir` : make a new directory  
`rmdir` : remove directory
`rmdir /s` : remove directory with stuffs inside it  
`path` : Displays or sets a search path for executable files  
`tree` : Graphically display the directory structure  
`color /?` : See color change options  
`attrib` : Display or changes file attributes  
`attrib +h bacon.txt` : Add attributes to a file  
`attrib /?` : Display or changes file attributes options  
`del` : Delete file  
`echo > bacon.txt` : Create an empty file  
`echo Chocolate > donuts.txt` : Create a file with Chocolate inside  
`echo Vanilla >> donuts.txt` : add Vanilla on second line  
`dir > dir.txt` : add dir results inside dir.txt file   
`type` : Displays the contents of a text file  
`copy donuts.txt folder-name` : Copy to another location  
`xcopy folder-name anotherfolder` : Copy files inside folder-name to anotherfolder  
`xcopy folder-name anotherfolder /s` : Copy files and folders inside folder-name to anotherfolder  
`move folder-name anotherfolder` : Move one or more files to another directory  
`rename` : Renames a file or files  
`set` : Sell all system variables

## Adicionando variáveis
`setx PATH "%PATH%;C:\Program Files\Java\jdk1.8.0_71\bin /M";`
`setx JAVA_HOME "C:\Program Files\Java\jdk1.8.0_71" /M`

