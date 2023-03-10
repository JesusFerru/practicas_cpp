# practicas_cpp 
Luis Jesús Ferrufino Burgos 


Repositorio donde se subirán ejercicios de ejemplo de cpp (conceptos básicos, estructura de datos, POO).
Se llevará a cabo los ejercicios prácticos de la ayudantía de la materia de Estructura de Datos.

Para usar C++ en VSC necesitaremos lo siguiente:

1) Visual Studio Code (Editor de texto/código fácil e intuitivo)
        
        * Si ya tienes otro editor (Dev++, CodeBlocks, VS2022, c++ online, etc), no hay ningun problema 
        ya que igual podrás usarlo para los programas que vamos a realizar.

2) Compilador g++ (Es un conmpilador, parte del conjunto de herramienta de GNU Compiler Collection "GCC".)

        * El uso de g++ permite a los programadores compilar sus programas C++ en código de máquina ejecutable, 
        que puede ser ejecutado en cualquier sistema operativo compatible con el compilador. 

        * Además, g++ ofrece muchas características avanzadas, como optimización de código, compatibilidad con 
        múltiples plataformas y una amplia variedad de opciones de línea de comandos para personalizar el proceso de compilación.

Pasos para instalar g++:

1. Verifica que no tengas g++ instalado en tu sistema. Puedes hacerlo escribiendo el comando g++ --version en la terminal y presionando Enter. Si g++ no está instalado, verás un mensaje de error.
    g++ --version

2. Si no tienes g++ instalado, instálalo en tu sistema. La forma de hacerlo varía dependiendo del sistema operativo que estés utilizando. Aquí te mostramos cómo hacerlo en algunos sistemas:

a) En Ubuntu y otras distribuciones de Linux basadas en Debian, puedes instalar g++ utilizando el comando sudo apt-get install g++.

b) En macOS, puedes instalar g++ utilizando Homebrew. Para hacerlo, primero instala Homebrew en tu sistema siguiendo las instrucciones en https://brew.sh/. Luego, ejecuta el comando brew install gcc.

c) En Windows, puedes instalar g++ como parte del paquete MinGW. Para hacerlo, sigue estos pasos:

    * Descarga el instalador de MinGW desde https://osdn.net/projects/mingw/releases/.
    * Ejecuta el instalador y sigue las instrucciones en pantalla para instalar MinGW.
    * En la sección "Select components", asegúrate de seleccionar "mingw32-gcc-g++" en la lista de paquetes a instalar.
    * En la sección "Installation folder", asegúrate de que la ruta de instalación no contenga espacios en blanco. Por ejemplo, en lugar de "C:\Program Files\MinGW", elige "C:\MinGW".
    * Completa la instalación.
    * Abre Visual Studio Code y abre la terminal en la parte inferior de la ventana.

3. Verifica que g++ esté disponible en la terminal. Puedes hacerlo escribiendo g++ --version en la terminal y presionando Enter. Si g++ está instalado correctamente, verás la versión instalada en la pantalla.

4. Ahora puedes compilar y ejecutar programas .cpp en Visual Studio Code utilizando g++. Primero revisas que te encuentres en la carpeta donde está guardado tu programa de c++.

Los comandos que necesitarás para hacerlo son 2 y son los siguientes:

    g++ -o ejemplo ejemplo.cpp           
<Este comando compilara el programa ".cpp" y creará una versión ejecutable para probarlo en la terminal de vsc>

    ./ejemplo                            
<Con este comando ejecutas el ".exe" creado a partir del anterior comando, ya con eso puedes interactuar con tu programa creado>

