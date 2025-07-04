Motor: Asynchronous Python driver for MongoDB
=============================================

.. image:: _static/motor.png
    :align: center

.. warning:: As of May 14th, 2025, Motor is deprecated in favor of the GA release of the PyMongo Async API.
  No new features will be added to Motor, and only bug fixes will be provided until it reaches end of life on May 14th, 2026.
  After that, only critical bug fixes will be made until final support ends on May 14th, 2027.
  We strongly recommend migrating to the PyMongo Async API while Motor is still supported.
  For help transitioning, see the `Migrate to PyMongo Async guide <https://www.mongodb.com/docs/languages/python/pymongo-driver/current/reference/migration/>`_.

About
-----

Motor presents a coroutine-based API for non-blocking access to
MongoDB from Tornado_ or asyncio_.

The `source is on GitHub <https://github.com/mongodb/motor>`_ and
the docs are on `ReadTheDocs <https://motor.readthedocs.io/>`_.

    "We use Motor in high throughput environments, processing tens of thousands
    of requests per second. It allows us to take full advantage of modern
    hardware, ensuring we utilise the entire capacity of our purchased CPUs.
    This helps us be more efficient with computing power, compute spend and
    minimises the environmental impact of our infrastructure as a result."

    --*David Mytton, Server Density*

    "We develop easy-to-use sensors and sensor systems with open source
    software to ensure every innovator, from school child to laboratory
    researcher, has the same opportunity to create. We integrate Motor into our
    software to guarantee massively scalable sensor systems for everyone."

    --*Ryan Smith, inXus Interactive*

Install with::

    $ python -m pip install motor

.. _Tornado: http://tornadoweb.org/

.. _asyncio: https://docs.python.org/3/library/asyncio.html

Getting Help
------------
If you're having trouble or have questions about Motor, ask your question on
our `MongoDB Community Forum <https://developer.mongodb.com/community/forums/tags/c/drivers-odms-connectors/7/motor-driver>`_.
You may also want to consider a
`commercial support subscription <https://support.mongodb.com/welcome>`_.
Once you get an answer, it'd be great if you could work it back into this
documentation and contribute!

Issues
------
All issues should be reported (and can be tracked / voted for /
commented on) at the main `MongoDB JIRA bug tracker
<http://jira.mongodb.org/browse/MOTOR>`_, in the "Motor"
project.

Feature Requests / Feedback
---------------------------
Use our `feedback engine <https://feedback.mongodb.com/forums/924286-drivers>`_
to send us feature requests and general feedback about PyMongo.

Contributing
------------
**Motor** has a large :doc:`community <contributors>` and
contributions are always encouraged. Contributions can be as simple as
minor tweaks to this documentation. To contribute, fork the project on
`GitHub <http://github.com/mongodb/motor/>`_ and send a
pull request.

Changes
-------
See the :doc:`changelog` for a full list of changes to Motor.

Contents
--------

.. toctree::
   :maxdepth: 1

   differences
   features
   installation
   requirements
   configuration
   tutorial-tornado
   tutorial-asyncio
   examples/index
   changelog
   migrate-to-motor-2
   migrate-to-motor-3
   developer-guide
   contributors

Classes
-------

.. toctree::

   api-tornado/index
   api-asyncio/index

.. getting the caption italicized with a hyperlink in it requires some RST hackage

*Logo by* |musho|_

.. _musho: http://whimsyload.com

.. |musho| replace:: *Musho Rodney Alan Greenblat*
