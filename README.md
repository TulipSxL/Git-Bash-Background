# Git-Bash-Background

BoldAsFont=yes  
FontHeight=12  
Scrollbar=none  
Term=xterm-256color  
BoldAsColour=yes  
Black=7,54,66  
Red=220,50,47  
Green=133,153,0  
Yellow=181,137,0  
Blue=38,139,210  
Magenta=211,54,130  
Cyan=42,161,152  
White=238,232,213  
BoldBlack=0,43,54  
BoldRed=203,75,22  
BoldGreen=88,110,117  
BoldYellow=101,123,131  
BoldBlue=131,148,150  
BoldMagenta=108,113,196  
BoldCyan=147,161,161  
BoldWhite=253,246,227  
ForegroundColour=192,192,192  
BackgroundColour=0,43,54  
CursorColour=133,153,0  
Columns=140  
Rows=40  

BoldAsFont=-1  
Locale=zh_CN  
Charset=UTF-8  
Font=Consolas  
Transparency=off  
CursorType=block  
CursorBlinks=yes  
FontWeight=700  
FontIsBold=yes  

# git log custom format
log --no-merges --color --date=format:'%Y-%m-%d %H:%M:%S' --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Cblue %s %Cgreen(%cd) %C(bold blue)<%an>%Creset' --abbrev-commit
