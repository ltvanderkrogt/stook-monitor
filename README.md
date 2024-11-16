# stook-monitor esphome
Per oktober 2024 is het beleid voor het stoken van haardhout aangepast. een onderzoek wijst uit dat niet de mate van fijnstof zorgt voor klachten maar de windsnelheid tijdens het stoken. Deze monitor maakt gebruik van een al bestaande eigen fijnstof sensor en de windsnelheid uit de regio. 

![de stookmonitor](https://github.com/ltvanderkrogt/stook-monitor/blob/d3214b5844a2931793106cac0d5dec4ee69dac7f/stookmonitor.jpg))

Deze monitor maakt gebruik van de criteria gesteld in dit document: [Gezondheids- en hindereffecten door houtkachels van particulieren](https://stab.nl/wp-content/uploads/2019/11/STAB-Kennisdocument-Houtstook-september-2019.pdf)

Belangrijkste regel: geen hout stoken als de windsnelheid minder dan 12 km/h is. 
Verder wordt een kleurentabel gebruikt voor de luchtkwaliteit. 

![luchtkwaliteit index](https://github.com/ltvanderkrogt/stook-monitor/blob/d3214b5844a2931793106cac0d5dec4ee69dac7f/Luchtkwaliteit.jpg)

De stookmonitor maakt gebruik van;
* Wemos D1 mini als esphome device
* een Wemos RGB shield met een ws2812 LED
* een bestaande fijnstof sensor 
* de Windsenlheid van ![Buienradar integratie voor Home Assistant](https://www.home-assistant.io/integrations/buienradar/#:~:text=Go%20to%20Settings%20%3E%20Devices%20%26%20Services,screen%20to%20complete%20the%20setup.)



