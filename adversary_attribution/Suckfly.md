# Suckfly
## Description
[[Group/G0039|Suckfly]] is a China-based threat group that has been active since at least 2014.Symantec Suckfly March 2016
## Attribution
| Tactic | Technique | Tool | Description |
|--------|---------|-------|---------|
| Discovery |                                        Network Service Scanning         |  |                            [[Suckfly]] the victim's internal network for hosts with ports 8080, 5900, and 40 open.Symantec Suckfly May 2016 |                                                                                
| Credential Access |                                Credential Dumping               |  |                            [[Suckfly]] used a signed credential-dumping tool to obtain victim account credentials.Symantec Suckfly May 2016 |                                                                                
| Execution |                                        Command-Line Interface           |  |                            Several tools used by [[Suckfly]] have been command-line driven.Symantec Suckfly May 2016 |                                                                                                       
| Defense Evasion |                                  Code Signing                     |  |                            [[Suckfly]] has used stolen certificates to sign its malware.Symantec Suckfly March 2016 |                                                                                                        
| Command and Control |                              Commonly Used Port               |   Nidiran, Backdoor.Nidiran | [[Nidiran]] communicates with its C2 domain over ports 443 and 8443.Symantec Suckfly May 2016 |                                                                                                   
| Persistence Privilege Escalation |                 New Service                      |   Nidiran, Backdoor.Nidiran | [[Nidiran]] can create a new service named msamger (Microsoft Security Accounts Manager).Symantec Backdoor.Nidiran |                                                                              
| Defense Evasion Persistence Privilege Escalation | Valid Accounts                   |  |                            [[Suckfly]] used legitimate account credentials that they dumped to navigate the internal victim network as though they were the legitimate account owner.Symantec Suckfly May 2016 |             
| Command and Control Lateral Movement |             Remote File Copy                 |   Nidiran, Backdoor.Nidiran | [[Nidiran]] can download and execute files.Symantec Backdoor.Nidiran |                                                                                                                            
| Defense Evasion |                                  Masquerading                     |   Nidiran, Backdoor.Nidiran | [[Nidiran]] can create a new service named msamger (Microsoft Security Accounts Manager), which mimics the legitimate Microsoft database by the same name.Symantec Backdoor.NidiranMicrosoft SAM |
| Command and Control |                              Standard Cryptographic Protocol  |   Nidiran, Backdoor.Nidiran | [[Nidiran]] uses RC4 to encrypt C2 traffic.Symantec Suckfly May 2016 |                                                                                                                            



