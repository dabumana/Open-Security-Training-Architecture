# :key: Open Security Training Architecture
Architecture internals learning path from Open Security Training, provides a set of resources to complete the learning path, includes code-base, videos, techniques, useful articles and concepts to understand the courses provided from Open Security Training.

### Register in [**p.ost2.fyi**](https://p.ost2.fyi)
___

### Resources

#### Videos:
* https://www.youtube.com/watch?v=eItru07D3aE&t=20s
* https://www.youtube.com/watch?v=TsXzDFjXj2s&t=1770s
* https://www.youtube.com/watch?v=JMEJCLX2dtw&t=1628s
* https://www.youtube.com/watch?v=2_aokrfcoUk&t=1887s
* https://www.youtube.com/watch?v=TsXzDFjXj2s&t=1635s

#### Articles:
* Bringing Call Gates Back - https://www.alex-ionescu.com/?p=340

#### Wiki:
* https://en.wikipedia.org/wiki/Memory_management_unit
* https://en.wikipedia.org/wiki/PaX#Enforced_non-executable_pages
* https://en.wikipedia.org/wiki/Win32_Thread_Information_Block

#### Concepts:
* TEB - https://www.geoffchappell.com/studies/windows/km/ntoskrnl/inc/api/pebteb/teb/index.htm
* KPCR (amd64)- https://www.geoffchappell.com/studies/windows/km/ntoskrnl/inc/ntos/amd64_x/kpcr.htm
* KPCR (i386) - https://www.geoffchappell.com/studies/windows/km/ntoskrnl/inc/ntos/i386_x/kpcr.htm
* Sysenter - https://manugarg.appspot.com/systemcallinlinux2_6.html
* Syscall - https://x86.lol/generic/2019/07/04/kernel-entry.html
* FS/GS Segments - https://www.kernel.org/doc/html/latest/x86/x86_64/fsgs.html
* FS/GS BASE - https://lwn.net/Articles/821723/
* SEH in x86 - https://learn.microsoft.com/en-us/previous-versions/ms253960(v=vs.90)

#### Techniques:
* VMM Detection - https://www.usenix.org/legacy/events/hotos07/tech/full_papers/garfinkel/garfinkel_html/index.html
* VMware Backdoor I/O Port - https://sites.google.com/site/chitchatvmback/backdoor
* Detect VMM with register instruction - https://web.archive.org/web/20041130172213/http://www.invisiblethings.org/papers/redpill.html
* Mitigating Meltdown on Windows - https://msrc.microsoft.com/blog/2018/03/kva-shadow-mitigating-meltdown-on-windows/
* Shadow Walker - http://phrack.org/issues/63/8.html

#### Ring-3 Vulnerabilities:
* PV Privilege Escalation - https://lists.xen.org/archives/html/xen-announce/2012-06/msg00001.html
* Privilege Escalation when returning from kernel - https://www.freebsd.org/security/advisories/FreeBSD-SA-12:04.sysret.asc
* Vulnerabilities in Windows kernel - https://learn.microsoft.com/en-us/security-updates/SecurityBulletins/2012/ms12-042?redirectedfrom=MSDN

#### CVE:
* https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-0217
* https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-19965

#### Tools:
* ScoopyNG (VMWare detection tool) - https://www.trapkit.de/tools/scoopyng/
* Swishdbgext - https://gitlab.com/opensecuritytraining/swishdbgext
