## Level 12 → 13

Task: Reverse a multi-layered compression/encoding chain (hexdump → gzip → bzip2 → tar → …).

# Commands used:

xxd -r data.txt > data.bin (reverse the hexdump)
file data.bin (identify each layer before deciding the next tool)
Repeated gzip -d, bunzip2, tar -xf depending on what file reported at each step

What I learned: When a file's been through several compression layers, file before each step tells you exactly which tool to reach for next instead of guessing.
