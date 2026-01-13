🎃 Terrores App - Guía de Instalación y Uso
Bienvenido a Terrores App, una aplicación desarrollada en JavaFX diseñada para ofrecer una experiencia de usuario fluida y profesional en entornos Windows. Este proyecto completa el ciclo profesional de desarrollo, desde la gestión con Maven hasta la creación de un instalador nativo.

📋 Requisitos del Sistema
Gracias al empaquetado de una máquina virtual de Java (JRE) dedicada, no es necesario que tengas Java instalado en tu equipo.

Sistema Operativo: Windows 10 o superior (64 bits).

Espacio en disco: Aproximadamente 150 MB (incluyendo el entorno de ejecución).

🚀 Instrucciones de Instalación
Para instalar la aplicación, sigue estos pasos:

Ejecuta el archivo Instalador_Terrores_v1.0.exe.

Sigue los pasos del asistente de instalación de Inno Setup.

Acepta los términos de la licencia y selecciona la ubicación de instalación (por defecto en C:\Program Files\TerroresApp).

Al finalizar, encontrarás un acceso directo con el icono de calabaza en tu escritorio.

🛠️ Detalles Técnicos para el Desarrollador
Si deseas revisar la estructura del proyecto, estos son los componentes principales:

JAR Ejecutable: Generado mediante maven-shade-plugin para asegurar la portabilidad de las librerías JavaFX.

Ejecutable (.exe): Creado con Launch4j, configurado en modo GUI para ocultar la consola de comandos.

JRE Embebido: El ejecutable utiliza la carpeta runtime interna para arrancar, eliminando dependencias externas.

🗑️ Desinstalación
La aplicación puede eliminarse de forma segura y completa:

Ve a Configuración de Windows > Aplicaciones.

Busca "Terrores App" y selecciona Desinstalar.

El proceso eliminará todos los archivos y accesos directos sin dejar rastros en el sistema.
