# Hello there, I'm BEGGAR SidAli (a.k.a Ali Beggar) :D

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?center=true&vCenter=true&font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=00FF9C&background=0D1117&width=700&lines=%24+objdump+-d+-M+intel+./whoami;%24+gdb+-q+./life+%E2%80%94+b+*main;x86_64+%7C+Reverse+Engineering+%7C+Computer+Architecture" alt="Typing SVG" />
  </a>
</p>

```nasm
section .rodata
    handle  db "Welcome to my GitHub profile! I'm a third-year Computer Science student at ESI Algiers (1CS) who enjoys Low-Level things, OS implementations, CPU/GPU architectures and sometimes CyberSecurity stuff!", 0x0a
    role    db "CS Engineering | Unix Operating Systems | Low-Level & Cybersecurity", 0x0a
    focus   db "x86_64, Reverse Engineering, CTFs, OS Internals", 0x0a
    len     equ $ - handle

section .text
    global _start

_start:
    mov     rax, 1              ; sys_write
    mov     rdi, 1              ; stdout
    lea     rsi, [rel handle]   ; RIP-relative load
    mov     rdx, len
    syscall

    mov     rax, 60             ; sys_exit
    xor     rdi, rdi            ; return 0
    syscall
```


---

## Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,kotlin,git,linux,java,tailwind,js,react,vscode,figma,ps,ai,pr&theme=dark" alt="Tech Stack" />
</div>

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AliBeggar&theme=dark&background=0d1117&border=30363d&stroke=58a6ff&ring=58a6ff&fire=58a6ff&currStreakLabel=c9d1d9" alt="GitHub Streak" />
</div>

---

```console
$ file ./whoami
./whoami: ELF 64-bit LSB pie executable, x86-64, dynamically linked, not stripped

$ checksec --file=./whoami
    Arch:     amd64-64-little
    RELRO:    Full RELRO
    Stack:    Canary found
    NX:       NX enabled
    PIE:      PIE enabled
    Focus:    Reverse Engineering, Computer Architecture, Systems
    Status:   Reading the Intel SDM & breaking binaries
```

<div align="center">
  <a href="https://www.linkedin.com/in/sid-ali-beggar/">
    <img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" />
  </a>
  <a href="https://www.instagram.com/ali.beggar/">
    <img src="https://skillicons.dev/icons?i=instagram" alt="Instagram" />
  </a>
  <a href="mailto:os_beggar@esi.dz">
    <img src="https://skillicons.dev/icons?i=gmail" alt="Email" />
  </a>
</div>

---
