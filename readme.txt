# RansomWare-Attack
Ransomware is a type of malware attack in which the attacker locks and encrypts the victim’s data
This type of attack takes advantage of human, system, network, and software vulnerabilities to infect the victim’s device—which can be a computer, printer, smartphone, wearable, point-of-sale (POS) terminal, or other endpoint.
# Examples
There are thousands of strains of ransomware malware. Below we list a few malware examples that made a global impact and caused widespread damage.
   -/WannaCry
   -/cerber
   -/Locky
   -/Cryptolocker
   -/NotPetya and Petya


# Ransomware Distribution Techniques

              Distribution Techniques 	                                                        Description


                Phishing email                                      
                                                                      Clicking a link embedded in an email, which redirects to a malicious web page. 


               Email attachments                                   
                                                                      Opening an email attachment and enabling malicious macros; or downloading a document 
                                                                      embedded with a Remote Access Trojan (RAT); or downloading a ZIP
                                                                      file containing a malicious JavaScript or Windows Script Host (WSH) file.

               Social media                                         
                                                                     Clicking a malicious link on Facebook, Twitter, social media posts, instant messenger chats,

               Malvertising                                         
                                                                      Clicking a legitimate advertising site seeded with malicious code. 

               Infected programs                                   
                                                                      Installing an application or program containing malicious code. 

               Drive-by-infections                                 
                                                                      Visiting an unsafe, suŝpicious, or fake web page or opening or closing a pop-up . 
                                                                        Note : 
                                                                         A legitimate web page can be compromised if a malicious javascript code is injected into the page's content .
               

               Traffic Distribution System (TDS)                       
                                                                      Clicking a link on a legitimate gateway web page that redirects the user to a malicious site, based on the user's geo-location, browser, operating systems, or others filter.

               Self-propagation  
                                                                      Spreading the malicious code th other devices through network and usb drives. 


# How does Ransomware work 

After a device is exposed to the malicious code, the ransomware attack proceeds as follows. Ransomware can remain dormant on a device until the device is at its most vulnerable, and only then execute an attack. 

Ransomware Seven-stage attack 


1.Infection 
         Ransomware is covertly downloaded and installed on the device 

2.Execution 
         Ransowmare Scans and maps locations for targeted file types, including locally stored files, and mapped and unmapped network-accessible systems, Some ransomware attacks also delete or encrypt any backup files and folders. 

3.Encryption 
         Ransomware performs a key ecchange with the command and control server, using the encryption key to scramble all files discovered during the execution step, it also locks acces to the data 

4.User Notification 
         Ransomware adds instruction files detailing the pay-for-decryption proces, then uses those files to display a ransom note th the user

5.Clean-UP
         Ransomware usually terminates and deletes itself, leaving only the payement instruction files. 
         
6.Payment
         Victim clicks a link in the payement instructions, which takes the victim to a web page with additional information on how to make the required ransom payment. Hidden TOR services are often used to encapsulate and obfuscate these communications to avoid detection by network traffic monitoring. 

7.Decryption 
         After the victim pays the ransom, usually via the attacker's bitcoin address, the victim may receive the decryption key, However, the is no guarantee the decryption key will be delivered as promised. 

Note : 
   One infected user can result in a data lockout for all users


