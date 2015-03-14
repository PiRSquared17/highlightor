To add syntax colouring from one of these:
Unpack to an .xml file, if zipped;
If you don't have an userDefineLang.xml file already, you can drop this file among your other configuration file, in the Notepad++ Install Folder. It should be named userDefineLang.xml.
Otherwise, open both the existing and new file.
Select all of the new file, copy, and paste at the end of the current file.
This will have created a spurious 

Unknown end tag for </Notepad\_Plus>



<Notepad\_plus>

 pair i the middle, each tag on a line by itself. Remove these two consecutive lines.
Close Notepad++.
Your Languages menu will show the newly added language at the bottom, next time you launch Notepad++.

more can refs. http://sourceforge.net/apps/mediawiki/notepad-plus/index.php?title=User_Defined_Language_Files#M