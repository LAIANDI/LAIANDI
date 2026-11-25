<div align="center">

# LAD / LAIANDI

**广东工业大学 · AD 攻防工作室**  
pwn / binary exploitation / CTF

[Blog](https://laiandi.github.io) · [CTF Writeups](https://github.com/LAIANDI/ctf-writeups)

</div>

## 关于我

- 广工 AD 攻防工作室成员，方向是 Linux 用户态漏洞利用与 CTF Pwn。
- 做过：栈溢出、格式化字符串、栈迁移、`seccomp` 下的 ORW、glibc 堆（UAF / tcache poisoning / FSOP）。
- 出题：ADCTF 2026 pwn 方向 6 道题，覆盖 ret2win → shellcode → fmt → pivot → ORW → heap 的难度曲线。
- 2028 届，寻找 2027 年暑期实习（深圳 / 广州）。

## 精选

| 项目 | 说明 |
|---|---|
| [ctf-writeups](https://github.com/LAIANDI/ctf-writeups) | 精选 CTF 题解：House of Apple 2、House of Some、`leave;ret` 栈迁移、ORW 等 |
| [glibc_master](https://github.com/LAIANDI/ctf-writeups/blob/main/pwn/glibc_master.md) | 堆 UAF + 负下标 OOB + House of Apple 2 FSOP |
| [superheap](https://github.com/LAIANDI/ctf-writeups/blob/main/pwn/superheap.md) | Go + protobuf、tcache poisoning、House of Some、ORW |
| [msgboard](https://github.com/LAIANDI/ctf-writeups/blob/main/pwn/msgboard.md) | 格式化字符串 + `leave;ret` 栈迁移 + seccomp 下的 ORW |
| [Blog](https://laiandi.github.io) | CTF / 安全学习笔记 |

## 技术栈

`C` `Python` `pwntools` `gdb / pwndbg` `IDA / Ghidra` `ROPgadget` `seccomp-tools` `Docker`

## 现在

- 把零散题解整理成可复现的作品集
- 补真实漏洞（CVE）复现，往 Linux 内核 / 虚拟化方向深入

## 联系

- Blog: <https://laiandi.github.io>
- GitHub: <https://github.com/LAIANDI>

> 只在本机隔离环境和授权目标上做安全研究。
