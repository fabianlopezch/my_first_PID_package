
my_first_PID_package
==============

TODO: input a short description of package my first PID package utility here

# Table of Contents
 - [Package Overview](#package-overview)
 - [Installation and Usage](#installation-and-usage)
 - [Offline API Documentation](#offline-api-documentation)
 - [License](#license)
 - [Authors](#authors)




Package Overview
================

The **my_first_PID_package** package contains the following:


Installation and Usage
======================

The **my_first_PID_package** project is packaged using [PID](http://pid.lirmm.net), a build and deployment system based on CMake.

If you wish to adopt PID for your develoment please first follow the installation procedure [here](http://pid.lirmm.net/pid-framework/pages/install.html).

If you already are a PID user or wish to integrate **my_first_PID_package** in your current build system, please read the appropriate section below.






Offline API Documentation
=========================

With [Doxygen](https://www.doxygen.nl) installed, the API documentation can be built locally by turning the `BUILD_API_DOC` CMake option `ON` and running the `doc` target, e.g
```bash
pid cd my_first_PID_package
pid -DBUILD_API_DOC=ON doc
```
The resulting documentation can be accessed by opening `<path to my_first_PID_package>/build/release/share/doc/html/index.html` in a web browser.

License
=======

The license that applies to the whole package content is **CeCILL**. Please look at the [license.txt](./license.txt) file at the root of this repository for more details.

Authors
=======

**my_first_PID_package** has been developed by the following authors: 
+ Fabian Lopez ()

Please contact Fabian Lopez -  for more information or questions.
