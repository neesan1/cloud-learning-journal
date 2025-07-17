# Day 5 – Simulating Cloud Security: File Access, SSH & Firewalls

Simulated cloud-style file permission control using Git Bash  
Used `chmod` to restrict file access to mimic IAM roles  
Practiced SSH and SCP commands to simulate secure cloud VM connections  
Explored the concepts of secure config management and user-based access


#Commands Used:

mkdir secure_area
echo "This is a sensitive cloud config file." > secure_area/config.txt
chmod 700 secure_area/config.txt
ls -l secure_area
ssh user@cloudvm.google.internal
scp secure_area/config.txt user@cloudvm.google.internal:/etc/


#Reflection:
Today I simulated how cloud engineers manage security using the command line. I restricted file access with Linux permissions to mimic GCP IAM roles. I also practiced SSH and SCP to simulate how teams deploy secure configs to VMs. These skills are foundational in cloud computing, cybersecurity, and DevOps.

#Screenshot:
Day5-Security-Simulation/day5-Simulating-Cloud-Security-Screenshot.png
