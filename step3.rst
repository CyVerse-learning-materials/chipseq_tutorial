.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


**Read mapping**
------------------

Any standard mapping program such as BWA, Bowtie can be used for this step. We will use Bowtie 1. For short reads (< 50bp), Bowtie 1 is faster and sensitive than Bowtie2.

----

**Input Data:**

.. list-table::
    :header-rows: 1

    * - Input
      - Description
      - Example
    * -
      -
      -

*Descriptive Steps*

.. 	#### Comment: Step title should be descriptive (i.e. Cleaning Read data) ###


1.

2.

**Sequencing depth**

Effective analysis of ChIP-seq data requires sufficient coverage by sequence reads (sequencing depth). The required depth depends mainly on the size of the genome and the number and size of the binding sites of the protein. ENCODE’s guidelines is to obtain minimum 10 million uniquely mapping reads per replicate experiment for mammalian genomes (Landt et al, 2009). 

.. note::

  Excercise 2
  
  If atleast 10 million uniquely mapping reads are required for human genome. How many minimum reads are required for E. coli dataset to have sufficent coverage for further analysis?

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
