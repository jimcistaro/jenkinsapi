============
jenkinsapi
============

.. contents:: Table of Contents
   :depth: 2


About this library
-------------------

Jenkins is the market leading continuous integration system, originally created by Kohsuke Kawaguchi. This API makes Jenkins even easier to use by providing an easy to use conventional python interface.

Jenkins (and It's predecessor Hudson) are useful projects for automating common development tasks (e.g. unit-testing, production batches) - but they are somewhat Java-centric. Thankfully the designers have provided an excellent and complete REST interface. This library wraps up that interface as more conventional python objects in order to make most Jenkins oriented tasks simpler.

This library can help you:

 * Query the test-results of a completed build
 * Get a objects representing the latest builds of a job
 * Search for artefacts by simple criteria
 * Block until jobs are complete
 * Install artefacts to custom-specified directory structures
 * username/password auth support for jenkins instances with auth turned on
 * Ability to search for builds by subversion revision
 * Ability to add/remove/query jenkins slaves

Important Links
----------------

Project source code: github: https://github.com/salimfadhley/jenkinsapi

Project documentation: http://packages.python.org/jenkinsapi/

Releases: http://pypi.python.org/pypi/jenkinsapi

Installation
-------------

Egg-files for this project are hosted on PyPi. Most Python users should be able to use pip or distribute to automatically install this project.

Most users can do the following:
::

    easy_install jenkinsapi

If you'd like to install in multi-version mode:
::

    easy_install -m jenkinsapi

Project Authors
----------------

 * Salim Fadhley (sal@stodge.org) 
 * Ramon van Alteren (ramon@vanalteren.nl) 
 * Ruslan Lutsenko (ruslan.lutcenko@gmail.com)
 * Cleber J Santos (cleber@simplesconsultoria.com.br)
