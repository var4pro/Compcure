\*️⃣ (n)  -  It's enough to choose only one, other points with the same tag can be omitted; 
**RU:** \*️⃣ (n)  - достаточно выбрать что-то одно, остальные пункты с такой же меткой можно опустить

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
6 CPU must have fTPM(\*️⃣ (1))

Also, be sure to check the internet for vulnerabilities in specific components.

**RU:**
1 Для дисков специальных требований нет.
2 Для GPU специальных требований нет.
3 Для ОЗУ специальных требований нет.
4 Корпус должен быть с крышкой для закрытия компонентов компьютера,  с поддержкой датчика вскрытия корпуса.
5 Материнская плата должна включать в себя:
	- IOMMU с отдельной группой для ОЗУ; 
	- dTPM 2.0+(\*️⃣ (1)); 
	- Возможность установки пароля/сертификата supervisor с запросом при попытке изменения boot order или захода в настройки биос, но без запроса при входе в ос;  
	- Хранение пароля/сертификата supervisor в защищенной EEPROM или же TPM-модуле; 
	- Опция выключения возможности сброса пароля/сертификата supervisor; 
	- Невозможность изменить версию биос без пароля/сертификата supervisor; 
	- Наличие опции блокировки биоса при срабатывании датчика вскрытия корпуса; 
	- Сохранение состояния системы для TPM модуля
6 CPU должен иметь fTPM(\*️⃣ (1))

Также обязательно проверить в интернете наличие уязвимостей у конкретных компонентов.
