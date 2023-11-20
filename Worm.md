# Worm
- - -
**computer worm**

  A computer worm is a standalone malware computer program that replicates itself in order to spread to other computers.
  1. It often uses a computer network to spread itself, 
  relying on security failures on the target computer to access it. It will use this machine as a host to scan and infect other computers. When these new worm-invaded computers are controlled, 
  the worm will continue to scan and infect other computers using these computers as hosts, and this behaviour will continue.
  2. Computer worms use recursive methods to copy themselves without host programs and distribute themselves based on exploiting the advantages of exponential growth, thus controlling and infecting more and more computers in a short time.
  3. Worms almost always cause at least some harm to the network, even if only by consuming bandwidth, whereas viruses almost always corrupt or modify files on a targeted computer. 

Many worms are designed only to spread, and do not attempt to change the systems they pass through. However, as the Morris worm and Mydoom showed, even these "payload-free" worms can cause major disruption by increasing network traffic and other unintended effects.

**Countermeasures**

Worms spread by exploiting vulnerabilities in operating systems. Vendors with security problems supply regular security updates (see "Patch Tuesday"), and if these are installed to a machine, then the majority of worms are unable to spread to it. If a vulnerability is disclosed before the security patch released by the vendor, a zero-day attack is possible.

Users need to be wary of opening unexpected email, and should not run attached files or programs, or visit web sites that are linked to such emails. However, as with the ILOVEYOU worm, and with the increased growth and efficiency of phishing attacks, it remains possible to trick the end-user into running malicious code.

Anti-virus and anti-spyware software are helpful, but must be kept up-to-date with new pattern files at least every few days. The use of a firewall is also recommended.

Users can minimize the threat posed by worms by keeping their computers' operating system and other software up to date, avoiding opening unrecognized or unexpected emails and running firewall and antivirus software.

Mitigation techniques include:

 + ACLs in routers and switches
 + Packet-filters
 + TCP Wrapper/ACL enabled network service daemons
 + EPP/EDR software
 + Nullroute

Infections can sometimes be detected by their behavior - typically scanning the Internet randomly, looking for vulnerable hosts to infect. In addition, machine learning techniques can be used to detect new worms, by analyzing the behavior of the suspected computer.

> https://en.wikipedia.org/wiki/Computer_worm#cite_note-1
