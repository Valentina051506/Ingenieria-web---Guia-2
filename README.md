# Ingeniería Web

Este proyecto presenta una página web básica desarrollada en HTML5, cuyo objetivo es aplicar correctamente la estructura semántica, siguiendo buenas prácticas de accesibilidad, organización del contenido y estándares web.

Por otro lado, se está desarrollando un proyecto con arquitectura web donde se resolverá una problemática del mundo real, documentada y analizada a lo largo de las diferentes etapas del proceso de ingeniería de software.

---

## Etapas del Proyecto

### Etapa 1 – Análisis del Sistema
El documento [`docs/etapa1 y 2.pdf`](docs/etapa1%20y%202.pdf) contiene el análisis inicial del sistema e incluye:
- El problema que se quiere resolver
- Los usuarios del sistema
- La entrada, el proceso y la salida del sistema
- El alcance del sistema

En esta etapa se define el contexto general del proyecto y se justifica la necesidad de la solución.

### Etapa 2 – Requisitos del Sistema
El documento [`docs/etapa1 y 2.pdf`](docs/etapa1%20y%202.pdf) contiene la especificación de los requisitos del sistema e incluye:
- Requisitos funcionales
- Requisitos no funcionales
- Actores del sistema

En esta etapa se detallan las funcionalidades que debe cumplir la aplicación y las características de calidad que debe garantizar.

Arquitectura del Sistema

El sistema se desarrollará bajo una arquitectura en capas, con el objetivo de separar responsabilidades y facilitar el mantenimiento, la escalabilidad y la evolución del software.

La arquitectura estará compuesta por las siguientes capas:

Capa de Presentación:
Encargada de la interfaz de usuario y la interacción con los miembros del grupo familiar.

Capa de Lógica de Negocio:
Contiene las reglas del sistema, como el registro de desacuerdos, gestión de acuerdos y validaciones.

Capa de Acceso a Datos:
Responsable de la persistencia de la información en la base de datos, garantizando la integridad y seguridad de los datos.

Esta arquitectura permite cumplir los requerimientos no funcionales relacionados con mantenibilidad, seguridad y escalabilidad, además de facilitar futuras modificaciones.

---

## Diagramas

Dentro de la carpeta `/diagrams` se encuentran:
- Diagrama de casos de uso
- Diagrama de secuencia
- Diagrama de clases

---

## Contenido del Proyecto

| Archivo / Carpeta | Descripción |
|---|---|
| `index.html` | Archivo principal con la estructura semántica del sitio. Descargar para visualizar. |
| `README.md` | Instrucciones de uso y explicación del proyecto. |
| `docs/etapa1 y 2.pdf` | Documento consolidado con el análisis y los requisitos del sistema (etapas 1 y 2). |
| `markdown-preview.pdf` | Propósitos, ventajas e importancia de la separación cliente-servidor. |
| `Diagrama de proyecto web profesional` | Diagrama de estructura de un proyecto web profesional. |
| `preguntas orientadoras` | Respuestas a las preguntas orientadoras de la guía propuesta. |

---

## Cómo clonar el proyecto

Clonar un repositorio significa descargar una copia completa del proyecto en tu computador, incluyendo todos los archivos y el historial de cambios de Git.

### Requisitos previos
Antes de clonar, asegúrate de tener instalado:
- [Git](https://git-scm.com/downloads) — puedes verificarlo ejecutando `git --version` en tu terminal.
- Un editor de código como [Visual Studio Code](https://code.visualstudio.com/) (opcional, pero recomendado).

### Pasos para clonar

**1. Abre la terminal**
- En Windows: usa **Git Bash** o el **Símbolo del sistema (cmd)**.
- En Mac/Linux: usa la **Terminal**.

**2. Navega a la carpeta donde quieres guardar el proyecto**
```bash
cd ruta/de/tu/carpeta
# Ejemplo: cd Documents/mis-proyectos
```

**3. Ejecuta el comando de clonación**
```bash
git clone https://github.com/Valentina051506/Ingenieria-web.git
```
Esto creará una carpeta llamada `Ingenieria-web` con todo el contenido del repositorio.

**4. Entra a la carpeta del proyecto**
```bash
cd Ingenieria-web
```

**5. Abre el proyecto en tu editor (opcional)**
```bash
code .
```
> El comando `code .` abre la carpeta actual en Visual Studio Code.

### ¿Qué hacer después de clonar?
- Abre el archivo `index.html` en tu navegador para visualizar la página web.
- Revisa la carpeta `docs/` para leer el análisis y los requisitos del sistema.
- Consulta la carpeta `diagrams/` para ver los diagramas del proyecto.

### ¿Quieres contribuir o guardar tus propios cambios?
Si realizas modificaciones y deseas registrarlas en Git, usa:
```bash
git add .
git commit -m "descripción de tus cambios"
git push origin main
```
