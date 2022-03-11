Adversaries may modify authentication mechanisms and processes to access user credentials or enable otherwise unwarranted access to accounts. The authentication process is handled by mechanisms, such as the Local Security Authentication Server (LSASS) process and the Security Accounts Manager (SAM) on Windows, pluggable authentication modules (PAM) on Unix-based systems, and authorization plugins on MacOS systems, responsible for gathering, storing, and validating credentials. By modifying an authentication process, an adversary may be able to authenticate to a service or system without using Valid Accounts.

[[T1556.001 - Domain Controller Authentication]]
[[T1556.002 - Password Filter DLL]]
[[T1556.003 - Pluggable Authentication Modules]]
[[T1556.004 - Network Device Authentication]]