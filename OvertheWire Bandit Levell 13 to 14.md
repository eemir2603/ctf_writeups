## Level 13 → 14

Task: Use a provided SSH private key to log in as the next level, instead of a password.

# Commands used:

ssh -i sshkey.private bandit14@localhost

What I learned: SSH key-based auth as an alternative to passwords — copied the key locally, set correct permissions (chmod 600), then connected.

Overall takeaways
Real comfort with piping (|) and redirection (>, 2>/dev/null) came from repetition, not from reading about it
file, grep, find, and strings cover a huge share of everyday recon/enumeration tasks
Learning to decide which tool to reach for (by checking file type first) matters more than memorizing commands
