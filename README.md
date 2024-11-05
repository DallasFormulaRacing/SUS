# Suspension-Sensor-System (SSS)
A device that is mounted near each wheel of the car that can record tire temperature and linear potentiometers (suspension travel)

### Schematic
![ESP32 Hat Schematic](Images/SSS_HAT_Schematic.png)
### PCB Drawing
![EPS32 Hat PCB Drawing](Images/SSS_HAT_PCB_Drawing.png)
### PCB 3D Model
![ESP32 HAT PCB 3D Model](Images/SSS_HAT_PCB.png)
![ESP32 HAT PCB 3D Model](Images/SSS_HAT_PCB_1.png)
![ESP32 HAT PCB 3D Model](Images/SSS_HAT_PCB_2.png)
### Bill of Materials
|Item|Description|Photo|# of items|Cost per item|
|:--|:--|:-:|--:|--:|
|[TJA1051T](https://www.digikey.com/en/products/detail/nxp-usa-inc/TJA1051T-3-1J/5035822?utm_adgroup=General&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Zombie%20SKUs&utm_term=&utm_content=General&utm_id=go_cmp-17815035045_adg-_ad-__dev-c_ext-_prd-_sig-Cj0KCQiAoae5BhCNARIsADVLzZfN85grpeifPYBOIfQZmqBnjhDgX5-_qDHaBMGXU3fkYhMCIpdmNZ4aAuLQEALw_wcB&gad_source=1&gclid=Cj0KCQiAoae5BhCNARIsADVLzZfN85grpeifPYBOIfQZmqBnjhDgX5-_qDHaBMGXU3fkYhMCIpdmNZ4aAuLQEALw_wcB)|CAN transceiver|![TJA1051T](Images/TJA1051T.jpg)|1|$1.22|
|[ADS8320EB/250](https://www.digikey.com/en/products/detail/texas-instruments/ADS8320EB-250/275813)|External ADC|![ADS8320EB/250](Images/ADS8320EB250.jpg)|1|$14.68|
|[ICM-42688-P](https://www.digikey.com/en/products/detail/tdk-invensense/ICM-42688-P/10824934)|6-DOF IMU|![ICM-42688-P](Images/ICM-42688-P.jpg)|1|$0.74|
|[DF3D(Z)-3P-2H(51)](https://www.digikey.com/en/products/detail/hirose-electric-co-ltd/DF3EA-3P-2H(51)/6148621?utm_adgroup=General&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Zombie%20SKUs&utm_term=&utm_content=General&utm_id=go_cmp-17815035045_adg-_ad-__dev-c_ext-_prd-6148621_sig-Cj0KCQjw1Yy5BhD-ARIsAI0RbXbq7SBVNmAXCWU9K1fzl8auF7Nl_61zIEXugZVVEsHFKjp7xJIr2FsaAh0eEALw_wcB&gad_source=1&gclid=Cj0KCQjw1Yy5BhD-ARIsAI0RbXbq7SBVNmAXCWU9K1fzl8auF7Nl_61zIEXugZVVEsHFKjp7xJIr2FsaAh0eEALw_wcB)|3-pin connector| ![DF3D(Z)-3P-2H(51)](Images/DF3D(Z)-3P-2H(50).jpg)|2|$0.95|
|[DF3D(Z)-3P-2H(51)](https://www.digikey.com/en/products/detail/hirose-electric-co-ltd/DF3EA-4P-2H-51/6148543?s=N4IgTCBcDaICIDEDMBRAggWgCwAUNgAkAKAVgEYBKEAXQF8g)|4-pin connector|![DF3D(Z)-4P-2H(51)](Images/DF3D(Z)-4P-2H(50).jpg)|3|$1.08|
