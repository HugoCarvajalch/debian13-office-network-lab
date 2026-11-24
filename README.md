
# Simulación de un entorno de red de oficina utilizando Debian 13

## Descripción del proyecto

Este proyecto consiste en diseñar, configurar y simular una infraestructura de red de oficina mediante máquinas virtuales, utilizando Debian 13 como sistema operativo para los routers y Windows 11 como equipos cliente.

El laboratorio permite implementar servicios de asignación dinámica de direcciones IP, enrutamiento entre diferentes redes y conectividad a Internet.

## Objetivo del proyecto

Implementar un entorno de red virtualizado que permita interconectar diferentes segmentos de red mediante routers Debian 13, proporcionando conectividad entre equipos Windows 11 y acceso a Internet.

## Tecnologías utilizadas

- Debian 13.
- Windows 11.
- VMware Workstation.
- Kea DHCPv4 Server.
- NFTables.
- NAT.
- Redes virtuales VMnet.

## Alcance del proyecto

El proyecto contempla las siguientes operaciones:

1. Creación y configuración de los routers virtuales RouEx4, RouEx5 y RouEx6.
2. Configuración del servicio Kea DHCPv4 para la asignación dinámica de direcciones IP.
3. Configuración de máquinas virtuales Windows 11 como clientes de red.
4. Implementación del enrutamiento mediante NFTables.
5. Configuración de la conectividad entre diferentes segmentos de red.
6. Comprobación del acceso a Internet desde los equipos cliente.
7. Verificación de la comunicación entre los tres equipos Windows 11.

## Configuración DHCP

Rango de direcciones IP configurado:

- Dirección inicial: `192.168.100.201`
- Dirección final: `192.168.100.230`

## Autor

Hugo Carvajal

## Estado del proyecto

Proyecto completado.

