Guide to reST
=============

reST is white space sensitive.
    * Like python, a lot of the structure of the text comes from indention.
    * A lot of things (like code blocks) require whitespace before and after.

reST groups strings together with `'s.

reST uses `..` as the means to call a function
    * So calling a 

reST uses :: in the main text to denote functions.
    * This is done because comments are likely to have a : in them.
    *ex::

        .. note:: This is a sweet note.
                  The whitespace here matters.


reST links to things with _
    * This means hyperlinks in the main body of text end in _
    * Single word hyperlinks can just be that::
        
        Look at the Python_ source.

    * Multiple word hyperlinks must be joined with `'s::

        Look in the `Django Documentation`_.
    
    * At the bottom of the page or paragraph, use the `..` syntax to match the links together::

        .. _Django Documentation: http://docs.djangoproject.com

.. note:: The hyperlink section with the actual URL only has one :, because it is seperate
          from the main body of the text, as noted above


