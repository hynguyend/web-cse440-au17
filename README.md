# web-jekyll-base

[![Build Status](https://travis-ci.org/uwcse440/web-cse440-au17.svg?branch=master)](https://travis-ci.org/uwcse440/web-cse440-au17)

The course website for CSE 440 in Autumn 2017.

## Project Dependencies

This project is based on a template:

[https://github.com/fogies/web-jekyll-base](https://github.com/fogies/web-jekyll-base)

Which is in turn based on:

[https://github.com/fogies/invoke-base](https://github.com/fogies/invoke-base)

Runtime dependencies for this project are:
- Python 3.5.2
- Node 4.5.0
- Ruby 2.3.3
- Ruby DevKit

See [Installation for Windows](https://github.com/uwcse440/web-cse440-au17/blob/master/readme/install_windows.md).

See [Installation for Mac](https://github.com/uwcse440/web-cse440-au17/blob/master/readme/install_mac.md).

## Tasks

This project uses Invoke for task execution. Available tasks can be listed:

`invoke -l`

See [Additional Task Documentation](https://github.com/uwcse440/web-cse440-au17/blob/master/readme/invoke.md).

Frequently used tasks will include:

### build_production

Build the site to `_site`, using the production configuration in `_config-production.yml`.

`invoke build_production` 

### build_test

Build the site to `_site`, using the test configuration in `_config-test.yml`.

`invoke build_test` 

### serve_production

Serve the site on port 4000, using the production configuration in `_config-production.yml`.

`invoke serve_production` 

### serve_test

Serve the site on port 4000, using the test configuration in `_config-test.yml`.

`invoke serve_test` 

