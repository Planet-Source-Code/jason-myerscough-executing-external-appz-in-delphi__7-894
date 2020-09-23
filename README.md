<div align="center">

## Executing External Appz In Delphi


</div>

### Description

This article show how to run start appz from your delphi program
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jason Myerscough](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jason-myerscough.md)
**Level**          |Beginner
**User Rating**    |4.5 (27 globes from 6 users)
**Compatibility**  |Delphi 7, Delphi 6, Delphi 5, Delphi 4
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__7-39.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jason-myerscough-executing-external-appz-in-delphi__7-894/archive/master.zip)





### Source Code

I saw no point in uploading a one liner so here is how you open other programs from your delphi program.
In the <b>uses</b> make sure you add ShellAPI.
The folllowing lines opens up notepad
<br>
<table align=center cellpadding=0 cellspacing=0 border=1 bordercolor=blue>
<tr>
<td>ShellExecute(Handle, 'Open', 'notepad', nil, nil, SW_SHOW);</td>
</tr>
</table>
<br>
To open the broswer and to go to a specific page use the following line.
<br>
<table align=center cellpadding=0 cellspacing=0 border=1 bordercolor=blue>
<tr>
<td>ShellExecute(Handle, 'Open', 'www.somesite.com', nil, nil, SW_SHOW);</td>
</tr>
</table>
Rate this superb article :P

