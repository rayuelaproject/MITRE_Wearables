# <Your-Project-Title>

## <img src="images/description.jpg" alt="Logo" width="1698">
  
<div align="justify">
 
The techniques chosen for the analysis are described below. They are classified into the different security and privacy tests performed:
<br />
<br />
<ul>
  <li><strong>Authentication</strong>: if the application uses a poor authentication method, attackers can take advantage of it by using the "Exploitation for credential access" attack. In this technique credentialing and authentication mechanisms may be targeted for exploitation by adversaries as a means to gain access to useful credentials or circumvent the process to gain access to systems. The results show that cyber groups do not usually apply it to the devices we are testing.</li>
  <br />
  <li><strong>Insecure pairing method</strong>: this vulnerability can be exploited with the “Adversary-in-the-Middle” technique when the wearable and the mobile device are being paired. The matrixes show that although it is not a usual technique, there is still good visibility and detection coverage.</li>
  <br />
  <li><strong>Unencrypted Communications</strong>: if the communication between the wearable device and the smartphone is not encrypted, adversaries may use one of these techniques included in exfiltration tactics.</li>
  <ul>
    <li><i>Exfiltration over Bluetooth</i>: it takes advantage of insecure Bluetooth communication between devices. There is good visibility coverage despite not being a usual technique.</li>
    <li><i>Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol</i>: it takes advantage of other unencrypted network protocols. The results show that the selected cyber groups employ this technique and that there is a null detection coverage.</li>
  </ul>
  <br />
  <li><strong>Encryption keys sent in plain text</strong>: attackers may obtain encryption keys using the “Unsecured credentials” technique by searching compromised systems to find and obtain insecurely stored credentials. The results show that among the sub-techniques described, some of them have poor visibility and detection coverage while being often used by cyber-criminal groups.</li>
  <br />
  <li><strong>Static MAC address</strong>: if the wearable uses a static MAC address, the device is exposed to attacks like “System Network Configuration Discovery” where adversaries may look for details about the network configuration and settings, such as IP or MAC addresses. As the matrixes prove, this technique is commonly used by the selected groups, and it has poor detection.</li>
  <br />
  <li><strong>Transmission of sensitive information to third-party servers</strong>: in this case, many attacks try to obtain sensitive information in the cloud. For instance, the “Data from cloud storage object” technique is often performed by groups and there is poor detection coverage.</li>
  <br />
  <li><strong>Sending of information and firmware updates via HTTP</strong>: if this kind of information is sent via HTTP the device is exposed to “Network sniffing” attacks. This technique is not commonly used by the selected cyber-criminal groups.</li>
</ul>

<p align="right">(<a href="https://rayuelaproject.github.io/Tests/">Back Testing</a>)</p>

</div>

## <img src="images/results.jpg" alt="Logo" width="1698">
  
<div align="justify">

To sum up, there are mainly four techniques that should be considered.  "Unsecured credentials" is the most important as it has a worse visibility and detection coverage while being commonly used by cyber groups.
<br />
<br />
The other three, “Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol”, “System Network Configuration Discovery” and “Data from cloud storage object”, have the same characteristics except for visibility coverage, which is better than in the previous technique.

<p align="right">(<a href="https://rayuelaproject.github.io/Tests/">Back Testing</a>)</p>

</div>
