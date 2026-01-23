```bash
root@AmpedWasTaken:~$ whoami
AmpedWasTaken

root@AmpedWasTaken:~$ cat /etc/motd
╔═══════════════════════════════════════════════════════════════════════════╗
║  Welcome to AmpedWasTaken's GitHub Profile                                ║
║  Full-Stack Developer & Ethical Hacker                                    ║
║  Building secure solutions while breaking things (ethically)              ║
╚═══════════════════════════════════════════════════════════════════════════╝

root@AmpedWasTaken:~$ cat /etc/passwd | grep AmpedWasTaken
AmpedWasTaken:x:1337:1337:Full-Stack Developer & Ethical Hacker:/home/hacker:/bin/bash

root@AmpedWasTaken:~$ sudo systemctl status skills.service
● skills.service - Professional Skills & Expertise
   Loaded: loaded (/etc/systemd/system/skills.service; enabled; vendor preset: enabled)
   Active: active (running) since Mon 2024-01-01 00:00:00 UTC; 999 days ago
   Main PID: 1337 (skills)
      Tasks: 4 (limit: 4915)
     Memory: 16.0G
        CPU: 24h 13m 37s
   CGroup: /system.slice/skills.service
           ├─ Full-Stack Development: [████████████████████] 100%
           ├─ Ethical Hacking: [████████████████████] 100%
           ├─ Penetration Testing: [████████████████░░] 90%
           ├─ Automation: [████████████████████] 100%
           ├─ UI/UX Design: [██████████████████░░] 95%
           └─ Continuous Learning: [████████████████████] 100% (always increasing)

Jan 01 00:00:00 AmpedWasTaken systemd[1]: Started Professional Skills & Expertise.

root@AmpedWasTaken:~$ uname -a
Linux AmpedWasTaken 5.15.0-kali2-amd64 #1 SMP Debian 5.15.5-2kali2 x86_64 GNU/Linux

root@AmpedWasTaken:~$ cat /proc/version
Linux version 1337.999 (AmpedWasTaken@github.com) (gcc version 11.2.0 (GCC)) #1 SMP Mon Jan 1 00:00:00 UTC 2024

root@AmpedWasTaken:~$ uptime
 23:59:59 up 999 days, 13:37:00,  1 user,  load average: 0.00, 0.01, 0.05
 (System has been running smoothly, no crashes detected... yet)

root@AmpedWasTaken:~$ free -h
              total        used        free      shared  buff/cache   available
Mem:           16Gi       8.5Gi       2.1Gi       512Mi       5.4Gi       7.2Gi
Swap:         2.0Gi          0B       2.0Gi

[+] System Status: OPTIMAL
[+] Security Level: MAXIMUM
[+] Hacking Mode: ENABLED
[!] Warning: Coffee levels critical, please refill ☕

root@AmpedWasTaken:~$ cat ~/.bashrc | grep -i "current_projects"
export CURRENT_PROJECTS="Glint and other innovative projects"
export WORKING_ON="Building tools with custom UI & automation"


root@AmpedWasTaken:~$ ./scan_motivation.sh
[*] Initializing motivation scanner...
[*] Scanning for inspirational targets...
[+] Target acquired: Juice WRLD 🕊️
[*] Extracting quote from memory...
[+] Quote extracted: "I'm still here, I'm still breathing"
[*] Processing inspiration data...
[+] 999 Forever - Building code that matters
[*] Status: PERSISTENT [████████████████████] 100%
[+] Motivation level: MAXIMUM
[*] Ready to build the future

root@AmpedWasTaken:~$ netstat -tulpn | grep -E "LISTEN|ESTABLISHED"
Active Internet connections (only servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name
tcp        0      0 0.0.0.0:723892462275395674   0.0.0.0:*               LISTEN      discord/1337
tcp        0      0 0.0.0.0:22                  0.0.0.0:*               LISTEN      sshd
tcp        0      0 0.0.0.0:80                  0.0.0.0:*               LISTEN      nginx
tcp        0      0 0.0.0.0:443                 0.0.0.0:*               LISTEN      nginx

root@AmpedWasTaken:~$ ping -c 3 discord.com
PING discord.com (162.159.128.232) 56(84) bytes of data.
64 bytes from 162.159.128.232: icmp_seq=1 ttl=54 time=12.3 ms
64 bytes from 162.159.128.232: icmp_seq=2 ttl=54 time=11.8 ms
64 bytes from 162.159.128.232: icmp_seq=3 ttl=54 time=12.1 ms

--- discord.com ping statistics ---
3 packets transmitted, 3 received, 0% packet loss, time 2002ms
rtt min/avg/max/mdev = 11.8/12.0/12.3/0.2 ms

[+] Connection established! Ready to collaborate.
[+] Discord: https://discordapp.com/users/723892462275395674
```

<p align="center">
  <a href="https://discordapp.com/users/723892462275395674">
    <img src="https://img.shields.io/badge/Discord-Contact%20Me-9D00FF?style=for-the-badge&logo=discord&logoColor=white">
  </a>
</p>

```bash
root@AmpedWasTaken:~$ nmap -sV -p- localhost | grep -E "PORT|STATE|SERVICE|VERSION"
Starting Nmap 7.92 ( https://nmap.org ) at 2024-01-01 23:59 UTC
Nmap scan report for localhost (127.0.0.1)
Host is up (0.000012s latency).
Not shown: 65530 closed ports
PORT     STATE    SERVICE           VERSION
22/tcp   open     ssh               OpenSSH 8.2p1 Ubuntu 4ubuntu0.5
80/tcp   open     http              Node.js Express framework
443/tcp  open     ssl/http          React.js development server
3306/tcp open     mysql             MySQL 8.0.31-0ubuntu0.22.04.1
5432/tcp open     postgresql        PostgreSQL DB 13.9
8080/tcp open     http-proxy        Go backend API
Nmap done: 1 IP address (1 host up) scanned in 2.34 seconds

[+] Tech Stack Arsenal Detected:
[+] Frontend: JavaScript, HTML, CSS, React, Tailwind
[+] Backend: Node.js, Python, Java, PHP, Go, C#, C++
[+] Databases: MySQL, PostgreSQL, SQLite
[+] Tools: Git, GitHub, VS Code, Linux, Lua, NPM
```

