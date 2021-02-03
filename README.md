# 3

# Objetivo
O projeto tem por objetivo, utilizar um Arduino Uno e Sensor Magnético para monitorar a porta de um Rack de Rede, demonstrando se ela está ABERTO ou FECHADO; posteriormente, deve-se enviar essa informação via Internet utilizando o protocolo MQTT (Message Queuing Telemetry Transport) para um servidor MQTT hospedado na Amazon Web Service (AWS) e exibir a informação em um cliente MQTT (MQTT Dash) instalado em um Smartphone, conforme imagem abaixo.


![imagem2](https://camo.githubusercontent.com/7beef2d4780d87a603d7de49b2da0467c8537dff96575b628a04bd4010ebb1cc/68747470733a2f2f692e696d6775722e636f6d2f4d576870586b562e706e67)

Foram utilizadas as seguintes bibliotecas:
UIPEthernet (conexão do ENC28J60 com o Arduino)
PubSubClient (cliente MQTT para o Arduino)

## Material
Arduino Uno

Módulo Ethernet (ENC28J60)

Sensor Magnético (MC-38)

Jumpers

## Circuito
![imagem1](https://camo.githubusercontent.com/ad1da211b35b60b23fb095a64e76dc6504d0c3229e853bd82a69a4d5d27bbb88/68747470733a2f2f692e696d6775722e636f6d2f594947477453472e706e67) 

Autor: Damião Costa de Oliveira
