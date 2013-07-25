ckanext-themeSmartStreets
=========================

This repository contains the ckan extension to override the default ckan front-end components with a Smart Streets theme.

Installation
============

To install this package, from your CKAN virtualenv, run the following from your CKAN base folder (e.g. ``pyenv/``)::

``pip install -e git+https://github.com/SenseTecnic/ckanext-themeSmartStreets#egg=ckanext-themeSmartStreets``

``pip install -r src/ckanext-themeSmartStreets/pip-requirements.txt``

Then activate it by setting ``ckan.plugins = themeSmartStreets`` in your main ``ini``-file.


=========================
Changelog

v1.1.2
- added link to wotkit sensors, api documentation and contacts page in the header
- removed search bar from header

v0.5 
- initial implementation of the smart streets theme extension
- changes to color and layout to fit the hub-landing page
- hard coded links to the hub-landing page instead of the default ckan home page
- hard coded links to the hub-landing about page

release-1.2
- Fixes in html templates after merging upstream into sensetecnic/ckan

