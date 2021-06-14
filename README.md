# Prior knowledge for OSED | EXP-301 (Guide)

This is a repository of notes and material that I consider necessary in advance to opt for the course and the OSED certification (Windows User Mode Exploit Development)

This guide was born as a result of my interest in obtaining previous knowledge before eventuring the preparation course for the certification exam OSED.

             ########    #####   ########    #####   ##     ##  
             ##     ##  ##   ##  ##     ##  ##   ##   ##   ##   
             ##     ## ##     ## ##     ## ##     ##   ## ##      
             ########  ##     ## ########  ##     ##    ###        
             ##   ##   ##     ## ##   ##   ##     ##   ## ##      
             ##    ##   ##   ##  ##    ##   ##   ##   ##   ##     
             ##     ##   #####   ##     ##   #####   ##     ## 
                                
## Contents

* [Programming languages](#Programming-languages)
* [Operating System](#Operating-System)
* [Intro Reverse Engineering](#Reverse-Engineering)
* [WinDbg and x86 Architecture](#WinDbg-and-x86-Architecture)
* [Exploiting Stack Overflows](#Exploiting-Stack-Overflows)
* [Exploiting SEH Overflows](#Exploiting-SEH-Overflows)
* [Introduction to IDA Pro](#Introduction-to-IDA-Pro)
* [Overcoming Space Restrictions: Egghunters](#Egghunters)
* [Shellcode from scratch](#Shellcode)
* [Stack Overflows and DEP Bypass](#DEP-Bypass)
* [Stack Overflows and ASLR Bypass](#ASLR-Bypass)
* [Overwriting EIP with Format Strings](#Overwriting-EIP)
* [ROP chains and Rop playloads decoders](#ROP-chains-and-Rop-playloads-decoders)

## Programming languages

For this certification it is very important to have a knowledge base in the following programming languages:

Python 3: https://youtube.com/playlist?list=PLBf0hzazHTGM_dncTqO9l-0zUQYP0nNPU

Bash: https://www.youtube.com/watch?v=smbeKPDVs2I

Assembly Language: 

https://youtu.be/HgEGAaYdABA

https://sensepost.com/blogstatic/2014/01/SensePost_crash_course_in_x86_assembly-.pdf

http://www.securitytube.net/groups?operation=view&groupId=6

C: https://youtu.be/KJgsSFOSQv0


## Operating System

Win register: https://docs.microsoft.com/en-us/troubleshoot/windows-server/performance/windows-registry-advanced-users


## Reverse Engineering

Introduction To Reverse Engineering | Beginners: 

https://youtube.com/playlist?list=PLMB3ddm5Yvh3gf_iev78YP5EPzkA3nPdL

Training By Ricardo Narvaja: 

http://ricardonarvaja.info/WEB/EXPLOITING%20Y%20REVERSING%20USANDO%20HERRAMIENTAS%20FREE/INGLES/


## WinDbg and x86 Architecture

x86 Architecture: https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/x86-architecture

Intermediate Intel x86: https://opensecuritytraining.info/IntermediateX86.html

## Exploiting Stack Overflows

Understanding & Exploiting: https://sghosh2402.medium.com/understanding-exploiting-stack-based-buffer-overflows-acf9b8659cba

Intro Exploiting 1: https://www.fuzzysecurity.com/tutorials/expDev/1.html

Intro Exploiting 2: https://www.fuzzysecurity.com/tutorials/expDev/2.html

Intro Exploiting 3: http://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/

Intro Exploiting 3: https://www.corelan.be/index.php/2009/07/23/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-2/

## Exploiting SEH Overflows

https://www.fuzzysecurity.com/tutorials/expDev/3.html

https://www.corelan.be/index.php/2009/07/28/seh-based-exploit-writing-tutorial-continued-just-another-example-part-3b/

https://www.securitysift.com/windows-exploit-development-part-6-seh-exploits/

http://www.corelan.be/index.php/2009/07/25/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-3-seh/


## Introduction to IDA Pro

https://resources.infosecinstitute.com/topic/basics-of-ida-pro-2/

## Egghunters

http://www.fuzzysecurity.com/tutorials/expDev/4.html

https://www.securitysift.com/windows-exploit-development-part-5-locating-shellcode-egghunting/


## Shellcode

http://www.hick.org/code/skape/papers/win32-shellcode.pdf

https://www.securitysift.com/windows-exploit-development-part-4-locating-shellcode-jumps/

http://www.corelan.be/index.php/2010/02/25/exploit-writing-tutorial-part-9-introduction-to-win32-shellcoding/

http://www.fuzzysecurity.com/tutorials/expDev/6.html

http://sh3llc0d3r.com/windows-reverse-shell-shellcode-i/


## DEP Bypass  

https://medium.com/cybersecurityservices/dep-bypass-using-rop-chains-garima-chopra-e8b3361e50ce

https://cwinfosec.org/Intro-ROP-DEP-Bypass/


## ASLR Bypass

http://www.corelan.be/index.php/2009/09/21/exploit-writing-tutorial-part-6-bypassing-stack-cookies-safeseh-hw-dep-and-aslr/

https://www.exploit-db.com/docs/english/17914-bypassing-aslrdep.pdf

https://www.ccn-cert.cni.es/pdf/documentos-publicos/xi-jornadas-stic-ccn-cert/2575-m11-06-rockandropeando/file.html

## Overwriting EIP

https://captmeelo.com/exploitdev/osceprep/2018/06/27/vulnserver-trun.html

https://h0mbre.github.io/Boofuzz_to_EIP_Overwrite/#

https://www.youtube.com/watch?v=IOjl3tU1Ht8


## ROP chains and Rop playloads decoders

https://scholars.unh.edu/cgi/viewcontent.cgi?article=2376&context=thesis

https://www.crowdstrike.com/blog/analysis-cve-2013-3906-exploit/




