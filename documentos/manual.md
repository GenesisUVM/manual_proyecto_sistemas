# Manual de Buenas Prácticas para Trabajos Universitarios en Equipo


## 1. Buenas prácticas de organización del equipo

### 1.1. Comunicación
- Definir un canal principal (WhatsApp, Telegram, Discord).
- Establecer horarios aproximados de respuesta.
- Registrar decisiones importantes dentro del repositorio (en Issues o en el README).
- Preferir comunicación escrita para mantener evidencia.

### 1.2. Roles y responsabilidades
- **Coordinador del equipo:** organiza tareas y reuniones.
- **Encargado de documentación:** administra el contenido del manual.
- **Encargado del control de versiones:** gestiona ramas, PR y merges.
- **Encargado de revisión:** valida contenido antes de aprobar cambios.
- **Encargado de diseño o formato:** estandariza estilos y estructura visual.


### 1.3. Reuniones y planificación
- Realizar reuniones cortas de seguimiento (10–15 minutos).
- Documentar acuerdos y tareas en GitHub Projects.
- Crear Issues para cada actividad asignada.
- Utilizar el tablero Kanban (To Do → In Progress → Done).

### 1.4. Gestión del tiempo
- Dividir el trabajo en tareas pequeñas y manejables.
- Establecer fechas claras para cada entregable.
- Utilizar etiquetas en Issues:
  - `prioridad-alta`
  - `documentación`
  - `en-revisión`
  - `completado`


## 2. Formato del documento

### 2.1. Estructura sugerida
- Portada  
- Índice  
- Introducción  
- Desarrollo (con subtítulos claros)  
- Conclusiones  
- Bibliografía  
- Anexos  

### 2.2. Reglas de estilo
- Fuente recomendada: Arial, Calibri o Roboto.
- Tamaño: 11–12 pt.
- Interlineado: 1.15 o 1.5.
- Márgenes estándar: 2.54 cm.
- Evitar bloques grandes de texto; usar listas, tablas y títulos descriptivos.

### 2.3. Imágenes y tablas
- Guardar archivos en la carpeta `/imagenes`.
- Nombrar archivos como: `figura_01.png`, `tabla_02.jpg`.
- Referenciar en el texto de esta forma:



### 2.4. Escritura
- Redacción formal y clara.
- Evitar muletillas y repeticiones.
- Revisar ortografía antes de enviar un Pull Request.
- Utilizar lenguaje inclusivo y profesional.


## 3. Cómo trabajar con ramas en Git

### 3.1. Flujo recomendado
1. Crear una rama por sección:  
   ```bash
   git checkout -b seccion-formato

