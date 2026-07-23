## Level 9 → 10

Task: Find a human-readable string inside a binary/data file.

# Commands used:

strings data.txt | grep -i "^="

What I learned: strings extracts printable text from binary data — useful for pulling readable content out of otherwise unreadable files.
