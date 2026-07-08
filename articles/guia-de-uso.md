# Guía de uso: Plantillas Aru

## Instalación

Para comenzar a utilizar las plantillas de `aruResearch`, instala el
paquete directamente desde GitHub:

``` r

# Si no tienes instalado 'remotes', instálalo primero
install.packages("remotes")

# Instalar aruResearch
remotes::install_github("AlvaroLimber/aruResearch")
```

## Cómo crear un nuevo reporte

Una vez instalado el paquete, tus plantillas estarán disponibles
directamente desde RStudio:

1.  Ve a **File \> New File \> R Markdown…**
2.  Selecciona **From Template** en el menú lateral izquierdo.
3.  Elige tu plantilla de `aruResearch` en la lista.
4.  Haz clic en **OK**.

Esto abrirá un nuevo archivo `.Rmd` con la estructura y configuración
predefinida de la Fundación Aru.

## Requisitos previos

Asegúrate de tener instalado el sistema de procesamiento de documentos
(como TinyTeX) si tus plantillas generan PDFs, para evitar errores de
compilación:

``` r

if (!requireNamespace("tinytex", quietly = TRUE)) install.packages("tinytex")
tinytex::install_tinytex()
```
