## Level 8 → 9

Task: Find the line that occurs only once in a large file.

# Commands used:

sort data.txt | uniq -u

What I learned: Piping sort into uniq -u isolates unique (non-duplicate) lines — uniq only works correctly on sorted input.
