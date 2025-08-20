# TALLER DE NIVELACIÓN PI A PII
 Parte Teorica 

 ¿ Que es Markdown?

Markdown es un lenguaje de marcado ligero que permite dar formato a
texto plano (legible en cualquier dispositivo) de forma sencilla y legible,
convirtiéndose fácilmente en HTML. Su sintaxis es muy sencilla, intuitiva y potente, ya que está formada por caracteres simples fáciles de recordar (por ejemplo, #, *, [], etc).


# 1. ¿Que es un repositorio en Git y como se diferencia de un proyecto "normal"?

 Un repositorio en Git es un espacio donde se almacena todo el historial de cambios de un proyecto (commits,ramas,versiones), un proyecto normal solo tiene los archivos actuales, sin historial ni control de versiones, Git añade esa memoria y herramientas para colaborar.

 # 2. ¿Cuales son las 3 areas principales de Git (Working Directory, Stanging Area/ Index y Repository) ¿ Que papel cumple cada una?

 Working Directory: Donde trabajas y editas los archivos.
 Staging Area: Area intermedia donde eligues que cambios quieres guardar.
 Repository: El hitorial definitivo de commits ya confirmados.

 # 3. ¿Como representa Git los cambios internamente? (Objetos blob, tree commit y tag)

 Blob: Contenido de un archivo.
 Commit: Captura de un estado del proyecto,enlaza blobs y trees.
 Tag: Etiqueta que marca un commit importante version.

 # 4. ¿Como se crea un commit y que informacion almacena un objeto commit?

 git add <archivo>
git commit -m "mensaje"

Un commit guarda: autor, fecha, mensaje, puntero al commit anterior y snapshot de los archivos seleccionados.

# 5. ¿Cuál es la diferencia entre git pull y git fetch?

git fetch: trae cambios remotos pero no los mezcla con tu trabajo.
git pull: trae y automáticamente mezcla los cambios en tu rama actual.

# 6. ¿Qué es un branch (rama) en Git y cómo Git gestiona los punteros a commits?

Un branch es una linea de desarrollo independiente Git maneja ramas como punteros a commits que avanzan cuando hacen nuevos commits.

# 7. ¿Cómo se realiza un merge y qué conflictos pueden surgir? ¿Cómo se resuelven?

Merge y conflictos:
Un merge combina dos ramas.
Conflictos surgen cuando el mismo archivo fue editado en partes incompatibles.
Se resuelven editando manualmente el archivo en conflicto y confirmando el merge.

# 8. ¿Cómo funciona el área de staging (git add) y qué pasa si omito este paso?

El staging selecciona qué cambios entrarán en el commit.Si lo omites, los cambios no entran al commit (aunque existen en tu carpeta).

# 9.¿Qué es el archivo .gitignore y cómo influye en el seguimiento de archivos?

Lista de archivos o carpetas que Git debe ignorar (ej. temporales, configuraciones locales). Evita que se suban al repositorio.

# 10. ¿Cuál es la diferencia entre un “commit amend” (--amend) y un nuevo commit?

--amend: modifica el último commit (mensaje o archivos).
Nuevo commit: crea un registro adicional en el historial.

# 11. ¿Cómo se utiliza git stash y en qué escenarios es útil?

Guarda temporalmente tus cambios sin hacer commit y limpia el directorio de trabajo,es útil cuando necesitas cambiar de rama sin perder lo que estabas haciendo.

# 12. ¿Qué mecanismos ofrece Git para deshacer cambios (por ejemplo, git reset, git revert, git checkout)?

git reset: mueve la rama a un commit anterior (puede borrar historial).
git revert: crea un commit nuevo que revierte otro.
git checkout: restaura archivos a un estado anterior sin borrar historial.

# 13.  ¿Cómo funciona la configuración de remotos (origin, upstream) y qué comandos uso para gestión de forks?

origin: el repositorio principal clonado.
upstream: el repositorio original del que se hizo fork.
Comandos útiles:
git remote add upstream <url>
git fetch upstream
git merge upstream/main

# 14. ¿Cómo puedo inspeccionar el historial de commits (por ejemplo, git log, git diff, git show)?

git log: lista de commits.
git diff: muestra diferencias entre versiones.
git show <commit>: muestra detalles de un commit específico.


# PROGRAMACIÓN 

# 15. ¿Cuales son los tipos de datos primitos en JAVA?

Lo mas basicos son estos: no son objetos.

Enteros: byte, short, int, long
Decimales: float, double
Carácter: char
Booleano: boolean

# 16. ¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en JAVA?

if / else: ejecutan un bloque de código según una condición.
switch: selecciona qué bloque ejecutar según el valor de una variable.
bucles (for, while, do-while): repiten instrucciones mientras se cumpla una condición.

# 17. ¿Por qué es importante usar nombres significativos para variables y métodos?

Porque hacen el código más claro, entendible y mantenible, facilitando el trabajo en equipo y evitando confusiones.

# 18. ¿Qué es la Programación Orientada a Objetos (POO)?

Es un paradigma de programación que organiza el código en objetos, los cuales combinan atributos (datos) y métodos (funciones).

# 19. ¿Cuáles son los cuatro pilares de la Programación Orientada a Objetos?

Encapsulamiento → proteger datos internos.
Abstracción → ocultar detalles y mostrar lo esencial.
Herencia → reutilizar código de una clase en otra.
Polimorfismo → usar un mismo método con comportamientos distintos.

# 20. ¿Qué es la herencia en POO y cómo se utiliza en Java?

Es cuando una clase (hija) puede heredar atributos y métodos de otra clase (padre).En Java se usa con la palabra clave extends.

# 21. ¿Qué son los modificadores de acceso y cuáles son los más comunes en Java?

Definen la visibilidad de clases, métodos o variables:

public: accesible desde cualquier parte.
private: solo dentro de la misma clase.
protected: accesible desde la misma clase, paquete o subclases.
default (sin palabra clave): accesible solo dentro del mismo paquete.

# 22. ¿Qué es una variable de entorno y por qué son importantes para JAVA o la programación general?

Es un valor configurado en el sistema operativo que influye en cómo se ejecutan los programas.En Java, por ejemplo, son importantes para ubicar el JDK, JRE o librerías, asegurando que el compilador y la máquina virtual funcionen correctamente.



