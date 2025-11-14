# Window-troubleshooting notes in 3 Months of some Experience 
 A collection of troubleshooting step, command ,fixed and practice help desk ticket system great for Tier 1 Support ,Comptia A+ and real job experiences .
--
# 1/ fix Essential WIndow commands
    note >Netwoek & IP Tools
    -ipconfig /all -show full ip config throught command line such as IP add ,subnetmask ,defaultgatway ....
    -ipconfig /realease : that release your computer current IP address ,which disconnected it from the network .
    -ipconfig /renew : to obtian a new ip address from DHCP server when current ip disconnected from network .
    -ping 8.8.8.8 -test internet 
    nslookup-DNS lookup
    netsh winsosck reset -reset network stack like can fix network and internet connectivity problems which can help resloved caused by corrupted settings .(EX: Inability to access the internet or specific websites despite a seemingy proper network configuration).
     -tracert-trace network path that data packet take from your computer to a specified destination it can be identifying such as bottlenecks, points of failuire,or latency issues.
  # System Tools
  - sfc /scannow — Check system files  
- dism /online /cleanup-image /restorehealth`  
- chkdsk /f — Fix disk errors  
- tasklist — Show running tasks  
- taskkill /pid #### /f` — Kill a process  
# Slow performence
 -The thing we shloud check a laptop or PC by checking CPU / RAM in Taskmanger 
 -disable the start up app 
 -scan malware by using window security virus and threat portection that already build by  mircrosoft window it free by quick  scan or we use some a antivirus software app or from the third-party .
 -check disk health ( chksdk,SMART) =defragment or cleanup space ..
 - clear DNS cache
 - checking any app or software that eat up so much RAM .
  # No internet / Wi-Fi issues
- Restart adapter  
- Update driver  
- Flush DNS  
- Reset TCP/IP stack  
- Check router or modem
  # Application crashes
- Update/reinstall app  
- Check Event Viewer  
- Check permissions
- Help Desk Practice Tickets

### Ticket #001 — Wi-Fi Not Connecting
**User:** “I can’t connect to Wi-Fi.”  
**Steps Taken:**  
- Checked airplane mode  
- Verified adapter enabled  
- Ran `ipconfig /flushdns`  
- Reset driver  
**Outcome:** Issue resolved.

### Ticket #002 — Printer Not Responding
**User:** “Printer won’t print.”  
**Steps Taken:**  
- Restarted Print Spooler service  
- Checked printer IP  
- Removed & re-added printer  
- Updated driver  
**Outcome:** Printer back online.

### Ticket #003 — Slow Computer
**User:** “My PC is very slow.”  
**Steps Taken:**  
- Disabled heavy startup apps  
- Scanned for malware  
- Checked disk usage  
- Cleared temp files  
**Outcome:** Performance improved.
