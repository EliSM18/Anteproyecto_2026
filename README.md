# Anteproyecto 

**Desarrollo de plataforma web para gestión de viviendas en arrendamiento en Miahuatlán de Porfirio Díaz, Oaxaca**

Anteproyecto de tesis para obtener el título de Licenciatura en Informática en la Universidad de la Sierra Sur (UNSIS).

- **Autoras:** Castellanos Pacheco Mayra y Sánchez Martínez Elisa
- **Formato:** clase `huthesis` 
- **Referencias:** APA 7 en español con `biblatex` + `biber`

## Estructura

```
main.tex                 Documento principal (datos de portada, paquetes, orden de capítulos)
Portada.sty              Diseño de la portada
huthesis.cls, hut12.clo  Clase del documento
bibliografia.bib         Referencias bibliográficas
capitulos/               Capítulos, apéndices, glosario y acrónimos
images/, logos/          Figuras y logotipos
defmat.tex, seppal.tex   Definiciones matemáticas y separación de palabras
cronograma.tex           Cronograma (pendiente de adaptar; no se incluye en main.tex)
```

## Compilación

Se necesita una distribución de LaTeX (MiKTeX o TeX Live) con `biber`.

```sh
pdflatex main
biber main
pdflatex main
pdflatex main
```

También se puede usar `latexmk -pdf main`. El resultado es `main.pdf`.

## Estado actual

| Apartado | Estado |
|---|---|
| Título de la investigación | Terminado |
| Antecedentes | Casi Terminado (falta agregar cifras para robustecer los antecedentes) |
| Planteamiento del problema | Casi Terminado (falta citar la fuente de la matrícula de la UNSIS) |
| Justificación | Por aprobar |
| Objetivos general y específicos | Por aprobar |
| Hipótesis | En proceso |
| Marco teórico | Pendiente |