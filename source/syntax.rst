Basic reST Syntax
=================

Hyperlinks
-----------

Single-word hyperlinks
~~~~~~~~~~~~~~~~~~~~~~
::
    
    This is my paragraph, and this is the link to my code_.

    .. _code: https://github.com/ericholscher/reStructuredText-Philosophy

This results in:

    This is my paragraph, and this is the link to my code_.

    .. _code: https://github.com/ericholscher/reStructuredText-Philosophy

Multi-word hyperlinks
~~~~~~~~~~~~~~~~~~~~~
::

    This is my paragraph, and this is the `link to my code`_.

    .. _link to my code: https://github.com/ericholscher/reStructuredText-Philosophy

This results in:

    This is my paragraph, and this is the `link to my code`_.

    .. _link to my code: https://github.com/ericholscher/reStructuredText-Philosophy

Lesson
^^^^^^

To learn more, see :ref:`rest-link-underscores`.

