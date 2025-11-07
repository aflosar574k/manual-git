# Manual-git
Este repositorio explica todos los comandos basicos de Git.

---

## Índice de comandos
1. `git init` – Inicializa un repositorio local  
2. `git clone` – Clona un repositorio remoto  
3. `git add` – Añade archivos al área de preparación  
4. `git commit` – Guarda los cambios en el historial  
5. `git log` – Muestra el historial de commits  
6. `git checkout` – Cambia entre ramas o versiones  
7. `git branch` – Crea o lista ramas  
8. `git push` – Envía los cambios al remoto  
9. `git pull` – Descarga y fusiona cambios del remoto  
10. `git merge` – Fusiona ramas  

---

## git init
**Descripción:**  
Inicializa un repositorio Git en la carpeta actual, creando la carpeta oculta `.git` donde se guarda todo el historial del proyecto.  

---

## git clone
**Descripción:**  
Clona (copia) un repositorio remoto en tu ordenador, para tener una versión local del proyecto.  

**Uso:**
git clone <url-del-repositorio>

---

## git add
**Descripción:**
Añade los archivos modificados al área de staging (preparación), para incluirlos en el próximo commit.

**Uso:**
git add <archivo>
git add .

---

## git commit
**Descripción:**
Guarda en el historial los cambios añadidos al staging area.
Cada commit incluye un mensaje que describe lo que se ha modificado.

**Uso:**
git commit -m "Mensaje descriptivo"

---

## git log
**Descripción:**
Muestra el historial de commits realizados, con su hash, autor, fecha y mensaje.

**Uso:**
git log

---

## git checkout
**Descripción:**
Permite cambiar entre ramas o moverse a un commit anterior.
También puede crear una nueva rama si se usa con -b.

**Uso:**
git checkout <rama>
git checkout -b <nueva-rama>

---

## git branch
**Descripción:**
Sirve para crear, listar o eliminar ramas dentro de un repositorio.

**Uso:**
git branch              # lista ramas
git branch <nombre>     # crea una rama
git branch -d <rama>    # elimina una rama

---

## git push
**Descripción:**
Envía los commits locales al repositorio remoto (por ejemplo, a GitHub).

**Uso:**
git push origin <rama>

---

## git pull
**Descripción:**
Descarga los cambios del repositorio remoto y los fusiona con tu rama local actual.

**Uso:**
git pull origin <rama>

---

## git merge
**Descripción:**
Fusiona el contenido de una rama en otra.
Se usa, por ejemplo, para unir una rama de desarrollo con la rama principal.

**Uso:**
git merge <rama>





