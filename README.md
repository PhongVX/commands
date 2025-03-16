# commands
## Linux
### Check Disk Usage Summary
```df -h```

df: disk free
-h: human-readable

### List Large Files and Directories
```du -ah / | sort -rh | head -10```

du: disk usage
du -ah: list all disk usage and human-readable
sort -rh:  
  + sort: Sorts lines of text.
  + -r or --reverse: Sorts in descending order.
  + -h or --human-numeric-sort: Sorts numbers with human-readable suffixes
head -10: Displays the first 10 lines.



