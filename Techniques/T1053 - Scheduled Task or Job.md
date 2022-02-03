# Scheduled Task/Job

Adversaries may abuse task scheduling functionality to facilitate initial or recurring execution of malicious code. Utilities exist within all major operating systems to schedule programs or scripts to be executed at a specified date and time. A task can also be scheduled on a remote system, provided the proper authentication is met (ex: RPC and file and printer sharing in Windows environments). Scheduling a task on a remote system typically requires being a member of an admin or otherwise privileged group on the remote system.

[[T1053.001 - At (Linux)]]
[[T1053.002 - At (Windows)]]
[[T1053.003 - Cron]]
[[T1053.004 - Launchd]]
[[T1053.005 - Scheduled Task]]
[[T1053.006 - Systemd Timers]]
[[T1053.007 - Container Orchestration Job]]