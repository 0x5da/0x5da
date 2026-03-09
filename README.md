<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00FF54,100:0d1117&height=200&section=header&text=0x5da&fontSize=80&fontColor=00FF54&animation=fadeIn&fontAlignY=38" width="100%"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00FF54&center=true&vCenter=true&repeat=true&width=500&lines=breaking+things+so+you+don't+have+to;if+it+has+an+IP%2C+it+has+a+vulnerability;london+%F0%9F%87%AC%F0%9F%87%A7+%7C+infosec+%7C+red+team" alt="Typing SVG" />
</div>

<br>

<div align="center">
  <img src="https://github.com/0x5da/0x5da/blob/main/picture/rep.gif" alt="rep" width="600"/>
</div>

---

i do offensive security — exploit dev, pentesting, building custom tools, the usual. been in the space long enough to know that the best security comes from understanding how things break.

currently spending most of my time on kernel-level exploitation research and building out OSINT automation. when i'm not doing that i'm probably reversing something i shouldn't be or competing in CTFs.

i work with **[Imperium Solutions](https://www.imperiumsolutions.xyz/)** — they run a solid OSINT/CSINT platform with 200+ tools, breach monitoring, dark web intel, the whole stack. if you need serious recon capabilities, [check their API](https://www.imperiumsolutions.xyz/api_docs.php).

---

### what i actually use daily

the stuff i reach for, not just everything i've ever touched:

![Python](https://img.shields.io/badge/-Python-0d1117?style=flat-square&logo=python&logoColor=00FF54)
![C](https://img.shields.io/badge/-C-0d1117?style=flat-square&logo=c&logoColor=00FF54)
![Go](https://img.shields.io/badge/-Go-0d1117?style=flat-square&logo=go&logoColor=00FF54)
![Bash](https://img.shields.io/badge/-Bash-0d1117?style=flat-square&logo=gnu-bash&logoColor=00FF54)
![Rust](https://img.shields.io/badge/-Rust-0d1117?style=flat-square&logo=rust&logoColor=00FF54)
![x86 Assembly](https://img.shields.io/badge/-x86_ASM-0d1117?style=flat-square&logo=assemblyscript&logoColor=00FF54)
![PowerShell](https://img.shields.io/badge/-PowerShell-0d1117?style=flat-square&logo=powershell&logoColor=00FF54)

**offensive** — burp suite, metasploit, ghidra, ida, nmap, wireshark, sqlmap, hashcat, cobalt strike, aircrack-ng<br>
**defensive** — splunk, elastic, snort, yara, suricata<br>
**infra** — kali, docker, aws, kubernetes, terraform, ansible<br>
**platforms** — hackthebox, tryhackme, ctftime

---

### what i'm good at

**exploit dev** — buffer overflows, rop chains, heap exploitation, format strings, shellcoding. this is where i spend most of my research time. kernel stuff lately.

**web security** — the full owasp spectrum. xss, sqli, ssrf, xxe, deserialization, jwt/oauth attacks. done enough bug bounties and pentests to have seen most of it in the wild.

**reverse engineering** — static and dynamic analysis, unpacking, anti-debug bypass. mostly x86/x64 but getting into ARM. ghidra and ida are basically my IDEs at this point.

**active directory** — kerberoasting, dcsync, golden tickets, ntlm relay, bloodhound-driven attack paths. AD environments are still absurdly fun to break.

**network** — packet-level analysis, protocol exploitation, mitm, pivoting through segmented networks. wireshark is always open somewhere.

**osint/recon** — automated reconnaissance pipelines, social engineering pretexts, attack surface mapping. built a lot of custom tooling here through the imperium partnership.

---

### stats

<div align="center">

<a href="https://github.com/0x5da">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=0x5da&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&count_private=true&include_all_commits=true&cache_seconds=1800" />
</a>
<a href="https://github.com/0x5da">
  <img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=0x5da&hide_border=true&background=0d1117&stroke=00FF5430&ring=00FF54&fire=FF6B00&currStreakLabel=00FF54&sideLabels=00FF54&currStreakNum=9f9f9f&sideNums=9f9f9f&dates=555555&cache_seconds=1800" />
</a>

</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=0x5da&hide_border=true&bg_color=0d1117&point=00FF54&line=00FF54&color=9f9f9f&area=true&area_color=00FF5415&custom_title=contribution%20activity" width="95%"/>
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=0x5da&theme=matrix&no-frame=true&no-bg=true&column=7&margin-w=8" width="90%"/>
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/0x5da/0x5da/raw/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/0x5da/0x5da/raw/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake" src="https://github.com/0x5da/0x5da/raw/output/github-contribution-grid-snake.svg" width="95%" />
  </picture>
</div>

---

### exploit research

educational PoCs demonstrating specific vulnerability classes from the ground up. each repo ships the vulnerable target binary, the working exploit, and a detailed writeup explaining what's happening at the memory level. written in C/C++, built to be readable — the goal is understanding, not just popping a shell.

<table>
<tr>
<td width="50%">
<a href="https://github.com/0x5da/New-Shellcode-Injection-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=New-Shellcode-Injection-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>shellcode injection</b> — demonstrates how position-independent shellcode is written, injected into a process, and executed. covers memory allocation with <code>VirtualAlloc</code>/<code>mmap</code>, marking regions executable, and transferring control via function pointer or thread creation. also touches on NX/DEP awareness and basic shellcode encoding to evade simple pattern detection.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Heap-Buffer-Overflow-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Heap-Buffer-Overflow-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>heap buffer overflow</b> — unlike stack overflows, heap corruptions require understanding the allocator internals. this one walks through how overflowing a heap chunk corrupts adjacent chunk metadata, how glibc's tcache and fastbin structures can be poisoned, and how to turn a controlled heap write into code execution by overwriting a function pointer or GOT entry.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/C-VTable-Hijack-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=C-VTable-Hijack-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>C++ vtable hijacking</b> — C++ virtual dispatch is a common attack surface in real-world software. this PoC shows how vtables are laid out in memory, how an adjacent heap corruption can overwrite an object's vtable pointer, and how the next virtual function call then dispatches into attacker-controlled memory. includes ASLR bypass via heap info leak.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Double-Free-Heap-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Double-Free-Heap-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>double-free heap exploitation</b> — freeing the same chunk twice corrupts the allocator's free list. this repo demonstrates how tcache/fastbin double-free turns into tcache poisoning, leading to <code>malloc</code> returning an arbitrary address. from there, overwriting <code>__malloc_hook</code> or a GOT entry gives code execution. covers how modern glibc mitigations try to catch this and how they're bypassed.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Format-String-Arbitrary-Read-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Format-String-Arbitrary-Read-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>format string — arbitrary read</b> — the first step in any format string chain is information leakage. covers using <code>%x</code>, <code>%p</code>, and <code>%s</code> specifiers to dump stack values, locate return addresses, and read arbitrary memory via direct parameter access (<code>%N$s</code>). primary use case here is defeating ASLR by leaking libc and binary base addresses before writing anything.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Format-String-Arbitrary-Write---exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Format-String-Arbitrary-Write---exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>format string — arbitrary write</b> — the <code>%n</code> specifier writes the character count to an address on the stack. this PoC demonstrates how to craft a format string that writes a controlled value to an arbitrary address — typically a GOT entry or a return address — to redirect execution. covers padding arithmetic and multi-write techniques to hit 8-byte values efficiently.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Format-String-Chain-Multi-Step-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Format-String-Chain-Multi-Step-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>format string — chained multi-step exploit</b> — combines read and write into a full end-to-end exploit chain against a ASLR + PIE binary. step 1: leak libc and binary base via <code>%p</code>/<code>%s</code>. step 2: calculate runtime addresses. step 3: overwrite GOT with a one_gadget via <code>%n</code>. step 4: trigger the overwritten function and pop a shell. this is the "complete" format string exploit — no training wheels.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Command-Injection-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Command-Injection-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>command injection</b> — demonstrates OS command injection through unsafe use of <code>system()</code> and <code>popen()</code> with unsanitized user input. covers shell metacharacter injection (<code>;</code>, <code>|</code>, <code>&&</code>, backticks), blind injection via timing and out-of-band channels, and escalation to full RCE. also looks at why string sanitization approaches fail and what safe alternatives look like.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/AMWP-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=AMWP-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>arbitrary memory write primitive (AMWP)</b> — the capstone of the series. demonstrates how to chain multiple lower-severity bugs to establish a write-what-where condition — writing an arbitrary value to an arbitrary address — and then escalate that primitive into full code execution. covers combining info leaks with controlled writes, targeting <code>__free_hook</code>/<code>__malloc_hook</code>, and ROP chain setup for modern mitigations. the most complex exploit in the collection.
</td>
</tr>
</table>

the progression is intentional — shellcode injection → heap overflow → vtable hijack → format string read → write → chained multi-step → double free → command injection → arbitrary memory write primitive. each one builds on concepts from the previous and represents a distinct class of memory corruption.

---

### security tools

real tools i've built and actively use. designed to be fast, composable, and useful in real engagements — not toys.

<table>
<tr>
<td width="50%">
<a href="https://github.com/0x5da/0x5da-VPS-Malware-C2-Scanner-Exploit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=0x5da-VPS-Malware-C2-Scanner-Exploit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>VPS malware & C2 scanner</b> — scans cloud and VPS IP ranges for indicators of malware hosting and active C2 infrastructure. fingerprints known C2 frameworks (Cobalt Strike, Sliver, Havoc, Metasploit) via TLS certificate patterns, HTTP response signatures, and characteristic open port/service combinations. useful for threat intel, hunting exposed C2 redirectors, and monitoring your own infrastructure for compromise.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Imperium-OSINT-Framework-tool">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Imperium-OSINT-Framework-tool&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>Imperium OSINT framework</b> — Python CLI that wraps the <a href="https://www.imperiumsolutions.xyz/api_docs.php">Imperium Solutions API</a> into a unified recon workflow. automates target profiling across 200+ OSINT sources — breach data lookups, domain/IP intelligence, historical WHOIS, SSL cert transparency, dark web monitoring, and social footprint mapping. designed for fast pre-engagement recon and attack surface discovery.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/DNS-Discovery-Tool">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=DNS-Discovery-Tool&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>DNS discovery tool</b> — DNS enumeration and subdomain discovery with multiple resolution strategies. covers brute-force subdomain enumeration against custom wordlists, zone transfer attempts, DNSSEC chain validation, PTR/reverse lookups, and full DNS record harvesting (A, AAAA, MX, NS, TXT, SRV, CAA). output is structured for piping into other tools. built for thorough attack surface mapping before a pentest.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Port-Auditor-tool">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Port-Auditor-tool&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>port auditor</b> — goes beyond raw port scanning. performs service fingerprinting against discovered open ports, cross-references identified versions against known CVEs, flags misconfigurations (default creds exposure, unauthenticated services, dangerous protocols like telnet/rsh), and generates structured JSON/HTML reports. designed for both internal network audits and external perimeter assessments.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Content-Discovery-Scanner">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Content-Discovery-Scanner&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>content discovery scanner</b> — web content and endpoint discovery via wordlist-based path fuzzing with smart response analysis. differentiates real content from generic 404s via response size/hash comparison, detects WAF presence and soft-block patterns, follows redirects intelligently, and supports authenticated sessions. finds hidden admin panels, backup files, configuration endpoints, and unlinked API paths that passive crawling misses.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/RESTful-API-security-assessment-framework">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=RESTful-API-security-assessment-framework&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>REST API security assessment framework</b> — automated framework for testing REST APIs against the OWASP API Security Top 10. tests for IDOR (horizontal and vertical privilege escalation), broken authentication (token reuse, JWT algorithm confusion, weak secrets), excessive data exposure in responses, missing rate limiting, mass assignment vulnerabilities, and injection flaws through all parameter types. takes an OpenAPI spec or auto-discovers endpoints via crawling.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/TLS-SSL-security-assessment-tool-for-certificate-validation">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=TLS-SSL-security-assessment-tool-for-certificate-validation&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>TLS/SSL security assessment tool</b> — comprehensive TLS/SSL configuration scanner. checks for deprecated protocol support (SSLv2, SSLv3, TLS 1.0/1.1), weak cipher suites (RC4, 3DES, export-grade), insecure renegotiation, BEAST/POODLE/BEAST vulnerability indicators, HSTS misconfiguration, certificate chain validation issues, wildcard cert risks, and certificate transparency log presence. produces a scored report with remediation guidance.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/cryptanalysis-toolkit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=cryptanalysis-toolkit&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>cryptanalysis toolkit</b> — collection of cryptanalysis and crypto-audit utilities. covers automated hash identification and offline cracking setup, frequency analysis and classical cipher breaking (Caesar, Vigenère, substitution), weak RSA key detection (small exponents, shared prime factors via GCD), ECB mode detection in block ciphers, padding oracle attack tooling, and JWT secret brute-forcing. useful for CTFs, pentest crypto findings, and understanding why custom crypto is always a bad idea.
</td>
</tr>
</table>

---

### forensics & analysis

blue team and IR tooling — built mostly because the existing options were either too slow, too expensive, or too noisy. understanding how attacks work from the offensive side makes writing detection and analysis tools a lot more useful.

<table>
<tr>
<td width="50%">
<a href="https://github.com/0x5da/Malware-behavior-analyzer">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Malware-behavior-analyzer&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>malware behavior analyzer</b> — dynamic analysis tool for observing malware at runtime without a full sandbox. monitors file system modifications, registry key changes (Windows), network connections established, child processes spawned, and loaded DLLs/modules. captures before/after snapshots and diffs them to produce an IOC-ready behavior report. useful for quick triage during incident response when you need to know what a suspicious binary actually does.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Network-Artifact-Recovery-tool">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Network-Artifact-Recovery-tool&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>network artifact recovery tool</b> — extracts forensic artifacts from PCAP files and live captures. automatically reassembles TCP streams, extracts transferred files (HTTP, FTP, SMB), recovers cleartext credentials from unencrypted protocols, carves session tokens and cookies, and identifies C2 communication patterns. designed for IR teams who need to quickly reconstruct what happened over the wire during an incident.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Network-Flow-Inspector-tool">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Network-Flow-Inspector-tool&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>network flow inspector</b> — ingests and correlates NetFlow, IPFIX, and sFlow records to surface anomalous traffic patterns. detects lateral movement indicators (port scanning, new east-west connections), potential data exfiltration (large outbound transfers to new destinations), C2 beaconing (periodic connections with consistent byte counts), and DNS tunneling via query volume and entropy analysis. outputs timeline-correlated findings and supports integration with SIEM platforms.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Log-Analysis-Engine">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Log-Analysis-Engine&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>log analysis engine</b> — multi-source log ingestion and correlation engine. parses syslog, Windows Event Log (EVTX), Apache/Nginx access logs, auth logs, and firewall logs. applies configurable detection rules to surface IOCs: brute force attempts, privilege escalation events, unusual logon times/locations, suspicious process execution chains, and known attack pattern signatures. designed to be fast on large log archives — useful for post-incident forensic reconstruction.
</td>
</tr>

<tr>
<td width="50%">
<a href="https://github.com/0x5da/Metadata-extraction-tool">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=0x5da&repo=Metadata-extraction-tool&hide_border=true&bg_color=0d1117&title_color=00FF54&icon_color=00FF54&text_color=9f9f9f&cache_seconds=1800" />
</a>
</td>
<td valign="top" width="50%">
<br>
<b>metadata extraction tool</b> — deep metadata extraction from documents, images, audio, and executables. pulls EXIF data from images (GPS coordinates, device info, timestamps), hidden properties from Office/PDF documents (author, revision history, tracked changes), PE header data from Windows binaries (compile timestamps, linker version, imports), and embedded strings from any file type. dual use: OSINT on files collected during recon, and forensic analysis of files recovered during an investigation.
</td>
</tr>
</table>

---

### reach me

<div align="center">

[![GitHub](https://img.shields.io/badge/-0x5da-0d1117?style=flat-square&logo=github&logoColor=00FF54)](https://github.com/0x5da)
[![Twitter](https://img.shields.io/badge/-@0x5da-0d1117?style=flat-square&logo=x&logoColor=00FF54)](https://twitter.com/0x5da)
[![LinkedIn](https://img.shields.io/badge/-0x5da-0d1117?style=flat-square&logo=linkedin&logoColor=00FF54)](https://linkedin.com/in/0x5da)
[![Email](https://img.shields.io/badge/-contact@0x5da.com-0d1117?style=flat-square&logo=gmail&logoColor=00FF54)](mailto:contact@0x5da.com)
[![Imperium](https://img.shields.io/badge/-Imperium_Solutions-0d1117?style=flat-square&logo=shield&logoColor=00FF54)](https://www.imperiumsolutions.xyz/)

</div>

---

<sub>everything in my repos is for authorized testing and education only. don't be stupid with it. unauthorized access is illegal and i'm not responsible for what you do with any of this. MIT licensed where applicable.</sub>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=0x5da&style=flat-square&color=00FF54&label=views" alt="views"/>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00FF54,100:0d1117&height=100&section=footer" width="100%"/>
</div>