# Ransomware Protection 
Here are several best practices that can help you prevent and protect against Ransomware infections in your organization:

   # Endpoint Protection 
      Antivirus is an obvious first step in ransomware protection, but legacy antivirus tools can only protect against some ransomware variants.
     
      Modern endpoint protection platforms provide next-generation antivirus (NGAV), which protects against evasive or obfuscated ransomware, fileless attacks like WannaCry, or zero-day malware whose signature is not yet found in malware databases. They also offer device firewalls and Endpoint Detection and Response (EDR) capabilities, which help security teams detect and block attacks occurring on endpoints in real time.
   
   # DAta Backup 
      Regularly backup data to an external hard-drive, using versioning control and the 3-2-1 rule (create three backup copies on two different media with one backup stored in a separate location). If possible, disconnect the hard-drive from the device to prevent encryption of the backup data.
   
   # Patch Management 
      Keep the device’s operating system and installed applications up-to-date, and install security patches. Run vulnerability scans to identify known vulnerabilities and remediate them quickly.

   # Application Whitelistening and control 
      Establish device controls that allow you to limit applications installed on the device to a centrally-controlled whitelist. Increase browser security settings, disable Adobe Flash and other vulnerable browser plugins, and use web filtering to prevent users from visiting malicious sites. Disable macros on word processing and other vulnerable applications.
   
   # Email Protection 
      Train employees to recognize social engineering emails, and conduct drills to test if employees are able to identify and avoid phishing. Use spam protection and endpoint protection technology to automatically block suspicious emails, and block malicious links if user does end up clicking on them.

   # Network Defenses 
      Use a firewall or web application firewall (WAF), Intrusion Prevention / Intrusion Detection Systems (IPS/IDS), and other controls to prevent ransomware from communicating with Command & Control centers.

# Ransomware Detection 

 Use real-time alerting and blocking to automate identifying ransomware-specific read/write behavior and then blocking users and endpoints from further data access.

 Use deception-based detection, which strategically plants hidden files on file storage systems to identify ransomware encryption behaviors at the earliest attack stage. Any write/rename actions on the hidden files automatically triggers a block of the infected user or endpoint, while continuing to allow access by uninfected users and devices.

 Use granular reporting and analysis to provide detailed audit trail support for forensic investigations into who, what, when, where, and how users access files.
 
 Deception-based detection measure ensures that only the infected user is blocked from accessing data

# Ransomware Removal : How to mitigate an active Ransomware Infection 
 If you detected a ransomware infection in your network,here are the immediate steps you should take to mitigate the ransomware threat. 

 1. Isolate 
         Identify infected machines, disconnect from networks and lock drives to prevent encryption. 

 2. Investigate 
         See what backups are available for encrypted data. Check what Strain on ransomware you were hit with, and if there are decryptors available. Understand if paying the ransom is a viable option

 3. Recover 
         if no decryptor tools are available, restore your data from backup. In most countries, the authorities do not recommend paying the ransom, but this may be a viable option in some extreme cases. Use standard practices to remove ransomware or wipe and reimage affected systems.

 4. Reinforce 
         run a lessons learned session to understand how internal systems were infected and how to prevent a recurrence. Identify the key vulnerabilities or lacking security practices that allowed the attackers in, and remediate them.

 5. Evaluation 
         once the crisis has passed, it’s important to evaluate what happened and the lessons learned. How was ransomware successfully executed? Which vulnerabilities made penetration possible? Why did antivirus or email filtering fail? How far did the infection spread? Was it possible to wipe and reinstall infected machines, and were you able to successfully restore from backup? Address the weak points in your security posture to be better prepared for the next attack.


# Data Protection Solution 
   Approach relies on multiple layers of protection, including : 
      
   1. DataBase Firewall 
            Blocks SQL injection and other threats, while evaluating for known vulnerabilities .

   2. Data masking and encryption 
            Obfuscates sensitives data so it would be useless to the bad actor, even if somehow extracted.

   3. Data loss prevention (DLP) 
            Inspect data in motion, at rest on servers, in cloud storage, or on endpoint devices.

   4. User behavior analytics 
            Establishes baselines of data access behavior, uses machine learning to detect and alert on abnormal and potentially risky activity.

   5. Data discovery and classification 
            Reveals the location, volume, and context of data on promises and in the cloud . 

   6. DataBase activity monitoring 
            Monitors relational databases, data warehouses, bigdata and  mainframes to generate real-time alerts on policy violations . 

   7. Alert prioritization 
            Uses AI and Machine learning technology to look across the stream of security events and prioritize the ones that matter most . 
            

