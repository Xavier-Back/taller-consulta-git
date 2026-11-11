# Solución Preguntas

## Punton 1:
Git es un sistema de control de versiones distribuido que rastrea y registra los cambios en los archivos de un proyecto a lo largo del tiempo. Funciona tomando "fotografías" (commits) del estado del código en momentos específicos, lo que permite navegar por su historial con total precisión.

El problema principal que resuelve es el caos de la colaboración concurrente y la gestión del código fuente. En un entorno de desarrollo, elimina directamente los siguientes obstáculos:

Pérdida de historial y versiones: Acaba con la necesidad de duplicar carpetas o renombrar archivos manualmente (index_final_v3.html). Mantiene un registro cronológico inmutable de quién cambió qué, cuándo y por qué (trazabilidad).

Conflictos de sobreescritura: Permite que múltiples desarrolladores trabajen en el mismo proyecto, e incluso en el mismo archivo, de forma simultánea. Git gestiona la integración (merge) de esos cambios y alerta sobre los conflictos antes de que el trabajo de alguien sea sobrescrito por error.

Riesgo al experimentar: Mediante el sistema de ramas (branches), permite crear entornos de trabajo aislados para desarrollar nuevas características o probar correcciones sin afectar la línea base de código estable (producción).

Dependencia de un servidor único: Al ser un sistema distribuido, cada desarrollador tiene una copia local completa de todo el repositorio y su historial. Esto significa que se puede trabajar sin conexión a internet y, si el servidor principal cae, cualquier copia local sirve como respaldo total.

## Punto 2:
Git es el software de control de versiones que instalas y ejecutas en tu computadora, mientras que GitHub es una plataforma en la nube diseñada para alojar y gestionar proyectos que usan Git.CaracterísticaGitGitHubNaturalezaHerramienta de software libre y de código abierto.Servicio comercial (propiedad de Microsoft).EntornoLocal. Se ejecuta en tu máquina (sin necesidad de internet).En la nube. Requiere conexión a internet para sincronizar.InterfazPrincipalmente mediante línea de comandos (Terminal/Consola).Interfaz gráfica web y visual.Propósito centralRastrear cambios, crear ramas y gestionar el historial del código.Facilitar la colaboración en equipo, alojar repositorios y centralizar el código.DependenciaEs autónomo. Puedes usar Git sin usar GitHub jamás.Depende de Git. No puedes alojar código en GitHub sin usar Git por debajo.Por qué no son lo mismo
La confusión ocurre porque GitHub lleva "Git" en su nombre y ambos trabajan en conjunto, pero cumplen roles distintos.Para ilustrarlo con un ejemplo práctico: Git es como el procesador de texto que usas en tu computadora para escribir y guardar versiones de un documento. GitHub es como Google Drive o Dropbox, el lugar en internet donde subes ese documento para que otras personas puedan leerlo, comentar sobre él (Issues) o proponer modificaciones (Pull Requests).Puedes usar Git con otras plataformas (como GitLab o Bitbucket) o simplemente dejar tu código de forma local. Git es la tecnología subyacente; GitHub es la red social y el espacio de almacenamiento construido alrededor de esa tecnología.