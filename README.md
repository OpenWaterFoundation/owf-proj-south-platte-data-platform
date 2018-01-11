# owf-project-south-platte-data-platform #

This repository contains the [Open Water Foundation (OWF)](http://openwaterfoundation.org/) project website content for
the South Platte Data Platform, which is a project funded by the
[Colorado Water Conservation Board](http://cwcb.state.co.us) through its Water Supply Reserve Fund grant program.
The project website is being maintained in version control on GitHub and uses MkDocs in order to streamline deployment of the
website to coordinate the project and provide access to preliminary products prior to deployment
to a system integrated with South Platte/Metro Roundtable.

See the deployed website [OWF / Projects](http://projects.openwaterfoundation.org/owf-proj-south-platte-data-platform/).

## Repository Contents ##

The repository contains the following:

```text
.github/              (Files specific to GitHub such as issue template)
.gitattributes        (Typical Git configuration file)
.gitignore            (Typical Git configuration file)
README.md             (This file)
build-util/           (Useful scripts to view, build, and deploy documentation)
mkdocs-project/       (Typical MkDocs project for this documentation)
  mkdocs.yml          (MkDocs configuration file for website)
  docs/               (Folder containing source Markdown and other files for website)
  site/               (Folder created by MkDocs containing the static website - ignored using .gitignore)

```

## Development Environment ##

The development environment for contributing to this project requires installation of Python, MkDocs, and Material MkDocs theme.
Python 2 on Cygwin has been used for development but other comparable environments should work.

## Editing and Viewing Content ##

If the development environment is properly configured, edit and view content as follows:

1. Edit content in the `mkdocs-project/docs` folder and update `mkdocs-project/mkdocs.yml` as appropriate.
2. Run the `build-util/run-mkdocs-serve-8000.sh` script (Cygwin) or equivalent.
3. View content in a web browser using URL `http://localhost:8000`.

## License ##

The OWF Learn MkDocs website content and examples are licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0).

## Contributing ##

Contribute to the project documentation as follows:

1. Use GitHub repository issues to report minor issues.
2. Use GitHub pull requests.

## Maintainers ##

This repository is maintained by the [Open Water Foundation](http://openwaterfoundation.org/).

## Contributors ##

* Steve Malers, Open Water Foundation (@smalers)
* Kristin Swaim, Open Water Foundation (@kswaim)

## Release Notes ##

The following release notes indicate the update history for documentation, with GitHub repository issue indicated,
if applicable (links to issues via README.md are not cleanly supported by GitHub so use the repository issues page to find).

* 2018-01-11 - add transbasin diversions dataset and update committee contacts
* 2017-12-13 - update committee list information
* 2017-11-25 - added dataset diagrams to illustrate how datasets are related and added additional GitHub dataset links
* 2017-10-29 - initial content
