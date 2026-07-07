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

### 🚀 Featured Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| **[ktmm-py](https://github.com/ao/ktmm-py)** | Keep That Mouse Moving — cross-platform utility to keep your machine awake | `Python` |
| **[Serengeti](https://github.com/ao/Serengeti)** | An autonomous, self-managing distributed database | `Java` |
| **[hivemind](https://github.com/ao/hivemind)** | Lightweight distributed container orchestration platform | `Go` |
| **[pyroid](https://github.com/ao/pyroid)** | Blazing-fast Rust-powered utilities to eliminate Python's bottlenecks | `Rust` |
| **[favicons](https://github.com/ao/favicons)** | Favicons for all — simple, reliable favicon serving | `PHP` |
| **[RunJavascript](https://github.com/ao/RunJavascript_ChromeExtension)** | Chrome extension to run custom JavaScript on any page | `JavaScript` |
