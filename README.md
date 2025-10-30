# Introducción a Quarto y VS Code

Este repositorio contiene el material para la charla "Introducción a Quarto y VS Code" del 30 de octubre de 2025.


## Descripción

Este repositorio contiene los materiales de la charla **"Introducción a Quarto y VS Code"** celebrada el 30 de octubre de 2025 en la Universidad de Granada. El objetivo es proporcionar una guía práctica para utilizar [Quarto](https://quarto.org) junto con [Visual Studio Code](https://code.visualstudio.com) como entorno de edición y publicación para documentos científicos y técnicos.

---

## Contenido

- **slides_quarto_1.qmd**  
  Presentación (en formato Quarto RevealJS) que cubre los siguientes temas:
    - Instalación de Quarto, VS Code y extensiones necesarias
    - Fundamentos de Markdown y Quarto Markdown (`.qmd`)
    - Ejemplos de sintaxis básica y avanzada
    - Código reproducible (Python, R)
    - Funciones de publicación multiplataforma (HTML, PDF, presentaciones)

- **styles.css**  
  Estilos CSS para personalizar tablas y formato visual de la presentación.

---

## Requisitos

- [Quarto CLI](https://quarto.org/docs/get-started)
- [Visual Studio Code](https://code.visualstudio.com/download)
- Extensión de Quarto para VS Code  
  (Busque *Quarto* en el Marketplace de extensiones)

**(Opcional para código ejecutable):**
- Python y/o R con los intérpretes configurados.

---

## Visualización rápida

Puedes ver la presentación ejecutando en terminal:

```bash
quarto preview slides_quarto_1.qmd
```

O renderizando el archivo:

```bash
quarto render slides_quarto_1.qmd
```

Abriendo `slides_quarto_1.html` o ejecutando un servidor local se puede presentar en vivo con RevealJS.

---

## Recursos adicionales

- [Documentación de Quarto](https://quarto.org/docs/)
- [Guía rápida de Markdown](https://markdownlivepreview.com)
- Ejemplos y plantillas en [quarto.org/docs/gallery](https://quarto.org/docs/gallery)

---

**© F. J. Martínez-Murcia, 2025**  [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)   
