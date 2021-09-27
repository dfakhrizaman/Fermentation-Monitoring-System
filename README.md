# Fermentation-Monitoring-System
Monitor fermentation using ESP32 and MQ-135 Sensor

## Functionalities
A back-end system which relies on IFTTT service, Google Sheets, Arduino IDE, MQ135 Air Quality Sensor, and ESP32 microcontroller. It relies on the MQ135 to track the level of CO2 produced by alcohol fermentation process. The CO2 concentration value is then forwarded to a webservice provided by IFTTT through HTTP requests. The IFTTT acts as an API that helps manage and forward the value given from the HTTP request and append a row of data including the time the data was taken, the date, and the CO2 concentration value to a Google Sheet.
