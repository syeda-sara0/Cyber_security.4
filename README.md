# Cyber_security.4
Objective:
To configure and test basic firewall rules on Windows.

Tool Used
Windows Defender Firewall

Steps:
(1) Opened Windows Defender Firewall with Advanced Security.
(Screenshot: Step1_Firewall_Opened.1.png)

(2) Viewed existing inbound firewall rules.
(Screenshot: Step2_Inbound_Rules_List.2.png)

(3) Created a rule to block TCP port 23 (Telnet).
(Screenshot: Step3_Block_Port23_Rule.3.png)

(4) Tested port 23 using PowerShell. The connection failed, confirming the block.
(Screenshot: Step4_Port23_Test_PowerShell.4.png)

(5) Deleted the test firewall rule to restore the system.
(Screenshot: Step5_Block_Rule_Removed.5.png)

Conclusion:
The firewall successfully blocked and controlled network traffic using port-based rules.
