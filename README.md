# 🖥️ NOC Lab Monitoring

Laboratorio práctico de monitoreo y troubleshooting orientado a simular un entorno real de Network Operations Center (NOC).

## 🎯 Objetivo

Diseñar e implementar un entorno de monitoreo capaz de:

* Supervisar recursos de sistemas (CPU, RAM, disco, red)
* Generar alertas ante fallos
* Visualizar métricas en dashboards
* Documentar incidentes y soluciones

## Arquitectura del laboratorio

* 1 VM Servidor (Ubuntu Server)
* 1 VM Cliente Linux
* 1 VM Cliente Windows (LTSC)
* Red en modo Bridge
  
## Tecnologías principales:

* [Oracle VirtualBox](https://download.virtualbox.org/virtualbox/7.0.16/)
* [Zabbix](https://www.zabbix.com/la/)
* [Grafana](https://grafana.com/)

## 📚 Contenido del repositorio

### Instalación

* [Instalación de VirtualBox](/01-Instalacion/virtualbox-install.md)
* [Instalación de Ubuntu Server](/02-VMs/VM-Ubuntu-NOC-Server.md)
* Configuración inicial del sistema

### Máquinas Virtuales

* [NOC Server](/02-VMs/VM-Ubuntu-NOC-Server.md)
* Linux Client
* Windows LTSC

### Monitoreo

* Instalación de Zabbix
* Configuración de hosts y templates
* Monitoreo activo

### Visualización

* Integración con Grafana
* Creación de dashboards

### Incidentes

* [Kernel Panic en VirtualBox](/05-Incidentes/virtualbox-kernel-panic.md)
* Fallos de agente Zabbix
* Problemas de red

## Documentación destacada

* Instalación de VirtualBox
* Instalación de Ubuntu Server
* Incidente: Kernel Panic

## Tecnologías utilizadas

* [Linux Mint 22.2](https://linuxmint.com/edition.php?id=322)
* [Oracle VirtualBox 7.0.16]((https://download.virtualbox.org/virtualbox/7.0.16/))
* [Ubuntu Server 24.04.4 LTS](https://ubuntu.com/download/server)
* [Zabbix](https://www.zabbix.com/la/)
* [Grafana](https://grafana.com/)

## Estado del proyecto

* En desarrollo activo

✔ Monitoreo funcional en Zabbix
🔄 Dashboards en Grafana en construcción
