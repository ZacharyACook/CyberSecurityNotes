- CIA Triad
	<font color = 'gold'><u>Confidentiality:</u></font> Ensure that information is accessible only to those authorized to access it *(Encryption, Access controls, Data classification and clearance levels)*
	
	<font color = 'gold'><u>Integrity:</u> </font> Ensure the accuracy and completeness of data and systems over their lifecycle.
	*(Hash functions and checksums, Digital signatures, Version control)*
	
	<font color = 'gold'><u>Avilablity:</u> </font> Ensure that authorized users have reliable and timely access to data and systems when needed.
	*(Redundancy and failover solutions, Regular backups, Protection against Denial of Service attacks)*

- Threats & Vulnerabilities
	Malware:
	 1.SocGholish
		 Type: JavaScript based downloader
		 Delivery Method: Malicious or compromised websites via fake browser updates
		 Capabilities: Downloads additional malware like Cobalt Strike, Nonsupport, and Async RATs; can lead to ransomware infections
		 Prevalence:  Accounted for 53% of observed malware infections in Q4 2024
	 2.CoinMiner
		 Type: Crypto Miner
		 Delivery Method: Malspam or dropped by other malware
		 Capabilities: Uses Windows Management Instrumentation (WMI) for propagation; executes scripts for persistence
		 Prevalence:  28.8% as of 3rd quarter of 2024 	 
	 3.Arechclient2 (SectopRAT)
		 Type: .NET-based RAT
		 Delivery Method: Malspam/ dropped by other malware
		 Capabilities: Uses Windows management instrumentation for propagation
		 Prevalence:  N/A	 
	 4.NanoCore
		 Type: RAT
		 Delivery Method: MalSpam with malicious attachments
		 Capabilities: Keylogging, screen capturing, password stealing, data exfiltration, etc..
		 Prevalence: N/A
	 5.Agent Tesla
		 Type: RAT
		 Delivery Method: Malspam
		 Capabilities: Captures keystrokes and screenshots, harvests saved credentials from web browsers, copies clipboard data, etc..
		 Prevalence: N/A 	 
	 6.Ratenjay
		 Type: RAT
		 Delivery Method: Dropped by other malware or downloaded as a file onto system
		 Capabilities: Executes commands remotely and includes keylogging capabilities
		 Prevalence:  N/A	 
	 7.ZPHP
		 Type: JavaScript based downloader
		 Delivery Method: Malicious or compromised websites via fake browser updates
		 Capabilities: Executes commands remotely and includes keylogging capabilities
		 Prevalence:  N/A	 
	 8.DarkGate
		 Type: Downloader
		 Delivery Method: Sold on Russian-language cybercriminal dark web forums
		 Capabilities: Steals financial info, exfiltrates PII, drops malware, uses AutoIT scripts, and has a HVNC module and Keylogging capabilities
		 Prevalence:  N/A
	 9.Jupyter (SolarMarker)
		 Type: .NET-based info stealer
		 Delivery Method: waterhole websites and SEO poisoning to distribute malicious docs
		 Capabilities: Highly evasive and adaptive; steals info from victims
		 Prevalence:  N/A
	 10.LandUpdate808
		 Type: JavaScript based downloader
		 Delivery Method: Malicious or compromised websites via fake browser updates
		 Capabilities: Downloads and installs additional tools, such as the NetSupport remote access tools
		 Prevalence:  N/A
	
	phishing:
	 1.Email Phishing - Attackers send fake emails pretending to be someone else
		
	 2.Spear Phishing - Targeted phishing directed at a specific individual or organization
	 	
	 3.Whaling - A form of spear phishing targeting high profile executives
		
	 4.Smishing - Phishing attacks carried out via Text
		
	 5.Vishing - attacks carried out over the phone, pretending to be from a high level organization
	
	 6.Pharming - Redirects users from legitimate websites to fraudulent ones without there  knowledge
		
	 7.Clone Phishing - An attacker copies a legitimate email and resends it with malicious links
		
	 8.Angler Phishing - Targets users through fake customer service accounts on social media
		
     9.Man-in-the-Middle (MitM) Phishing - Intercepts communications between two parties
		
	 10.Business Email Compromise (BEC) - pretends to be a big organization in order to trick users
		
	
	ransomware:
	 1.Crypto Ransomware - Encrypts the victim's files and demands payment for the decryption key
		
	 2.Locker Ransomware - Locks users out of their entire system rather than individual files
	
	 3.Double Extortion Ransomware - Exfiltrates data before encrypting it, then threatens to publish or sell the data if ransom isn't paid
	
	 4.Ransomware-as-a-Service (RaaS) - A model where ransomware developers lease their code to affiliates who launch attacks
	
	 5.Mobile Ransomware - Targets smartphones. locking access or encrypting files
	
	 6.Scareware - Displays fake alerts claiming the device is infected then demands payment to fix it
	
	 7.Wiper Ransomware - Pretends to demand ransom, but actually destroys or permanently deletes data
	
	 8.Fileless Ransomware - Operates in-memory without writing files to disk, making it harder to detect
	
	 9.IoT Ransomware - Targets IoT devices like smart TVs, thermostats, or cameras
	
	 10.Social Engineering Ransomware - Relies heavily on phishing or tricking users into manually downloading and executing the malware
		
	
	social engineering:
	 1.Pretexting - creating a fabricated scenario to steal info
		
	 2.Baiting - Using a tempting item to lure victims into a trap
		
	 3.Tailgating - following someone into a restricted area by exploiting trust
		
	 4.Quid pro Quo - Offering a benefit in exchange for info
		
	 5.Impersonation - Pretending to be someone else to gain trust or access
		
	 6.Watering hole attack - compromising websites likely to be visited by targeted victims
		

-<font color = 'crimson'><u> Risk Management</u></font>
	<font color  = 'Gold'><u>Risk assessment:</u></font> *<font size = 2,>the process of identifying, evaluating, and prioritizing risks to an organization’s assets and operations</size>*
1.Identify Assets 

2.Identify Threats
	
3.Identify Vulnerabilities

4.Analyze Existing Controls

5.Determine likelihood

6.Determine Impact

7.Calculate Risk
	
<font color = 'gold'><u>mitigation strategies:</u></font>


- Security Controls
	Administrative:
	technical:
	physical: