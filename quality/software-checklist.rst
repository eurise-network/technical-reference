Software Quality Checklist
==========================

General
-------

-  [ ] Does the software have a descriptive name?
-  [ ] Is there a short high-level description of the software?
-  [ ] Is the purpose of the software clear?
-  [ ] Does the software exactly match its requirements?
-  [ ] Is the targeted audience of the software clear?
-  [ ] Has the software been tested by members of the target audience in respect of its usability?
-  [ ] Does the software (and its dependencies) use OSI approved licenses?
-  [ ] Is the software under version control?
-  [ ] Is there a website for the software?
-  [ ] Is the software's website mobile friendly to a certain degree? I.e. can it be accessed on a smartphone or
   tablet without hiding the most important information and features?
-  [ ] Are the user interface design and the software's website mindful of accessibility? I.e. does it consider e.g.
   a high contrast between colors for colorblind users, are there alternative texts for images that can be read by a
   screenreader, are texts easily resizeable, ...?
-  [ ] Does the software have a release mechanism?
-  [ ] Is the software available in packaged format or only sources?
-  [ ] Are maintainer and development status clear, including up to date and accessible contact information?
-  [ ] Are the requirements listed and up to date?
-  [ ] Is copyright and authorship clear and accessible?
-  [ ] Is there a contribution guide?

Documentation
-------------

-  [ ] Is there an accessible low-level guide for getting started?
-  [ ] Is there an accessible user guide?
-  [ ] Is there a full user documentation?
-  [ ] Does the user interface link to held references?
-  [ ] Are there examples, FAQs and tutorials?
-  [ ] Is there information stated about who to ask when a problem is not covered by the FAQ?
-  [ ] Are known issues documented and easily accessible for all user groups?
-  [ ] Can bugs/issues be reported easily by other developers and users?

Development
-----------

-  [ ] Is the development setup documented?
-  [ ] Is the build mechanism documented?
-  [ ] Does the build mechanism use a common single-command system (i.e. Maven)?
-  [ ] Is the software API documented?
-  [ ] Are all appropriate config options externalised and documented?
-  [ ] Does the code allow internationalisation (i18n)?
-  [ ] Is the software localised (l10n)? English is mandatory.
-  [ ] Is there a test suite?
-  [ ] Is test coverage above 80%?
-  [ ] Are the tests run on a regular and frequent basis, e.g. on commit/every night/...?
-  [ ] Do you have and stick to a policy for security by design?
-  [ ] Is the software portable?
-  [ ] Has the portability been tested?

Interoperability
----------------

-  [ ] Are file formats standard compliant and documented?
-  [ ] Is the API standard compliant?
-  [ ] Does it provide a monitoring endpoint?
-  [ ] Does it adhere to an interface style guide?
-  [ ] Does it use existing authentication systems (OAuth2/eduGain)?

Administration
--------------

-  [ ] Are software requirements such as operating system, required libraries and dependencies specified including
   versions?
-  [ ] Are hardware requirements for CPU, RAM, HDD, Network specified?
-  [ ] Are there deployment instructions?
-  [ ] Is there a comprehensive and fully documented example configuration?
-  [ ] Is a startup script provided?
-  [ ] Are there troubleshooting guides?
