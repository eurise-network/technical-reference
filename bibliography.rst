.. Bugfix, this removes additional chapter header
.. https://github.com/sphinx-doc/sphinx/issues/4775
.. raw:: latex

   \cleardoublepage
   \begingroup
   \renewcommand\chapter[1]{\endgroup}
   \phantomsection

Bibliography
============

.. [CleanCode] Robert C. Marton: **Clean Code: A Handbook of Agile Software Craftsmanship**, Prentice Hall PTR, 2008
.. [FitSM] ITEMO: **FitSM** – A free standard for lightweight ITSM, http://fitsm.itemo.org/, 2016
.. [ProGit] Scott Chacon, Ben Straub: **Pro Git**, https://git-scm.com/book/en/v2, Version 2.1.64, 2018-06-01
.. [Sirtfi] AARC: **Security Incident Response Trust Framework for Federated Identity**, https://aarc-project.eu/policies/sirtfi/, 2015
.. [Snctfi] AARC: **Scalable Negotiator for a Community Trust Framework in Federated Infrastructures** https://aarc-project.eu/policies/snctfi/, 2017

.. [NLeSCGuide] Netherlands eScience Center: **Guide**, https://guide.esciencecenter.nl/
.. [CLARIAHsqg] CLARIAH: **Software Quality Guidelines**, <https://github.com/CLARIAH/software-quality-guidelines>

