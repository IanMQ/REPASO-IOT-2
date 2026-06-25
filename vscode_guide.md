Necesitas:
Wokwi-extension
platformIO-extension

Crea un proyecto con platformIO, desde la extension, considera esto
    
    [env:esp32doit-devkit-v1]
    platform = espressif32
    board = esp32doit-devkit-v1
    framework = arduino

Para probar un proyecto de wokwi necesitaras un wokwi.toml  

    # Wokwi Configuration File
    # Reference: https://docs.wokwi.com/vscode/project-config
    [wokwi]
    version = 1
    firmware = '.pio/build/esp32doit-devkit-v1/firmware.bin'
    elf = '.pio/build/esp32doit-devkit-v1/firmware.elf'

Comando para buildear pio run

Puedes ver ModestIOT template 1, sin usar ModestIOT lib:
https://wokwi.com/projects/467832317857764353


como puedo hacer para que te centres en una sola carpeta, te puedo indicar con cd o como seria, dime como hacerlo en mac y windows?
+ Thought: Explaining folder navigation 
Sí. Lo mejor es darme la ruta exacta de la carpeta.
- En esta conversación: dime algo como trabaja en /Users/tuusuario/proyecto o trabaja en C:\Users\TuUsuario\proyecto.
- No hace falta que me mandes un cd; con la ruta basta.
- Si quieres, también puedes decirme “solo revisa esa carpeta” y yo me limito a ella.
En tu terminal:
macOS:
cd /Users/tuusuario/proyecto
Windows PowerShell:
cd C:\Users\TuUsuario\proyecto
Si quieres, te puedo decir también cómo pasarme una carpeta concreta para que yo la use en una tarea aquí mismo.