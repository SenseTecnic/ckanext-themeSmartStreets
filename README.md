ckanext-themeSmartStreets
=========================

This repository contain the ckan extension to override the default ckan front-end components with a Smart Streets theme.

Installation
============

To install this package, from your CKAN virtualenv, run the following from your CKAN base folder (e.g. ``pyenv/``)::

``pip install -e git+https://github.com/SenseTecnic/ckanext-themeSmartStreets#egg=ckanext-themeSmartStreets``

``pip install -r src/ckanext-themeSmartStreets/pip-requirements.txt``

Then activate it by setting ``ckan.plugins = themeSmartStreets`` in your main ``ini``-file.


=========================
Changelog

v0.5 
- initial implementation of the smart streets theme extension
- changes to color and layout to fit the hub-landing page
- hard coded links to the hub-landing page instead of the default ckan home page
- hard coded links to the hub-landing about page
