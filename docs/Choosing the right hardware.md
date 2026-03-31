\*️⃣ (n)  -  It's enough to choose only one, other points with the same tag can be omitted; 

1 No special requirements for **disks**.
2 No special requirements for **GPU**.
3 No special requirements for **RAM**.
4 Computer **case** must have a lid that covers the computer components and support a chassis intrusion sensor.
5 **Motherboard** must include: 
	- IOMMU with a separate group for RAM only;
	- dTPM 2.0+(\*️⃣ (1)); 
	- Possibility to set supervisor password/certificate with a request when attempting to change boot order or enter BIOS settings, but without a request when booting the OS;
	- Storage of the supervisor password/certificate in secure EEPROM memory or TPM; 
	- Option to disable clearing supervisor password/certificate; 
	- Option to disable changing BIOS version without supervisor password/certificate; 
	- Option to block BIOS on opening case lid;
	- Saving system state in the TPM
6 CPU must have: 
	- fTPM(\*️⃣ (1)); 
	- SME/TME - RAM encryption

Also, be sure to check the internet for vulnerabilities in specific components.