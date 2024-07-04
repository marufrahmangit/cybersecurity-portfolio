# Scenario
In this challenge, you will familiarize yourself with Unix auth.log and wtmp logs. We’ll explore a scenario where a Confluence server was brute-forced via its SSH service. After gaining access to the server, the attacker performed additional activities, which we can track using auth.log. Although auth.log is primarily used for brute-force analysis, we will delve into the full potential of this artifact in our investigation, including aspects of privilege escalation, persistence, and even some visibility into command execution.

# Success Metric
To solve this challenge, I’ll need to answer the following 8 questions:
1. Analyzing the auth.log, can you identify the IP address used by the attacker to carry out a brute force attack?
2. The brute force attempts were successful, and the attacker gained access to an account on the server. What is the username of this account?
3. Can you identify the timestamp when the attacker manually logged in to the server to carry out their objectives?
4. SSH login sessions are tracked and assigned a session number upon login. What is the session number assigned to the attacker’s session for the user account from Question 2?
5. The attacker added a new user as part of their persistence strategy on the server and gave this new user account higher privileges. What is the name of this account?
6. What is the MITRE ATT&CK sub-technique ID used for persistence?
7. How long did the attacker’s first SSH session last based on the previously confirmed authentication time and session ending within the auth.log? (seconds)
8. The attacker logged into their backdoor account and utilized their higher privileges to download a script. What is the full command executed using sudo?



