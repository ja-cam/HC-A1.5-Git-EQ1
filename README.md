# Proyecto de Herramientas Colaborativas (HC) – UD1, Ejercicio 1

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


- `index.html` → Página principal  
- `pages/about.html` → Página “Sobre nosotros”  
- `pages/contact.html` → Página “Contacto”  

> Cada alumno será responsable de una de estas páginas en su **rama personal**.

---

## 👥 Organización de los equipos

- **Equipo A:** alumnos 1, 2 y 3  
- **Equipo B:** alumnos 4, 5 y 6  

Cada equipo trabaja en su propio repositorio:

- `HC_UD1_Ej1_EquipoA`  
- `HC_UD1_Ej1_EquipoB`  

> Tú, como supervisor, serás el propietario de ambos repositorios y revisarás los PRs antes de integrarlos a `main`.

---

## 🌿 Ramas personales de alumnos

| Alumno | Página asignada     | Rama recomendada          |
|--------|-------------------|--------------------------|
| Alumno 1 | `index.html`      | `alumno1-index`          |
| Alumno 2 | `pages/about.html`| `alumno2-about`          |
| Alumno 3 | `pages/contact.html`| `alumno3-contact`      |

> Cada alumno trabaja **solo en su rama**. No se permite modificar directamente `main`.

---

## 🧭 Flujo de trabajo básico

1. Clonar el repositorio de tu equipo:

```bash
git clone <URL-del-repo>
cd <nombre-repo>

