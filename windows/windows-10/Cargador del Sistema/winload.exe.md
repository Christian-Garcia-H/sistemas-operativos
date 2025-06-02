## ⚙️ ¿Qué es Winload.exe?

**Winload.exe** es un componente fundamental del proceso de arranque de Windows. Es el **cargador del sistema operativo** que se ejecuta justo después del gestor de arranque (`bootmgr`) para iniciar el núcleo (kernel) de Windows y los controladores esenciales.

---

## 🔍 ¿Qué hace exactamente?

* Carga el **núcleo de Windows (ntoskrnl.exe)** en memoria.
* Carga los **controladores básicos necesarios para iniciar el sistema** (drivers de disco, sistema de archivos, etc.).
* Prepara el entorno para que el sistema operativo pueda continuar su arranque.

---

## 🛠️ ¿Dónde está ubicado?

Se encuentra en la carpeta **\Windows\System32** del disco donde está instalado Windows.

---

## ⚠️ ¿Qué pasa si Winload.exe falla o está dañado?

Si Winload.exe está corrupto, falta o no puede ejecutarse, puedes ver errores como:

* `0xc000000f: The selected entry could not be loaded because the application is missing or corrupt`
* `Winload.exe is missing or corrupt`

Estos errores impiden que Windows arranque correctamente.
