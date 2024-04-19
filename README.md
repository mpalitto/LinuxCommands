** VEDI WIKI 4 more **

* Display each directory along with the count of files in that directory and its subdirectories
`tree -i -f -L 1 --dirsfirst | while read dir; do echo -n "$dir: "; find "$dir" -type f | wc -l; done`
