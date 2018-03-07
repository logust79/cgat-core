.. getting_started-Installation


============
Installation
============

The following sections describe how to install the CGATCore framework. For instructions on how to install
the CGAT-apps (scripts) and CGAT-flow (workflows/pipelines) please follow these instructions `here <https://www.cgat.org/downloads/public/cgatpipelines/documentation/InstallingPipelines.html>`_ .
Please note that installing the apps and flow will also install CGATCore as part of this process.

We distinguish between two different installation types: production and development. The former refers to a well tested subset of pipelines, and is the recommended installation.
The latter refers to the whole collection of pipelines developed at CGAT, which may contain code under active development.

Automated installation
----------------------

The preferred method to install the CGATCore is using the installation script,
which uses conda_.

Here are the steps::

   Add steps here...........

The installation script will put everything under the specified location. It needs
? GB of disk space and it takes about ? minutes to complete. The aim of the
script is to provide a portable installation that does not interfere with the existing
software. As a result, you will have a conda environment working with the CGAT Pipelines
which can be enabled on demand according to your needs.

Manual installation
-------------------

To obtain the latest code, check it out from the public git_ repository and activate it::

   git clone https://github.com/cgat-developers/cgat-core.git
   cd cgat-core
   python setup.py develop

The CGAT-core depends on the CGAT scripts, which can be installed by following the
`installation <http://www.cgat.org/downloads/public/cgat/documentation/CGATInstallation.html>`_ instructions.

Once checked-out, you can get the latest changes via pulling::

   git pull 

.. _conda: https://conda.io
.. _git: https://git-scm.com/