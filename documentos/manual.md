4. Resolución de conflictos

4.1. ¿Qué es un conflicto?

Ocurre cuando dos personas editan la misma parte del documento antes de hacer merge.

4.2. Cómo evitarlos

Cada estudiante trabaja en su propia sección.

Usar ramas diferentes.

Hacer pull antes de editar.

4.3. Cómo resolverlos

Git marcará el archivo con:
<<<<<< HEAD
tu versión
=======
versión del compañero
>>>>>>> rama-del-compañero
Elegir qué parte conservar y editar manualmente.

Guardar el archivo corregido.

Hacer commit del conflicto resuelto → git add . y git commit.

4.4. Buenas prácticas

Consultar a tu compañero antes de eliminar contenido.

Describir en el PR cómo se resolvió el conflicto.
