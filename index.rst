.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

**ChIP-seq Tutorial**
=================

This tutorial introduces the basic principles of analyzing chromatin immunoprecipitation sequencing (ChIP-seq) data. This documentation is intended to provide enough information to allow a biologist perform key steps of ChIP-seq analysis: quality control of data, mapping data to a reference genome and peak calling. CyVerse Discovery Environment (DE) public apps will be used to run analysis on a sample dataset.

Learning Objectives
--------------------

- Understand the nature of ChIP-seq data

- Efficiently manage and analyze ChIP-seq data

- How to do quality assessment using R ChIPQC package

----

.. toctree::
	:maxdepth: 2

	Tutorial home <self>
	Sample dataset <step1.rst>
	Preprocessing <step2.rst>
  Read mapping <step3.rst>
  Peak calling <step4.rst>
  Postprocessing- ChIP quality assessment <step5.rst>
  Further reading <step6.rst>


Prerequisites
-------------

Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Prerequisite
      - Preparation/Notes
      - Link/Download
    * - CyVerse account
      - You will need a CyVerse account to complete this exercise
      - |CyVerse User Portal|
    * - Cyberduck
      - Standalone software for upload/download to Data Store
      - |Download Cyberduck|

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

 ..
   #### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Documentation
      - Quick Start
    * - Data Store
      - GUI/Command line
      - |Data Store|
      - |Data Store Manual|
      - |Data Store Guide|
    * - Discovery Environment
      - Web/Point-and-click
      - |Discovery Environment|
      - |DE Manual|
      - |Discovery Environment Guide|
    
Application(s) used
~~~~~~~~~~~~~~~~~~~
..
	#### Comment: these tables are examples, delete whatever is unnecessary ####

**Discovery Environment App(s):**

.. list-table::
    :header-rows: 1

    * - App name
      - Version
      - Description
      - App link
      - Notes/other links
    * - Muscle
      - 3.8.31
      - Multiple sequence aligner
      -	|DE Application URL|
      - |Original App Documentation|


**Atmosphere Image(s):**

.. list-table::
    :header-rows: 1

    * - Image name
      - Version
      - Description
      - Link
      - Notes/other links
    * - CyVerse CentOS 6.8 GUI Base
      - 1.0
      - base image CentOS 6.8 with GNOME GUI
      - |Atmosphere Image|
      -



Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need to have the following inputs prepared*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Example Data
    * -
      -
      -
      -

----

**Fix or improve this documentation**

Search for an answer:
|CyVerse Learning Center| or
|CyVerse Wiki|

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`__


.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX" target="blank">Github Repo Link</a>

.. |Download Cyberduck| raw:: html

   <a href="https://cyberduck.io/" target="blank">Download Cyberduck</a>

.. |DE Application URL|  raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=9b41c9e4-5031-4a49-b1cb-c471335df16e&system-id=de" target="blank">DE Application URL</a>

.. |Original App Documentation|  raw:: html

   <a href="http://www.drive5.com/muscle/manual/" target="blank">Original App Documentation</a>

.. |Atmosphere Image|  raw:: html

   <a href="https://atmo.cyverse.org/application/images/1384" target="blank">Atmosphere Image</a>
