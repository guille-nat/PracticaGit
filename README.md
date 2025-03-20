# 🚀 Práctica de Git: Trabajo en Equipo

## 📌 Introducción

Esta práctica de Git simula un escenario real de trabajo en equipo sobre un proyecto, enfrentando distintas situaciones que deben resolverse colaborativamente.

> **Antes de comenzar, es fundamental leer todo el enunciado.**

---

## 🔧 Preparación

### 1️⃣ Crear Repositorio en GitHub

- Crear un repositorio nuevo en GitHub y nombrarlo **"PracticaGit"**.

### 2️⃣ Clonar el Repositorio

- Cada miembro del equipo debe clonar el repositorio en su máquina local usando:

  ```bash
  git clone https://github.com/usuario/PracticaGit.git
  ```

---

## 🎯 Tareas de Práctica

### 📂 1. Crear Archivos

- Cada miembro debe crear una **nueva rama de desarrollo** y trabajar en ella:

  ```bash
  git checkout -b nombre_rama
  ```

- En la rama creada, generar **4 archivos de texto plano**:

  ```bash
  touch archivo1.txt archivo2.txt archivo3.txt archivo4.txt
  ```

- Agregar contenido a los archivos y guardar los cambios.

### ⬆️ 2. Subir Cambios al Repositorio

- Agregar los archivos al control de versiones:

  ```bash
  git add .
  ```

- Commit con un mensaje descriptivo:

  ```bash
  git commit -m "Añadiendo archivos iniciales"
  ```

- Subir la rama al repositorio remoto:

  ```bash
  git push origin nombre_rama
  ```

### 🔄 3. Fusionar Ramas con `main/master`

- Un miembro del equipo debe **fusionar** cada rama con `main/master`:

  ```bash
  git checkout main
  git merge nombre_rama
  ```

- Resolver posibles **conflictos** y confirmar los cambios.
- Subir la rama `main/master` actualizada:

  ```bash
  git push origin main
  ```

### ✍️ 4. Modificar Archivos Nuevamente

- Cada miembro debe:
  1. Descargar la última versión de `main/master`.
  2. Crear **otra nueva rama de desarrollo**.
  3. Modificar los archivos con contenido diferente.
  4. Commits, merge y push compartiendo pantalla con los demás.

### 💡 5. Practicar Comandos Útiles de Git

Durante el proceso, utilizar comandos como:

- Ver el estado del repositorio:

  ```bash
  git status
  ```

- Ver historial de commits:

  ```bash
  git log --oneline --graph
  ```

- Ver ramas disponibles:

  ```bash
  git branch
  ```

- Cambiar entre ramas:

  ```bash
  git checkout nombre_rama
  ```
