Adversaries may modify access tokens to operate under a different user or system security context to perform actions and bypass access controls. Windows uses access tokens to determine the ownership of a running process. A user can manipulate access tokens to make a running process appear as though it is the child of a different process or belongs to someone other than the user that started the process. When this occurs, the process also takes on the security context associated with the new token.

[[T1134.001 - Token Impersonation or Theft]]
[[T1134.002 - Create Process with Token]]
[[T1134.003 - Make and Impersonate Token]]
[[T1134.004 - Parent PID Spoofing]]
[[T1134.005 - SID-History Injection]]