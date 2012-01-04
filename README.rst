Introduction
============

This addon register JQuery Mousewheel_ plugin to Plone's resource registry

Version: 3.0.6

About mousewheel
================

A jQuery plugin that adds cross-browser mouse wheel support.

In order to use the plugin, simply bind the "mousewheel" event to an element. It also provides two helper methods called mousewheel and unmousewheel that act just like other event helper methods in jQuery. The event callback receives an extra argument which is the normalized "delta" of the mouse wheel.

Here is an example of using both the bind and helper method syntax.

:: 

    // using bind
    $('#my_elem').bind('mousewheel', function(event, delta) {
        console.log(delta);
    });
    
    // using the event helper
    $('#my_elem').mousewheel(function(event, delta) {
        console.log(delta);
    });

Credits
=======

Companies
---------

|makinacom|_

  * `Planet Makina Corpus <http://www.makina-corpus.org>`_
  * `Contact us <mailto:python@makina-corpus.org>`_


Authors

  - JeanMichel FRANCOIS aka toutpt <toutpt@gmail.com>

.. Contributors

.. |makinacom| image:: http://depot.makina-corpus.org/public/logo.gif
.. _makinacom:  http://www.makina-corpus.com
.. _Mousewheel: http://brandonaaron.net/code/mousewheel/docs
