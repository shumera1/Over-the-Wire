# OverTheWire Wargames

My notes and progress from the [OverTheWire](https://overthewire.org/wargames/) wargames, a set of free challenges for learning security concepts in a hands-on, game-style format.

## Purpose

This repository documents what I learned at each level: the concepts involved, the commands and tools I used, and the mistakes that taught me something. It is not a list of answers. The goal is to build practical skills I can apply in penetration testing.

> **Spoiler policy:** OverTheWire asks players not to publish passwords or full solutions, so this repo contains **no level passwords** and no copy-paste walkthroughs.

## Progress

| Wargame | Focus | Status |
|---|---|---|
| [Bandit](./bandit) | Linux command line, file handling, SSH, networking basics | In progress |
| [Leviathan](./leviathan) | Basic Linux exploitation and binary analysis | Not started |
| [Natas](./natas) | Web application security | Not started |
| [Krypton](./krypton) | Classical cryptography | Not started |
| [Narnia](./narnia) | Binary exploitation basics | Not started |
| [Behemoth](./behemoth) | Binary exploitation and reverse engineering | Not started |
| [Utumno](./utumno) | Binary exploitation and reverse engineering | Not started |
| [maze](./maze) | Binary exploitation and reverse engineering | Not started |


## Skills Practised

Each wargame targets a different area of security. The skills listed are the ones each game is designed to build.

### Core Progression

#### Bandit (beginner)
- **Prerequisites:** none
- **Skills:** Linux command line, file searching and filtering (`find`, `grep`, `sort`, `uniq`), encoding and compression (`base64`, `tar`, `gzip`), SSH and key-based authentication, basic networking with `nc`, `nmap` and `openssl s_client`, Git basics, cron jobs, SUID binaries and shell escapes

#### Leviathan (beginner to intermediate)
- **Prerequisites:** Bandit
- **Skills:** analysing compiled programs without source code (`ltrace`, `strings`), SUID binary abuse, symbolic link and race condition tricks, reading how a program behaves to find weaknesses

#### Natas (web security)
- **Prerequisites:** Bandit, basic HTTP knowledge
- **Skills:** inspecting page source and HTTP headers, cookies and session handling, `robots.txt` and hidden directories, authentication flaws, file upload abuse, command injection, SQL injection, encoding and weak obfuscation, request manipulation with `curl` or an intercepting proxy

#### Krypton (cryptography)
- **Prerequisites:** Bandit, basic scripting
- **Skills:** classical ciphers (Caesar, Vigenère, substitution), frequency analysis, key length analysis, known-plaintext attacks, weaknesses in simple stream ciphers and poor randomness

#### Narnia (introduction to binary exploitation)
- **Prerequisites:** Bandit, basic C
- **Skills:** reading C source, stack buffer overflows, shellcode, environment variables, format string vulnerabilities, debugging with `gdb`

#### Behemoth (intermediate binary exploitation)
- **Prerequisites:** Narnia
- **Skills:** buffer overflows, race conditions, privilege escalation via vulnerable SUID programs, working without source code, deeper `gdb` use

#### Utumno (advanced)
- **Prerequisites:** Narnia, Behemoth
- **Skills:** memory corruption, ELF internals, crafting custom shellcode, exploiting under tighter constraints

#### Maze (advanced)
- **Prerequisites:** Utumno
- **Skills:** analysing complex programs with minimal hints, developing custom exploits, applying a broad mix of earlier techniques

### Skills Summary

| Area | Games |
|---|---|
| Linux fundamentals | Bandit, Leviathan |
| Scripting and automation | Bandit, Krypton, Natas |
| Web application security | Natas |
| Cryptography | Krypton |
| Reverse engineering and binary analysis | Leviathan, Narnia, Behemoth, Utumno, Maze |
| Exploit development | Narnia, Behemoth, Utumno, Maze |
| Privilege escalation | Bandit, Leviathan, Behemoth |

