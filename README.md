# Learning resources and workshop tutorials site

RAPID infrastructure and cybertraining for scientific research before the next hurricane season, [https://rapid.github.io](https://rapid.github.io)

## Technical notes for site development

* This documentation is built and deployed using [MkDocs](https://www.mkdocs.org/), and uses the markdown extension [admonition](https://squidfunk.github.io/mkdocs-material/extensions/admonition/) and the markdown plugin [markdownextradata](https://github.com/rosscdh/mkdocs-markdownextradata-plugin/)
* Install `mkdocs` and the markdown plugin from conda-forge: ```conda install -c conda-forge mkdocs mkdocs-markdownextradata-plugin```
* To develop locally: ```mkdocs serve```
* To publish to GitHub: ```mkdocs gh-deploy```
* Edit the `mkdocs.yml` file to customize the hackweek name and website to your particular event.
