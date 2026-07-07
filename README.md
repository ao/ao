<h1 align="center">whoami</h1>

```asm
; x86-64 · Linux · NASM
section .data
    id      db  "distributed systems // low-level // always shipping", 0x0a
    len     equ $ - id

section .text
    global _start

_start:
    mov     rax, 1          ; sys_write
    mov     rdi, 1          ; fd = stdout
    lea     rsi, [rel id]   ; buf
    mov     rdx, len        ; count
    syscall

    xor     rdi, rdi        ; exit code 0
    mov     rax, 60         ; sys_exit
    syscall
```

---

### 📊 Stats

<p align="center">
  <img src="https://img.shields.io/github/followers/ao?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117&color=1f6feb&label=Followers" alt="Followers" />
  <img src="https://img.shields.io/github/stars/ao?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117&color=1f6feb&label=Stars&affiliations=OWNER" alt="Stars" />
  <img src="https://img.shields.io/badge/Public%20repos-133-1f6feb?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" alt="Repos" />
  <img src="https://img.shields.io/badge/On%20GitHub%20since-2012-1f6feb?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" alt="Since 2012" />
</p>

```console
$ gh api user | jq '.stats'
{
  "member_since"        : "2012",          # 13 years on GitHub
  "public_repos"        : 133,
  "total_stars_earned"  : 142,
  "contributions_1y"    : 10990,
  "commits_1y"          : 448
}

$ gh repo list --json language | jq 'group_by(.language)'
JavaScript  ████████████████░░░░░░░░░░░░░░░░  18%
Python      ███████████████░░░░░░░░░░░░░░░░░  17%
PHP         ███████████░░░░░░░░░░░░░░░░░░░░░  12%
Go          ██████████░░░░░░░░░░░░░░░░░░░░░░  11%
Java        ███████░░░░░░░░░░░░░░░░░░░░░░░░░   8%
TypeScript  █████░░░░░░░░░░░░░░░░░░░░░░░░░░░   5%
```

---

### 🚀 Featured Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| **[ktmm-py](https://github.com/ao/ktmm-py)** | Keep That Mouse Moving — cross-platform utility to keep your machine awake | `Python` |
| **[Serengeti](https://github.com/ao/Serengeti)** | An autonomous, self-managing distributed database | `Java` |
| **[hivemind](https://github.com/ao/hivemind)** | Lightweight distributed container orchestration platform | `Go` |
| **[pyroid](https://github.com/ao/pyroid)** | Blazing-fast Rust-powered utilities to eliminate Python's bottlenecks | `Rust` |
| **[favicons](https://github.com/ao/favicons)** | Favicons for all — simple, reliable favicon serving | `PHP` |
| **[RunJavascript](https://github.com/ao/RunJavascript_ChromeExtension)** | Chrome extension to run custom JavaScript on any page | `JavaScript` |
