# FIAP CHALLENGE 2024 - Fórmula E & TECH Mahindra 
![image](https://github.com/user-attachments/assets/722301ee-6d7f-4837-9187-7def48d1167b)

## Engenharia de Software - 2º SEMESTRE  
### Disciplina:  Edge Computing

#### Integrantes do grupo:
- Léo Masago RM:557768
- Herbert Souza RM: 555701
- Alexandre Assis RM: 558927
- Eduardo Tomazela RM: 556807
- Gustavo Ramalho RM: 554582


## 💡 Projeto: Controle de Motor via MQTT
Este projeto implementa um sistema de controle de motor utilizando a comunicação MQTT. Um dispositivo Arduino se conecta a uma rede Wi-Fi e se comunica com um broker MQTT. O usuário pode enviar comandos de direção e velocidade para o motor através do broker MQTT, e o Arduino controla o motor de acordo com os comandos recebidos.

#### Hardware
- Arduino (modelo específico)
- Motor DC
- Ponte H (driver de motor)
- Módulo Wi-Fi (e.g., ESP8266, ESP32)

#### Software
- Arduino IDE
- Biblioteca PubSubClient
- Biblioteca WiFi

#### Instalação
- Clone este repositório.
- Instale as bibliotecas PubSubClient e WiFi no Arduino IDE.
- Carregue o código no Arduino.

#### Configuração
- Rede Wi-Fi: Modifique os valores de default_SSID e default_PASSWORD para corresponder à sua rede Wi-Fi.
- Broker MQTT: Altere default_BROKER_MQTT e default_BROKER_PORT se necessário.
- Tópicos MQTT: Customize os tópicos de publicação e assinatura conforme sua necessidade.


