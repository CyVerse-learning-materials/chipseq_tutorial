.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


**Sample dataset and preprocessing**
----------------------------------------

We are analyzing Fumarate and nitrate reduction (FNR) transcription factor dataset in this tutorial (Myers et al., 2013). FNR transcription factor controls the expression of over 100 target genes in response to anoxia. It facilitates the adaptation to anaerobic growth conditions by regulating the expression of gene products that are involved in anaerobic energy metabolism. We will use the FNR IP ChIP-seq Anaerobic A (GSM1010219) dataset and compare this with the input (GSM1010224).

----------------------------------------

**Input Data:**

.. list-table::
    :header-rows: 1

    * - Input
      - Description
      - Location
    * - FNR transcription factor data 
      - FNR IP ChIP-seq and INPUT DNA in anaerobic condition
      - iplantcollaborative > example_data > chipseq_webinar -> fastqfiles

**Preprocessing**

*Evaluate the quality of your sequencing data using FastQC*

Preprocessing of ChIP-seq data is similar to that of any other sequencing data and will assess the quality of the raw reads to identify possible sequencing errors or biases. FastQC can be used for an overview of the data quality but this does not assess if your ChIP experiment has worked. We will assess that in Step4- Postprocessing- ChIP quality assessment.

1. Login to the |discovery_enviornment|.

2. CLick on "Apps" tab in the Discovery Environment and search for "fastqc".

3. Click on the app icon.

|fastqc_app_icon|_

4. Change the name of the analysis and output folder as needed or leave for defaults.

5. Under "Input" leave the default database or browse through the datastore and change the path to a custom database. Change the number of CPUs as per requirement. For next section "Resource Requirements" request resources as needed or leave for defaults 

7. Click **Launch Analysis**. You will receive a notification that the job has been submitted and running. Click on 'Access your analysis here' link.

8. Once the analysis is launched, you will see the SequenceServer user interface. Input your query sequences and click Blast.



**Output/Results**

.. list-table::
    :header-rows: 1

    * - Output
      - Description
      - Example
    * -
      -
      -


----

**Description of output and results**


----

**Fix or improve this documentation**

Search for an answer:
|CyVerse Learning Center| or
|CyVerse Wiki|

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

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

.. |discovery_enviornment| raw:: html

    <a href="https://de.cyverse.org/de/" target="_blank">Discovery Environment</a>

.. |fastqc_app_icon| image:: ./img/fastqc.png
    :width: 300
    :height: 150
.. _fastqc_app_icon: http://learning.cyverse.org/ <a href="https://de.cyverse.org/de/" target="_blank">fastqc_app_icon</a>