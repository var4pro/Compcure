\*️⃣ (n)  -  It's enough to choose only one, other points with the same tag can be omitted; 

For example I'll use ThinkCentre M90t Gen 6 BIOS settings:
- [In USB Provisioning form](../files/ThinkCentre%20M90t%20Gen%206%20settings.txt)
- In the visual form: 
SECURITY SETTINGS:
	Set supervisor password(\*️⃣ (1))
	System Management Password Access Control:
		Access Security Settings: Disabled
		Remote Set SMP: Disabled
	Password Policies:
		BIOS Password At System Boot: No
		BIOS Password At Reboot: No
		BIOS Password At Boot Device List: Yes
		Require SVP when Flashing: Yes
		Allow the Jumper to Clear SVP: No
		Password Count Exceeded Error: Enabled
	Secure Roll Back Prevention: Yes
	Smart USB Protection: No access(if no need for connecting flash-disk)
	TCG Feature Setup:
		Security Chip 2.0: Enabled
		Clear TCG Security Feature: No
	Secure Boot:
		Secure Boot: Enabled
		Allow Microsoft 3rd Party UEFI CA: Disabled
	Use Certificate-based BIOS Authentication(\*️⃣ (1))
	Certificate-based BIOS Authentication(\*️⃣ (1)):
		Allow the Jumper to Reset Certificate: No
	Computrace:
		Absolute Persistence Module: Disabled
	Secure Core PC Level3: Enabled	
	Electronic Lock: Lock
	Cover Tamper Detected: Enabled
	Configuration Change Detection: Enabled
	Key Part Replacement Detection: Authenticate
DEVICES SETTINGS:
	Disable what you don't need.
ADVANCED SETTINGS:
	Cpu setup:
		Intel(R) Virtualization Technology: Enabled
		VT-d Feature: Enabled
		TxT: Enabled
		IOMMU: Enabled
	Intel(R) Manageability:
		Intel(R) Manageability Control: Disabled
		Intel(R) Manageability Reset: Disabled
		 USB Provisioning: Disabled(after configuration)
	Intel(R) Total Memory Encryption: Enabled
	Intel(R) SIPP Support: Enabled