# Process Injection

Adversaries may inject code into processes in order to evade process-based defenses as well as possibly elevate privileges. Process injection is a method of executing arbitrary code in the address space of a separate live process. Running code in the context of another process may allow access to the process's memory, system/network resources, and possibly elevated privileges. Execution via process injection may also evade detection from security products since the execution is masked under a legitimate process.

[[T1055.001 - Dynamic-link Library Injection]]
[[T1055.002 - Portable Executable Injection]]
[[T1055.003 - Thread Execution Hijacking]]
[[T1055.004 - Asynchronous Procedure Call]]
[[T1055.005 - Thread Local Storage]]
[[T1055.008 - Ptrace System Calls]]
[[T1055.009 - Proc Memory]]
[[T1055.011 - Extra Window Memory Injection]]
[[T1055.012 - Process Hollowing]]
[[T1055.013 - Process Doppelgänging]]
[[T1055.014 - VDSO Hijacking]]