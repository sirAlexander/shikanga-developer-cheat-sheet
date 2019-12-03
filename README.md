# shikanga-developer-cheat-sheet
Useful tools, tips, commands etc.. you name it, the stuff that gets developers through the day

### How to kill a process running on particular port in Linux?
```
kill -9 $(lsof -t -i:3000 -sTCP:LISTEN)
```
