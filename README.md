# 🍄 Cepamétrica | MVP Frontend
> **"Ingeniería en cada espora."**

![Nuxt 3](https://img.shields.io/badge/Nuxt_3-00DC82?style=for-the-badge&logo=nuxt.js&logoColor=white)
![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![ECharts](https://img.shields.io/badge/ECharts-AA344D?style=for-the-badge&logo=apache-echarts&logoColor=white)

## 📌 Sobre el Proyecto
**Cepamétrica** es una startup FoodTech/AgroTech B2B enfocada en el desarrollo de sistemas ciberfísicos para la producción estandarizada de biomasa fúngica (*Pleurotus ostreatus*). 

Este repositorio contiene el frontend del sistema, diseñado para monitorear en tiempo real la telemetría de las cámaras de secado. Nuestro objetivo principal es garantizar que las variables de temperatura y humedad se mantengan en rangos óptimos para evitar la desnaturalización de la proteína del hongo durante el proceso de deshidratación.

## 🏗️ Alcance del MVP (Fase 1)
Esta versión inicial (MVP) opera bajo un modelo **estrictamente OFFLINE**:
- **Sin conexión a Base de Datos:** Los registros se mantienen en memoria local.
- **Sin Broker MQTT:** No hay ingesta de datos en tiempo real desde hardware físico.
- **Simulación de Telemetría:** El Dashboard se alimenta de un archivo estático `telemetria.json` que simula un historial de sensores IoT, garantizando la validación de la interfaz y la experiencia de usuario B2B antes de la integración con el hardware real.

## 🎨 Identidad Visual y UI/UX
La interfaz sigue un enfoque minimalista, de corte industrial estricto, utilizando una paleta de colores semántica y orientada a la biotecnología:
- **Verde Biotecnología:** `#116A64` *(Énfasis y datos biológicos)*
- **Azul Ciberfísico:** `#1C3B5E` *(Estructura y UI profunda)*
- **Plata Industrial:** `#C0C0C0` *(Bordes y textos secundarios)*
- **Fondo General:** `#FFFFFF` *(Minimalismo estricto)*

## 🚀 Instalación y Entorno de Desarrollo

Asegúrate de tener [Node.js](https://nodejs.org/) instalado (versión 18+ recomendada).

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/TU_USUARIO/cepametrica.git](https://github.com/iraledezma2414/cepametrica.git)
   cd cepametrica