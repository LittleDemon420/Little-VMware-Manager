<div align="center">
Little VMware Manager
CLI Manager para VMware Workstation

Herramienta de automatización, mantenimiento y administración para VMware Workstation en Windows.






<!-- Banner --> <!-- <img src="assets/banner.png" alt="Little VMware Manager Banner" width="100%"> --> </div>
📖 Descripción

Little VMware Manager es una utilidad de línea de comandos (CLI) diseñada para facilitar la administración diaria de VMware Workstation en sistemas Windows.

Centraliza la gestión de servicios, procesos y configuraciones de red en una única consola interactiva con un diseño de estilo retro/ASCII, evitando tener que utilizar services.msc, el Administrador de tareas o recordar comandos complejos.

Está pensado para administradores de sistemas, profesionales IT, estudiantes y usuarios habituales de VMware Workstation que buscan una forma rápida de gestionar su entorno de virtualización.

✨ Características
🚀 Inicio, parada y reinicio de todos los servicios de VMware.
⚡ Kill Switch para cerrar procesos bloqueados.
🌐 Gestión rápida de las redes virtuales de VMware.
🔄 Cambio entre inicio Manual y Automático de los servicios.
📊 Dashboard con información del sistema y estado de VMware.
🛠 Accesos directos a herramientas administrativas de Windows.
💻 Interfaz CLI ligera, rápida y totalmente interactiva.
🛠 Funciones Principales
Función	Descripción
Iniciar Servicios	Inicia todos los servicios de VMware Workstation.
Detener Servicios	Detiene correctamente todos los servicios.
Reiniciar Servicios	Reinicia completamente el entorno VMware.
Kill VMware	Finaliza inmediatamente todos los procesos relacionados con VMware.
Virtual Network Editor	Abre el editor de redes virtuales de VMware.
Reiniciar Adaptadores	Reinicia los adaptadores de red virtuales.
Modo Manual	Configura los servicios para iniciarse manualmente.
Modo Automático	Configura el inicio automático de los servicios.
Dashboard	Consulta información del sistema y del estado de VMware.
Herramientas del Sistema	Accesos rápidos a CMD, PowerShell y Administrador de tareas.
📊 Funciones Destacadas
🚀 Gestión de Servicios

Permite administrar completamente los servicios de VMware Workstation mediante acciones rápidas:

Iniciar servicios
Detener servicios
Reiniciar servicios
Finalizar procesos bloqueados
🌐 Gestión de Redes Virtuales

Facilita el mantenimiento de la conectividad de las máquinas virtuales.

Incluye herramientas para:

Abrir Virtual Network Editor
Reiniciar adaptadores VMware
Diagnóstico rápido de direcciones IP
Restaurar conectividad
⚙️ Automatización del Arranque

Permite cambiar rápidamente el comportamiento de VMware al iniciar Windows.

Inicio Manual (ahorro de recursos)
Inicio Automático (VMware siempre preparado)
📈 Dashboard del Sistema

Muestra información relevante en tiempo real como:

Usuario actual
Dirección IP
Versión del Kernel de Windows
Estado de los servicios VMware
Información general del sistema
🛠 Herramientas Integradas

Acceso directo a herramientas administrativas de Windows.

PowerShell (Administrador)
CMD (Administrador)
Administrador de tareas
📋 Requisitos
Requisito	Valor
Sistema Operativo	Windows 10 o superior
Software	VMware Workstation
Arquitectura	Windows 10.0+
Privilegios	Administrador
📂 Ruta Esperada

VMware Workstation debe encontrarse instalado en su ubicación predeterminada.

🚀 Instalación
Descarga Little VMware Manager.bat.
Colócalo en la ubicación que prefieras.
Haz clic derecho sobre el archivo.
Selecciona Ejecutar como administrador.
Comienza a administrar VMware desde el menú principal.
💻 Uso

Una vez iniciado aparecerá un menú interactivo desde el que podrás:

Gestionar los servicios de VMware.
Reiniciar procesos bloqueados.
Configurar el modo de inicio.
Administrar la red virtual.
Consultar el estado del sistema.
Abrir herramientas administrativas.

Todo ello desde una única ventana de consola.

⚠️ Advertencias

[!WARNING]
Este programa requiere permisos de Administrador para gestionar servicios de Windows, procesos y configuraciones de red.

Instalación

VMware Workstation debe instalarse utilizando las rutas predeterminadas del instalador.

Modificar la ubicación de instalación puede impedir que algunas funciones localicen correctamente los ejecutables.

Servicios

Si has detenido los servicios de VMware y, tras volver a iniciarlos, alguna máquina virtual no dispone de conexión a Internet:

Pulsa la opción 10 del menú.
No es necesario apagar la máquina virtual.
Icono personalizado

Windows no permite asignar un icono directamente a un archivo .bat.

Si deseas personalizar el icono:

Guarda el archivo .ico.
Crea un acceso directo al script.
Asigna el icono al acceso directo desde sus propiedades.
📌 Recomendaciones
Ejecuta siempre el programa como Administrador.
Mantén VMware Workstation actualizado.
Utiliza el modo Manual cuando no necesites virtualización para ahorrar recursos.
Reinicia los adaptadores de red si alguna máquina virtual pierde conectividad.
📸 Capturas
<img width="931" height="740" alt="Captura de pantalla 2026-06-19 221856" src="https://github.com/user-attachments/assets/008959cf-9a18-4409-9dde-37deecfb1512" />
📝 Changelog
Primera versión
Nuevo
Gestión centralizada de servicios VMware.
Dashboard con información del sistema.
Herramientas de red integradas.
Kill Switch para procesos bloqueados.
Automatización del modo de inicio.
Accesos directos a herramientas administrativas.
📄 Licencia

Este proyecto se distribuye con fines educativos y de automatización para usuarios de VMware Workstation.

<div align="center">

⭐ Si este proyecto te resulta útil, considera darle una estrella al repositorio.

</div>

