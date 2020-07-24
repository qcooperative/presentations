:data-transition-duration: 1500
:skip-help: true
:css: hovercraft-qcooperative-theme/css/custom-hov.css
:css: hovercraft-qcooperative-theme/css/custom.css
:css: custom.css

.. title:: Yes QGIS Server rocks!... But why?

----

:id: presentation-title


Yes QGIS Server rocks!... But why?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Paul Blottiere and Alessandro Pasotti

31-07-2020

.. image:: images/qgis.png
    :class: centered
    :width: 400

----

Who?
====

+ Paul Blottiere
    + Lead Software Engineer
    + QGIS developer
    + QCooperative member

.. image:: images/pblottiere.png
    :class: centered
    :width: 200

.. class:: center

   **@pblottiere**

----

Who?
====

+ Alessandro Passoti
    + itOpen
    + QGIS developer and vice chair of QGIS.org PSC
    + QCooperative member

.. image:: images/elpaso.png
    :class: centered
    :width: 200

.. class:: center

   **@elpaso66**

-----

QCooperative
============

+ Broad range of services
+ Open Source ethics
+ International
+ Active members of the QGIS community

.. image:: images/qcooperative.png
    :class: centered
    :width: 500


.. class:: center

  **@CooperativeQ**

-----

QGIS Desktop
============

+ Main canvas as we know it
+ Layout manager
+ Processing framework
+ Database manager
+ ...

.. image:: images/desktop.png
    :class: centered
    :width: 600

-----

QGIS Server?
============

+ Map server based on QGIS core library
+ Same release cycle with a **qgis-server** package
+ Numerous services:
    + WMS 1.1.0 and WMS 1.3.0
    + WFS 1.1 and OGC API Features (aka WFS3)
    + WMTS
    + WCS

.. image:: images/wfs3.png
    :class: centered
    :width: 500

-----

OGC certification
=================

+ QGIS 3.10 is certified for WMS 1.3.0
+ Ongoing certification for OGC API Features

.. image:: images/badge.png
    :class: centered
    :width: 200

-----

Configuration
=============

+ QGIS Desktop acts like a WYSIWYG

.. image:: images/config.png
    :class: centered
    :width: 800

.. class:: center

  **http://localhost/qgisserver?MAP=myproject.qgz**

-----

Vendor parameters and requests
==============================

+ Extensions of OGC standards
+ Take full advantage of QGIS specificities
+ The most famous: **GetPrint**

.. image:: images/getprint.jpg
    :class: centered
    :width: 600

-----

Programmability
===============

+ Python plugins

  + Filtering
  + Custom services (à la WMS)
  + Custom API (à la OGCAPIF)

+ Hello world plugin: https://github.com/elpaso/qgis-helloserver

.. image:: images/hw.png
    :class: centered
    :width: 400

-----

Robustness
==========

+ Numerous unit tests
+ Continuous integration
+ Nightly OGC tests for WMS 1.3.0 and OGCAPIF on master

.. image:: images/certif.png
    :class: centered
    :width: 800

.. class:: center

   http://test.qgis.org/ogc_cite/

-----

Docker images
=============

+ OpenQuake (my favorite): https://hub.docker.com/r/openquake/qgis-server
+ Kartoza: https://registry.hub.docker.com/u/kartoza/qgis-server
+ C2C: https://hub.docker.com/r/camptocamp/qgis-server
+ Oslandia: https://gitlab.com/Oslandia/qgis/docker-qgis
+ and a lot more

.. image:: images/docker.png
    :class: centered
    :width: 300

-----

Web client
==========

TODO

-----

Official resources
==================

+ `Documentation: QGIS as OGC Data Server <https://docs.qgis.org/3.10/en/docs/user_manual/working_with_ogc/server/index.html>`_
+ `Cookbook: QGIS Server and Python <https://docs.qgis.org/testing/en/docs/pyqgis_developer_cookbook/server.html>`_
+ `PyQGIS: QGIS ServerAPI <https://qgis.org/pyqgis/3.10/server/index.html>`_

.. image:: images/doc.png
    :class: centered
    :width: 600

-----

Drawbacks
=========

+ No official logo
+ Documentation
+ Performances
+ Monitoring
+ Very few plugins https://plugins.qgis.org/plugins/server/

-----

Is it alive?
============

TODO
