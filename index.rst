.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

**Introduction**
=================

This tutorial introduces the basic principles of analyzing chromatin immunoprecipitation sequencing (ChIP-seq) data and is intended to provide enough information to perform key steps of ChIP-seq analysis: quality control of data, mapping data to a reference genome and peak calling. We will be using Cyverse discovery environment public apps for analysis of a sample set. Command-line expertise is not required to follow most of this tutorial.

Learning Objectives
--------------------

- Efficiently manage and analyze ChIP-seq data

- How to do quality assessment using ChIPQC R package

- Using CyVerse Discovery Environment apps to do ChIP-seq analysis

----

Step-by-step Tutorial:
~~~~~~~~~~~~~~~~~~~~~~~

.. toctree::
  :titlesonly:

  step1.rst
  step3.rst
  step2.rst
  step4.rst
  step5.rst
  step6.rst

----

.. Note::

  Acknowledgments: Thanks to VIB and Harvard Chan Bioinformatics training for making wonderful teaching material available for ChIP-seq.

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
    * - Bowtie
      - 1.2.2
      - Short-read sequence aligner
      -	|DE Application URL|
      - |Original App Documentation|
    * - FastQC
      - 0.11.5
      - Quality Control tool for HTS data
      - |DE Application URL1|
      - |Original App Documentation1|
    * - MACS2
      - 2.7.1
      - Model-based analysis of ChIP-seq
      - |DE Application URL2|
      - |Original App Documentation2|
    * - ChIPQC
      - 1.22
      - Quality assessment tool for ChIP-seq
      - |DE Application URL3|
      - |Original App Documentation3|


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
    * - ChIP-seq experiment data
      - fastq or sra files
      - Data downloaded from GEO or ENA database
      - Myers et al., 2013 FNR dataset (iplantcollaborative > example_data > chipseq_webinar)

----

**Fix or improve this documentation**

Search for an answer:
|CyVerse Learning Center| or
|CyVerse Wiki|

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`__
[Back to top]

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

   <a href="https://de.cyverse.org/de/?type=apps&app-id=0145bfbe-8eb8-11e8-a11a-008cfa5ae621&system-id=de" target="blank">DE Application URL</a>

.. |Original App Documentation|  raw:: html

   <a href="https://wiki.cyverse.org/wiki/display/DEapps/Bowtie--Build-and-Map" target="blank">Original App Documentation</a>

.. |DE Application URL1|  raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=dbd0de10-97da-11e6-8f91-008cfa5ae621&system-id=de" target="blank">DE Application URL</a>

.. |Original App Documentation1|  raw:: html

   <a href="https://wiki.cyverse.org/wiki/display/DEapps/FastQC" target="blank">Original App Documentation</a>

.. |DE Application URL2|  raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=4bde65c8-7dac-11ea-ac57-008cfa5ae621&system-id=de" target="blank">DE Application URL</a>

.. |Original App Documentation2|  raw:: html

   <a href="https://wiki.cyverse.org/wiki/display/DEapps/FastQC" target="blank">Original App Documentation</a>

.. |DE Application URL3|  raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=bdcfa09a-7e72-11ea-9807-008cfa5ae621&system-id=de" target="blank">DE Application URL</a>

.. |Original App Documentation3|  raw:: html

   <a href="https://wiki.cyverse.org/wiki/display/DEapps/FastQC" target="blank">Original App Documentation</a>
   

