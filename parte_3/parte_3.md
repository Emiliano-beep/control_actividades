git status = Verificar el estado actual del repositorio
git add README.md = Sirve para mandar a STAGE el archivo para despues hacerle un commit y despues un push
git commit -m "Actualiza documentación" = Crea un punto en el historial del repositorio
git push = Sube a github los archivos

2. Identifica qué falta
Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push
Indica qué operación falta y explica su función.

R = Falto el git commit -m "**********". Sirve para poner un punto en el historial del repositorio.

Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local
Indica qué operación utilizarías y explica por qué.

R = Git clone para que se duplique el repositorio..

Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado

R = Git pull, para que se sincronize los datos.


