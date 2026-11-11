Windows logs

Security event id’s
    4624 : Successful login attempts
    4625 : Unsuccessful login attempts
    4634 : Account was logged off
    4647 : User initiated log off
    4648 : User used explicit credentials for login (Run as)
    4672 : Special privileges given to a logon (Admin Login)
    4776 : Domain controller attempted to validate credentials of account
    4768 : Kerberos requested TGT ticket
    4769 : Kerberos requested Service ticket
    4771 : Kerberos pre-authentication failed
    4720 : New user account was created
    4722 : New user account was enabled
    4688 : New process was created
    4698 : New scheduled task was created
    4798 : User’s local group membership was enumerated
    4799 : Security-enabled local group membership was enumerated
    5145 : Network share object was accessed to check if required access can be given
    5140 : Network share object was accessed
    1102 : Audit log cleared

System event id’s
    104 : System, Security, and Application log file cleared

Powershell event id’s
    4104 : Command line auditing for PowerShell

Windows Defender event id’s
    1116 : Malware detected in system
    1117 : Protection action taken on malware

Scheduled Task event id’s
    100 : Scheduled task started
    106 : New scheduled task created

Sysmon Event ID’s
    1 : Process creation
    3 : Network connection
    7 : Image loaded — DLL loaded in process
    11 : File created in system
    12, 13, 14 : Registry events
    15 : Look for files in ADS (Alternate Data Streams)
    22 : DNS query

Linux logs
    /var/log/auth.log : Authentication logs (failed & successful logins)
    /var/log/syslog : System logs
    /var/log/messages : Errors & messages in system
    /var/log/kern.log : Kernel logs
    /var/log/cron.log : Cron jobs (scheduled tasks)
    bash history : Shows commands executed previously in system
