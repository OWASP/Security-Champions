# OWASP Security Champions Guide

[![OWASP Incubator](https://img.shields.io/badge/owasp-incubator-blue.svg)](https://owasp.org/projects/)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/9961/badge)](https://www.bestpractices.dev/projects/9961)

This is the repository that provides the source for the [Security Champions Guide](https://securitychampions.owasp.org/) site.

Using MKDocs to host our content on https://securitychampions.owasp.org/.
This is in addition to the OWASP project page at https://owasp.org/www-project-security-champions-guidebook/

Inspired by https://github.com/OWASP/API-Security and https://github.com/OWASP/Top10/tree/master/2021.

## Building a local copy on Windows

Install python
python3 -m pip install -r requirements.txt
python3 -m pip install mkdocs

## Testing locally

python3 -m mkdocs serve to run website on http://127.0.0.1:8000/

or

python3 -m mkdocs build to generate site content for deployment

## Plugins

Install plugins when running locally:
pip install mkdocs-open-in-new-tab
