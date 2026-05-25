# Cybersecurity Portfolio — Shivam Pajiyar

**Security Architect · GIAC Advisory Board Member · GCIH · GSEC (97th percentile) · GFACT**
Toronto, ON · [LinkedIn](https://linkedin.com/in/shivampajiyar) · [GitHub](https://github.com/shivampajiyar) · pajiyarshivam@gmail.com

---

## About Me

I got into cybersecurity through the back door. I started as a software developer, founded a company (Nepal Technology Service), and built a production social media app (Migrease) that is currently live on the App Store and Google Play. The more systems I built, the more I found myself spending equal time thinking about how those systems could be broken. That pull eventually became a deliberate career pivot.

I enrolled in the SANS Bachelor of Professional Studies in Applied Cybersecurity and earned GFACT, then GSEC at the 97th percentile, then GCIH. I was selected for the GIAC Advisory Board. I competed in NCL Spring 2026 and placed 38th out of 341 teams (89th percentile) in the Team Game and 80th out of 466 players (83rd percentile) individually — both in the Experienced Students Bracket, reserved for students in advanced degree programs or with extensive industry experience. I presented at the Harvard CS50 Fair and have acknowledged responsible disclosure credits with Samsung and D-Link.

My goal is a mid-level security engineering or detection engineering role where I can apply both the builder and the breaker mindset.

---

## CTF Experience — NCL Spring 2026

The National Cyber League (NCL) Spring 2026 competition placed me against 7,520 players from over 440 schools across all 50 U.S. states. I competed in the Experienced Students Bracket across both the Individual Game (April 10–12) and Team Game (April 24–26), covering nine categories: cryptography, password cracking, log analysis, network traffic analysis, scanning and reconnaissance, open source intelligence, web application exploitation, enumeration and exploitation, and forensics.

**The individual game is the more revealing data point.** With teammates, you can divide and cover — the team result reflects collective skill. The individual result is you, alone, under a timer, working through every category. My 80th place finish (83rd percentile) out of 466 experienced students, scoring 2480/3000 with 85.1% completion against a field average of 55.5%, tells me where I genuinely stand and what still needs work.

The starkest contrast between my two games is in the categories where I had no safety net. Password cracking dropped from 99th percentile (team) to 73rd (individual) — without a teammate to handle the harder hash types while I focused elsewhere, time management under pressure became the limiting factor. OSINT was the opposite story: I completed every single challenge individually (100% completion, 69th/466) including the hardest one — tracing a malicious actor through repositories, usernames, emails, and Bitcoin addresses — despite the field average completion being 73.7%. I just needed more attempts on individual questions to nail the exact answer format.

**What the competition taught me:** methodology matters more than tools, and time under pressure reveals the gaps that study does not. The categories where I underperformed individually — cryptography (48.8% accuracy, particularly the pigpen cipher), log analysis (ADpocalypse DCSync evtx parsing), and forensics (RDP bitmap recovery, heap dump analysis) — are now my specific training targets.

---

## NCL Spring 2026 — Team Game Results

**38th place out of 341 teams · 89th percentile · Experienced Students Bracket**

Scouting Report (verified): [cyberskyline.com/report/XKBKM9G39TK4](https://cyberskyline.com/report/XKBKM9G39TK4)

| Category | Score | Accuracy | Rank | Percentile |
|----------|-------|----------|------|------------|
| Cryptography | 360 / 360 | 100% | 14th / 341 | 96th |
| Password Cracking | 355 / 355 | 100% | 5th / 341 | 99th |
| Network Traffic Analysis | 300 / 300 | 100% | 9th / 341 | 98th |
| Scanning & Reconnaissance | 300 / 300 | 100% | 10th / 341 | 98th |
| Enumeration & Exploitation | 300 / 300 | 100% | 14th / 341 | 96th |
| Web Application Exploitation | 300 / 300 | 94.4% | 16th / 341 | 96th |
| Log Analysis | 300 / 300 | 95.2% | 14th / 341 | 96th |
| Open Source Intelligence | 295 / 385 | 94.9% | 78th / 341 | 78th |
| Forensics | 220 / 300 | 66.7% | 81st / 341 | 77th |
| **Total** | **2830 / 3000** | **94.7%** | **38th / 341** | **89th** |

*Field average accuracy: 71.7% — team finished 23 percentage points above average.*

---

## NCL Spring 2026 — Individual Game Results

**80th place out of 466 players · 83rd percentile · Experienced Students Bracket**

Scouting Report (verified): [cyberskyline.com/report/B7MAEU47WL3T](https://cyberskyline.com/report/B7MAEU47WL3T)

*Also earned 15 CompTIA-approved CEUs for this performance.*

| Category | Score | Accuracy | Rank | Percentile |
|----------|-------|----------|------|------------|
| Scanning & Reconnaissance | 300 / 300 | 94.7% | 35th / 466 | 93rd |
| Enumeration & Exploitation | 300 / 300 | 68.2% | 55th / 466 | 89th |
| Web Application Exploitation | 300 / 300 | 82.6% | 59th / 466 | 88th |
| Open Source Intelligence | 385 / 385 | 39.4% | 69th / 466 | 86th |
| Network Traffic Analysis | 300 / 300 | 48.9% | 99th / 466 | 79th |
| Cryptography | 290 / 360 | 48.8% | 94th / 466 | 80th |
| Log Analysis | 220 / 300 | 50.0% | 136th / 466 | 71st |
| Password Cracking | 170 / 355 | 60.0% | 126th / 466 | 73rd |
| Forensics | 115 / 300 | 54.5% | 150th / 466 | 68th |
| **Total** | **2480 / 3000** | **53.9%** | **80th / 466** | **83rd** |

*Field average completion: 55.5% — I completed 85.1% of all challenges attempted.*

---

## Highlights

**Scanning & Reconnaissance — 35th place individually (93rd percentile)**
Perfect score solo, including enumerating Avahi/mDNS services on a remote machine, DNS reconnaissance of internal resources, and mail server enumeration with IMAP access via VRFY username brute-forcing. This category rewards methodical nmap usage and service-layer thinking, which transfers directly from my background building networked systems.

**OSINT — 69th place individually, 100% completion**
Full 385/385 points with every challenge completed. The hardest challenge (Ergo Propter Hoc, Hard) involved tracing a malicious actor backward through GitHub repositories, username pivots, email addresses, and Bitcoin addresses. The 39.4% accuracy figure reflects questions that required exact answer formatting rather than failed investigative paths — I found the data consistently, but got penalized on presentation. This is fixable.

**Cryptography highlights — RSA signing oracle, AES-CBC bit-flip, PRNG seed recovery**
Perfect marks on the RSA signing oracle (Broken Signer, Hard: computing the private key from an unreliable signing oracle to decrypt the flag) and AES-CBC bit-flip challenge (team game, Checkpoint: forging a trusted session token by flipping ciphertext bits). The PRNG seed recovery challenge (Lottery, Medium) involved recovering the internal seed from an insecurely used Java PRNG — 72.7% accuracy, some questions missed.

**Network Traffic Analysis — full marks, both games**
300/300 in both team and individual, covering HTTP object carving, Minecraft protocol parsing, LAN device enumeration from a packet capture, DNS packet parsing, MITM post-compromise analysis, and ISO 8583 replay attack detection. The ISO 8583 challenge (Replay, Hard) was one I particularly enjoyed — parsing financial transaction messages to detect a replay attack is the kind of problem that does not appear in most security curricula.

**Enumeration & Exploitation — full marks, both games**
Team game: chaining buffer overflow with use-after-free to bypass an MTE simulator. Individual game: sudo CVE exploitation, C++ executable reverse engineering, and environment variable injection into a Rust binary. These challenges rewarded patience and reading compiled output carefully.

**Honest gaps**
Forensics was my weakest category in both games. The individual forensics score (115/300) reflects near-zero progress on RDP bitmap recovery and heap dump IoC analysis — tools and artifact locations I had not practiced enough. DCSync attack detection in Windows event logs (ADpocalypse) and the custom SQLcipher password cracking challenge (Serpens) are specific skills I am adding to my training rotation.

---

## Certifications

| Certification | Issuer | Notes |
|---------------|--------|-------|
| GIAC Certified Incident Handler (GCIH) | GIAC / SANS | |
| GIAC Security Essentials (GSEC) | GIAC / SANS | 97th percentile |
| GIAC Foundational Cybersecurity Technologies (GFACT) | GIAC / SANS | |
| GIAC Advisory Board Member | GIAC | Selected based on exam performance |

---

## Other Work

- **[ncl-ctf-writeups](https://github.com/shivampajiyar/ncl-ctf-writeups)** — Technical writeups from NCL Spring 2026 covering network forensics, cryptography, web exploitation, and forensics
- **Nepal Technology Service** — Software development company I founded; clients across North America and Asia
- **Vulnerability Research** — Responsible disclosures acknowledged by Samsung and D-Link
- **Harvard CS50 Fair** — Selected presenter

---

## Currently Studying

SANS Bachelor of Professional Studies in Applied Cybersecurity (Expected 2027)

---

*This portfolio was created as part of the SANS BPS Applied Cybersecurity program, Spring 2026.*
