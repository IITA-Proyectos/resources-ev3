# Guía para actualizar/flashear firmware EV3

## Herramientas Incluidas

- EV3 Lab Software versión 1.4.5
- Firmware V1.10E (en la carpeta *firmwares* encontrarás versiones anteriores a esta)
- Navegador web (preferentemente Chrome)

## Pasos a seguir

### Método actualizado (vía web)

1. **Actualizar con EV3 Device Manager:**
    - **Pasos:**
      1. Ve a la [página de EV3 Device Manager](https://ev3manager.education.lego.com/#). Visita la página preferiblemente con Google Chrome, pero puedes usar Edge, Brave, etc.
      2. Haz clic en el botón **"Available Bricks (0)"** y espera a que aparezca un diálogo para descargar e instalar el **EV3 Device Manager** en tu computadora. 
      3. Descarga e instala el **EV3 Device Manager** (dejamos en el repositorio el ejecutable compatible con Windows).
      3. Conecta tu EV3 mediante un cable USB.
      4. Verifica la versión del firmware que quieres instalar y haz click en **Update Firmware**.
      5. Si la actualización no inicia o falla, repite los pasos anteriores.

>El programa se ejecutará en segundo plano y se comunicará con la página web para actualizar el firmware.

### Método antiguo (Usando EV3 Lab Software 1.4.5)

1. **Descargar e instalar el EV3 Lab Software 1.4.5:**
    - [Descarga el EV3 Lab Software 1.4.5](https://education.lego.com/en-us/downloads/retiredproducts/mindstorms-ev3-lab/software/)
    - Instala el software en tu computadora (Windows 7, 8, 10, 11).

2. **Actualizar el firmware manualmente:**
    - Descarga el [firmware V1.10E](#).
    - Conecta tu EV3 a la computadora mediante USB.
    - Abre EV3 Lab Software y selecciona `Herramientas > Actualización de firmware`.
    - En la ventana emergente, haz clic en "Mostrar detalles".
    - Haz clic en "Explorar" y selecciona el archivo `firmware_v1.10E.bin` (o una versión anterior si lo deseas).
    - Haz clic en "Actualizar firmware". El proceso comenzará Preparando el ladrillo y luego Descargará el software. Al terminar, se reiniciará.
