## 📦 ¿Qué es el archivo BCD?

El **BCD (Boot Configuration Data)** es una base de datos de configuración de arranque usada por Windows desde Vista en adelante.
Reemplaza al antiguo archivo *boot.ini* de versiones anteriores.

---

## 🔍 ¿Para qué sirve?

* Almacena las opciones de arranque del sistema operativo.
* El **Windows Boot Manager** lo usa para saber:

  * Qué sistema operativo cargar.
  * Desde qué partición.
  * Qué parámetros usar.
  * Si debe arrancar en modo seguro o depuración.

---

## 📁 ¿Dónde se encuentra?

Generalmente, está en la partición reservada del sistema:

* En sistemas UEFI, dentro de la carpeta EFI en la partición del sistema.
* En sistemas BIOS/MBR, en la raíz de la partición reservada.

Esta partición suele estar oculta en el explorador de archivos.

---

## 🛠️ ¿Cómo se edita o repara?

* Con la herramienta de línea de comandos **bcdedit** para ver o modificar entradas.
* Con **bootrec** en modo recuperación para reparar el BCD.
* Con programas gráficos como **EasyBCD** para una edición más sencilla.

---

## ⚠️ ¿Qué errores pueden surgir?

Si el BCD está dañado o falta, puedes ver errores como:

* `Boot Configuration Data file is missing`
* `Un dispositivo requerido no está conectado o no puede ser accedido`
* `BOOTMGR is missing`
