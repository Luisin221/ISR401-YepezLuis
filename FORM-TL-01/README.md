
# FORM-TL-01

## Taller de identificación y clasificación de tipos de requisitos

**Asignatura:** Ingeniería de Requisitos (ISR-401)

**Estudiante:** Luis Yepez

**Tipo de actividad:** Formativa

**Semana:** 1

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

**Archivo principal:** `main.tex`

**Compilador:** pdfLaTeX

**Gestor bibliográfico:** Biber

**Secuencia de compilación:**

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El resultado será `main.pdf`, con las referencias bibliográficas procesadas mediante Biber.

También puede utilizarse Overleaf, configurando `main.tex` como documento principal.

## Referencias

- ISO/IEC/IEEE 29148:2018.
- ISO/IEC 25010:2023.
- Klaus Pohl, Requirements Engineering, segunda edición.


