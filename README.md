<div align="center">

# Little VMware Manager V8🛠️⚡

### **CLI Manager para VMware Workstation**

*Herramienta de automatización, mantenimiento y administración para VMware Workstation en Windows.*

![Windows](https://img.shields.io/badge/Windows-10%2B-0078D6?style=for-the-badge&logo=windows)
![VMware](https://img.shields.io/badge/VMware-Workstation-607078?style=for-the-badge)
![Batch](https://img.shields.io/badge/Language-Batch-black?style=for-the-badge)

<!-- Banner -->
<!-- <img src="assets/banner.png" alt="Little VMware Manager Banner" width="100%"> -->

</div>

---

# 📖 Descripción

**Little VMware Manager** es una herramienta de interfaz de línea de comandos (CLI) ligera e interactiva diseñada para entornos **Windows**.

Su objetivo es centralizar, automatizar y simplificar la administración de **VMware Workstation**, permitiendo gestionar servicios, procesos y configuraciones de red desde una única consola con una interfaz de estilo **retro/ASCII**.

Olvídate de navegar por **services.msc**, abrir múltiples herramientas del sistema o recordar comandos complejos. Todo el control de VMware está disponible desde un único panel de administración.

Está pensado para administradores de sistemas, profesionales IT, estudiantes y cualquier usuario que utilice VMware Workstation de forma habitual.

---

# ✨ Características

- 🚀 Inicio, parada y reinicio de todos los servicios de VMware.
- ⚡ Kill Switch para finalizar procesos bloqueados.
- 🌐 Gestión rápida de las redes virtuales.
- 🔄 Cambio entre inicio Manual y Automático de los servicios.
- 📊 Dashboard con información del sistema en tiempo real.
- 🛠 Accesos directos a herramientas administrativas de Windows.
- 💻 Interfaz CLI ligera, rápida y totalmente interactiva.

---

# 🛠 Funciones Principales

| Función | Descripción |
|---------|-------------|
| **Iniciar Servicios** | Inicia todos los servicios de VMware Workstation. |
| **Detener Servicios** | Detiene correctamente todos los servicios. |
| **Reiniciar Servicios** | Reinicia completamente el entorno VMware. |
| **Kill VMware** | Finaliza inmediatamente todos los procesos relacionados con VMware. |
| **Virtual Network Editor** | Abre el editor de redes virtuales. |
| **Reiniciar Adaptadores** | Reinicia los adaptadores de red VMware. |
| **Modo Manual** | Configura los servicios para iniciarse manualmente. |
| **Modo Automático** | Configura los servicios para iniciarse automáticamente con Windows. |
| **Dashboard** | Muestra información del sistema y del estado de VMware. |
| **Herramientas del Sistema** | Accesos rápidos a CMD, PowerShell y Administrador de tareas. |

---

# 📊 Funciones Destacadas

## 🚀 Gestión de Servicios

Administra completamente VMware Workstation mediante acciones rápidas:

- Iniciar servicios
- Detener servicios
- Reiniciar servicios
- Finalizar procesos bloqueados

---

## 🌐 Gestión de Redes Virtuales

Incluye herramientas para mantener la conectividad de las máquinas virtuales.

- Apertura del Virtual Network Editor.
- Reinicio de adaptadores VMware.
- Diagnóstico rápido de IP.
- Restauración de la conectividad.

---

## ⚙️ Automatización del Arranque

Permite cambiar rápidamente el comportamiento de VMware al iniciar Windows.

- Inicio Manual (ahorro de recursos).
- Inicio Automático (VMware siempre listo).

---

## 📈 Dashboard del Sistema

Consulta información relevante en tiempo real.

- Usuario actual.
- Dirección IP.
- Versión del Kernel de Windows.
- Estado de los servicios VMware.
- Información general del sistema.

---

## 🛠 Herramientas Integradas

Accesos rápidos a utilidades administrativas.

- PowerShell (Administrador).
- CMD (Administrador).
- Administrador de tareas.

---

# 📋 Requisitos

| Requisito | Valor |
|-----------|-------|
| Sistema Operativo | Windows 10 o superior |
| Software | VMware Workstation |
| Arquitectura | x64 |
| Privilegios | Administrador |

---

# 📂 Ruta Esperada

VMware Workstation debe encontrarse instalado utilizando la ruta predeterminada del instalador.

---

# 🚀 Instalación

1. Descarga **Little VMware Manager.bat**.
2. Colócalo donde prefieras.
3. Haz clic derecho sobre el archivo.
4. Selecciona **Ejecutar como administrador**.
5. Comienza a administrar VMware desde el menú principal.

---

# 💻 Uso

Una vez iniciado aparecerá un menú interactivo desde el que podrás:

- Gestionar los servicios de VMware.
- Reiniciar procesos bloqueados.
- Configurar el modo de inicio.
- Administrar la red virtual.
- Consultar el estado del sistema.
- Abrir herramientas administrativas.

Todo ello desde una única ventana de consola.

---
<br>
<br>
 <h1>⚠️ Advertencias</h1>

> [!WARNING⚠️]
> **Este programa requiere permisos de Administrador** para gestionar servicios de Windows, procesos y configuraciones de red.

### ⚠️Conectividad de red

Si has detenido los servicios de VMware y, tras volver a iniciarlos, alguna máquina virtual no dispone de conexión a Internet:

- Pulsa la **opción 10** del menú.
- No es necesario apagar la máquina virtual.

### ⚠️Instalación

VMware Workstation debe instalarse utilizando **las rutas predeterminadas** del instalador.

Modificar la ubicación de instalación puede impedir que algunas funciones localicen correctamente los ejecutables.

### ⚠️Icono personalizado

Windows no permite asignar un icono directamente a un archivo **.bat**.

Si deseas personalizar el icono:

1. Guarda el archivo **.ico**.
2. Crea un acceso directo del script.
3. Asigna el icono al acceso directo desde sus propiedades.

---

# 📌 Recomendaciones

- Ejecuta siempre el programa como Administrador.
- Mantén VMware Workstation actualizado.
- Utiliza el modo Manual cuando no necesites virtualización para ahorrar recursos.
- Reinicia los adaptadores de red si alguna máquina virtual pierde conectividad.

---

# 📸 Capturas

<img width="931" height="740" alt="Captura de pantalla 2026-06-19 221856" src="https://github.com/user-attachments/assets/008959cf-9a18-4409-9dde-37deecfb1512" />

---

# 📝 Changelog

## Primera versión

### Nuevo

- Gestión centralizada de servicios VMware.
- Dashboard con información del sistema.
- Herramientas de red integradas.
- Kill Switch para procesos bloqueados.
- Automatización del modo de inicio.
- Accesos rápidos a herramientas administrativas.

---

# 📄 Licencia

Este proyecto se distribuye con fines educativos y de automatización para usuarios de VMware Workstation.

---

<div align="center">

⭐ **Si este proyecto te resulta útil, considera darle una estrella al repositorio.**

</div>
