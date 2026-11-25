<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,55:12304a,100:1f6feb&height=200&section=header&text=LAD&fontSize=68&fontColor=ffffff&desc=LAIANDI%20%C2%B7%20pwn%20%2F%20binary%20exploitation&descSize=16&descAlignY=80" width="100%" alt="header" />

<a href="https://laiandi.github.io"><img src="https://img.shields.io/badge/Blog-laiandi.github.io-1f6feb?style=flat-square&logo=hexo&logoColor=white" alt="Blog" /></a>
<a href="https://github.com/LAIANDI/ctf-writeups"><img src="https://img.shields.io/badge/Writeups-ctf--writeups-0b1220?style=flat-square&logo=github&logoColor=white" alt="Writeups" /></a>
<img src="https://img.shields.io/badge/GDUT-ADSec-12304a?style=flat-square" alt="GDUT ADSec" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1200&color=58A6FF&center=true&vCenter=true&width=560&lines=Linux+userland+exploitation;glibc+heap+%C2%B7+FSOP+%C2%B7+ORW;CTF+pwn+%2F+binary+exploitation" alt="typing" />

</div>

```console
lad@github:~$ whoami
LAD / LAIANDI
GDUT · AD 攻防工作室
focus: Linux userland exploitation · glibc heap · CTF pwn
```

## 精选

| 题目 | 赛事 | 考点 |
|:--|:--|:--|
| [glibc_master](https://github.com/LAIANDI/ctf-writeups/blob/main/pwn/glibc_master.md) | 长城杯 2022 | 堆 UAF · 负下标 OOB · House of Apple 2 FSOP |
| [superheap](https://github.com/LAIANDI/ctf-writeups/blob/main/pwn/superheap.md) | CISCN 2024 | Go + protobuf · tcache poisoning · House of Some · ORW |
| [msgboard](https://github.com/LAIANDI/ctf-writeups/blob/main/pwn/msgboard.md) | DASCTF | 格式化字符串 · `leave;ret` 栈迁移 · seccomp ORW |
| [minihttpd](https://github.com/LAIANDI/ctf-writeups/blob/main/pwn/minihttpd.md) | CISCN 2025 Quals | 非 PIE 栈溢出 · 无 pop rdx · 任意文件读 |

→ 更多见 [**ctf-writeups**](https://github.com/LAIANDI/ctf-writeups)

## 出题

**ADCTF 2026 · pwn**：6 道题，难度曲线 `ret2win → shellcode → fmt → pivot → ORW → heap`。

## 工具箱

<p>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/pwntools-0b1220?style=flat-square&logo=python&logoColor=white" alt="pwntools" />
<img src="https://img.shields.io/badge/GDB%20%2F%20pwndbg-12304a?style=flat-square&logo=gnu&logoColor=white" alt="GDB" />
<img src="https://img.shields.io/badge/IDA%20%2F%20Ghidra-1f6feb?style=flat-square" alt="IDA Ghidra" />
<img src="https://img.shields.io/badge/ROPgadget-0b1220?style=flat-square" alt="ROPgadget" />
<img src="https://img.shields.io/badge/seccomp--tools-12304a?style=flat-square" alt="seccomp-tools" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

## 现在

- 把零散题解整理成可复现的作品集
- 补真实漏洞（CVE）复现，往 Linux 内核 / 虚拟化方向深入
- 近期关注：heap feng shui、`io_uring`、KVM

## 联系

[Blog](https://laiandi.github.io) · [GitHub](https://github.com/LAIANDI)

<div align="center"><sub>只在本机隔离环境和授权目标上做安全研究。</sub></div>
