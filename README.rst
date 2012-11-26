sIBL_GUI
========

..  image:: https://secure.travis-ci.org/KelSolaar/sIBL_GUI.png?branch=master

Introduction
------------

| **sIBL_GUI** is an open source lighting assistant making the Image Based Lighting process easier and straight forward through the use of sIbl files (*.Ibl*).
| What is sIBL? It’s a short for *Smart IBL*, a standard describing all informations and files needed to provide a fast and easy Image Based Lighting Setup in the 3d package of your choice.

More detailed informations are available here: http://www.smartibl.com

Installation
------------

For Installation and Usage check the Manual / Help File available here: http://kelsolaar.hdrlabs.com/sIBL_GUI/Support/Documentation/Help/index.html and the related thread here: http://www.hdrlabs.com/cgi-bin/forum/YaBB.pl?num=1271609371
sIBL_GUI depends on some other packages / repositories:

-   Foundations package available from Github: https://github.com/KelSolaar/Foundations. You will need to create a symbolic link from "Foundations/src/foundations" to "sIBL_GUI/src/foundations" and from "Foundations/src/tests/testsFoundations" to "sIBL_GUI/src/tests/testsFoundations" or ensure the packages are available in Python path.
-   Manager package available from Github: https://github.com/KelSolaar/Manager. You will need to create a symbolic link from "Manager/src/manager" to "sIBL_GUI/src/manager" and from "Manager/src/tests/testsManager" to "sIBL_GUI/src/tests/testsManager" or ensure the packages are available in Python path.
-   Umbra package available from Github: https://github.com/KelSolaar/Umbra. You will need to create a symbolic link from "Umbra/src/umbra" to "sIBL_GUI/src/umbra" and from "Umbra/src/tests/testsUmbra" to "sIBL_GUI/src/tests/testsUmbra" or ensure the packages are available in Python path.
-   sIBL_GUI_Templates repository available from Github: https://github.com/KelSolaar/sIBL_GUI_Templates. You will need to create a symbolic link from "sIBL_GUI_Templates/src/templates" to "sIBL_GUI/src/sibl_gui/resources/templates".

Quick Repositories Cloning Commands::

   mkdir HDRLabs
   cd HDRLabs/
   git clone git://github.com/KelSolaar/sIBL_GUI.git && git clone git://github.com/KelSolaar/Foundations.git &&  git clone git://github.com/KelSolaar/Manager.git && git clone git://github.com/KelSolaar/Umbra.git && git clone git://github.com/KelSolaar/sIBL_GUI_Templates.git
   cd sIBL_GUI/src/
   python sIBL_GUI.py

Usage
-----

About
-----

| **sIBL_GUI** by Thomas Mansencal – 2008 - 2012
| Copyright© 2008 - 2012 – Thomas Mansencal – `thomas.mansencal@gmail.com <mailto:thomas.mansencal@gmail.com>`_
| This software is released under terms of GNU GPL V3 license: http://www.gnu.org/licenses/
| `http://www.thomasmansencal.com/ <http://www.thomasmansencal.com/>`_