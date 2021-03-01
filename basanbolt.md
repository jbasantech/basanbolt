## Raspberry Pi

### El sistema operativo
1. Descarga e instala [Ubuntu Server 64-bit](https://ubuntu.com/download/raspberry-pi)
2. Graba la imagen descargada en la tarjeta microSD siguiendo esta [guía](https://ubuntu.com/tutorials/how-to-install-ubuntu-on-your-raspberry-pi#1-overview)

## Conectar a la raspberrypi

# Acceso a través de una shell segura

Para conectarte remotamente averigua la IP de la Raspi introduciendo el siguiente comando en la Terminal de Linux:
```
arp -na | grep -i "dc:a6:32"
```
La Ip será algo parecido a esto:
- 192.168.X.XX

En la Terminal de Linux:
- ssh ubuntu@192.168.X.XX

Escribe **Sí** para confirmar
