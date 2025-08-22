# dmz-lab
# 🛡️ Laboratorio DMZ - Cisco Packet Tracer

## 🎯 Objetivo del laboratorio

Diseñar e implementar una arquitectura de red segmentada que incluya una zona desmilitarizada (DMZ) utilizando Cisco Packet Tracer. El propósito es aplicar técnicas de traducción de direcciones (NAT) y listas de control de acceso (ACLs) para gestionar el tráfico entre la red interna (LAN), la DMZ y la red externa, simulando un entorno empresarial seguro y funcional.

## 🧩 Descripción de la topología

La topología está compuesta por tres segmentos de red conectados a un router central (Router_FW):

- **LAN Interna (Verde):** Red privada con acceso completo a la DMZ.
- **DMZ (Naranja):** Servidor web accesible desde la red externa mediante NAT estático.
- **Red Externa (Amarillo):** Simulación de Internet con acceso limitado a la DMZ.

Se han configurado ACLs para restringir el tráfico entre zonas y se ha implementado NAT para permitir el acceso externo al servidor DMZ sin comprometer la seguridad de la LAN.

## 📁 Contenido del repositorio
Objetivo del laboratorio

Implementar una arquitectura de red segmentada con una zona desmilitarizada (DMZ) utilizando Cisco Packet Tracer. Se aplican técnicas de NAT y ACLs para controlar el tráfico entre la LAN interna, la DMZ y la red externa, simulando un entorno empresarial seguro.

Descripción de la topología

La red está compuesta por tres zonas conectadas a un router central:

LAN Interna (Verde): Recursos internos

DMZ (Naranja): Servidor accesible desde el exterior

Red Externa (Amarillo): Simulación de Internet

Contenido del repositorio

informe/Informe_DMZ_Laboratorio.md: Informe técnico completo del laboratorio

evidencias/: Capturas de pantalla de la topología, configuraciones y pruebas realizadas

PacketTracer_DMZ.pkt: Archivo final del laboratorio en Cisco Packet Tracer

README.md: Descripción general del proyecto


## 👨‍🎓 Autor

**Carlos Navarro**  
**4Geeks Academy**  



