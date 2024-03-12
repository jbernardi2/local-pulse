# LocalPulse
## To use:
### If on Windows:
#### You must open ports 8088 for RC50 and 8089 for SD30 through your Windows Firewall <- create inbound rule for tcp ports 8088 and 8089.
##### Using Windows Firewall with Advanced Security (GUI):
##### 1. Open Windows Firewall with Advanced Security: Press Windows + R to open the Run dialog, type wf.msc, and press Enter.
##### 2. Inbound Rules: In the left pane, click on Inbound Rules.
##### 3. New Rule: On the right pane, click on New Rule.
##### 4. Rule Type: Select Port and click Next.
##### 5a. Protocol and Ports: Choose TCP
##### 5b Select Specific local ports, enter the port number you want to open (8088,8089), and click Next.
##### 6. Action: Choose Allow the connection and click Next.
##### 7. Profile: Select when this rule applies (Domain, Private, Public). It's common to select all options if you're unsure. Click Next.
##### 8. Name: Give your rule a name and an optional description. Click Finish.

### Ensure that your machine's (computer/pc) IP address is set to static and is set to the following: 
#### IP: 192.168.4.127
#### Netmask: 255.255.255.0
#### Gateway (if needed): 192.168.4.1
##### ** RC50/SD30 should also reflect the same IP for the server field, same goes for the netmask and gateway. Device IP must be 192.168.4.* where * can be any number 1-255 except for 127 since the server is running on 127.


### To run the application, please select and download the appropriate zip for your operating system (Mac for MacOS, and Windows for Windows). Extract the zip file and run the executable (if on Windows). If on mac, it will show up as an application. Make sure to right click the application and select open to make sure MacOS will open the app <- first time only. Windows should have no issue running the executable. 
