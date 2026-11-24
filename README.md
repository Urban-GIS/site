# Urban GIS and Visual Tools

This repository contains the source files for the course [Urban GIS and Visual Tools (USP-303)](https://studies.helsinki.fi/courses/course-unit/otm-dd8857e3-61df-4b67-8d0c-45c15302d9c5) at the [University of Helsinki](https://www.helsinki.fi/). The course is a 5-credit introductory course in the [Master's Programme in Urban Studies and Planning (USP)](https://www.helsinki.fi/en/degree-programmes/urban-studies-and-planning-masters-programme), offered in cooperation with Aalto University. It introduces the principles and practices of geographic information systems (GIS) through urban questions, data, and visual communication.

The course materials are openly available at **[urbangis.readthedocs.io](https://urbangis.readthedocs.io/)**. Course registration, assessment, submissions, and implementation-specific communication are handled through the University of Helsinki's course systems.

## Course content

The course begins with a two-week QGIS bootcamp, followed by weekly lessons and practicals on urban topics such as map design, density, socio-economic structure, urban planning, participatory mapping, accessibility, GIS automation, and web maps. It ends with a final project.

## Repository structure

- `docs/` – the course website (Sphinx, with the pages written as Jupyter notebooks)
  - `course-info/` – general information, schedule, grading, and course policies
  - `lessons/` – the bootcamp and the weekly lessons and practicals
  - `final-project/` – the final project
- `.readthedocs.yaml` – build configuration for Read the Docs

To build the site locally:

```bash
pip install -r docs/requirements.txt
cd docs
make html
```

## Terms of use

© 2026 Kamyar Hasanzadeh, University of Helsinki. All rights reserved. The teaching materials may be used and adapted for non-commercial purposes, provided that the source is acknowledged. See [LICENSE](LICENSE) and the [licence and terms of use](https://urbangis.readthedocs.io/en/latest/course-info/license.html) for details.

## Contact

This course was created by [Kamyar Hasanzadeh](https://www.kamyarhz.com/), University Lecturer in Geoinformatics and Docent in Urban Informatics at the University of Helsinki, and its development was supported by the Master's Programme in Urban Studies and Planning. Contact information is on the [general information page](https://urbangis.readthedocs.io/en/latest/course-info/general-info.html).
