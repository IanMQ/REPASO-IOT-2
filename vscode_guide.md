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

Puedes ver ModestIOT template 1:
https://wokwi.com/projects/467832317857764353