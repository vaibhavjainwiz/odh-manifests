Open Data Hub Tier 1 Notebooks
===

All of the notebooks in this repo are supported by the ODH Community as a Tier 1 component but not part of the ODH Core deployment.
The source build files for any notebook in this repo must exist under the [opendatahub-io](https://github.com/opendatahub-io) organization

Notebooks:
===
* [Code Server Notebook ](https://github.com/opendatahub-io/notebooks/tree/main/codeserver) - Notebook image, allows to run Visual Studio Code (VSCode)
* [R Studio Notebook](https://github.com/opendatahub-io/notebooks/tree/main/rstudio) - Notebook image, integrated development environment (IDE) for R
* [CUDA R Studio Notebook](https://github.com/opendatahub-io/notebooks/tree/main/rstudio) - Notebook image, integrated development environment (IDE) for R with embedded CUDA capabilities

Deprecated Notebooks:
===
* [Elyra Notebook](https://github.com/opendatahub-io/s2i-lab-elyra) - Jupyter notebook image with Elyra-AI installed
It is no-longer shipped with ODH, as all the base notebook images (except minimal) contain are installed with Elyra-Plugin
