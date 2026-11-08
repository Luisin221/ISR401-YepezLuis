
# FORM-TL-01

## Taller de identificación y clasificación de tipos de requisitos

**Universidad:** Universidad Técnica Estatal de Quevedo (UTEQ)

**Carrera:** Software

**Asignatura:** Ingeniería de Requisitos (ISR-401)

**Estudiante:** Luis Yepez

**Periodo académico:** 2026-2027

**Tipo de actividad:** Formativa

**Semana:** 1

## Objetivo

Identificar y clasificar los requisitos de una plataforma de gestión de citas médicas, aplicando los fundamentos de Ingeniería de Requisitos y las normas ISO/IEC/IEEE 29148:2018 e ISO/IEC 25010:2023.

## Caso de estudio

Plataforma de gestión de citas médicas del Policlínico Ribera del Quevedo.

## Contenido

- Clasificación de 20 enunciados.
- Identificación de requisitos funcionales, de calidad y restricciones.
- Clasificación por producto/proceso y sistema/software.
- Análisis de características de calidad ISO/IEC 25010:2023.
- Identificación de requisitos ambiguos o no verificables.
- Reformulación de cinco requisitos de calidad.
- Sección de comparación de resultados.
- Referencias bibliográficas en formato IEEE.

## Archivos

| Archivo | Descripción |
|---|---|
| `main.tex` | Código fuente del informe en LaTeX. |
| `main.pdf` | Documento académico compilado. |
| `referencias.bib` | Referencias bibliográficas. |
| `README.md` | Descripción e instrucciones de compilación. |

## Requisitos para compilar

Se necesita una distribución de LaTeX, como TeX Live o MiKTeX, que incluya:

- pdfLaTeX.
- Biber.
- biblatex.
- babel con soporte para español.
- Los paquetes utilizados en `main.tex`.

## Instrucciones de compilación

1. Clonar el repositorio:

```bash
git clone https://github.com/Luisin221/ISR401-YepezLuis.git
```

2. Acceder a la carpeta del proyecto:

```bash
cd ISR401-YepezLuis/FORM-TL-01
```

3. Compilar el documento ejecutando los siguientes comandos en orden:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El archivo principal es `main.tex`.

El resultado será `main.pdf`, con las referencias bibliográficas procesadas mediante Biber.

También puede utilizarse Overleaf, configurando `main.tex` como documento principal.

## Referencias

- ISO/IEC/IEEE 29148:2018.
- ISO/IEC 25010:2023.
- Klaus Pohl, Requirements Engineering, segunda edición.

## Estado de la actividad

El documento incluye la clasificación de los requisitos y las propuestas de mejora.

La comparación con un compañero permanece pendiente.

## Repositorio

https://github.com/Luisin221/ISR401-YepezLuis
