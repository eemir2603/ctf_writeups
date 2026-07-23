Level 1 → 2

Task: Read a file whose name starts with a dash (-), which normally confuses the shell into thinking it's a flag.

Commands used:

cat ./-

What I learned: Using ./ to explicitly point to a file in the current directory avoids the shell misreading - as an option flag.
