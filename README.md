# Gitlab-PDF

<img src="img/logo.png" alt="" align="center" width="200"/>


Generación de Artefactos PDF con GitLab CI/CD.

> **Nota**: Para obtener más detalles sobre GitLab CI/CD, consulta el siguiente artículo [enlace]().

## ¿Por qué utilizar GitLab CI/CD?
El propósito principal es versionar todos los avances de los archivos LaTeX (`.tex`)
utilizando GitLab en lugar de GitHub. Esto se debe a que al emplear la funcionalidad de CI/CD de GitLab, los artefactos permanecen disponibles durante un período de tiempo mucho más prolongado, sin expirar, a diferencia de GitHub,
donde los artefactos tienen una duración máxima de 90 días.

> **Nota**: Puedes obtener más información sobre los artefactos en GitLab en [GitLab Artifacts](https://docs.gitlab.com/ee/ci/jobs/job_artifacts.html) y en GitHub en [Github Artifacts](https://docs.github.com/en/rest/actions/artifacts?apiVersion=2022-11-28).
## Proyectos

| Nombre                                                 | Descripción                                                               | Artefactos                                                                                                                                                                                                                                                  |
|--------------------------------------------------------|---------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [cv](https://gitlab.com/fralfaro/cv)                   | Un Pipeline de integración continua para obtener un buen CV sin esfuerzo. | <a href="https://gitlab.com/fralfaro/cv/-/jobs/artifacts/main/browse?job=generate_pdf" target="_parent"><img src="https://img.shields.io/badge/gitlab%20ci-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white" alt="Open In Colab"/></a>         |
| [dmat-latex](https://gitlab.com/fralfaro/dmat-latex)   | Plantillas LaTeX: Tarea, Beamer (DMAT - UTFSM).                           | <a href="https://gitlab.com/fralfaro/dmat-latex/-/jobs/artifacts/main/browse?job=generate_pdf" target="_parent"><img src="https://img.shields.io/badge/gitlab%20ci-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white" alt="Open In Colab"/></a> |

