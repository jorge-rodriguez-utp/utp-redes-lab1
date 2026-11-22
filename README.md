# Laboratorio 1: Construcción de una Red Doméstica y Conectividad al ISP

**Institución:** Universidad Tecnológica de Panamá (UTP) — Facultad de Ingeniería en Sistemas Computacionales.  
**Curso:** Redes Informáticas I.
**Herramienta:** Cisco Packet Tracer.

## Topología y Direccionamiento
Simulación de una red doméstica (`PC-A` y `PC-B`) conectada a un router inalámbrico (`Wireless-Router-Hogar WRT300N`), módem de cable (`CABLE-PT`), nube del proveedor (`Nube-ISP`) y servidor web (`Servidor-Web`).

- **Segmento Privado (LAN):** Direccionamiento por DHCP en `192.168.0.x` (máscara `255.255.255.0`, puerta de enlace `192.168.0.1`).
- **Router Doméstico:** IP LAN `192.168.0.1`, servidor DHCP local, traducción de direcciones (NAT) y enlace WAN hacia el ISP.
- **Servidor Web:** IP estática `200.10.20.5` con servicio HTTP activo.

## Roles y Seguridad en la Red
- **Cliente vs. Servidor:** `PC-A` actúa como cliente solicitando contenido vía navegador web a `200.10.20.5`, mientras que `Servidor-Web` responde entregando la página configurada.
- **Función del Router:** Separa la red local privada del tráfico externo, asigna direcciones de forma automática y ayuda a proteger los equipos internos frente a la exposición directa en la red pública.
