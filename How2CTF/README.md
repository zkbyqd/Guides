# How to Learn and Play CTFs: Step-by-Step Guide + training plan

## Step 1: Understand What CTFs Are

**CTFs** are cybersecurity competitions where participants solve challenges to capture "flags" (usually a string like `flag{you_got_the_string}`).

There are three common formats:

- **Jeopardy** – Solve standalone challenges in categories like cryptography, forensics, reverse engineering, etc. Each challenge is worth points based on difficulty.
- **Attack/Defense** – Teams are assigned identical environments. They must patch vulnerabilities in their own systems while exploiting others to steal flags.
- **Wargames** – Ongoing, gamified learning environments that simulate CTF challenges in a progressively difficult series. Unlike CTFs, they aren't live competitions, but are used to practice and build foundational skills.

> Start with Jeopardy-style CTFs; they’re beginner-friendly and skill-focused.

---

## Step 2: Learn the Basics of Cybersecurity

Before diving into CTFs, you should be comfortable with:

- Linux command line (bash/shell)
- Networking fundamentals (IP, DNS, ports, protocols)
- Basic programming (Python is highly recommended)
- File systems and permissions
- Hex editors, encodings (Base64, Hex, etc.)

---

## Step 3: Practice With Beginner-Friendly Platforms

Start playing beginner-friendly CTFs or wargames:

- [Hack The Box](https://www.hackthebox.com/)
- [TryHackMe](https://tryhackme.com/)
- [picoCTF](https://picoctf.org/)
- [CTFlearn](https://ctflearn.com/)
- [OverTheWire](https://overthewire.org/)

These platforms expose you to real CTF problems in a safe, learn-as-you-go environment.

---

## Step 4: Set Up Your Toolkit

Install essential tools every CTF player should have:

- **Linux VM** (Kali Linux, Parrot OS, Ubuntu)
- **Burp Suite** (for web exploitation)
- **Ghidra** (reverse engineering)
- **Wireshark** (network forensics)
- **CyberChef** (online encoding/decoding tool)
- **Python + pwntools** (for scripting exploits)

Optional: Create a dedicated VM or Docker setup for CTFs.

---

## Step 5: Learn Core CTF Categories

Focus on mastering these categories:

1. **Cryptography** – Caesar cipher, XOR, RSA, SHA-2
2. **Web Exploitation** – SQLi, XSS, IDOR, SSRF
3. **Reverse Engineering** – Analyze and decompile binaries
4. **Forensics** – PCAP analysis, metadata, steganography
5. **Binary Exploitation** – Buffer overflows, format strings
6. **Miscellaneous/OSINT** – Trivia, sleuthing, logic puzzles

> Don’t try to learn everything at once, specialize gradually.

---

## Step 6: Join Live CTF Competitions

Start participating in real CTF events:

- Browse upcoming events on [CTFtime.org](https://ctftime.org/)
- Join solo or as part of a beginner team
- Find teammates via Reddit or Discord communities:
  - [r/securityCTF](https://www.reddit.com/r/securityCTF/)
  - CTF Discord servers like [HackSmarter](https://discord.gg/k4pXKvzdVE) [CyberInfo](https://discord.gg/cyberinfo)

> Focus on learning, not winning.

---

## Step 7: Write Writeups

Document each challenge you solve:

- Problem description
- Your approach & tools used
- Final solution/flag (respect platform guidelines to not post flags online!!)
- What you learned

This builds your personal knowledge base and helps with future challenges.

---

## Step 8: Grow Your Skills Continuously

- Read writeups (CTFtime, Medium, GitHub repos)
- Follow CTF streamers and YouTube channels
- Join a local CTF team
- Contribute to CTF challenges or open-source platforms

--- 

## CTF training plan by category (beginner to advanced)
Goal: A structured overview of how to learn and improve in the main CTF categories

### Web Exploitation
- beginner: XSS, SQLi, CSRF, Directory Traversal -> TryHackMe: "OWASP Top 10", PortSwigger Academy
- advanced: SSTI, RCE, IDOR, OAuth bypass -> HackTheBox: Web Challenges, Bug Bounty labs
- pro: Deserialization, Race Conditions -> CTFtime Events, Custom Labs

### Cryptography
- beginner: Caesar, XOR, Base64, ROT13 -> PicoCTF, CryptoHack
- advanced: RSA math, LSB attacks -> CryptoPals Challenges
- pro: ECC, Timing Attacks -> Real CTFs (HTB Crypto)

### Forensics
- beginner: File Carving, Strings, Steganografie -> TryHackMe: "Intro to Forensics"
- advanced: PCAP-Analyse, Memory Dumps -> Wireshark Challenges, Volatility
- pro: Malware Analysis, Reverse Engineering -> HTB Forensics, CTFtime.org

### Reverse Engineering
- beginner: Strings, Ghidra Basics, Obfuscation -> PwnCollege, CrackMe
- advanced: Decompiled Logic, Jump Tables -> HTB Reversing, ROP Emporium
- pro: Binary Obfuscation, Anti-Debugging -> Real CTFs, Malware Playground

### Binary Exploitation
- beginner: Buffer Overflows, Stack Analysis -> TryHackMe: "Buffer Overflow Prep"
- advanced: ASLR, NX bypass, Format String -> pwn.college, ROP Emporium
- pro: Heap Exploits, GOT Overwrite -> Real CTFs (e.g. PlaidCTF)

---

## Final Advice

CTFs are less about "hacking" and more about learning to think like an attacker. Be curious, persistent, and don't be afraid to search the web or ask AI for *everything*. Every solved challenge makes you better.
