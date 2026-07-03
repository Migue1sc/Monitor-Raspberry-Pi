# Monitor-Raspberry-Pi
Este sistema se encarga de monitorear espacios de trabajo por medio de sensores conectados a la raspberry. Los datos obtenidos por los sensores son almacenados en una base de datos para mostrarlos al usuario en gráficas interactivas por medio una págna web, esto con el fin de que el usuario pueda tomar decisiones para mejorar su entorno mientras trabaja.

## Hardware
### Raspberry Pi:
Se utilizó una Raspberry Pi 5 como dispositivo central del sistema, debido a su capacidad de procesamiento, conectividad y compatibilidad con múltiples sensores. Este dispositivo fue el encargado de ejecutar los scripts de lectura de datos, gestionar la comunicación con la base de datos y permitir el acceso a la interfaz web.
<img width="500" height="280" alt="imagen" src="https://github.com/user-attachments/assets/e5a972c4-0313-4cc6-8a47-884b31c1b2f5" />

### Sensor DHT11:
Sensor de temperatura y humedad DHT11, utilizado para medir las condiciones térmicas del entorno y analizar sus variaciones a lo largo del tiempo. 
<img width="386" height="386" alt="imagen" src="https://github.com/user-attachments/assets/92043dd0-a76b-4774-9bdd-d47b5d56a11e" />

### Sensor I2C Decibel Sound Level Meter Module:
 Sensor de sonido I2C Decibel Sound Level Meter Module, empleado para la medición del nivel de ruido ambiental en decibeles dentro del espacio de trabajo
