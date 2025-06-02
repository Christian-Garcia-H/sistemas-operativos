### 1. **Gestor de arranque del sistema operativo (Boot Manager)**

Este es un **programa ubicado en el disco duro**, que se **carga desde el firmware** para iniciar un sistema operativo.

🔹 Ejemplos:

* **Windows Boot Manager** (`bootmgr`)
* **GRUB** (en sistemas Linux)
* **systemd-boot** o **rEFInd** (en sistemas modernos con UEFI)

Este gestor permite:

* Elegir entre varios sistemas operativos (dual boot).
* Seleccionar modos de recuperación.
* Pasar parámetros al kernel.

---

### 2. **Boot Menu del firmware (menú de arranque temporal)**

Cuando presionas una tecla como `F12`, `ESC`, o `F9` al encender el equipo, accedes al:

🟦 **Boot Menu del firmware**

Este te permite:

* Seleccionar **desde qué dispositivo arrancar** (USB, disco, red, etc.).
* Es una función del firmware UEFI/BIOS, **no un gestor de arranque real**, pero **sí controla qué gestor se ejecutará**.
