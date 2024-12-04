<h1>Incident handler's journal</h1>

|Date: October 6, 2024	|Entry: 1|
|-----------------------|--------|
Description	|A ransomware attack occured at a small U.S. health care clinic, which severly disrupted their business operations.<br/> NIST Incident Response Lifecycle phases for the incident:<br/>- Detection and Analysis: It was detected by reading the ransom note that was displayed on the employees' computers while they were unable to access the files and software needed to do their job. For analysis, the organization contated several organizations for technical assistance.<br/>- Containment, Eradication, and Recovery: For containment, the organization shut down their computer systems. For eradication and recovery, several organizations were contacted for assistance.|
|Tool(s) used	|None.|
|The 5 W's 	|Capture the 5 W's of an incident.<li>Who: The incident was caused by an organized group of unethical hackers.</li><li>What: The hackers left a ransom note stating that the company's files were encrypted and demanded money in exchange for the decryption key.</li><li>When: The incident occured on Tuesday at 9:00 am.</li><li>Where: It took place at a small U.S. health care clinic.</li><li>Why: This incident happened because of a phishing email that contained a malicious attachment. Once it was downloaded, ransomware was deployed encrypting the organization's computer files. The attackers' motivation appears to be financial, since they demanded a large sum of money through the ransom note in exchange for the decryption key.</li>|
|Additional notes	|Is there a way to fix the system without paying the ransom?</br>Employees should be better educated in and aware of phishing attacks to prevent such incidents in the future.|



|Date: October 12, 2024	|Entry: 2|
|-----------------------|--------|
|Description|	Investigation of a suspicious file hash; malware was downloaded on an employee's computer.<br/>NIST Incident Response Lifecycle phases for the incident:<br/>- Detection and Analysis: The suspicious file was detected by the security systems in place.<br/>Deeper analysis and investigation was performed to determine if the alert signified a real threat.|
|Tool(s) used|	VirusTotal, an investigative tool that analyzes files and URLs for malicious content such as viruses, worms, trojans, and more. VirusTotal was used to analyze a file hash, which was reported as malicious (SHA-256 file hash).|
|The 5 W's| 	Capture the 5 W's of an incident. Who: Advanced threat actor BlackTech What: An email sent to an employee contained a malicious file attachment (SHA-256 file hash of 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b. When: The incident occured at 9:30 a.m. Where: An employee's computer at a financial services company. Why: This incident happened because of a phishing email that contained a malicious attachment. Once it was downloaded, an alert was received by a level one SOC analyst.|
|Additional notes|	To prevent such incidents in the future, employees should be trained to be more aware before clicking on links in emails.|



|Date: October 15, 2024	|Entry: 3|
|-----------------------|--------|
|Description|	A forced browsing attack occured at a mid-sized retail company, where an individual was able to gain unauthorized access to customer PII and financial information. NIST Incident Response Lifecycle phases for the incident: - Detection and Analysis: An employee received an email from an external email address claiming that the sender had successfully stolen customer data, and requested a $25,000 cryptocurreny payment in exchange for not releasing the data to the public. The email was assued to be spam and was deleted. Detection took place when the employee received a second email from the same sender with a sample of the stolen data and an increased payment demand of $50,000. For analysis, the security team was notified and they started their investigation into the incident. - Post-Incident Activity: To prevent future recurrences, it has been planned to perform routine vulnerability scans and penetration testing. Additionally, the following access control mechanisms have been implemented:
- Implement allowlisting to allow access to a specified set of URLs and automatically block all requests outside of this URL range.
- Ensure that only authenticated users are authorized access to content.
Tool(s) used	Web server logs.
The 5 W's 	Capture the 5 W's of an incident.
Who: Unknown.
What: A threat actor used forced browsing attack to access customer transaction data by modifying the order number included in the URL string of a purchase confirmation page.This vulnerability allowed the attacker to access thousands of customer purchase confirmation pages, exposing customer data, which the attacker then collected and exfiltrated.
When: December 22, 2022 at approximately 3:13 pm.
Where: At a mid-sized retail company.
Why: This incident happened because of a vulnerability in the e-commerce web application that allows individuals to access a customer confirmation page by modifying the order number included in the URL string.
Additional notes	



Date: 
October 21, 2024	Entry:
4
Description	Analyze a packet capture file.
Tool(s) used	Wireshark, a network protocol analyzer that used a graphical user interface. It allows security analyste to capture and analyze network traffic, which helps in detecting and investigating malicious activity.
|The 5 W's |	Capture the 5 W's of an incident. Who: N/A What: N/A When: N/A Where: N/A Why: N/A|
|Additional notes|	Wireshark seems to be a very powerful tool to search through packet information efficiently. |
