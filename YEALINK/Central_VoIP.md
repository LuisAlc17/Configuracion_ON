<div align="center"><img src="../STATIC/images/logo.png" width="200px"></img></div></br>

<h1>Central VoIP TrixBox</h1>

<span style="font-size:1.5em">Configuración servidor VoIP</span>

---


<!-- ## Accesorios usadas -->
| Tools|Descripción|
|-----------|---------------------|
| [:gear: ISO TrixBox ](https://drive.google.com/file/d/14bn-idMmm8p7bElqQWo7Dd2uuHNtz6nt/view?usp=drive_link)  | TrixBox solución de software basada en Asterisk, una plataforma de telefonía de código abierto. |
| [:gear: VirtualBOX ](https://download.virtualbox.org/virtualbox/7.0.12/VirtualBox-7.0.12-159484-Win.exe)  | VirtualBox es un software de virtualización desarrollado por Oracle. Permite crear y ejecutar máquinas virtuales en un entorno de escritorio |

---

## I. Instalación de VirtualBox

1. **Instalación de VirtualBox:**
    - Una vez descargado, ejecuta el archivo de instalación (generalmente un archivo .exe).
    - Se abrirá el asistente de instalación. Haz clic en "Siguiente" para avanzar en cada paso.
    - Lee y acepta los términos del acuerdo de licencia.
    - Elige las opciones de instalación deseadas (selección predeterminada es generalmente adecuada).
    - Haz clic en "Siguiente" y "Instalar" para comenzar la instalación.


2. **Configuración durante la instalación:**

    - Durante la instalación, es posible que se te pida instalar controladores adicionales. Acepta esto si se solicita.
    - Dependiendo de la configuración de tu sistema, es posible que se te solicite reiniciar la computadora después de la instalación.

3. **Finalización de la instalación:**

    - Una vez completada la instalación, podrás encontrar el acceso directo de VirtualBox en tu menú de inicio o en el escritorio.

---

## II. Crear una máquina virtual en VirtualBox:
1. **Abrir VirtualBox:**

    - Abre VirtualBox desde el menú de inicio o desde el acceso directo en tu escritorio si lo has creado durante la instalación.

2. **Crear una nueva máquina virtual:**

    - Haz clic en el botón "Nueva" en la barra de herramientas.

    - Se abrirá un asistente para crear una nueva máquina virtual.
4. **Asignar un nombre y seleccionar el sistema operativo:**

    - Ingresa un nombre para tu máquina virtual.

    - Selecciona el tipo de sistema operativo que deseas instalar (Windows, Linux, macOS, etc.).

    - Elige la versión correspondiente del sistema operativo si es necesario.

5. **Asignar memoria (RAM):**

    - Especifica la cantidad de memoria RAM que deseas asignar a la máquina virtual. Se recomienda asignar al menos 1 GB para sistemas operativos ligeros.

6. **Crear un disco duro virtual:**

    - Selecciona "Crear un disco duro virtual ahora" y haz clic en "Crear".
    - Elige el tipo de archivo de disco duro. La opción predeterminada (VDI) generalmente es adecuada.
    - Selecciona si el disco debe ser dinámico (crece a medida que se llena) o fijo (tamaño predefinido). El dinámico es más flexible pero puede ser menos eficiente en espacio.

7. **Tamaño del disco y ubicación:**

    - Define el tamaño del disco duro virtual. Puede ser cualquier tamaño que desees según la capacidad de tu disco duro físico.

    - Elige la ubicación donde se almacenará el disco virtual y haz clic en "Crear".

## III. Instalar el sistema operativo en la máquina virtual:

1. **Configurar la máquina virtual:**

    - Selecciona la máquina virtual recién creada y haz clic en "Configuración".
    - En la pestaña "Almacenamiento", selecciona la imagen ISO del sistema operativo que deseas instalar en el controlador de almacenamiento (CD/DVD).

2. **Iniciar la máquina virtual:**

    - Con la máquina virtual seleccionada, haz clic en "Iniciar" en la barra de herramientas.
    - La máquina virtual se iniciará desde la imagen ISO que has seleccionado, y podrás seguir las instrucciones para instalar el sistema operativo dentro de la máquina virtual.

3. Seguir el proceso de instalación:

    - Sigue las indicaciones de instalación del sistema operativo dentro de la máquina virtual, como lo harías en una computadora física.
