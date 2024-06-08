# Categories of Cyber Attacks

## Active Attacks

Active attacks: An active attack is a network exploit in which a hacker attempts to make changes to data on the target or data en route to the target.

### Types of Active Attacks

**Masquerade**  
In this attack, the intruder pretends to be a particular user of a system to gain access or to gain greater privileges than they are authorized for. A masquerade may be attempted through the use of stolen login IDs and passwords, by finding security gaps in programs, or by bypassing the authentication mechanism.

**Session Replay**  
In this type of attack, a hacker steals an authorized user’s login information by stealing the session ID. The intruder gains access and the ability to do anything the authorized user can do on the website.

**Message Modification**  
In this attack, an intruder alters packet header addresses to direct a message to a different destination or modify the data on a target machine.

**Denial of Service (DoS)**  
In a DoS attack, users are deprived of access to a network or web resource. This is generally accomplished by overwhelming the target with more traffic than it can handle.

**Distributed Denial-of-Service (DDoS)**  
In a DDoS exploit, large numbers of compromised systems (sometimes called a botnet or zombie army) attack a single target.

## Passive Attacks

Passive attacks are relatively scarce from a classification perspective but can be carried out with relative ease, particularly if the traffic is not encrypted.

### Types of Passive Attacks

**Eavesdropping (Tapping)**  
The attacker simply listens to messages exchanged by two entities. For the attack to be useful, the traffic must not be encrypted. Any unencrypted information, such as a password sent in response to an HTTP request, may be retrieved by the attacker.

**Traffic Analysis**  
The attacker looks at the metadata transmitted in traffic to deduce information relating to the exchange and the participating entities, e.g., the form of the exchanged traffic (rate, duration, etc.). In cases where encrypted data are used, traffic analysis can also lead to attacks by cryptanalysis, whereby the attacker may obtain information or succeed in unencrypting the traffic.

#### Software Attacks

Malicious code (sometimes called malware) is a type of software designed to take over or damage a computer user's operating system without the user's knowledge or approval. It can be very difficult to remove and very damaging. Common malware examples are listed below:

| **Type**         | **Description**                                                                                                                                                                                                                             | **Characteristics**                                                                                                                                                                                               | **Examples**                    |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------|
| **Virus**        | A virus is a program that attempts to damage a computer system and replicate itself to other computer systems.                                                                                                                              | - Requires a host to replicate and usually attaches itself to a host file or a hard drive sector.<br> - Replicates each time the host is used.<br> - Often focuses on the destruction or corruption of data.<br> - Usually attaches to files with execution capabilities such as .doc, .exe, and .bat extensions.<br> - Often distributes via e-mail.<br> - Many viruses can e-mail themselves to everyone in your address book. | Stoned, Michelangelo, Melissa, I Love You |
| **Worm**         | A worm is a self-replicating program that can be designed to do any number of things, such as delete files or send documents via e-mail. A worm can negatively impact network traffic just in the process of replicating itself.              | - Can install a backdoor in the infected computer.<br> - Is usually introduced into the system through a vulnerability.<br> - Infects one system and spreads to other systems on the network.                                                      | Code Red                         |
| **Trojan Horse** | A Trojan horse is a malicious program that is disguised as legitimate software. Discretionary environments are often more vulnerable and susceptible to Trojan horse attacks because security is user-focused and user-directed.               | - Cannot replicate itself.<br> - Often contains spying functions (such as a packet sniffer) or backdoor functions that allow a computer to be remotely controlled from the network.<br> - Often is hidden in useful software such as screen savers or games. | Back Orifice, NetBus, Whack-a-Mole |
| **Logic Bomb**   | A Logic Bomb is malware that lies dormant until triggered. A logic bomb is a specific example of an asynchronous attack.                                                                                                                      | - A trigger activity may be a specific date and time, the launching of a specific program, or the processing of a specific type of activity.<br> - Logic bombs do not self-replicate.                             | N/A                             |

#### Hardware Attacks

Common hardware attacks include:
- Manufacturing backdoors for malware or other penetrative purposes; backdoors aren’t limited to software and hardware, but they also affect embedded radio-frequency identification (RFID) chips and memory.
- Eavesdropping by gaining access to protected memory without opening other hardware.
- Inducing faults, causing the interruption of normal behavior.
- Hardware modification tampering with invasive operations.
- Backdoor creation; the presence of hidden methods for bypassing normal computer authentication systems.
- Counterfeiting product assets that can produce extraordinary operations and those made to gain malicious access to systems.