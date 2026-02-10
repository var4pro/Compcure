\*️⃣ (n)  -  It's enough to choose only one, other points with the same tag can be omitted; 
**RU:** \*️⃣ (n)  - достаточно выбрать что-то одно, остальные пункты с такой же меткой можно опустить

For example I'll use ThinkCentre M90t Gen 6 BIOS settings:
**RU:** Для примера я буду использовать ThinkCentre M90t Gen 6 настройки BIOS:
- [In USB Provisioning form / **RU:** В форме USB Provisioning](../files/ThinkCentre%20M90t%20Gen%206%20settings.txt)
- In the visual form: 
  **RU:** В визуальном виде:
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
	Windows UEFI Firmware Update: Enabled
	Smart USB Protection: No access(если не требуется подключение флэш-накопителей)
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
		Absolute Persistence Module: Enabled
	Secure Core PC Level3: Enabled	
	Electronic Lock: Lock
	Cover Tamper Detected: Enabled
	Configuration Change Detection: Enabled
	Key Part Replacement Detection: Authenticate
DEVICES SETTINGS:
	Отключить то, что не понадобиться
ADVANCED SETTINGS:
	Cpu setup:
		Intel(R) Virtualization Technology: Enabled
		VT-d Feature: Enabled
		TxT: Enabled
		IOMMU: Enabled
	Intel(R) Manageability:
		Intel(R) Manageability Control: Enabled
		Intel(R) Manageability Reset: Disabled
		 USB Provisioning: Disabled(после конфигурации)
	Intel(R) Total Memory Encryption: Enabled
	Intel(R) SIPP Support: Enabled