# Laboratorio #1: Fundamentos de Redes y Topologías Seguras (UTP)

Repositorio académico de soporte para la asignatura de **Redes de Datos / Sistemas Colaborativos** de la Licenciatura en Ciberseguridad — **Universidad Tecnológica de Panamá (UTP)**.

## 1. Propósito del Laboratorio
Diseñar, simular y verificar la conectividad básica de una red local (LAN) aplicando el modelo de referencia **OSI / TCP-IP**, direccionamiento IPv4 y buenas prácticas iniciales de segmentación y control de acceso.

## 2. Topología de Red Implementada
- **Dispositivos Finales:** 2 estaciones de trabajo (PC-01, PC-02) y 1 servidor local.
- **Dispositivos Intermediarios:** 1 Switch Capa 2 (2960) y 1 Router (ISR 4331).
- **Esquema de Direccionamiento:** Subred `192.168.10.0/24` (Gateway predeterminado: `192.168.10.1`).
- **Herramienta de Simulación:** Cisco Packet Tracer.

## 3. Procedimiento Realizado
1. **Levantamiento físico y lógico:** Interconexión de equipos mediante cableado directo UTP (Copper Straight-Through) en el entorno de simulación.
2. **Configuración de interfaces:** Asignación de direcciones IP estáticas, máscaras de subred y puerta de enlace en los hosts y la interfaz GigabitEthernet del router.
3. **Pruebas de conectividad:** Verificación de comunicación extremo a extremo mediante comandos `ping` y `tracert` (ICMP).
4. **Análisis de tráfico:** Inspección de tramas Ethernet y paquetes ARP/ICMP en modo simulación para validar el encapsulamiento de datos.

## 4. Licencia
Este proyecto académico se distribuye bajo los términos de la **Licencia MIT** incluida en este repositorio.
