# T490s hackintosh
## Patches
I forked this in order to do a couple of [patches](https://mrmad-com-tw.translate.goog/fix-hackintosh-liteon-plextor-skhynix-m2-ssd?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp), and to try to get Monterey to boot.
## Specs
### CPU
Intel i5-8265U (8) @ 3.900GHz
### GPU
Intel® UHD Graphics 620
### Audio
Realtek High Definition Audio
### Internet
Intel® Wireless-AC 9560 160MHz
Intel® Ethernet Connection (6) I219-V
### Bluetooth
Intel® Wireless Bluetooth®
### RAM
8GB.
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
NVMe (hopefully working soon)  
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
!!! Thunderbolt BIOS Assist enabled  
