# Anti-K
Anti keylogger and malware detection tool

Keylogger detection tool using SMTP port monitoring, active progess scanning and signature analysis to detect malware. 

Automated continuous port scanning while the app is runnig. 
System scans initiated by user. 
Suspicious processes hashed and quieried to VirusTotal.  

Python app developed with a GUI using PySimpleGUI. 
Can be packaged as a windows executable using PyInstaller. 
Can be run from portable media with no dependencies installed. 

Keylogger script created as part of the project. 
If bundled as a one-file executable, can run undetected by windows defender. 
Edit email address and pass to suit. edit email server as per provider. Email timer can be changed to suit.  
Logs of prossed keys will be emailed to the address provided. Unsuccessful emails will be saved as drafts with keylogs. 
