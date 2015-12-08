===================
librarian-flatpages
===================

Flatpages provide an API for registering static pages in librarian_, meant to
avoid the addition of redundant empty route handlers that just return a simple
template anyway.

Installation
------------

The component has the following dependencies:

- librarian-core_

To enable this component, add it to the list of components in librarian_'s
`config.ini` file, e.g.::

    [app]
    +components =
        librarian_flatpages

Configuration
-------------

``flat.root``
    A path relative to the root template folder, holding static templates.
    Example::

        [flat]
        root = flatpages

.. _librarian: https://github.com/Outernet-Project/librarian
.. _librarian-core: https://github.com/Outernet-Project/librarian-core
