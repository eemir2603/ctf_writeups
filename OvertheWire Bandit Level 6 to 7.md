## Level 6 → 7

Task: Find a file somewhere on the whole filesystem owned by a specific user/group and of a specific size.

# Commands used:

find / -user bandit7 -group bandit6 -size 33c 2>/dev/null

What I learned: Redirecting stderr (2>/dev/null) hides "permission denied" spam so real results are readable.
