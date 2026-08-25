#  LazyForge - Creador de Mods para Minecraft

LazyForge es una herramienta visual que te permite crear mods para **Minecraft 1.21.1** de forma rápida, intuitiva y **sin necesidad de escribir una sola línea de código**. Diseña los elementos de tu mod directamente desde el navegador y compílalos fácilmente en tu computadora.

 **[¡Comienza a diseñar tu mod aquí!](https://luchidev17.github.io/lazyforge-web/)**

##  Características Principales

*   **Cero Programación:** Interfaz web amigable pensada para enfocarse en la creatividad, no en el código.
*   **Versión Específica:** Construido y optimizado para funcionar con Minecraft 1.21.1.
*   **Compilación Local Segura:** El código de tu mod se genera y compila directamente en tu máquina.

## ¿Cómo usar LazyForge?

Sigue estos 5 simples pasos para obtener tu mod:

1.  **Diseña:** Ingresa a [LazyForge Web](https://luchidev17.github.io/lazyforge-web/) y personaliza todos los aspectos de tu mod.
2.  **Descarga:** Una vez que tu diseño esté listo, descarga el archivo comprimido generado por la web.
3.  **Descomprime:** Extrae el contenido del archivo descargado en una carpeta de tu computadora.
4.  **Ejecuta:** Haz doble clic en el archivo `.exe` que viene dentro de la carpeta.
5.  **¡Juega!** El ejecutable hará el trabajo pesado y te entregará un archivo `.jar`. Simplemente copia ese `.jar` en tu carpeta `mods` de Minecraft y disfruta.

---

## 💻 Para Desarrolladores (React + Vite)

Este proyecto está construido con React y Vite, proporcionando una configuración inicial rápida con HMR (Hot Module Replacement) y reglas de Oxlint.

Actualmente, hay dos plugins oficiales disponibles en este entorno:
*   `@vitejs/plugin-react` que utiliza Oxc.
*   `@vitejs/plugin-react-swc` que utiliza SWC.

**Sobre el React Compiler:**
El compilador de React no está activado por defecto en este proyecto debido a su impacto en el rendimiento durante el desarrollo y la compilación.

**Ampliando la configuración de Oxlint:**
Si deseas clonar y escalar esta aplicación para un entorno de producción más grande, te recomendamos integrar TypeScript con las reglas de *linting* avanzadas.

