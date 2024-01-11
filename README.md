<p align="center">
  <b>apiTwitch</b>
</p>


# Twitch Viewer Bot

Este proyecto consiste en un programa en Python que utiliza Selenium para automatizar la generación de vistas en streams de Twitch. El código está diseñado para abrir múltiples pestañas del navegador con proxies aleatorios, cada una reproduciendo el canal de Twitch proporcionado por el usuario. Además, ofrece la opción de configurar la calidad de la transmisión.

## Funciones Principales

1. **Configuración:**
    - `save_settings(twitch_username, set_160p)`: Guarda la configuración del usuario en 'settings.txt'.
    - `load_settings()`: Lee la configuración almacenada desde 'settings.txt'.

2. **Cambio de Calidad de Transmisión:**
    - `set_stream_quality(driver, quality)`: Utiliza Selenium para modificar la calidad del stream en el reproductor de Twitch.

3. **Ejecución Principal (`main`):**
    - `print_announcement()`: Muestra un anuncio obtenido desde un archivo en GitHub.
    - Solicita al usuario ingresar información si no hay configuraciones guardadas.
    - Abre múltiples pestañas con diferentes proxies para aumentar las vistas.
    - Espera a que el usuario presione Enter antes de cerrar el programa.

> [!CAUTION]
> Es importante señalar que el uso de este tipo de herramientas para inflar artificialmente las vistas en Twitch puede violar los términos de servicio de la plataforma y tener consecuencias negativas para el canal y el usuario. Se recomienda encarecidamente cumplir con las políticas y términos de servicio de Twitch.

## Instrucciones de Uso

1. **Requisitos:**
   - Asegúrate de tener [Python](https://www.python.org/) instalado.
   - Instala las dependencias ejecutando `pip install -r requirements.txt`.

2. **Ejecución:**
   - Ejecuta el programa usando `python twitch_viewer_bot.py`.
   - Sigue las instrucciones para ingresar tu nombre de canal y preferencias.

3. **Aviso Legal:**
   - Este proyecto está sujeto a derechos de autor y se proporciona bajo la licencia especificada en el código. Lee el aviso de derechos de autor y la licencia antes de utilizar el software.

---
> [!NOTE]
> El uso responsable y ético de esta herramienta es fundamental para evitar posibles consecuencias negativas.
