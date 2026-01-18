# Actividad 3 — Configuración de un Entorno de Desarrollo Integrado (IDE)

**Alumno:** Raziel Osmar Sánchez Ruiz 
**Grupo:** 2DSM-G3  
**Fecha:** 18-ENERO-2026
**Unidad:** 1

## 1. IDE seleccionado
- IDE: Visual Studio Code  
- Versión: 1.107.1  
- Sistema operativo: Windows 10 / Windows 11 

## 2. Justificación
- Criterio 1: Visual Studio Code es un IDE ligero, rápido y fácil de usar para principiantes.
- Criterio 2: Cuenta con integración nativa con Git y GitHub, lo que facilita el control de versiones.
- Criterio 3: Dispone de una gran variedad de extensiones para diferentes lenguajes y tecnologías.

## 3. Requisitos previos
- Requisito 1: Sistema operativo Windows 10 o superior.
- Requisito 2: Conexión a internet para la descarga del IDE y extensiones.
- Permisos: Permisos de administrador para instalar software.

## 4. Instalación (paso a paso)
1. Accedí al sitio oficial de Visual Studio Code.
2. Descargué el instalador compatible con Windows.
3. Ejecuté el instalador y seguí las instrucciones por defecto hasta completar la instalación.

### 4.1 Verificación
- ¿Cómo comprobé que funciona?: Abrí Visual Studio Code desde el menú de inicio sin errores.
- Evidencia (captura o descripción): El IDE abrió correctamente y permitió crear un archivo nuevo.

## 5. Configuración inicial
### 5.1 Ajustes básicos
- Cambio de tema visual a un tema oscuro para mayor comodidad.
- Activación del guardado automático de archivos.

### 5.2 Extensiones / plugins

| Extensión/Plugin | Función | Por qué |
|---|---|---|
| GitLens | Mejora el uso de Git dentro del IDE | Facilita el control de versiones |
| Markdown Preview | Vista previa de archivos Markdown | Permite revisar el reporte correctamente |
| Spanish Language Pack | Traduce la interfaz al español | Mejora la comprensión del IDE |

### 5.3 Herramientas adicionales (si aplica)
- Compilador/intérprete: Git
- Prueba: Se ejecutó el comando `git --version` y se mostró la versión instalada.

## 6. Prueba final (mini-ejercicio)
```txt
git init
git status
```
## 7. Conclusiones
- Visual Studio Code es un IDE adecuado para proyectos académicos y personales.

- La integración con Git y GitHub facilita el control de versiones y el trabajo organizado.

## 8. Uso de Git y GitHub

Para el control de versiones del proyecto se utilizó Git, y como repositorio remoto se empleó la plataforma GitHub. Esto permitió llevar un registro de los cambios realizados y asegurar el respaldo del archivo Markdown de la actividad.

### 8.1 Inicialización del repositorio local
Una vez creada la carpeta del proyecto, se inicializó un repositorio Git local para comenzar el control de versiones. Este paso crea la estructura necesaria para que Git pueda rastrear cambios en los archivos.

Comando utilizado:
```bash
git init
```

### 8.2 Creación y preparación del archivo Markdown

El reporte técnico fue creado utilizando el formato Markdown con el nombre Actividad3_IDE.md.
Posteriormente, el archivo fue agregado al área de preparación (stage) para que pudiera ser incluido en un commit.

Comando Utilizado:
```
git add .
```
### 8.3 Registro de cambios (commit)

Después de agregar el archivo al stage, se realizó un commit para guardar el estado del proyecto con un mensaje descriptivo, lo cual permite identificar claramente el propósito del cambio realizado.

Comando utilizado:
```
git commit -m "Actividad 3: Configuración de IDE"

```

### 8.4 Creación del repositorio en GitHub

Se creó un repositorio público en GitHub desde el navegador web, con el nombre Actividad3_IDE, el cual serviría como repositorio remoto para alojar el proyecto.

### 8.5 Vinculación del repositorio local con GitHub

Una vez creado el repositorio en GitHub, se enlazó el repositorio local con el repositorio remoto mediante la URL proporcionada por GitHub, estableciendo la rama principal como main.

Comandos utilizados:
```
git branch -M main
git remote add origin https://github.com/TheRaziel/Actividad3_IDE.git

```

### 8.6 Subida del proyecto al repositorio remoto

Finalmente, se subieron los archivos del proyecto al repositorio remoto en GitHub, quedando disponible para consulta y evaluación.

Comando utilizado:
```
git push -u origin main

```



