Le système utilise un capteur de température et d'humidité DHT11, un capteur de gaz, un capteur de feu et un buzzer pour alerter en cas de détection d'incendie. Les données des capteurs sont affichées sur un écran LCD et sont envoyées à Firebase, permettant un accès à distance aux informations.

Bibliothèques Utilisées :

Wire.h : Gère la communication I2C avec l'écran LCD.
LiquidCrystal_I2C.h : Contrôle l'écran LCD I2C.
DHT.h : Gère la lecture du capteur DHT11 pour la température et l'humidité.
WiFi.h : Permet la connexion au réseau WiFi.
FirebaseESP32.h : Fournit une interface pour interagir avec Firebase à partir de l'ESP32.*

Définition des Périphériques :

Écran LCD (I2C) : Affiche les valeurs des capteurs.
Capteur DHT11 : Mesure la température et l'humidité.
Capteur de gaz : Mesure la concentration de gaz dans l'air.
Capteur de feu : Détecte la présence d'incendie.
Buzzer : Émet une alarme sonore en cas de détection de feu.
