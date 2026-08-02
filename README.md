# Proyecto 1 — Bioinformática

> **Curso:** Introducción a la Programación Científica **Programa:** Maestría en Bioinformática **Fecha:** Julio 2026

------------------------------------------------------------------------

## Descripción

Este proyecto es el primer trabajo práctico del curso de Introducción a la Programación Científica. El cual tiene como objetivo la creación de un repositorio que permita un flujo de trabajo estandarizado y la trazabilidad de los cambios. Posibilitando una comunicación y colaboración más eficiente en el proyecto.

Este es un proyecto ficticio de bioinformática cuyo objetivo es el uso de Git.

## Estructura del repositorio

```         
bioinformatica-proyecto1/
├── data/               # Datos de entrada (secuencias, tablas, etc.)
├── scripts/            # Scripts de análisis
├── results/            # Resultados generados (figuras, tablas)
├── README.md           # Este archivo
└── LICENSE
```

```         
## Integrantes

- Melisa Quesada Corza
- Jacob Israel Gonzalez Ruiz
```

## Instrucciones de uso

### Requisitos previos

- Python 3.9+ (o R 4.x según corresponda)
- Paquetes necesarios listados en `requirements.txt` (o `environment.yml`)

``` bash
# Clonar el repositorio
git clone https://github.com/MelSkywalker/bioinformatica-proyecto1.git
cd bioinformatica-proyecto1

# Crear entorno virtual (Python)
python -m venv venv
source venv/bin/activate

# Instalar dependencias
pip install -r requirements.txt
```

### Ejecución

``` bash
# Correr el script principal
python scripts/main.py --input data/sequences.fasta --output results/

# O abrir el notebook interactivo
jupyter notebook notebooks/analisis.ipynb
```

------------------------------------------------------------------------

## Datos

Los datos utilizados en este proyecto son de carácter ficticio.

------------------------------------------------------------------------

## Licencia

Este proyecto está bajo la licencia especificada en el archivo [LICENSE](LICENSE).
