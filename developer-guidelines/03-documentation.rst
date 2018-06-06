Documentation
=============

Documentation is fundamental to ensure usability and usefulness of the software. It must be stored along the code, ideally in the
repository's ``docs`` folder. Basic documentation should also be included in the :doc:`README <02-readme>`.

Documentation is relevant in many forms, each of which should be addressed for different audiences with varying degree of experience and
knowledge.

#. **User documentation**: Include a documentation for end users, including e.g.

   -  Examples
   -  Tutorials
   -  How-Tos
   -  FAQs
   -  Screen-casts
   -  API documentation

#. **Developer documentation**: Provide instructions for developers.

   -  How to set up the environment.
   -  Dependencies, including

      -  Supported operating systems
      -  Required libraries
      -  External dependencies

   -  Requirements, e.g. hardware, architecture, CPU, RAM, disk space and network bandwidth.
   -  How to build the code.
   -  How to package the code.

   Additionally, inline code documentation should be used as appropriate.

   -  Always adhere to the language's standard or well established once such as the `Google Style Guides <https://google.github.io/styleguide/>`__.
   -  Document the *why* and not the *what*, cf. [CleanCode]_.

#. **Administration documentation**: Provide instructions for installation, configuration and maintenance, in particular when as a daemon
   (e.g. a micro service).

   -  Configuration instructions
   -  Start-up script (e.g. init or systemd)
   -  Monitoring setup, ideally through a monitoring endpoint
