# Hackintoshing T490s
## Specs
### i7 Variant
Intel® Core™ i7-8565U CPU @ 1.80GHz  
### i5 Variant
Intel i5-8265U (8) @ 3.900GHz
### GPU
Intel® UHD Graphics 620  
### Audio
Realtek High Definition Audio
### Internet
Intel® Wireless-AC 9560 160MHz
Intel® Ethernet Connection (6) I219-V
### Bluetooth
Bluetooth Device (Personal Area Network)
Intel® Wireless Bluetooth®
### RAM
8GB is what I have, however you can get 16GB.
## Working
Battery Status  
Display  
Sound  
WiFi  
Bluetooth  
Trackpad  
Power Management  
Camera  
## Not working
Battery status updates when charging  
DisplayPort via USB-C  
Bluetooth bugs when sleep wakeup  
itlwm bugs  
## BIOS Changes Needed
Config  
| Security  
|| >> Security Chip  
Security Chip DISABLED  
| Fingerprint  
Predesktop Authentication DISABLED  
| I/O Port Access  
Wireless WAN DISABLED *ENABLED if you have a 2nd drive attached  
Fingerprint Reader DISABLED  
| Secure Boot Configuration  
Secure Boot DISABLED  
Press Clear All Secure Boot Keys  
| Intel SGX  
Intel SGX Control DISABLED  
| Startup  
UEFI/Legacy Boot UEFI Only  
CSM Support No (per OpenCore Documentation)   
!!! Thunderbolt BIOS Assist enabled  (0,8W idle)  
