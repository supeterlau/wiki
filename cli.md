CommandLine in Action

## find

https://stackoverflow.com/questions/5905054/how-can-i-recursively-find-all-files-in-current-and-subfolders-based-on-wildcard linux - How can I recursively find all files in current and subfolders based on wildcard matching? - Stack Overflow

find . -name "foo*"

find . -name "*.log" | xargs grep -rin 'IPAddress'

https://stackoverflow.com/questions/6844785/how-to-use-regex-with-find-command linux - How to use regex with find command? - Stack Overflow

find . -regextype sed -regex ".*/[a-f0-9\-]\{36\}\.jpg"

https://superuser.com/questions/294161/unix-linux-find-and-sort-by-date-modified Unix/Linux find and sort by date modified - Super User

https://superuser.com/questions/294161/unix-linux-find-and-sort-by-date-modified/546900#546900 Unix/Linux find and sort by date modified - Super User
https://unix.stackexchange.com/questions/29899/how-can-i-use-find-and-sort-the-results-by-mtime ls - How can I use `find` and sort the results by mtime? - Unix & Linux Stack Exchange

GNU find

find . -printf "%T@ %Tc %p\n"

non-GNU find

https://superuser.com/a/298173