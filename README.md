# Reverse Engineering Resources ⚡
- [Assembly](#assembly)
  * [Linux specific](#linux-specific)
  * [Windows specific](#windows-specific)
  * [Miscellaneous](#miscellaneous)
- [Operating System Internals](#operating-system-internals)
- [Assembly Projects](#assembly-projects)
- [Getting started](#getting-started)
- [Getting your hands dirty](#getting-your-hands-dirty)
- [Deobfuscation](#deobfuscation)
- [Anti-debug and Anti-analysis](#anti-debug-and-anti-analysis)
- [Anti-analysis](#anti-analysis)
- [C++ Reversing](#c-reversing)
- [Great blogs on Windows Internals](#great-blogs-on-windows-internals)
- [Others](#others)
- [Symbolic Execution](#symbolic-execution)

## Assembly

### Linux specific

- [https://asmtutor.com](https://asmtutor.com/)
- [https://www.plantation-productions.com/Webster/www.artofasm.com/Linux/index.html](https://www.plantation-productions.com/Webster/www.artofasm.com/Linux/index.html)

### Windows specific

- [https://www.plantation-productions.com/Webster/www.artofasm.com/Windows/index.html](https://www.plantation-productions.com/Webster/www.artofasm.com/Windows/index.html)
- [https://sonictk.github.io/asm_tutorial/](https://sonictk.github.io/asm_tutorial/)

### Miscellaneous
- [https://www.felixcloutier.com/x86/index.html](https://www.felixcloutier.com/x86/index.html)
- [https://cs.lmu.edu/~ray/notes/x86assembly/](https://cs.lmu.edu/~ray/notes/x86assembly/)
- [https://godbolt.org](https://godbolt.org/)
- [https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Arch1001_x86-64_Asm+2021_v1/about](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Arch1001_x86-64_Asm+2021_v1/about)

## Assembly Projects

After learning assembly, you can try some projects like making a bootloader or a whole simple Operating System.
I have wrote a blog on this topic, [here](https://de-engineer.github.io/Understanding-booting-process-and-writing-own-os/).
- [http://brokenthorn.com/Resources/OSDev1.html](http://brokenthorn.com/Resources/OSDev1.html)
- [https://raw.githubusercontent.com/tuhdo/os01/master/Operating_Systems_From_0_to_1.pdf](ttps://raw.githubusercontent.com/tuhdo/os01/master/Operating_Systems_From_0_to_1.pdf)
- [https://cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf](https://cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)


## Operating System Internals
- [https://www.youtube.com/playlist?list=PLmbPuZ0NsyGS8ef6zaHd2qYylzsHxL63x](https://www.youtube.com/playlist?list=PLmbPuZ0NsyGS8ef6zaHd2qYylzsHxL63x)
- [https://www.youtube.com/playlist?list=PLgre7dUq8DGKbtnlMuJPvPYlvLdXOC9uh](https://www.youtube.com/playlist?list=PLgre7dUq8DGKbtnlMuJPvPYlvLdXOC9uh)
- [https://pages.cs.wisc.edu/~remzi/OSTEP/](https://pages.cs.wisc.edu/~remzi/OSTEP/)

## Getting started
- [Roadmap for RE](https://wiki.bi0s.in/reversing/roadmap)
- [COMPSCI 390R - Reverse Engineering & Vulnerability Analysis](https://pwn.umasscybersec.org/lectures/index.html)
- [https://www.begin.re](https://www.begin.re/)
- [https://artik.blue/reversing](https://artik.blue/reversing)
- [https://legend.octopuslabs.io/sample-page.html](https://legend.octopuslabs.io/sample-page.html)
- [https://www.youtube.com/watch?v=mDyQBM-_T1g](https://www.youtube.com/watch?v=mDyQBM-_T1g)
- [https://www.youtube.com/watch?v=gPsYkV7-yJk](https://www.youtube.com/watch?v=gPsYkV7-yJk)
- [https://www.youtube.com/watch?v=d4Pgi5XML8E](https://www.youtube.com/watch?v=d4Pgi5XML8E)
- [https://www.youtube.com/watch?v=9vKG8-TnawY](https://www.youtube.com/watch?v=9vKG8-TnawY) (Recommended)

## Getting your hands dirty

- [https://crackmes.one](https://crackmes.one/)
- [http://reversing.kr/challenge.php](http://reversing.kr/challenge.php)
- [https://github.com/Maijin/radare2-workshop-2015/tree/master/IOLI-crackme](https://github.com/Maijin/radare2-workshop-2015/tree/master/IOLI-crackme)
- [http://reversing.kr/challenge.php](http://reversing.kr/challenge.php)
- [https://0x00sec.org/t/challenge-collection-reverse-engineering-and-crackme/3027](https://0x00sec.org/t/challenge-collection-reverse-engineering-and-crackme/3027)
- [Youtube playlist on Malware Analysis](https://www.youtube.com/watch?v=n06QSoICU6c&list=PLt9cUwGw6CYG2DSfjXEE3GotkQDa5b-6s)
- [Binary Analysis Free Course](https://maxkersten.nl/binary-analysis-course/)

## Deobfuscation

- [https://www.vadesecure.com/en/blog/malware-analysis-understanding-code-obfuscation-techniques](https://www.vadesecure.com/en/blog/malware-analysis-understanding-code-obfuscation-techniques)
- [https://www.youtube.com/watch?v=bEsQ8UYioU4](https://www.youtube.com/watch?v=bEsQ8UYioU4)
- [https://0x00sec.org/t/packers-executable-compression-and-data-obfuscation/847](https://0x00sec.org/t/packers-executable-compression-and-data-obfuscation/847)
- [https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf](https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf)
- [https://www.varonis.com/blog/x64dbg-unpack-malware](https://www.varonis.com/blog/x64dbg-unpack-malware)
- [https://apr4h.github.io/2021-05-01-Manually-Unpacking-Remcos-Malware/](https://apr4h.github.io/2021-05-01-Manually-Unpacking-Remcos-Malware/)
- [https://www.youtube.com/watch?v=EdchPEHnohw](https://www.youtube.com/watch?v=EdchPEHnohw)
- [https://www.youtube.com/playlist?list=PLynb9SXC4yER8NinXJwV4GHUM9-jaIsN_](https://www.youtube.com/playlist?list=PLynb9SXC4yER8NinXJwV4GHUM9-jaIsN_)

## Anti-debug and Anti-analysis

- [https://iopscience.iop.org/article/10.1088/1742-6596/1744/4/042186/pdf](https://iopscience.iop.org/article/10.1088/1742-6596/1744/4/042186/pdf)
- [https://wikileaks.org/vault7/document/2015-07-PoC-Anti_Debugging_and_Anti_Emulation/2015-07-PoC-Anti_Debugging_and_Anti_Emulation.pdf](https://wikileaks.org/vault7/document/2015-07-PoC-Anti_Debugging_and_Anti_Emulation/2015-07-PoC-Anti_Debugging_and_Anti_Emulation.pdf)
- [https://anti-reversing.com/Downloads/Anti-Reversing/The_Ultimate_Anti-Reversing_Reference.pdf](https://anti-reversing.com/Downloads/Anti-Reversing/The_Ultimate_Anti-Reversing_Reference.pdf)
- [https://anti-debug.checkpoint.com/](https://anti-debug.checkpoint.com/)
- [https://www.youtube.com/watch?v=WlE8abc8V-4&feature=emb_title](https://www.youtube.com/watch?v=WlE8abc8V-4&feature=emb_title)

## Anti-analysis

- [https://www.malwarebytes.com/blog/news/2014/09/five-anti-debugging-tricks-that-sometimes-fool-analysts](https://www.malwarebytes.com/blog/news/2014/09/five-anti-debugging-tricks-that-sometimes-fool-analysts)
- [https://www.oic-cert.org/en/download/Anti-Analysis techniques (OIC Talk).pdf](https://www.oic-cert.org/en/download/Anti-Analysis%20techniques%20(OIC%20Talk).pdf)
- [https://www.cynet.com/attack-techniques-hands-on/malware-anti-vm-techniques/](https://www.cynet.com/attack-techniques-hands-on/malware-anti-vm-techniques/)
- [https://www.youtube.com/watch?v=5NO-W3SVjak&feature=emb_title](https://www.youtube.com/watch?v=5NO-W3SVjak&feature=emb_title)

## C++ Reversing
- [Reversing C++ Virtual Functions](https://alschwalm.com/blog/static/2016/12/17/reversing-c-virtual-functions/)
- [Reversing C++](https://www.blackhat.com/presentations/bh-dc-07/Sabanal_Yason/Paper/bh-dc-07-Sabanal_Yason-WP.pdf)

## Windows Research

If you want to get into Windows Research, then you need to learn Windows Internals.

- [My blog on Windows Internals](https://de-engineer.github.io)
- [Book on Windows Internals published by MS. Use it like a reference to learn about specific topics when needed](https://learn.microsoft.com/en-us/sysinternals/resources/windows-internals)
- [Has the best video courses](https://www.pluralsight.com/authors/pavel-yosifovich)
- [Windows Process Internals](https://www.youtube.com/watch?v=4AkzIbmI3q4&feature=emb_title)
- [Windows Internals Overview](https://samsclass.info/140/lec/Excerpted-PRE07_Solomon.pdf)
- [Intro to Windows Internals](https://vimeo.com/49347561)
- [Win32 programming with code examples](https://installsetupconfig.com/win32programming)
- [Notes for Windows API programming](https://caiorss.github.io/C-Cpp-Notes/WindowsAPI-cpp.html)
- [Windows undocumented functions documentation](http://undoc.airesoft.co.uk)
- [Windows undocumented stuff's documentation](https://geoffchappell.com/index.htm)
- [Windows Internals Book 7th edition Tools](https://github.com/zodiacon/windowsinternals)
- [Full source code of ReactOS (open-source reimplementation of Windows)](https://doxygen.reactos.org/index.html)
- [Explanation of key data structures used by device drivers, kernel, and HAL](https://codemachine.com/articles/kernel_structures.html)
- [Take a look at more than 6000 Windows Undocumented structures](https://www.vergiliusproject.com/)
- [Resources For Advanced Windows Development](https://pastebin.com/NXxrYHp8)
- [Understanding the EPROCESS data structure](https://info-savvy.com/understanding-eprocess-structure/)
- [The NT Handle Table](https://www.cs.miami.edu/home/burt/journal/NT/handle_table.html)
- [Anatomy of the thread suspension mechanism in Windows.](https://ntopcode.wordpress.com/2018/01/16/anatomy-of-the-thread-suspension-mechanism-in-windows-windows-internals/)
- [Automatically generated diff of Windows structures](http://terminus.rewolf.pl/terminus/)
- [Thread Scheduling Windows](https://www.i.u-tokyo.ac.jp/edu/training/ss/lecture/new-documents/Lectures/03-ThreadScheduling/ThreadScheduling.pdf) 
- [Kernel Callback Functions](https://codemachine.com/articles/kernel_callback_functions.html)
- [Decompilation of NT API functions](http://likeagod.revers.engineering)

## Great blogs on Windows Internals

- [https://secret.club](https://secret.club/)
- [wumb0.in](https://t.co/TQttGxnkVF)
- [voidsec.com](https://t.co/Rz220SAwbt)
- [https://poppopret.blogspot.com/?m=1](https://poppopret.blogspot.com/?m=1)
- [https://www.ragestorm.net/blogs/?cat=13](https://www.ragestorm.net/blogs/?cat=13)
- [https://www.x86matthew.com](https://www.x86matthew.com/)
- [https://www.tiraniddo.dev](https://www.tiraniddo.dev/)
- [https://googleprojectzero.blogspot.com](https://googleprojectzero.blogspot.com/)

## Others

- [Compiler Optimizations for Reverse Engineers.](https://www.msreverseengineering.com/blog/2014/6/23/compiler-optimizations-for-reverse-engineers)
- [Reversing Stories: Updating the Undocumented ESTROBJ and STROBJ Structures for Windows 10 x64.](https://versprite.com/blog/security-research/reverse-engineering-undocumented-structures/)
- [Methodology for Static Reverse Engineering of Windows Kernel Drivers.](https://posts.specterops.io/methodology-for-static-reverse-engineering-of-windows-kernel-drivers-3115b2efed83)
- [What I Have Learned from Reverse Engineering Windows Containers.](https://unit42.paloaltonetworks.com/what-i-learned-from-reverse-engineering-windows-containers/)
- [A Syscall Journey in the Windows Kernel.](https://alice.climent-pommeret.red/posts/a-syscall-journey-in-the-windows-kernel/)

## Symbolic Execution
- [Video lectures on Symbolic Execution](https://pwn.umasscybersec.org/lectures/index.html)
- [Youtube video covering the basics of z3](https://www.youtube.com/watch?v=kZd1Hi0ZBYc)
- [Learn z3](https://github.com/ViRb3/z3-python-ctf)
- [Course on Symbolic Analysis](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+RE3201_symexec+2021_V1/course)
- https://sat-smt.codes/SAT_SMT_by_example.pdf
