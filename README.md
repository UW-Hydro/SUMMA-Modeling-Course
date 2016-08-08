# The Art and Science of Hydrologic Modeling

[![Documentation Status](https://readthedocs.org/projects/summa-modeling-course/badge/?version=develop)](http://summa-modeling-course.readthedocs.io/en/develop/?badge=develop) [![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://raw.githubusercontent.com/UW-Hydro/SUMMA-Modeling-Course/develop/LICENSE.txt)

This web site serves as the source code repository for a hydrologic modeling course built around the Structure for Unifying Multiple Modeling Alternatives ([SUMMA](https://www.ral.ucar.edu/projects/summa)). This repository simply contains the code to build the course web site. To see the actual course, click on the `docs` button at the top of this README.

Unlike this file, which uses [github flavored Markdown](https://guides.github.com/features/mastering-markdown/), the actual course web site uses [Sphinx](http://www.sphinx-doc.org/) and [reStructuredText](http://docutils.sourceforge.net/rst.html). This should not matter to you if you just want to read the [course documents] (http://summa-modeling-course.readthedocs.io/en/develop/?badge=develop), but may be useful information if you want to contribute.

The repository is organized as follows:

| Directory | Contents |
| --- | --- |
| `.` | top level directory with this README, license information, etc. |
| `./docs` | directory with the course content. This will be automatically rendered by [readthedocs](http://readthedocs.org). You can also render the course material locally in various formats by using the `Makefile`. Type `make` in this directory for more information. You may need to install extra software for some of the rendering options. |
| `./docs/_static` | static html files and resources such as css files |
| `./docs/_templates` | reStructuredText `templates_path` |
