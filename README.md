# Cybersecurity Lab

Mi laboratorio personal de aprendizaje enfocado en:

- Networking
- Linux
- Python
- Cybersecurity
- Pentesting
- Red Team

## Actualmente estudiando

- Cisco CCNA v7
  - ITN
  - SRWE
  - ENSA
- Debian Linux
- Python

## Objetivo

Construir una base sólida en redes, sistemas y seguridad
para posteriormente especializarme en Red Team.

## Laboratorios

## Práctica 01 — Auditoría de Permisos y Hardening en Linux (`chmod`)
- **Objetivo:** Aplicar el principio de menor privilegio a archivos sensibles.
- **Conceptos:** Permisos POSIX, propietario, grupo y otros.
- **Comandos utilizados:** `chmod 600 credenciales.txt`, `ls -l`
- **Aprendizaje:** Restringir el acceso para evitar que usuarios no autorizados o procesos secundarios lean credenciales del sistema.

## Práctica 02 — Sockets TCP y Servidor HTTP Local
- **Objetivo:** Iniciar un servicio web en *loopback* e inspeccionar su estado en la tabla de sockets.
- **Conceptos:** Sockets TCP, interfaz `127.0.0.1`, inspección con `ss`.
- **Comandos utilizados:** `python -m http.server 8000 --bind 127.0.0.1`, `ss -tuln`, `curl`
- **Aprendizaje:** Identificar la diferencia entre servicios expuestos localmente y servicios en escucha externa, interpretando los estados `LISTEN` en TCP.

