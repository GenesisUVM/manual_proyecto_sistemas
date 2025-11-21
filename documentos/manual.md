

1. Buenas prácticas de organización del equipo

1.1. Comunicación

Establecer un canal principal (WhatsApp, Telegram, Discord).

Definir horarios aproximados de respuesta.

Registrar decisiones importantes dentro del repositorio (en Issues o en el README).

1.2. Roles y responsabilidades

Coordinador del equipo

Encargado de documentación

Encargado del control de versiones

Encargado de revisión

Encargado del diseño o formato

Los roles pueden rotar semanalmente para equilibrar trabajo.

1.3. Reuniones y planificación

Reuniones cortas de seguimiento (10–15 minutos).

Documentar acuerdos y tareas en GitHub Projects.

Crear Issues para cada actividad asignada.

1.4. Gestión del tiempo

Dividir el trabajo en tareas pequeñas.

Establecer fechas claras para entregables.

Utilizar etiquetas en Issues:
prioridad-alta, documentación, en revisión, completado.

2. Formato del documento

2.1. Estructura sugerida

Portada

Índice

Introducción

Desarrollo (con subtítulos claros)

Conclusiones

Bibliografía

Anexos

2.2. Reglas de estilo

Fuente recomendada: Arial, Calibri o Roboto.

Tamaño: 11–12 pt.

Interlineado: 1.15 o 1.5.

Márgenes estándar: 2.54 cm.

Evitar bloques grandes de texto; usar listas y títulos.

2.3. Imágenes y tablas

Guardarlas en /imagenes.

Referenciarlas con texto descriptivo.

Usar nombres como: figura_01.png, tabla_02.jpg.

2.4. Escritura

Redacción formal.

Evitar muletillas y repeticiones.

Revisar ortografía antes de hacer un pull request.
3. Cómo trabajar con ramas

3.1. Flujo recomendado

Crear una rama por sección → git checkout -b seccion-formato

Editar únicamente esa parte del manual.

Subir los cambios → git push

Crear un Pull Request en GitHub.

Solicitar revisión a otro compañero.

Luego de aprobar, hacer merge a main.

3.2. Nombres recomendados para ramas

seccion-buenas-practicas

seccion-formato

seccion-rama

seccion-conflictos

PDF-final

3.3. Buenas prácticas

No trabajar directamente en main.

Hacer commits pequeños y descriptivos.

Sincronizar antes de empezar → git pull origin main.
5. Generación del PDF final

5.1. Si el manual está en Markdown

Puedes convertirlo usando un convertidor online o Pandoc:

pandoc manual.md -o manual.pdf

5.2. Si está en Google Docs o Word

Exportar como PDF.

Asegurarse de que los títulos y numeraciones estén correctos.

Guardar el PDF en la carpeta /documentos.

5.3. Versión final

Etiquetar la versión → v1.0.

Registrar cambios en CHANGELOG.md:

Secciones añadidas

Correcciones

Revisiones

Subir el PDF con un mensaje claro:
“Versión final del manual para entrega – v1.0”