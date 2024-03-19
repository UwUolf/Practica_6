## Practica 8

### 1. ¿Cómo se inicializa un repositorio en Git?
Usando el comando **_git init_** en tu terminal de comandos.

### 2. ¿Cómo creas un repositorio en GitHub?
Una vez entrando a tu cuenta del lado izquierdo podremos encontrar un botón para crear el nuevo repositorio.

  ![Git hub home page](https://kinsta.com/wp-content/uploads/2023/02/create-github-repository-1024x505.png)

Esto nos llevará a otra página donde podremos configurar nuestro nuevo repositorio, dándole nombre, estableciendo si es público o no, e incluso establecer una lisencia.

  ![Creando nuevo repositorio](https://kinsta.com/wp-content/uploads/2023/02/new-repository-1024x760.png)

### 3. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
Después de haber creado nuestro nuevo repositorio, git hub nos proporcioará un link con el que podremos vincular el local con el remoto usando el código **_git remote add origin https://github.com/usuario/repositorio.git_**.

  ![Link repositorio remoto](https://kinsta.com/wp-content/uploads/2023/02/ssh-github-connection.png)

### 4. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
 El flujo básico de git y github se divide en 4:
  1. **Working directory** : Es donde podemos encontrar al estado **_Modified_** y es cuando estamos trabajndo en nuestro reositorio local y todo se guarda en nuestro dispositivo actual.

  1. **Staging** : Aquí se encuentra el estado **_Staged_** y es cuando subimos nuestros cambios a git antes de que los guarde .
  1. **Local Repository** : Es donde se encuentra el estado **_Commited_** y es cuando los cambios han sido guardados por git.
  1. **Remote Repository** : Aquí el estado cambia a **_Remote_** y es cuando subimos los cambios de nuestro repositori a uno remoto usando alguna página web.

### 5. ¿Para qué sirve el archivo .gitignore?
Se usa cuando creamos un archivo, pero no queremos que se suba a nuestro repositorio o genere algún cambio.

### 6. ¿Cuál es el propósito de una rama?
Las ramas son usadas cuando queremos crear funciones externas a nuestra rama principal y que posteriormente podremos agregárle a la misma.

### 7. ¿Qué es una fusión?
La fusiones son la implementación de los cambios de una rama a otra.

### 8. Explica los diferentes tipos de fusión que existen.
Existen 2 tipos de escenarios cuando realizamos una fusión:
1. **Fast-Forward** : La fusión es automática, y ocurre cuando no se presenta ningún problema o incongruencia. 
2. **Manual Merge** : La fusión la tenemos que hacer de forma manual, y ocurre cuando se encuentra algún archivo duplicado con contenido diferente y hay que establecer que cambiós serán implementados y cuales no.

### 9. ¿Cómo puedes ver el historial de tu repositorio?
Para poder ver nuestro historial hacemos el uso de una variedad de comandos en nuestra terminal, siendo estos:

  1. **_git log_** : Nos muestra el historial de forma completa y detallada.

  1. **_git log --oneline_** : Nos muestra el historial en una sola linea.
  1. **_git log -n_** : Muestra el número de cambios que indicamos en _-n_.
  1. **_git log --after "2024-07-07 00:00:00"_** : Muestra los cambios hechos después de la feha y hora escrita.
  1. **_git log --before "2024-07-07 00:00:00"_** : Muestra los cambios hechos antes de la fecha y hora escrita.
### 10. ¿Cuál es el propósito de una etiqueta?
Las etiquetas las usamos cuando queremos dividir nuestro repositorio en versiones del mismo.