## ⚙️ Languages & Tools  

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,html,css" />
  <br>
  <img src="https://skillicons.dev/icons?i=lua,nodejs,npm,python,java,php,go" />
  <br>
  <img src="https://skillicons.dev/icons?i=cs,cpp,mysql,linux,git,github,vscode,react,tailwind,sqlite" />
</p>

```bash
root@AmpedWasTaken:~$ git log --oneline --all --graph --decorate | head -20
* 7a3f2d1 (HEAD -> main, origin/main) [FEAT] Added new security feature
* 9b4e5c2 [FIX] Resolved memory leak in authentication module
* 2c8d1f3 [REFACTOR] Optimized database queries
* 5e7f9a4 [FEAT] Implemented automated testing suite
* 1a2b3c4 [DOCS] Updated README with terminal theme
* 8d9e0f1 [FEAT] Added dark mode support
* 3f4a5b6 [FIX] Fixed cross-browser compatibility issues
* 6c7d8e9 [FEAT] Implemented real-time notifications
* 4a5b6c7 [REFACTOR] Code cleanup and optimization
* 9e0f1a2 [FEAT] Added new API endpoints
* 2b3c4d5 [FIX] Security patch for XSS vulnerability
* 7c8d9e0 [FEAT] Enhanced user authentication
* 1f2a3b4 [DOCS] Updated API documentation
* 5a6b7c8 [FEAT] Implemented caching layer
* 8e9f0a1 [FIX] Resolved race condition in async operations
* 3c4d5e6 [FEAT] Added comprehensive error handling
* 6d7e8f9 [REFACTOR] Improved code structure
* 9a0b1c2 [FEAT] Implemented logging system
* 4d5e6f7 [FIX] Fixed memory management issues
* 7e8f9a0 [FEAT] Added performance monitoring

[+] Commit Status: ACTIVE
[+] Code Quality: EXCELLENT
[+] Repositories: GROWING
[+] Contributions: CONSISTENT
```

```bash
root@AmpedWasTaken:~$ ./analyze_profile.sh AmpedWasTaken
[*] Initializing GitHub profile analyzer...
[*] Connecting to GitHub API...
[+] Connection established
[*] Fetching user data...
[+] User: AmpedWasTaken
[*] Analyzing repositories...
[+] Total repositories: 42
[*] Analyzing contributions...
[+] Total contributions: 999+
[*] Analyzing code quality...
[+] Code quality score: 98/100
[*] Calculating threat level...
[+] Threat Level: LEGENDARY ⚡
[*] Status: BUILDING THE FUTURE
[*] Risk assessment: This developer is too dangerous to be left alive (in a good way)
[+] Analysis complete!

root@AmpedWasTaken:~$ cat /proc/github/stats
GitHub Statistics:
  Commits: ████████████████████ 999+
  Repositories: ████████████████░░░░ 42
  Contributions: ████████████████████ 999+
  Code Quality: ████████████████████ 98%
  Streak: ████████████████████ ACTIVE
```

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AmpedWasTaken&show_icons=true&theme=radical&locale=en&hide_border=true&bg_color=0D1117&title_color=9D00FF&icon_color=9D00FF" width="49%">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AmpedWasTaken&theme=radical&hide_border=true&background=0D1117&ring=9D00FF&fire=9D00FF&currStreakLabel=9D00FF" width="49%">
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AmpedWasTaken&theme=radical&hide_border=true&bg_color=0D1117&title_color=9D00FF" width="100%">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmpedWasTaken&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=9D00FF&text_color=ffffff" width="49%">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=AmpedWasTaken&theme=radical&hide_border=true&bg_color=0D1117&title_color=9D00FF" width="49%">
</p>

```bash
root@AmpedWasTaken:~$ git clone https://github.com/AmpedWasTaken/repos.git
Cloning into 'repos'...
remote: Enumerating objects: 999, done.
remote: Counting objects: 100% (999/999), done.
remote: Compressing objects: 100% (999/999), done.
remote: Total 999 (delta 0), reused 999 (delta 0), pack-reused 0
Receiving objects: 100% (999/999), 133.7 MiB | 13.37 MiB/s, done.
Resolving deltas: 100% (0/0), done.
[+] Repository cloned successfully!
[+] Location: ./repos
[+] Ready for exploration
```

<p align="center">
  <a href="https://github.com/AmpedWasTaken?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Explore%20Repositories-9D00FF?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>

```bash
root@AmpedWasTaken:~$ exit
logout

╔═══════════════════════════════════════════════════════════════════════════╗
║  [*] Session terminated                                                   ║
║  [+] Building the future, one commit at a time...                         ║
║  [*] Status: ACTIVE                                                       ║
║  [+] Made with ❤️ and lots of ☕                                         ║
║  [*] Access granted. Welcome to the matrix.                               ║
║  [+] Check out my work: https://github.com/AmpedWasTaken?tab=repositories ║
║  [*] 999 Forever 🕊️❤️                                                    ║
╚═══════════════════════════════════════════════════════════════════════════╝

Connection to AmpedWasTaken closed.
```
