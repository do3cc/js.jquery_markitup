js.jquery_markitup
******************

Introduction
============

This library packages `markitup`_ for `fanstatic`_.

.. _`fanstatic`: http://fanstatic.org
.. _`markitup`: http://markitup.jaysalvat.com/home/

To include the javascript, call

    js.jquery_markitup.markitup.need()

You also need to add a set and a style, for the defaults, call

    js.jquery_markitup.simple_style.need()
    js.jquery_markitup.default_set()

This requires integration between your web framework and ``fanstatic``,
and making sure that the original resources (shipped in the ``resources``
directory in ``js.jquery_markitup``) are published to some URL.

The provided  markitup code is licenced under MIT and GPL, the integration
code uses a BSD Licence.


