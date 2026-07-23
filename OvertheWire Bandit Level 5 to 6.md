## Level 5 → 6

Task: Find a file with specific properties (size, permissions) buried in a directory tree.

# Commands used:

find . -size 1033c -not -executable

What I learned: find can filter by size, permission, type — much faster than manually checking every file.
