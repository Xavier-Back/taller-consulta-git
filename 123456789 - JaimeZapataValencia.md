# Solución Preguntas

## Punton 1:
Git es un sistema de control de versiones distribuido que rastrea y registra los cambios en los archivos de un proyecto a lo largo del tiempo. Funciona tomando "fotografías" (commits) del estado del código en momentos específicos, lo que permite navegar por su historial con total precisión.

El problema principal que resuelve es el caos de la colaboración concurrente y la gestión del código fuente. En un entorno de desarrollo, elimina directamente los siguientes obstáculos:

Pérdida de historial y versiones: Acaba con la necesidad de duplicar carpetas o renombrar archivos manualmente (index_final_v3.html). Mantiene un registro cronológico inmutable de quién cambió qué, cuándo y por qué (trazabilidad).

Conflictos de sobreescritura: Permite que múltiples desarrolladores trabajen en el mismo proyecto, e incluso en el mismo archivo, de forma simultánea. Git gestiona la integración (merge) de esos cambios y alerta sobre los conflictos antes de que el trabajo de alguien sea sobrescrito por error.

Riesgo al experimentar: Mediante el sistema de ramas (branches), permite crear entornos de trabajo aislados para desarrollar nuevas características o probar correcciones sin afectar la línea base de código estable (producción).

Dependencia de un servidor único: Al ser un sistema distribuido, cada desarrollador tiene una copia local completa de todo el repositorio y su historial. Esto significa que se puede trabajar sin conexión a internet y, si el servidor principal cae, cualquier copia local sirve como respaldo total.