# cmd_launcheur
this is a launcher wich only need cmd to work

to make it work you need to download the txt and launch cmd
and paste : <br>

`reg add "hklm\software\microsoft\command processor" /v autorun /t reg_expand_sz /d "doskey /listsize=999 /macrofile=PATH_OF_LAUNCHEUR.TXT" /f`
<br>

REPLACE "PATH_OF_LAUNCHEUR.TXT" by the path of your txt file
