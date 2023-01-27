"Living off the land binaries" (LOLBins) are legitimate system or software utilities that can be used in a malicious way by attackers. These utilities are often already present on a system and are not typically flagged by security software as malicious, making them a useful tool for attackers to evade detection.

Examples of LOLBins include:

powershell.exe: This is a command-line shell and scripting language that is often used for automation and system administration tasks. Attackers can use it to run malicious scripts or commands on a system.

certutil.exe: This is a utility that is used to manage digital certificates and can be used to encode and decode files. Attackers can use it to exfiltrate data from a system.

net.exe: This is a command-line utility that can be used to manage network resources. Attackers can use it to enumerate network information and move laterally within a network.

rundll32.exe: This is a utility that can be used to execute functions exported from a dynamic-link library (DLL) file. Attackers can use it to run malicious code on a system.

It's important to note that these utilities are not inherently malicious, they can be used in a malicious way if they are misused or abused. To protect against LOLBins, it is important to monitor and control the use of these utilities, and to have a strong security posture in place, including endpoint protection and network monitoring.


Inbound connections should be blocked to improve security on a system or network.

                When a system or network allows inbound connections, it means that external entities can initiate a connection with the system or network. This can                     leave the system or network vulnerable to attack, as malicious actors can use this ability to connect to a system or network as a means of gaining                     access and compromising it.

                By blocking inbound connections, a system or network is effectively closed off to external entities, making it much more difficult for malicious actors                 to gain access. This can greatly reduce the risk of a successful attack, and help to protect sensitive data and other assets.

                It's worth noting that, while blocking all inbound connections can greatly improve security, it also limits the functionality of the system or network.                 Therefore, it's important to strike a balance between security and functionality by only allowing necessary inbound connections and closely monitoring                 any inbound connections that are allowed.


