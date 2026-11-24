# Mishchenko Sergey (serbekun)

14, live in Japan. I write code because I want a specific tool and either nobody built it
or I had a search skill issue.
Started with Batch scripts on a school computer. Now it is mostly Java, Rust and Python,
plus a homelab that I break more often than I fix.

## Stack

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=serbekun&layout=compact&hide=html,css,shell,c,c%2B%2B,gnuplot,lua&theme=transparent"/>

- **Java + Javalin** — backends and REST APIs.
- **Rust** — CLI tools, TUIs, anything where the binary matters.
- **Python** — scripts and ML, mostly data work.
- **Arch Linux** — laptop and servers. Ubuntu only where I have no choice: the DMZ proxy and WSL.
- **nginx, SSH, tmux, git** — used daily, not a "skills" list.

## Infrastructure

A small home network, all reachable over SSH:

- `dmz` — Ubuntu Server. nginx, Java services, 80/443. Public entry point.
- `node2` — Arch laptop. Where I actually write code.
- `node3` — main Arch server. CPU is nice relative to my other CPUs, GPU is a Quadro P2200.
  Where I train CCAiM and run the Minecraft server for friends.
- A Windows box with WSL — for the things that refuse to run on Linux.

Domain: serbekun.com. Repos also live on a private git-shell host, not only on GitHub.

## Projects

- [serbekun_services](https://github.com/serbekun/serbekun_services) — Javalin API toolbox:
  hashing, Base64/hex/URL encoding, AES/RSA/hybrid encryption, UUID/ULID, short links with QR,
  burn-after-reading links, JSON format/diff.
- [CCAiM](https://github.com/serbekun/CCAiM) — cloud type classifier from ground photos,
  10 WMO classes. Current ResNet18: 50.34% validation accuracy, macro-F1 0.390 on 916 labelled
  images. Small unbalanced dataset, honest baseline, no leaderboard claims. Dataset and weights
  on Hugging Face.
- [serbekun.com](https://serbekun.com) — terminal-style link card. Static, no framework,
  no reason for one.

Email: serbekun@gmail.com
