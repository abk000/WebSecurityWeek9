# WebSecurityWeek9
Using honey-potting to detect attacks. 

# Honeypots 
 Only the Dionaea honeypot was used for this experiment. 
 
# Issues 

 I encountered a bit of trouble in the setup of the environment, particularly while installing MHN onto the admin instance. It delayed more than expected and got stuck during one attempt so I had to delete the VM instance and start over. In addition, the firewall did not configure correctly at first and I could not access the admin console via browser until a while after manually checking off the 'allow http' box in my GCP firewall settings. 
 
 # Summary of Attacks 
 
  - Time Interval - 20 minutes
  - Number of attacks - 1,164
  - Majority of attacks came from my own public IP address: 134.74.251.201 on the pcap protocol. 
  
# Questions/Concerns

   I did not expect this many attacks in such a short period of time. I'm curious as to what other factors can influence vulnerability. I believe it may be because I also checked the firewall option to allow traffic from 'HTTPS', and also because the honeypot allows connection to all ports. This is apparent in the amounts of unfamiliar ports listed in the attacks.
