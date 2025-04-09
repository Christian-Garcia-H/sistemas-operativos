# 🧱 Estructura Técnica por Bloques – Windows 10

> Esta sección documenta cómo está compuesto internamente el sistema operativo Windows 10, usando una estructura modular para facilitar el análisis, diagnóstico y resolución de errores.

---

## 📑 Índice de Bloques

- [1. Hardware Base](#1-hardware-base)
- [2. Firmware (BIOS/UEFI)](#2-firmware-biosuefi)
- [3. Proceso de Arranque](#3-proceso-de-arranque)
- [4. Cargador del Sistema](#4-cargador-del-sistema)
- [5. Kernel Mode](#5-kernel-mode)
- [6. User Mode](#6-user-mode)
- [7. Gestores de Recursos](#7-gestores-de-recursos)
- [8. Subsistemas y Compatibilidad](#8-subsistemas-y-compatibilidad)
- [9. Interfaz Gráfica y UX](#9-interfaz-gráfica-y-ux)
- [10. Seguridad y Control](#10-seguridad-y-control)
- [11. Redes y Conectividad](#11-redes-y-conectividad)
- [12. Actualizaciones y Mantenimiento](#12-actualizaciones-y-mantenimiento)
- [13. Registro del Sistema](#13-registro-del-sistema)
- [14. Errores y Diagnóstico](#14-errores-y-diagnóstico)

---

## 1. Hardware Base

> Componentes físicos que soportan el sistema operativo.

- CPU, RAM, Disco duro/SSD
- GPU, placa madre, buses
- Dispositivos externos y periféricos

---

## 2. Firmware (BIOS/UEFI)

> Control inicial del hardware antes de que el sistema operativo tome control.

- POST (Power-On Self Test)
- Configuración de Secure Boot
- Fast Boot y prioridades de arranque

---

## 3. Proceso de Arranque

> Transición desde el encendido hasta la carga del sistema operativo.

- Gestor de arranque (Boot Manager)
- Archivo BCD (Boot Configuration Data)
- Elección de sistema operativo (dual boot, recovery, etc.)

---

## 4. Cargador del Sistema

> Encargado de inicializar el kernel y preparar el sistema operativo.

- Winload.exe
- NTOSKRNL.exe (núcleo del sistema)

---

## 5. Kernel Mode

> Parte más crítica del sistema, opera con privilegios máximos.

- HAL (Hardware Abstraction Layer)
- Drivers del sistema
- Servicios esenciales en bajo nivel

---

## 6. User Mode

> Donde se ejecutan las aplicaciones y servicios interactivos.

- Autenticación y Winlogon
- Explorador (explorer.exe)
- Servicios alojados en svchost.exe

---

## 7. Gestores de Recursos

> Administran el uso eficiente del hardware.

- Planificador de procesos
- Gestión de memoria
- Control de entrada/salida

---

## 8. Subsistemas y Compatibilidad

> Capas para correr software de otras plataformas o versiones.

- Subsistema Win32
- WSL (Windows Subsystem for Linux)
- Compatibilidad hacia atrás (modo de compatibilidad)

---

## 9. Interfaz Gráfica y UX

> Elementos visuales e interacción con el usuario.

- Shell de Windows
- Cortana, menú de inicio, barra de tareas
- Aplicaciones UWP y tradicionales (Win32)

---

## 10. Seguridad y Control

> Mecanismos para proteger el sistema y al usuario.

- UAC (User Account Control)
- Antivirus integrado (Defender)
- Cifrado (BitLocker), políticas de grupo

---

## 11. Redes y Conectividad

> Módulos que gestionan las comunicaciones.

- Configuración de adaptadores de red
- TCP/IP stack
- Firewall, DNS, VPN

---

## 12. Actualizaciones y Mantenimiento

> Mantención del sistema a través del tiempo.

- Windows Update
- Herramientas de reparación (DISM, SFC)
- Recovery Environment

---

## 13. Registro del Sistema

> Base de datos de configuraciones críticas.

- Estructura del registro (HKEY_CLASSES_ROOT, etc.)
- Configuraciones de usuario y sistema

---

## 14. Errores y Diagnóstico

> Localización y análisis de problemas.

- Visor de eventos
- STOP codes y BSOD
- Logs, herramientas de diagnóstico

---
