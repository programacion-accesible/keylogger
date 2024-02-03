# keylogger

Gerardo Kessler <gera.ar@yahoo.com>

Pequeño módulo global que permite obtener las estadísticas de las teclas alfanuméricas pulsadas por el usuario.

Los gestos pueden asignarse desde el apartado gestos de entrada, categoría keylogger

Se utiliza la plantilla de complementos desde el repositorio [addon template](https://github.com/nvdaaddons/AddonTemplate)

Hay que modificar el archivo buildVars.py con los datos como está especificado en el readme del repositorio de la plantilla.

Para complilar el complemento es necesario contar con las librerías de python scons y markdown. NVDA utiliza python 3.7.9 en la versión 2023 de NVDA, y python 3.11.6 en la versión 2024

Es conveniente asimismo agregar la ruta de la carpeta bin del programa de traducciones poedit previamente instalado a las variables de entorno, por ejemplo; C:\Program Files (x86)\Poedit\GettextTools\bin

El comando scons aplicado en la raíz de este repositorio genera el archivo compilado en formato nvda-addon
