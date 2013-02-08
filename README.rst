==================
geniatagger-python
==================

Python library for GeneiaTagger

-------
License
-------

GPL version 3 or later. Please read ``LICNESE``.

-------
Install
-------

Run ``python setup.py install``

----------
How to use
----------

::

  import geniatagger

  tagger = GeniaTagger('.../path_to_geniatagger/geniatagger')
  print tagger.parse('This is a pen.')
  
