# Proctor-webapp-library

---

**This repository is now archived, the contents have been moved to https://github.com/indeedeng/proctor**

---

Proctor-Webapp-Library is a library used for running a web application to create and modify [Proctor](https://github.com/indeedeng/proctor) definitions.

# Features:

# Installation

# Example
See [proctor-webapp](http://www.github.com/indeedeng/proctor-webapp)

# Documentation

Proctor-Webapp-Library assumes that users will have a trunk/qa/prod lifecycle for test definitions. Users can define tests in trunk, and promote them to qa, then prod. 

## Backend configuration

Proctor-webapp-library has a bean RevisionControlStoreFactory which expects several properties to be set, defining the storage of the test matrix.

* `revision.control` whether to use git or svn
* `scm.path` location of the repository

Based on this, 3 test matrix stores will be created based on applicationContext.xml:

* TRUNK
* QA
* PROD


# Discussion

Join the [indeedeng-proctor-users](https://groups.google.com/d/forum/indeedeng-proctor-users) mailing list to ask questions and discuss use of Proctor-Webapp and/or Proctor.

# Deploying

# Contributing

# License

[Apache License Version 2.0](https://github.com/indeedeng/proctor-webapp-library/blob/master/LICENSE)

