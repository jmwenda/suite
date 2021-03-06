.. _qgis.explorer.install:

Installation
============

This section will describe how to install the OpenGeo Explorer plugin.

With Boundless QGIS
-------------------

The OpenGeo Explorer plugin comes preinstalled with Boundless QGIS for OpenGeo Suite. **No installation is necessary.**

To access OpenGeo Explorer, navigate to the :guilabel:`OpenGeo` menu and select :guilabel:`OpenGeo Explorer`.

   .. figure:: actions/img/plugin_menu.png

      OpenGeo Explorer menu

Custom install
--------------

.. note:: This section is only for when installing OpenGeo Explorer on a version of QGIS that isn't released by Boundless. It is included here as a convenience.

The OpenGeo Explorer plugin requires **QGIS version 2.8 or higher** to run, and is installed using the QGIS Plugin Manager.

#. In QGIS, navigate to :menuselection:`Plugins --> Manage and Install Plugins`.

#. Click :guilabel:`Settings`

#. Scroll down to the bottom and click :guilabel:`Add`.

#. Add the following repository to the list of plugin repositories:

   * **Name**: Boundless plugin repository
   * **URL**: http://qgis.boundlessgeo.com/plugins.xml

   .. figure:: actions/img/plugin_repo.png

      Adding a new plugin repository

#. Click :guilabel:`OK`.

   .. figure:: actions/img/plugin_repo_added.png

      New plugin repository added successfully

#. With the Boundless repository added, the OpenGeo Explorer plugin will now be available to be installed. Click :guilabel:`All` to see a list of all plugins.

#. You should see one titled :guilabel:`OpenGeo Explorer`. Select it and click :guilabel:`Install plugin`.

   .. figure:: actions/img/plugin_install.png

      OpenGeo Explorer in the list of plugins

#. The plugin will be installed. To verify that installation was successful, you should see a new menu in the QGIS menu bar called :guilabel:`OpenGeo`.

   .. figure:: actions/img/plugin_menu.png

      OpenGeo Explorer menu
