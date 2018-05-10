# Software Quality Checklist

## General

- [ ] Does the software have a descriptive name?
- [ ] Is there a short high-level description of the software?
- [ ] Is the purpose of the software clear?
- [ ] Is the targeted audience of the software clear?
- [ ] Does it (and its dependencies) use OSI approved licenses?
- [ ] Is the software under version control?
- [ ] Is there a website for the software?
- [ ] Does the software have a release mechanism?
- [ ] Is the software available in packaged format or only sources?
- [ ] Are maintainer and development status clear, including contact information?
- [ ] Are the requirements listed and up to date?
- [ ] Is the interface responsive and accessible?
- [ ] Is copyright and authorship clear and accessible?
- [ ] Is there a contribution guide?

## Documentation

- [ ] Is there an accessible low-level getting started guide?
- [ ] Is there an accessible user guide?
- [ ] Is there a full user documentation?
- [ ] Does the user interface link to held references?
- [ ] Are there examples, FAQs and tutorials?
- [ ] Are known issues documented and easily accessible for all user groups?

## Development

- [ ] Is the development setup documented?
- [ ] Is the build mechanism documented?
- [ ] Does the build mechanism use a common single-command system (i.e. Maven)?
- [ ] Is the software API documented?
- [ ] Are all appropriate config options externalised and documented?
- [ ] Does the code allow internationalisation (i18n)?
- [ ] Is the software localised (l10n)? English is mandatory.
- [ ] Is there a test suite?
- [ ] Is test coverage above 80%?
- [ ] Are the tests run on a regular and frequent basis, e.g. on commit/every night/...?
- [ ] Do you have and stick to a policy for security by design?

## Interoperability

- [ ] Are file formats standard compliant and documented?
- [ ] Is the API standard compliant?
- [ ] Does it provide a monitoring endpoint?
- [ ] Does it adhere to an interface style guide?
- [ ] Does it use existing authentication systems (OAuth2/eduGain)?

## Administration

- [ ] Are software requirements such as operating system, required libraries and dependencies specified including versions?
- [ ] Are hardware requirements for CPU, RAM, HDD, Network specified?
- [ ] Are there deployment instructions?
- [ ] Is there a comprehensive and fully documented example configuration?
- [ ] Is a startup script provided?
- [ ] Are there troubleshooting guides?
