# DineDisplay Cafetería ITAM

Una aplicación móvil para que la cafetería del ITAM pueda gestionar y actualizar fácilmente los menús digitales que se muestran en sus pantallas, con la posibilidad de personalizar plantillas, promover productos y adaptar la información según el momento del día.

---

## 📂 Entregables

| Entregable | Descripción |
|------------|-------------|
| 👩🏽 Persona | [Salvadora de la cafeteria](https://github.com/ITAM-ADSI2025/dinedisplay/blob/main/PersonaDineDisplay.jpg)|
| 📍 Customer Journey | [Parte 1](https://github.com/ITAM-ADSI2025/dinedisplay/blob/main/DineDisplay_customerJourney_pt1.jpg), [Parte 2](https://github.com/ITAM-ADSI2025/dinedisplay/blob/main/DineDisplay_customerJourney_pt2.jpg) |
| 🚧 Prototipo Moqups | [Prototipo medio nivel en Moqups](https://app.moqups.com/Q92BbW9H1q2GsYbUSK3SSp5n0u7hViva/view/page/ad64222d5)|
| 🎨 Prototipo Figma | [Prototipo final en Figma](https://www.figma.com/proto/ATJbBcgw1Xop6atFN2p44q/DineDisplay?node-id=0-1&t=M2oGO1QaShU4wLg0-1 ) |
| 📋 Backlog en Issues | [Issues en GitHub](https://github.com/tu-usuario/tu-repo/issues) |
| 🧪 Pruebas| [Prueba 1](https://app.lyssna.com/tests/jyivvjr4jrea/results/qoagxzc4rygd) , [Prueba 2](https://app.lyssna.com/tests/eclpzlaytklz/results/oxdhoi22wvyd) |
| 📊 Presentación final | [Presentación](https://github.com/ITAM-ADSI2025/dinedisplay/blob/main/DineDisplay.pdf) |

---

## Problema detectado

La cafetería del ITAM ha enfrentado dificultades para mantener actualizados y organizados sus menús en pantallas digitales. Los productos no están categorizados, el orden visual es poco claro y no existe un sistema flexible que les permita modificar el contenido con agilidad. Esta falta de claridad ha generado confusión entre los clientes, pérdida de oportunidades para promover productos y una experiencia de usuario deficiente, lo que ha contribuido a una disminución en ventas y satisfacción.

---

## Objetivo del proyecto

Desarrollar una herramienta intuitiva y flexible que permita a la cafetería:
- Crear, editar y eliminar productos fácilmente.
- Personalizar plantillas por pantalla, categoría o momento del día (desayuno, comida, promociones).
- Visualizar y administrar varias pantallas digitales desde una sola plataforma.

---

## Funcionalidades principales

1. **Gestión dinámica de productos**
   - Agrega productos con nombre, categoría, precio y descripción.
   - Filtra productos por tipo y edítalos desde múltiples secciones.

2. **Plantillas personalizables**
   - Cada pantalla se puede configurar con una plantilla distinta (por tiempo del día, promociones, etc.).
   - Cambios reflejados instantáneamente en las pantallas.

---

## Proceso UX y desarrollo

### Fase de investigación
- Visita de campo y entrevistas a usuarios de la cafeteria.
- Definición de la persona principal: *Salvadora de la cafeteria*.
- Customer Journey: Mapeo de frustraciones y necesidades.

### Prototipos y pruebas
- **Prototipo en papel**: foco en navegación general.
- **Mockups de media fidelidad**: primera iteración visual.
- **Figma de alta fidelidad**: versión final con funcionalidades activas.
- Pruebas con usuarios en **Lyssna** con tareas clave:
  - Cambiar productos en pantalla.
  - Navegar entre secciones.
  - Añadir nuevos productos.

### Resultados clave de pruebas (Lyssna)
- 59% de misclicks en tareas como cambiar productos.
- Usuarios confundidos por falta de botones claros y etiquetas poco descriptivas.
- Solicitud frecuente: agregar botón de regreso y permitir edición directa desde más de una vista.

### Cambios implementados tras pruebas
- Botones visibles para editar pantalla desde inicio.
- Funcionalidad de creación de producto desde más de un flujo.
- Icono 📖 ("menu") añadido como acceso directo a productos.

---

## Backlog 

Las tareas principales del backlog del proyecto fue gestionado directamente desde los **Issues de GitHub**, organizando tareas por prioridad.

👉 [Ver Issues del proyecto](https://github.com/ITAM-ADSI2025/dinedisplay/issues)  

### 3 tareas principales basadas en pruebas:

| Historia de Usuario                                                                                      | Descripción detallada                                                                                      | Estado | Prioridad |
|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|--------|-----------|
| “Como manager, quiero añadir un producto desde la pantalla 'Mis Productos'”                               | Flujo optimizado para crear un producto nuevo directamente desde la vista de productos existentes.          | ✅     | Alta      |
| “Como manager, quiero acceder a la sección 'Mis Productos' desde diversos lugares de la aplicación”       | Acceso intuitivo desde el ícono del librito, la barra de navegación y desde cada plantilla editable.        | ✅     | Alta      |
| “Como manager, quiero cambiar el producto que se muestra en mi segunda pantalla por otro diferente”       | Edición directa desde la pantalla principal para actualizar promociones o reemplazar productos fácilmente. | ✅     | Alta      |

Las tareas que se realizaron durante el semestre pero sin historia de usuario:

### Investigación y UX

| Función                        | Descripción detallada                                                                                       | Estado | Prioridad |
|-------------------------------|--------------------------------------------------------------------------------------------------------------|--------|-----------|
| Investigación en cafetería    | Realizar observaciones con el personal del ITAM para entender el flujo operativo y áreas de oportunidad. | ✅     | Alta      |
| Detección de problema         | Sintetizar hallazgos de la investigación y delimitar el problema.                          | ✅     | Alta      |
| Customer Journey              | Mapear la experiencia actual del administrador en el control de la cafeteria.     | ✅     | Media     |
| Creación de Persona           | Diseñar un perfil detallado del usuario principal (Gerente de Cafetería), con objetivos y necesidades.        | ✅     | Alta      |
| Prototipo en papel            | Boceto inicial de pantallas para validar el concepto rápidamente sin invertir en diseño.   | ✅     | Alta      |
| Pruebas con prototipo en papel| Validar con usuarios la lógica básica del flujo y detectar errores de navegación.         | ✅     | Alta      |
| Moqups (medio nivel)         | Diseño de prototipos de media fidelidad con mayor detalle visual para seguir afinando la interacción.            | ✅     | Media      |
| Pruebas con Lyssna            | Usar Lyssna para pruebas remotas de usabilidad, recolectando datos como heatmaps, misclicks y feedback.       | ✅     | Media      |
| Prototipo en Figma (alto nivel)    | Diseño funcional de alta fidelidad con navegación completa y todos los elementos visuales e interactivos.     | ✅     | Alta      |
| Pruebas con Lyssna            | Usar Lyssna para más pruebas remotas de usabilidad, recolectando datos como heatmaps, misclicks y feedback.       | ✅     | Alta      |
| Cambios a prototipo en Figma (final)    | Cambios en diseño basados en las pruebas de usuario.     | ✅     | Alta      |

### Tareas que podríamos continuar

| Función                 | Descripción detallada                                                                 | Estado | Prioridad |
|------------------------|----------------------------------------------------------------------------------------|--------|-----------|
| Documentación técnica  | Documentar componentes clave para facilitar mantenimiento y escalabilidad. | ❌     | Media     |
| Validación con cliente | Revisión final del prototipo con la gerente real de la cafetería antes de implementación. | ❌     | Alta      |
| Pruebas con más usuarios | Hacer pruebas adicionales con personal de cafetería  para validar consistencia. | ❌     | Media     |

---

## Principales aprendizajes

- El apego emocional al diseño inicial puede interferir con las necesidades reales del usuario.
- Iterar constantemente, con retroalimentación frecuente, es clave para mejorar.
- Las pruebas deben estar bien planeadas y contextualizadas para obtener insights útiles.

---

## Si volviéramos a empezar...

- Realizaríamos entrevistas más profundas y estructuradas desde el inicio.
- Usaríamos prototipos de media fidelidad por más tiempo antes de pasar a alta fidelidad.
- Invertiríamos más en planeación y definición de pruebas de usuario antes de diseñar soluciones.

---

## 🐛 Equipo Bugs

- Harry Dawson
- Javier Escalante 
- Mauricia Peña 
- Fernando Retama 

---

## Licencia

MIT © 2025


