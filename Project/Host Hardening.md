# What this activity is about
This activity consists of closong unnecessary ports on a Windows 10 VM

# Blocking a Port in Windows Firewall
As you can see in the photos, we are blocking port 3389 on the Windows 10 VM
![Windows Firewall Port Block](https://github.com/user-attachments/assets/aa49f625-ffc3-459b-bc8b-892c5350901e)
![Windows Firewall Port Block](https://github.com/user-attachments/assets/13c7c4c1-95ae-4986-acc9-b89315aec531)

# Before and After Firewall Rule
As you can see in the photo, when we first ran the command "sudo nmap <windows 10 vm ip>, Port 3389 is open. 
Once we make the firewall rule in the Windows 10 VM, the second time we run the command the port is now gone and closed.
![Host Hardening Before and After Blocking Port](https://github.com/user-attachments/assets/c1f7237b-b340-4dcf-8ddd-a2e2409727b1)
