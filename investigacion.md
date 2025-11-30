
### **Parte I – Investigación (50%)**

1. ¿Qué es Git y para qué se utiliza?

- **Git** es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios en el código fuente durante el desarrollo de software. Se utiliza para gestionar proyectos de software, facilitando la colaboración entre múltiples desarrolladores, permitiendo revertir cambios, y manteniendo un historial detallado de las modificaciones realizadas en los archivos del proyecto.

- **¿Para qué se utiliza?** Git se utiliza para:

  - Controlar versiones del código fuente.
  - Facilitar la colaboración entre desarrolladores.
  - Mantener un historial de cambios.
  - Permitir la creación de ramas para desarrollar nuevas características sin afectar la versión principal del proyecto.
  - Facilitar la integración y despliegue continuo en proyectos de software.

- **GitHub** es una plataforma de alojamiento de código fuente basada en la web que utiliza Git como sistema de control de versiones. Proporciona una interfaz gráfica y herramientas adicionales para facilitar la colaboración, revisión de código, gestión de proyectos y despliegue de aplicaciones.

- **¿Para qué se utiliza?** GitHub se utiliza para:
  - Alojar repositorios de código fuente.
  - Facilitar la colaboración entre desarrolladores a través de pull requests y revisiones de código.
  - Gestionar proyectos mediante issues, tableros Kanban y wikis.
  - Integrar con herramientas de CI/CD para automatizar pruebas y despliegues.
  - Compartir código y proyectos con la comunidad de desarrolladores.

2. ¿Qué diferencia hay entre Git y GitHub?

- **Diferencia entre Git y GitHub:**
  - **Git** es un sistema de control de versiones que se utiliza localmente en la computadora del desarrollador para rastrear cambios en el código fuente.
  - **GitHub** es una plataforma en línea que aloja repositorios Git y proporciona herramientas adicionales para la colaboración, gestión de proyectos y revisión de código. En resumen, Git es la herramienta de control de versiones, mientras que GitHub es un servicio que utiliza Git para facilitar la colaboración y el alojamiento de código.

3. Explica en tus palabras qué es un _repositorio_.

- Un _repositorio_ es un espacio donde se almacena y gestiona el código fuente de un proyecto. En Git, un repositorio contiene todos los archivos del proyecto, así como el historial de cambios realizados en esos archivos. Los repositorios pueden ser locales (en la computadora del desarrollador) o remotos (en plataformas como GitHub), y permiten a los desarrolladores colaborar, rastrear modificaciones y mantener versiones del código de manera organizada.

4. ¿Qué significa hacer un _commit_ en Git?

- Hacer un _commit_ en Git significa guardar un conjunto de cambios realizados en los archivos del proyecto en el historial de versiones del repositorio. Un commit actúa como un punto de control que registra el estado actual del código, junto con un mensaje descriptivo que explica qué cambios se hicieron y por qué. Esto permite a los desarrolladores rastrear la evolución del proyecto, revertir cambios si es necesario y colaborar de manera efectiva con otros miembros del equipo.

5. Investiga y explica brevemente los siguientes comandos de Git:
   - `git config --local user.name "<GitHub user name>"`: Configura el nombre de usuario que se asociará con los commits realizados en el repositorio local. Este nombre aparecerá en el historial de commits para identificar al autor de los cambios.
   - `git config --local user.email "<GitHub email>"`: Configura la dirección de correo electrónico que se asociará con los commits realizados en el repositorio local. Al igual que el nombre de usuario, este correo electrónico aparecerá en el historial de commits para identificar al autor.
   - `git init`: Inicializa un nuevo repositorio Git en el directorio actual. Crea una carpeta oculta llamada `.git` que contiene todos los archivos necesarios para rastrear los cambios en el proyecto.
   - `git add`: Agrega archivos específicos o todos los archivos modificados al área de preparación (staging area) para que estén listos para ser incluidos en el próximo commit. Por ejemplo, `git add .` agrega todos los archivos modificados en el directorio actual.
   - `git commit`: Crea un nuevo commit que guarda los cambios agregados al área de preparación. Se debe proporcionar un mensaje descriptivo que explique los cambios realizados, por ejemplo, `git commit -m "Mensaje del commit"`.
   - `git push`: Sube los commits locales al repositorio remoto en GitHub. Este comando actualiza el repositorio remoto con los cambios realizados localmente, permitiendo que otros colaboradores accedan a la versión más reciente del código.
   - `git clone`: Clona un repositorio remoto desde GitHub (u otra plataforma) a la computadora local. Crea una copia completa del repositorio, incluyendo todo su historial de cambios, permitiendo al desarrollador trabajar en el proyecto de manera local.
   - `git init --initial-branch=main`: Inicializa un nuevo repositorio Git en el directorio actual y establece la rama principal con el nombre `main` en lugar de `master`.
   - `git remote add origin https://github.com/<user-name>/tarea-git-github.git`: Agrega un repositorio remoto llamado `origin` que apunta a la URL especificada en GitHub. Esto permite que el repositorio local se conecte con el repositorio remoto para subir y descargar cambios.
   - `git add .`: Agrega todos los archivos modificados en el directorio actual al área de preparación (staging area) para que estén listos para ser incluidos en el próximo commit.
   - `git commit -m "Initial commit"`: Crea un nuevo commit con el mensaje "Initial commit" que guarda todos los cambios agregados al área de preparación.
   - `git push --set-upstream origin main`: Sube los commits locales a la rama `main` del repositorio remoto llamado `origin` y establece esta rama como la rama predeterminada para futuros pushes.
6. ¿Qué es un archivo `README.md` y por qué es importante?

- Un archivo `README.md` es un documento escrito en formato Markdown que se encuentra en la raíz de un repositorio de código fuente. Su propósito principal es proporcionar información esencial sobre el proyecto, incluyendo una descripción general, instrucciones de instalación, uso, contribución y cualquier otra información relevante para los usuarios y desarrolladores que interactúan con el proyecto.
