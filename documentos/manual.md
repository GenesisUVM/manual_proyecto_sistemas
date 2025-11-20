 Manual de Uso del Repositorio de SVG
Gestión de íconos administrativos — Documentación oficial
1️. Introducción

Este manual describe cómo utilizar, descargar e integrar los íconos SVG incluidos en este repositorio.
El objetivo es proporcionar una guía clara para cualquier usuario que necesite incorporar estos recursos visuales en un proyecto web o visual.

Los SVG disponibles representan distintos roles administrativos, y pueden adaptarse fácilmente en tamaño y color gracias a la naturaleza del formato vectorial.

2️. Estructura del Repositorio

La estructura recomendada del repositorio es la siguiente:

/
├── README.md
├── CHANGELOG.md
├── /svg/
│   ├── admin.svg
│   ├── supervisor.svg
│   ├── operador.svg
│   └── asistente.svg
└── /docs/
    └── manual.md

3️. Acceso a los Íconos SVG
✔ Paso 1: Abrir el repositorio

Accede a tu repositorio de GitHub con la URL:

https://github.com/tu-usuario/nombre-del-repositorio

✔ Paso 2: Ir a la carpeta /svg/

Dentro de esta carpeta encontrarás todos los íconos en formato .svg.

✔ Paso 3: Descargar un archivo SVG

Haz clic en el archivo deseado.

Selecciona el botón Download raw file.

O clic derecho → Guardar como….

4️. Cómo usar los SVG en un proyecto web
✔ Opción 1: Insertar el SVG como imagen
<img src="./svg/admin.svg" alt="Icono de administrador">

✔ Opción 2: Insertar el SVG directamente en el HTML

Copia el contenido del archivo .svg y pégalo donde lo necesites:

<div class="icon-admin">
    <!-- Contenido del admin.svg -->
</div>

5️. Cómo modificar el tamaño y el color
✔ Cambiar tamaño con CSS
.icon-admin {
    width: 50px;
    height: 50px;
}

✔ Cambiar color del ícono

Si el SVG contiene fill="currentColor", puedes alterarlo con CSS:

.icon-admin {
    color: #4A90E2; /* azul */
}

6️. Buenas prácticas del repositorio

Mantén nombres simples y consistentes para los SVG.

Organiza los archivos dentro de carpetas (/svg/, /docs/, etc.).

Documenta cualquier cambio en CHANGELOG.md.

Usa versiones con tags (v1.0, v1.1) cuando agregues o modifiques recursos.

Mantén este manual actualizado si agregas nuevos íconos o funcionalidades.

7️. Actualización de versiones (CHANGELOG y tags)

Cuando agregues nuevos SVG o modifiques los existentes:

Sube o modifica los archivos en /svg/.

Añade una entrada al CHANGELOG.md:

## [1.1.0] - 2025-11-20
### Added
- Nuevo ícono para el rol “coordinador”.


Crea un tag en GitHub:

v1.1.0
