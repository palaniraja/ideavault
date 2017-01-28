**Find Files over 20MB/20000KB**

    find / -type f -size  20000k -exec ls -lh {} \; | awk '{ print $9 ": " $5 }'

or

    find . -size  20000k -exec du -h {} \;

**List all files**

find . -name \*.* -print


---
2012-07-14