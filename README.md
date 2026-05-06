# Auditoría Preliminar de Accesibilidad: UTN FRLP (LINA)

Este proyecto forma parte de un voluntariado en el **LINA (Laboratorio de Innovación Abierta)** de la UTN Facultad Regional La Plata. El objetivo es realizar un diagnóstico técnico del sitio web institucional para establecer estándares de calidad e inclusión digital.

## 🤝 Contexto del Proyecto
Como parte del equipo de accesibilidad, colaboro en la identificación de barreras críticas de navegación. Este trabajo es el resultado de un análisis multidisciplinario enfocado en la mejora continua de la plataforma de la facultad.

## 🛠️ Metodología Aplicada
Se realizó un testeo preliminar utilizando:
* **Análisis con Lectores de Pantalla:** Uso de **NVDA** para verificar la jerarquía de regiones y el anuncio de elementos (especialmente en la sección de noticias).
* **Evaluación de Imágenes:** Auditoría de atributos `alt` y etiquetas ARIA mediante **Stark Accessibility Checker**.
* **Validación Automática:** Detección de errores de código con **Axe DevTools**.

## 📂 Documentación y Hallazgos
La información se organiza en:
* **[Reporte de Análisis Preliminar (PDF)](./docs/Analisis-Preliminar-UTNFRLP.pdf):** Detalle de hallazgos iniciales sobre roles ARIA faltantes y gestión de contenido no textual.
* **[Evidencias de Testeo](./evidencias/):** Capturas del comportamiento del sitio con herramientas de asistencia.
* **[Listado de Herramientas](./herramientas/herramientas.md):** Detalle técnico de los softwares (Stark, NVDA, Axe) utilizados en el Laboratorio LINA.

## 🚀 Impacto
Este diagnóstico sirve como base para las futuras implementaciones del laboratorio, buscando que el sitio de la UTN FRLP cumpla con los niveles de conformidad A y AA de las pautas **WCAG**.
