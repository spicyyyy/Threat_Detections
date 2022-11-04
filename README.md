# The Science of Threat Detections
A work in progress to keep my threat detections and ideas across platforms


Exfiltration AND Collection

EXFILTRATION is moving data to a COLLECTION site. COLLECTION sites hold data for EXFILTRATION.

  The above statement is a circle and the core statement to base your detections on. The MITRE ATTCK framework breaks both tactics out separately. To detect malicious and non-malicious threats, these two tactics must cross domains from a blue team perspective. 

General questions to be answered:
What are the approved collection sites?
What are users acutely using to store data?
What are the approved exfiltration methods?
What are users accurately using to exfil data?

Questions for approved collection sites
Who can access?
Who can download?
What data sits on the site?(DLP/Content inspection)


Notes to edit.
Endpoint. 
The users are the weakest link of course; the endpoint should be the hardest place to have sensitive data. 
