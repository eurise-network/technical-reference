Basics
======

All development should be made available publicly under `open source <https://opensource.org/osd>`__ licences.

#. Use version control right from the beginning of a new project.

   -  If in doubt, use `Git <https://git-scm.com/>`__.
   -  Implement a :doc:`Code Hosting Policy <../policies/code-hosting>`.
   -  Use meaningful commit `messages <https://xkcd.com/1296/>`__, cf. [ProGit]_ Sec. 5.2:

      - Capitalised summary with a maximum of 50 characters followed by a blank line.
      - Detailed but concise explanations in paragraphs or bullet points at 72 characters line length.
      - Explain *what* you do and *why*, but *not how*.

   - Never include any secrets in the code.

#. Use an appropriate `OSI <https://opensource.org/licenses>`__ approved license.

   -  Decide on an appropriate license before you first commit.
   -  Ensure the license is compatible with all dependencies.
   -  If in doubt, choose `APACHE-2.0 <https://choosealicense.com/licenses/apache-2.0/>`__ or
      `EUPL-1.2 <https://choosealicense.com/licenses/eupl-1.2/>`__.
   -  Add the text in a ``LICENSE.txt``.
   -  Add license statements to code files, consider using `SPDX <https://spdx.org/specifications>__` identifiers.

#. Maintain a :doc:`README <02-readme>`.

#. :doc:`Document <03-documentation>` your software properly.

#. Use existing :doc:`tooling <04-tooling>` to support development workflows.

#. Ensure maximal :doc:`interoperability <05-interoperability>`.

#. Ensure your software is usable and accessible.

#. Implement a :doc:`release policy <../policies/releasing>` and keep a :doc:`changelog <06-changelog>`.

#. Add a code of conduct in a ``CODE_OF_CONDUCT.md``, like :download:`we do <../CODE_OF_CONDUCT.md>`.

#. Specify contribution policies in a ``CONTRIBUTING.md``, like :download:`we do <../CONTRIBUTING.md>`.
   Don't ignore `non-code contributions <https://allcontributors.org/docs/en/overview>`__.
   A legitimate policy can be that external contributions are not accepted and merged.

