# ✈️   ADSB-sv Spain — Distribución Oficial

![Version](https://img.shields.io/badge/Versi%C3%B3n-v1.0.0--beta-purple)
![Platform](https://img.shields.io/badge/Plataforma-Raspberry%20Pi%20%7C%20PC%20X86-blue)
![OS](https://img.shields.io/badge/SO-DietPi%20%28Debian%29-green)

BIENVENIDO A LA **COMUNIDAD DE ENTUSIASTAS DEL SDR PARA ADSB (1090 MHz)** EN ESPAÑOL

**ADSB-sv** es una distribución de código abierto desarrollada por el laboratorio de **Localízanos** y diseñada específicamente para facilitar el despliegue de estaciones en el seguimiento de vuelos con alta precisión.

---

## 🚀 Características Principales

* **Arranque Dual Híbrido:** Ejecución en entornos nativos `Debian`  o mediante **Live USB** (compatible con modos *Legacy* y *UEFI*) tanto en **Raspberry Pi** como en **PC**.
* **Core Decodificador:** Integración del decodificador `readsb`  y la interfaz gráfica `tar1090`  corriendo bajo el sistema operativo **DietPi**.
* **Sincronización de Alta Precisión:** Configuración cronométrica sincronizada con la **Red de Observación de la Armada (ROA)** para multilateración (MLAT).
* **Preconfiguración Servidores DNS:** Establecimiento de servidores **DNS comunes** para agilidad de integración en comunidad.


---

## 📡 Alimentación de Datos (Feeders)

La suite inicialmente permite ya la difusión simultánea y empaquetada de tramas de datos hacia las principales redes de monitorización global:

* **ADSBexchange** (ADSBx)
* **FlightRadar24** (FR24)
* **AirNavRadar** (RadarBox)
* **FlightAware**
* **PlaneFinder**

---

## 🛠️ Modos de Trabajo

La arquitectura del proyecto incluye scripts de control específicos administrados desde la consola de comandos de la distribución:
* **Modo Desarrollador - Yoda `[Y]`:** Permite la inyección de datos de prueba, depuración de tramas complejas para cualquier código Hex ID y personalización visual de la interfaz.
* **Modo Entusiasta - Novel `[N]`:** Configuración blindada del laboratorio, manteniendo la distribución abierta para la comunidad estándar de entusiastas.

---

## 👥 Comunidad y Soporte

¿Quieres formar parte del proyecto, descargar la imagen preconfigurada que se publicará próximamente o compartir tus inquietudes técnicas?
* **Canal Oficial de Telegram:** [t.me/ADSB_sv_Spain](https://t.me/ADSB_sv_Spain)
* **Web Drive del Proyecto:** [Repositorio Documental Localízanos](https://drive.google.com/drive/folders/19CYSe_Q1p4EegJNYkjt5qwRJ8ifbYT-h)

---

_Desarrollado por ADSB-sv Team._
