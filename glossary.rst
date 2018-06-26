.. Don't use numbered chapter but unnumbered with TOC enty
.. based on https://github.com/sphinx-doc/sphinx/issues/4775
.. raw:: latex

   \cleardoublepage
   \begingroup
   \renewcommand\chapter[1]{\endgroup\chapter*{#1}%
     \addcontentsline{toc}{chapter}{#1}}
   \phantomsection

Glossary
========

These are some of the most important terms used throughout. See also `GitHub
Glossary <https://help.github.com/articles/github-glossary/>`__.

-  *Collaborator* – Someone with write access to the repository.
-  *Contributor* – Someone who submits code to the repository, either directly or via pull-/merge-request.
-  *Developer* – Anyone who writes code.
-  *Maintainer* – The person responsible for feature development and deciding about contributions.
