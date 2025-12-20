---
layout: project
type: project
image: ../img/cookiecutter/nanosystems-logo-square.png
title: "Nanosystems Lab Cookiecutter"
date: 2024
published: true
labels:
  - Templating
  - Python
summary: "A Cookiecutter template for the Nanosystems Lab's Python packages."
---

<div class ="rounded float-start text-center p-4">
    <img height="300" src="../img/cookiecutter/github.png">
</div>

This project focused on developing and deploying a standardized Python library template to improve software quality, consistency, and efficiency within the Nanosystems Laboratory at the University of Hawaii at Manoa. The lab relies heavily on Python-based software libraries for lab automation and experimental control, but prior workflows suffered from inconsistent project structures, manual setup overhead, and error-prone deployment processes. To address this, I customized and extended the [Hypermodern Python Cookiecutter](https://github.com/cjolowicz/cookiecutter-hypermodern-python) framework into a lab-specific template that automatically generates well-structured Python projects with modern best practices, including testing, documentation, and CI/CD pipelines.

<div class ="rounded float-end text-center p-4">
    <img height="400" src="../img/cookiecutter/pypi.png">
</div>

My primary contribution was evaluating existing templating tools, selecting the feature-rich Hypermodern Python Cookiecutter as the template foundation, and modifying it to align with the lab’s requirements. This included expanding Python version support to 3.9–3.12, replacing third-party CLI tooling with Python’s built-in argparse module for improved compatibility, and adding dynamic configuration options during project generation. I validated the template by migrating several of the lab's existing automation libraries to the new structure, writing unit tests, and ensuring successful publication to PyPI. I also created a user guide to simplify adoption by lab members with varying levels of Python experience.

Through this project, I gained practical experience with Python packaging ecosystems ([Poetry](https://python-poetry.org/), [PyPI](https://pypi.org/)), testing ([Nox](https://nox.thea.codes/en/stable/)), CI/CD automation ([Github Actions](https://github.com/features/actions)), and documentation ([Sphinx](https://www.sphinx-doc.org/en/master/)). Beyond technical skills, the project taught me how to balance usability and features, document workflows, and gather user feedback. to balance feature richness with usability, document complex workflows clearly, and gather user feedback to iteratively improve tooling. It reinforced the importance of standardization and automation in research software environments, particularly when multiple contributors and long-term maintenance are involved.