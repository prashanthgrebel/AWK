# AWK

# * Print all but the first column:
```
cat <file> | awk '{$1=""; print $0}'
cat <file> | awk '{$1=$2=""; print $0}'    
```


