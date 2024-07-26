# Pen testing Using METASPLOIT

## Objective

The Pentesting activity was used to simulate a real-life company pen-testing report while an exploit was found in a simulated company.

### Skills Learned

- Understanding of METASPOIT and its commands
- Proficiency using VM machines. VMWare and Metasploit2-Linux
- Identifying open ports with Nmap and how to exploit them
- Putting backdoors on the system
- Development of a Pen-test report with extensive details
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- METASPLOIT
- Network analysis tools (such as Nmap)
- VMWare
- Kali Linux

## Steps

*Pen-Testing Document* --> [0o0yhCWkQwmgzLUQxjp9FA_ebd394c6868243608768b747f63894f1_Blank_Penetration_Testing_Report_Template.docx](https://github.com/user-attachments/files/16385243/0o0yhCWkQwmgzLUQxjp9FA_ebd394c6868243608768b747f63894f1_Blank_Penetration_Testing_Report_Template.docx)

Document with the description of the attack and how it was accessed

*Metasploit VM* 

![Screenshot 2024-07-25 204210](https://github.com/user-attachments/assets/805070fa-4c1d-4d5a-8674-c7f117e7858f)

*Nmap Scan*  

![Screenshot 2024-07-25 204404](https://github.com/user-attachments/assets/72c2edc2-a310-4046-b40e-2cb9e6d00004) 

In this image is possible to observe a namp scan using the command line (nmap -sC -sV [port number of attacking machine]) to identify the version and the open ports on the machine. With further analysis, we observed some flaws in the FTP port 

*METASPLOIT interaction* 

![Screenshot 2024-07-25 204456](https://github.com/user-attachments/assets/8169e230-50eb-49b2-8265-1500c877a56d) ; ![Screenshot 2024-07-25 204606](https://github.com/user-attachments/assets/9da3f81a-bb77-4579-b732-10fe50b84458) ; ![Screenshot 2024-07-25 204629](https://github.com/user-attachments/assets/4ab012ef-30cb-4f38-a303-bef9c773dd69)

In these pictures we were able to observe several different methods of using the METASPLOIT, including on searching for an exploit to utilize the vulnerability of samba, setting up rhost, and finally getting access to the host machine. With that, we were also able to jump to the "PERSISTANCE" phase and add a backdoor to the system to access at any convenient time
