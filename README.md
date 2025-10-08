# Proyecto de Herramientas Colaborativas (HC) – UD1

Bienvenidos al **proyecto colaborativo de HTML** para la Unidad Didáctica 1 de la asignatura **Herramientas Colaborativas (HC)**.  
En este ejercicio, aprenderemos a trabajar en equipo usando **Git** y **GitHub**, aplicando buenas prácticas de control de versiones.

---

## 📌 Objetivo del ejercicio

- Construir un **sitio web sencillo** con varias páginas HTML enlazadas.  
- Practicar el flujo de trabajo **real en Git**:
  - Ramas personales
  - Commits frecuentes
  - Push al repositorio remoto
  - Pull Requests (PR) revisados por el supervisor

---

## 📂 Estructura del proyecto

index.html
about.html
contact.html
README.md


- `index.html`   → Página principal  
- `about.html`   → Página “Sobre nosotros”  
- `contact.html` → Página “Contacto”  

> Cada alumno será responsable de una de estas páginas en su **rama personal**.

---

## 👥 Organización de los equipos

- **Supervisor:** Ja-Cam  
- **Equipo 1:** alumnos 1, 2 y 3  
- **Equipo 2:** alumnos 4, 5 y 6  
- **Equipo 3:** alumnos 7, 8 y 9  

Cada equipo trabaja en su propio repositorio:

- `HC-A1.5-Git-EQ1`  
- `HC-A1.5-Git-EQ2`  
- `HC-A1.5-Git-EQ3`  

> El supervisor, es el propietario de los repositorios y revisarás los PRs antes de integrarlos a `main`.

---

## 🌿 Ramas personales de alumnos

| Alumno | Página asignada     | Rama recomendada          |
|--------|-------------------|--------------------------|
| Alumno 1 | `index.html`      | `alumno1-index`          |
| Alumno 2 | `about.html`| `alumno2-about`          |
| Alumno 3 | `contact.html`| `alumno3-contact`      |

> Cada alumno trabaja **solo en su rama**. No se permite modificar directamente `main`.

---

## 🧭 Flujo de trabajo básico

1. Clonar el repositorio de tu equipo:

git clone <URL-del-repo>
cd <nombre-repo>


2. Crear tu rama personal:

git checkout -b alumnoX-page


3. Hacer cambios en tu página asignada y guardar con commits frecuentes:

git add archivo.html
git commit -m "Mensaje claro de lo que hiciste"


4. Subir tu rama al remoto:

git push origin alumnoX-page


5. Crear un Pull Request (PR), desde github, hacia main para que el supervisor revise y apruebe los cambios.

📌 Recuerda: nunca trabajar directamente en main.

📝 Recomendaciones:

- Mensajes de commit claros y descriptivos.
- Hacer commits frecuentes, no al final de todo.
- Revisar siempre la rama main antes de hacer push o PR.
- Esperar aprobación del supervisor antes de considerar tu trabajo “finalizado”.
