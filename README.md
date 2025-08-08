# ElevateLabs_Task4

📄 Setup and Use a Firewall on Windows/Linux

🔧 Objective:
To configure and test basic firewall rules on both Windows and Linux operating systems.

How Firewalls Filter Traffic
1. Matching criteria: Protocol, IP address, port, and connection state.

2. Stateful firewalls track connection states and allow return traffic for established connections.

3. Actions:

   ALLOW: Permit the packet.

   DENY/REJECT: Block with an error response.

   DROP: Silently discard.

4. Best practice: Use a default-deny policy and only allow necessary ports/services.

5. Windows Firewall uses profiles (Domain, Private, Public) to apply rules.

6. Linux UFW is a simplified interface to iptables that manages inbound/outbound rules.

📝 Explanation:
Windows Firewall uses inbound and outbound rules to manage traffic. We blocked port 23 to prevent Telnet access and verified the block using PowerShell.

📸 Screenshots Attached:
Telnet Connection Attempt
Windows Defender Firewall Inbound Rule
PowerShell Telnet Test Result
UFW Rules in Terminal

✅ Conclusion:
Both Linux (UFW) and Windows Defender Firewall allow administrators to control traffic using rule-based systems. Blocking unnecessary ports like Telnet enhances system security.

