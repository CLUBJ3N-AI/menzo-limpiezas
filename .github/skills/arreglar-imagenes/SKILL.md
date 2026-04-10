---
name: arreglar-imagenes
description: "Guía paso a paso para encontrar y corregir problemas con imágenes en HTML/CSS, rutas, accesibilidad y rendimiento."
---

# Skill: Arreglar problemas de imágenes

## Cuándo usarlo
- Cuando una imagen no se muestra en la página
- Cuando hay rutas rotas o archivos faltantes
- Cuando las imágenes no se adaptan correctamente en móvil
- Cuando quieres mejorar accesibilidad y rendimiento de imágenes

## Pasos recomendados
1. Inspeccionar `index.html`, `styles.css` y la carpeta `images/`.
2. Listar imágenes usadas en etiquetas `<img>` y en reglas CSS `background-image`.
3. Verificar que cada `src`, `srcset`, `sizes` o ruta CSS apunte a un archivo existente.
4. Corregir rutas relativas, mayúsculas/minúsculas y nombres de archivo inconsistentes.
5. Añadir o mejorar atributos `alt` en cada `<img>` para accesibilidad.
6. Revisar `srcset`/`sizes`, `loading="lazy"` y formatos de imagen para rendimiento.
7. Ajustar CSS de contenedores, `width`, `height`, `max-width` y `object-fit` para un diseño responsivo.
8. Probar la página en diferentes anchos de pantalla y verificar que las imágenes se carguen sin errores.
9. Confirmar que no aparecen errores de imágenes en la consola del navegador.

## Resultado esperado
- Todas las imágenes se muestran correctamente
- No hay rutas rotas ni errores 404
- El contenido alternativo (`alt`) es adecuado
- El diseño es responsivo y las imágenes se escalan bien
- El HTML y CSS de las imágenes está limpio y coherente
