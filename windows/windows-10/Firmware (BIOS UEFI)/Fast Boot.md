## 🚀 ¿Qué es Fast Boot?

**Fast Boot (Arranque rápido)** es una opción en el BIOS/UEFI que reduce el tiempo que tarda el equipo en iniciar. Lo hace **saltándose o reduciendo ciertas comprobaciones del hardware** durante el proceso de POST (Power-On Self Test).

### 🔍 ¿Cómo acelera el arranque?

* Omite comprobaciones de memoria RAM.
* No busca dispositivos USB o CD/DVD si no son el dispositivo de arranque principal.
* Carga directamente desde el disco donde está instalado el sistema operativo.

### ⚠️ ¿Cuándo puede causar problemas?

* Si necesitas **arrancar desde una USB o DVD** (por ejemplo, para instalar un sistema operativo).
* Si has hecho cambios de hardware (como agregar RAM o cambiar el disco duro).
* Si necesitas entrar al BIOS con teclas como `F2` o `DEL` (algunas veces Fast Boot lo bloquea).

---

## 🔄 ¿Qué son las prioridades de arranque?

Las **prioridades de arranque (boot order)** determinan **en qué orden la computadora busca los dispositivos para arrancar un sistema operativo**.

### 📋 Ejemplo típico de orden de arranque:

1. USB Drive
2. DVD/CD-ROM
3. SSD o HDD
4. Red (PXE Boot)

### 📌 ¿Por qué es importante?

* Si quieres **instalar un sistema operativo desde una USB**, debes poner la USB como primer dispositivo de arranque.
* Si tienes múltiples discos con diferentes sistemas, puedes elegir desde cuál arrancar primero.

---

## 🛠️ ¿Cómo cambiar Fast Boot y el orden de arranque?

### 1. **Entrar al BIOS/UEFI**

* Enciende o reinicia la computadora.
* Pulsa repetidamente la tecla de acceso (`DEL`, `F2`, `F10`, `ESC`, o según el fabricante).

### 2. **Desactivar Fast Boot (opcional)**

* Busca la opción "Fast Boot" y ponla en **Disabled** si quieres tener control total del arranque.

### 3. **Cambiar la prioridad de arranque**

* Ve al menú **Boot** o **Boot Order**.
* Mueve el dispositivo deseado al primer lugar (por ejemplo, tu pendrive USB si vas a instalar Linux o Windows).
* Guarda y sal (`F10` generalmente).
