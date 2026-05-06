# Stack Tecnológico de Accesibilidad - Proyecto LINA (UTN FRLP)

Para este análisis preliminar en el **Laboratorio de Innovación Abierta**, se seleccionaron herramientas que permiten una inspección profunda del DOM y de la experiencia con tecnologías asistivas.

## 🛠️ Herramientas de Inspección Técnica
* **Stark Accessibility Checker:** Utilizada principalmente para la auditoría de **Contenido no textual**. Permitió listar y verificar la existencia (o ausencia) de atributos `alt` en iconos de redes sociales y el carrusel institucional.
* **Axe DevTools:** Herramienta base para la detección del error crítico en el criterio **4.1.2 (Nombre, Rol, Valor)** detectado en la región de noticias.

## 🔊 Tecnologías Asistivas (Validación de Usuario)
* **Lector de Pantalla NVDA:** Fundamental para confirmar el "Resultado Obtenido" reportado. Se utilizó para validar cómo la tecnología de asistencia anuncia los elementos sin roles ARIA definidos (ej. el anuncio de la región de noticias sin jerarquía clara).

## 🎨 Metodología de Análisis
* **Inspección de Atributos ARIA:** Verificación manual de etiquetas `aria-label` y `aria-level` para asegurar que la estructura del sitio sea comunicada correctamente a los usuarios con ceguera o baja visión.
* **Auditoría de Enlaces:** Análisis de los iconos de información y micrófono para validar que el texto alternativo describa la función del enlace y no solo el contenido visual.

---
> **Impacto Profesional:** El uso de estas herramientas permitió identificar que elementos críticos para la navegación (como los iconos de redes sociales en el header) carecían de descripciones adecuadas, afectando la percepción y operación del sitio.
