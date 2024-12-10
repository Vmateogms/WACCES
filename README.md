# WACCES
Pequeño script en batch files para hacer ataques por fuerza bruta a un wifi utilizando un diccionario. 


## Características
Detección de interfaces WiFi: Identifica todas las interfaces WiFi disponibles en el sistema y permite seleccionar la deseada.
Escaneo de redes WiFi: Lista las redes WiFi disponibles junto con su fuerza de señal.
Gestión de interfaces: Conexión y desconexión de redes según la selección del usuario.
Ataque de fuerza bruta: Prueba contraseñas de una lista para intentar acceder a redes WiFi.

## Requisitos
Sistema Operativo: Windows.
Permisos de Administrador: Es necesario ejecutar el script con permisos de administrador para usar comandos como netsh.
Archivos necesarios:
    passlist.txt: Archivo con las contraseñas a probar.
    colorchar.exe: Programa auxiliar para mejorar la visualización en la consola.
    importwifi.xml: Archivo base para generar configuraciones temporales.
Codificación UTF-8: El script utiliza chcp 65001 para asegurar la correcta visualización de caracteres.
## Uso
Ejecución:
Abrir consola: Abre una consola (cmd) con permisos de administrador.
Ejecutar el script: Usa el comando wifiacc.bat para iniciar el programa.
Seleccionar una opción:
  help: Ver las instrucciones y comandos disponibles.
  interface: Seleccionar la interfaz WiFi para operar.
  wifiscan: Escanear las redes WiFi disponibles.
  attack: Iniciar un ataque de fuerza bruta en la red seleccionada.

# Advertencias
Uso Responsable: Este script debe usarse exclusivamente para pruebas de seguridad en redes WiFi de tu propiedad o con autorización explícita.
Limitaciones: La efectividad del ataque de fuerza bruta depende de la calidad de la lista de contraseñas y la fuerza de la señal WiFi.
Hardware Recomendado: Se sugiere el uso de una antena WiFi USB de buena calidad para mejorar la detección de redes.
