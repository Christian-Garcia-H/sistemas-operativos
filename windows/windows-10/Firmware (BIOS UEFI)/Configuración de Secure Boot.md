La **configuración de Secure Boot** (Arranque Seguro) se realiza desde el **BIOS o UEFI** de tu computadora. Secure Boot es una función de seguridad que **solo permite arrancar sistemas operativos firmados digitalmente por fabricantes confiables**, evitando la carga de malware o sistemas operativos no autorizados durante el arranque.

---

### 🔐 ¿Qué es Secure Boot?

* Verifica la **firma digital** del sistema operativo y de los controladores durante el arranque.
* Previene el **bootkit** y ciertos tipos de malware que atacan antes de que se cargue el sistema operativo.
* Es **requisito para ciertas funciones**, como **Windows 11**, que lo exige activado.

---

### ⚙️ Cómo configurar Secure Boot (paso a paso)

#### 1. **Entrar al BIOS/UEFI**

* Reinicia tu computadora.
* Pulsa repetidamente una tecla como `DEL`, `F2`, `F10`, `ESC` o `F12` justo después de encender (depende del fabricante).
* Accederás a la interfaz del BIOS/UEFI.

#### 2. **Localizar la opción "Secure Boot"**

* Ve a una pestaña llamada **"Boot"**, **"Security"** o **"Authentication"**.
* Busca la opción **"Secure Boot"**.

#### 3. **Habilitar o deshabilitar**

* Para **activar**, selecciona "Enabled".
* Si está desactivado y aparece en gris, tal vez necesites cambiar el modo de arranque de **Legacy/CSM** a **UEFI** primero.

#### 4. **Guardar y salir**

* Pulsa `F10` o selecciona "Save & Exit".
* El sistema se reiniciará con los cambios aplicados.
