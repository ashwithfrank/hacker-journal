- L0 -> 1: cat readme
- L1 -> 2: cat ./-
- L2 -> 3: cat ./"--spaces in this filename--"
- L3 -> 4: ls inhere -a && cat inhere/...Hiding-From-You
- L4 -> 5: file inhere/* && cat inhere/-file07
- L5 -> 6: find inhere -type f -size 1033c ! -executable -exec file {} + && cat inhere/maybehere07/.file2
- L6 -> 7: find / -user bandit7 -group bandit6 -size 33c 2>/dev/null && cat /var/lib/dpkg/info/bandit7.password
- L7 -> 8: grep "millionth" data.txt
- L8 -> 9: sort data.txt | uniq -u

