# Suspension-Sensor-System (SSS)
A device that is mounted near each wheel of the car that can record tire temperature and linear potentiometers (suspension travel)

### Schematic
![ESP32 Hat Schematic](Images/SUS-HAT_Schematic.jpg)
### PCB Drawing
![EPS32 Hat PCB Drawing](Images/SUS_HAT_PCB_Drawing.png)
### PCB 3D Model
![ESP32 HAT PCB 3D Model](Images/SUS_HAT_PCB.png)
![ESP32 HAT PCB 3D Model](Images/SUS_HAT_PCB_1.png)
![ESP32 HAT PCB 3D Model](Images/SUS_HAT_PCB_2.png)
### Bill of Materials
|Part|Description|Photo|# of parts|Cost per part|
|:--|:--|:-:|--:|--:|
|[TJA1051T](https://www.digikey.com/en/products/detail/nxp-usa-inc/TJA1051T-3-1J/5035822?utm_adgroup=General&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Zombie%20SKUs&utm_term=&utm_content=General&utm_id=go_cmp-17815035045_adg-_ad-__dev-c_ext-_prd-_sig-Cj0KCQiAoae5BhCNARIsADVLzZfN85grpeifPYBOIfQZmqBnjhDgX5-_qDHaBMGXU3fkYhMCIpdmNZ4aAuLQEALw_wcB&gad_source=1&gclid=Cj0KCQiAoae5BhCNARIsADVLzZfN85grpeifPYBOIfQZmqBnjhDgX5-_qDHaBMGXU3fkYhMCIpdmNZ4aAuLQEALw_wcB)|CAN transceiver|<img src="Images/TJA1051T.jpg" alt="TJA1051T" width="100"/>|1|$1.22|
|[ADS8320EB/250](https://www.digikey.com/en/products/detail/texas-instruments/ADS8320EB-250/275813)|External ADC|<img src="Images/ADS8320EB250.jpg" alt="ADS8320EB/250" width="100"/>|1|$14.68|
|[ICM-42688-P](https://www.digikey.com/en/products/detail/tdk-invensense/ICM-42688-P/10824934)|6-DOF IMU|<img src="Images/ICM-42688-P.jpg" alt="ICM-42688-P" width="100"/>|1|$0.74|
|[DF3D(Z)-3P-2H(51)](https://www.digikey.com/en/products/detail/hirose-electric-co-ltd/DF3EA-3P-2H(51)/6148621?utm_adgroup=General&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Zombie%20SKUs&utm_term=&utm_content=General&utm_id=go_cmp-17815035045_adg-_ad-__dev-c_ext-_prd-6148621_sig-Cj0KCQjw1Yy5BhD-ARIsAI0RbXbq7SBVNmAXCWU9K1fzl8auF7Nl_61zIEXugZVVEsHFKjp7xJIr2FsaAh0eEALw_wcB&gad_source=1&gclid=Cj0KCQjw1Yy5BhD-ARIsAI0RbXbq7SBVNmAXCWU9K1fzl8auF7Nl_61zIEXugZVVEsHFKjp7xJIr2FsaAh0eEALw_wcB)|3-pin connector|<img src="Images/DF3D(Z)-3P-2H(50).jpg" alt="DF3D(Z)-3P-2H(51)" width="100"/>|2|$0.95|
|[DF3D(Z)-3P-2H(51)](https://www.digikey.com/en/products/detail/hirose-electric-co-ltd/DF3EA-4P-2H-51/6148543?s=N4IgTCBcDaICIDEDMBRAggWgCwAUNgAkAKAVgEYBKEAXQF8g)|4-pin connector|<img src="Images/DF3D(Z)-4P-2H(50).jpg" alt="DF3D(Z)-4P-2H(51)" width="100"/>|3|$1.08|
|[S02-20150300](https://www.mouser.com/ProductDetail/Harwin/S02-20150300?qs=rE7yDObIq0ygO5qZqrVEAg%3D%3D)| EMI shield | <img src="Images/S02-20150300.jpg" alt="S02-20150300" width="100"/>|1|$4.26|
|[S1001-46R](https://www.mouser.com/ProductDetail/Harwin/S1001-46R?qs=HTI7V3DFux8iE7nFrNF%2Fww%3D%3D)| EMI shield connectors |<img src="Images/S1001-46R.jpg" alt="S1001-46R" width="100"/>|4|$0.58|
