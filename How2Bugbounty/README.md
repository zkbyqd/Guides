# How to become a Bug Bounty Hunter and why + Starter-Checklist + 30 day training plan (beginner-friendly & realistic)

## What is a bug bounty hunter?
> A bug bounty hunter is a person who uncovers security vulnerabilities in real systems, with explicit authorisation, and receives rewards for doing so. These programmes are offered by companies to find vulnerabilities before real attackers do.

## Why is this useful, especially for prospective pentesters?
- Practice in real environments (no labs or simulations)
- Training for pentest skills such as recon, exploits, reporting
- Build a portfolio (e.g. "Hall of Fame" or published reports)
- Job advantage: Many employers love practical evidence
- Side income: Bounties between $50 and $50,000+ possible

## How to become a Bug Bounty Hunter step-by-step

### Learn the basics of web hacking
- Focus on OWASP Top 10, HTTP, cookies, sessions, web technologies

#### Resources:
- PortSwigger Web Security Academy
- TryHackMe: "OWASP Top 10", "Burp Suite Basics"
- Learn Burp Suite the right way (Proxy, Repeater, Intruder, Decoder)

### Train with CTFs and Labs
- Before you go for real programmes, train on exercise systems

#### Resources:
- Hacker101 CTF (from HackerOne)
- Bugcrowd University
- TryHackMe: "Bug Bounty Hunter Path"
- HackTheBox: "Bug Bounty Labs"

### Start with public bug bounty programmes
- Register on platforms, read the rules and start small

#### Resources:
- HackerOne: Many large programmes (e.g. GitHub, PayPal, TikTok)
- Bugcrowd: Good learning resources & smaller programmes
- Intigriti: EU-centred, fair & accessible
- YesWeHack: Alternative with a focus on Europe

### Work systematically
- Bug Bounty is not a matter of luck, you need technique, patience and structure

#### Procedure for bug hunting:
1. Read target & rules (Scope, Out of Scope!)
2. Recon (subdomains, DNS, directories)
3. Search for vulnerabilities (e.g. IDOR, XSS, SSTI)
4. Document exploit (steps, screenshots, video if necessary)
5. Submit report: clear, reproducible, responsible

### Accept mistakes & stick with it
- Not every discovery is a security vulnerability
- Not every vulnerability is accepted
- Every report improves your skillset
- Read many public bug bounty writeups (e.g. [Hacktivity](https://hackerone.com/hacktivity/overview) )

## Conclusion
Bug Bounty Hunting is ideal for:
- People who want to become pentesters
- Developers with an interest in security
- Self-learners with a bite & a thirst for discovery

> It is a realistic addition to the pentesting learning path and sometimes even a door opener to a career

--- 

## Starter-Checklist
> Everything you need to get started in Bug Bounty programmes seriously and effectively

### Requirements
- Good knowledge of web technologies (HTML, JS, HTTP, cookies, sessions, APIs)
- Practical experience with Burp Suite, Recon Tools, Browser DevTools
- Familiar with OWASP Top 10
- Experience with CTFs or Labs (see above)
- Clean legal situation: Only test with permission!

### Toolset for Bug Gunting
- Recon: amass, assetfinder, subfinder
- Crawling: gau, httpx, waybackurls
- Fuzzing: ffuf, dirsearch
- Web Analysis: Burp Suite, Zap
- Javascript analysis: LinkFinder, JSParser

### Vulnerabilities to focus on
- Auth-Bypass: Brute-force login, token reuse
- Broken access control: IDOR, privilege escalation
- Injections: SQLi, XSS, SSTI
- Misconfig: Exposed Admin Panels, CORS Errors
- Business logic: price manipulation, workflow bugs

### Reporting
- Reproducible steps
- Screenshot/video
- Description of the risk
- Fix recommendation
- No infringement of rights!
> Use templates like [Awesome-Bugbounty-Writeups](https://github.com/devanshbatham/Awesome-Bugbounty-Writeups)

### Learning Sources
- Hacker101 CTF
- Bugcrowd University
- Web Security Academy
- YouTube: NahamSec, InsiderPhD, STÖK

--- 

## 30-day bug hunting plan
> Goal: gain practice, learn methodology, find your first real bug or write your first report

### Prerequisites (before starting!)
- Burp Suite set up (Community or Pro)
- Account on: HackerOne, PortSwigger, optionally Bugcrowd
- Basic knowledge of OWASP Top 10, HTTP, cookies, DevTools

### Week 1: Basics & Recon
Day 01: Bug Bounty introduction videos (YouTube: NahamSec, InsiderPhD) \
Day 02: Read OWASP Top 10 Cheatsheet + open Burp Suite \
Day 03: Practise with Burp Suite: Proxy, Repeater, Target, Intruder \
Day 04: Learn subdomain recon: assetfinder, amass, httpx \
Day 05: Practice: Use Bugcrowd/HackerOne to scope a program \
Day 06: Read 3 bug write-ups (e.g. on hackerone.com/hacktivity) \
Day 07: Pause or play CTF on Hacker101 CTF (1 challenge)

### Week 2: Understanding vulnerabilities & web logic
Day 08: Web Injection Basics: XSS (Reflected & Stored) \
Day 09: Practice PortSwigger Labs: XSS (DOM + Reflected) \
Day 10: Analysing authentication: Tokens, Sessions, Cookies \
Day 11: Learn IDOR (Insecure Direct Object Reference) \
Day 12: PortSwigger Lab: Broken Access Control / IDOR \
Day 13: Make Recon on a public program \
Day 14: Test e.g. on exposed endpoints, parameters, login pages

### Week 3: Find errors & prepare reporting
Day 15: Test for CORS errors or outdated APIs \
Day 16: Learn about parameter pollution & open redirects \
Day 17: Search for errors in logout, password reset, auth bypass \
Day 18: Take screenshots & practice writing bug reports \
Day 19: Read 3 reports from HackerOne & analyse structure \
Day 20: Write 1 dummy bug report (practise with a non-real bug) \
Day 21: Rest or optionally upload your reports for review in Discord (e.g. NahamCon server)

### Week 4: Focus on practice & real report
Day 22: Focus on 1 bug type (e.g. IDOR or Stored XSS) \
Day 23: Search specifically for one program (do not jump!) \
Day 24: Document everything: payloads, URLs, screenshots \
Day 25: Finalise a real report (also for "low severity") \
Day 26: Read Bug Bounty Disclosure Policies (Responsible Disclosure) \
Day 27: Submit or save report for review \
Day 28: Solve CTF or Hacker101 Challenge

### Recall and repetition
Day 29: Reflect: What have you learnt? What to improve? \
Day 30: Plan the next 30 days yourself and stick with it!
