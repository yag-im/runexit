The most recent version of RUNEXIT (available at https://www.shdon.com/blog/2013/05/25/update-to-runexit-tool) has a bug
that hinders the launching of a target application in Windows 3.11. This occurs when the directory path passed into 
ShellExecute ends with a backslash ("\\") instead of the correct format (e.g., "C:\ACE\\" instead of "C:\ACE"), thus 
causing the application to not start properly. This fork contains a fix for that. 

Win3x executable: https://github.com/rayrapetyan/runexit/files/15227813/RUNEXIT.ZIP
Win9x executable: https://github.com/rayrapetyan/runexit/files/15227813/RUNEXIT.ZIP
