## Level 11 → 12

Task: Decode text that's been rotated with ROT13.

# Commands used:

cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

What I learned: tr can do character-by-character substitution — this is literally how ROT13 works under the hood, just shifting each letter 13 places.
