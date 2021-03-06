.. index::
    single: Polyfill
    single: PHP
    single: Components; Polyfill

The Symfony Polyfill / PHP 5.4 Component
========================================

    This component provides some PHP 5.4 features to applications using earlier
    PHP versions.

Installation
------------

.. code-block:: terminal

    $ composer require symfony/polyfill-php54

.. include:: /components/require_autoload.rst.inc

Usage
-----

Once this component is installed in your application, you can use the following
functions, no matter if your PHP version is earlier than PHP 5.4.

Provided Functions
~~~~~~~~~~~~~~~~~~

* :phpfunction:`class_uses`
* :phpfunction:`hex2bin`
* :phpfunction:`session_register_shutdown`
* :phpfunction:`trait_exists`
