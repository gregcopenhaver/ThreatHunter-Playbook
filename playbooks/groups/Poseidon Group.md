# Poseidon Group
## Description
[[Group/G0033|Poseidon Group]] is a Portuguese-speaking threat group that has been active since at least 2005. The group has a history of using information exfiltrated from victims to blackmail victim companies into contracting the [[Group/G0033|Poseidon Group]] as a security firm.[[CiteRef::Kaspersky Poseidon Group]]
## Attribution
| Tactic | Technique | Tool | Description |
|--------|---------|-------|---------|
| Discovery |         System Network Connections Discovery  |  | [[Group/G0033 Poseidon Group]] obtains and saves information about victim network interfaces and addresses.[[CiteRef::Kaspersky Poseidon Group]] |                                           
| Discovery |         System Service Discovery              |  | After compromising a victim, [[Group/G0033 Poseidon Group]] discovers all running services.[[CiteRef::Kaspersky Poseidon Group]] |                                                           
| Credential Access | Credential Dumping                    |  | [[Group/G0033 Poseidon Group]] conducts credential dumping on victims, with a focus on obtaining credentials belonging to domain and database servers.[[CiteRef::Kaspersky Poseidon Group]] |
| Defense Evasion |   Masquerading                          |  | [[Group/G0033 Poseidon Group]] tools attempt to spoof anti-virus processes as a means of self-defense.[[CiteRef::Kaspersky Poseidon Group]] |                                                
| Execution |         PowerShell                            |  | The [[Group/G0033 Poseidon Group]]'s Information Gathering Tool (IGT) includes PowerShell components.[[CiteRef::Kaspersky Poseidon Group]] |                                                 
| Discovery |         Process Discovery                     |  | After compromising a victim, [[Group/G0033 Poseidon Group]] lists all running processes.[[CiteRef::Kaspersky Poseidon Group]] |                                                              
| Discovery |         Account Discovery                     |  | [[Group/G0033 Poseidon Group]] searches for administrator accounts on both the local victim machine and the network.[[CiteRef::Kaspersky Poseidon Group]] |                                  



