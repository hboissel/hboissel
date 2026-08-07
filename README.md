# Hugo Boissel

I am a security-focused developer trained at 42 School. I learn how systems fail by building them, reproducing attacks in isolated labs, and documenting the path from analysis to exploitation. 🙂

[LinkedIn](https://www.linkedin.com/in/hugoboissel/) · [Email](mailto:hboissel@student.42.fr) · [All repositories](https://github.com/hboissel?tab=repositories)

## Projects 🧪

### [Override — Binary Exploitation](https://github.com/hboissel/override)

Ten progressively hardened binary-exploitation challenges with reconstructed source code and detailed walkthroughs. The work covers stack overflows, format-string vulnerabilities, shellcode, GOT overwrites, return-to-libc, and exploitation under RELRO, NX, and PIE protections.

`C` `Python` `x86` `GDB` `ELF` `ret2libc`

### [Inquisitor — ARP Spoofing & Traffic Inspection](https://github.com/hboissel/inquisitor)

A Rust man-in-the-middle lab that forges ARP replies, captures Ethernet/IPv4/TCP traffic, extracts filenames from FTP transfers, and restores the victims' ARP tables when interrupted. A three-container Docker environment provides a controlled attacker/victim test network.

`Rust` `pnet` `ARP` `TCP/IP` `Docker` `Packet Analysis`

### [Snow Crash — Linux Security & Privilege Escalation](https://github.com/hboissel/snow-crash)

Fifteen documented security challenges covering password and hash analysis, PATH hijacking, symlink abuse, command injection, weak service configurations, and debugger-assisted program analysis.

`Linux` `GDB` `Shell` `Python` `Privilege Escalation`

### [BADASS — Network Architecture Lab](https://github.com/hboissel/BADASS)

A GNS3 and Docker network lab that progresses from custom router containers to a VXLAN overlay and a BGP EVPN control plane, using OSPF as the underlay and FRRouting for routing services.

`GNS3` `Docker` `FRRouting` `VXLAN` `BGP EVPN` `OSPF`

### [ft_ssl — Cryptographic Primitives in C](https://github.com/hboissel/ft_ssl)

An OpenSSL-style command-line tool implementing MD5 and SHA-256 in C, including file, string, and standard-input processing with compatible output modes.

`C` `MD5` `SHA-256` `Cryptography` `CLI`

## Additional security work 🔐

* [Rainfall](https://github.com/hboissel/rainfall) — binary-exploitation exercises involving stack overflows, format strings, function-pointer corruption, shellcode, and integer overflow.
* [ft_otp](https://github.com/hboissel/ft_otp) — TOTP generation, encrypted key storage, and QR-code enrollment implemented in Rust.
* [Arachnida](https://github.com/hboissel/Arachnida) — a recursive web image collector and an EXIF/metadata inspection utility.
* [ft_onion](https://github.com/hboissel/ft_onion) — a containerized Tor onion service with SSH hardening.
* [Stockholm](https://github.com/hboissel/stockholm) — a file-encryption/decryption simulation restricted to a controlled test directory.

## Systems foundations 🛠️

* [malloc](https://github.com/hboissel/malloc) — a C allocator with `mmap`-backed zones, block splitting/coalescing, memory inspection, and `LD_PRELOAD` support.
* [webserv](https://github.com/hboissel/webserv) — an HTTP/1.1 web server written from scratch in C++98, including request parsing, concurrent connections, and CGI handling.
