2isa suite
==========

The 2isa suite is a collection of programs that can extract metadata out of various metabolomics
file formats and write them to `ISA-Tab <http://isa-tools.org/format/specification/>`__ files,
creating the backbone for an ISA-Tab study that can then be shared on databases such as
`MetaboLights <http://metabolights.org>`__. Right now the following source files are supported:

  `.mzML <http://www.psidev.info/mzml_1_0_0%20>`__
    XML-like files containing derived spectral data of mass spectrometry scans

  `.imzML <http://www.imzml.org/index.php?option=com_content&view=article&id=188&Itemid=63>`__
    XML-like files containing metadata about imaging mass spectrometry scans

  `.nmrML <http://nmrml.org/schema/>`__
    XML-like files containing derived spectral data of nuclear magnetic resonance scans


Documentation
-------------

Command Line Applications / Librairies
''''''''''''''''''''''''''''''''''''''

.. toctree::
   :maxdepth: 2

   mzml2isa  <mzml2isa/index.rst>
   nmrml2isa <nmrml2isa/index.rst>


Graphical User Interface
'''''''''''''''''''''''''

.. toctree::
   :maxdepth: 2

   mzml2isa-qt <mzml2isa-qt/index.rst>
   imzml2isa-qt <imzml2isa-qt/index.rst>
   nmrml2isa-qt <nmrml2isa-qt/index.rst>


About
-----

.. toctree::

   Contacts  <contacts.rst>
