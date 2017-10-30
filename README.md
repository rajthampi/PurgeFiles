# PurgeFiles
A Command line tool for deleting files from Server/PC matching user defined age in days

Idea

Servers & PCs those accummulate large volume of log files, database export files require frequent house keeping activities committed by administrators on regular intervals to free up the storage. Using this little tool, an administrator could schedule a task using Windows task scheduler to purge those files on regular intervals. Basically this tool deletes files matching a particular type chosen by end user when those files age exceeds user defined age in days.

Usage Syntax

purgefiles.exe -dFolder <Target Folder Name> -fType <Targetted file type> -nDays <Age of files in number of days>

eg: PurgeFiles.exe -dFolder C:\myfolder -fType *.txt -nDays 100

-dFolder: Source folder from which the .txt files will be deleted which are exceeding 100 days from the date of creation
  

