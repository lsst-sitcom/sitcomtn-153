.. image:: https://img.shields.io/badge/sitcomtn--153-lsst.io-brightgreen.svg
   :target: https://sitcomtn-153.lsst.io
.. image:: https://github.com/lsst-sitcom/sitcomtn-153/workflows/CI/badge.svg
   :target: https://github.com/lsst-sitcom/sitcomtn-153/actions/

######################################################
Improving temperature control of the AuxTel WREB board
######################################################

SITCOMTN-153
============

Tempeature control of the AuxTel WREB board was greatly improved by installing a script to control the cooling fan.  However, there are still temperature excursiond when the ambient temperature is too hot or too cold.  We have purchased from ELMEKO a Peltier cooling module, which can also heat, to improve the situation.  This technote describes the situation and the plans for implementing the Peltier cooler. 

**Links:**

- Publication URL: https://sitcomtn-153.lsst.io
- Alternative editions: https://sitcomtn-153.lsst.io/v
- GitHub repository: https://github.com/lsst-sitcom/sitcomtn-153
- Build system: https://github.com/lsst-sitcom/sitcomtn-153/actions/


Build this technical note
=========================

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

   git clone https://github.com/lsst-sitcom/sitcomtn-153
   cd sitcomtn-153
   make init
   make html

Repeat the ``make html`` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run ``make clean``.

The built technote is located at ``_build/html/index.html``.

Publishing changes to the web
=============================

This technote is published to https://sitcomtn-153.lsst.io whenever you push changes to the ``main`` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://sitcomtn-153.lsst.io/v.

Editing this technical note
===========================

The main content of this technote is in ``index.rst`` (a reStructuredText file).
Metadata and configuration is in the ``technote.toml`` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
