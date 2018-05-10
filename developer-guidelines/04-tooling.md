# Tooling

Use of appropriate tooling to support the development workflow is highly recommended.

Possibilities are

1. An appropriate code editor or IDE must be used.

   While the individual person should be free to choose the solution that best fits their need, it should provide standard features such as
   syntax highlighting and code completion for all relevant languages.

   Use [EditorConfig](http://editorconfig.org/) to ensure consistency of code submitted by all developers.

1. Code linting within the editor, as pre-commit hooks and part of furher automation should be used.

1. Use of unit testing is highly recommended to improve code quality and enable future development.

1. Static code analysis can be used to reduce common errors and improve overall quality by adhering to standards and best practices.

1. A Continuous Integration solution that runs on every code commit can be used
   to verify the test suite, code linting, perform static analysis and more.

   Popular choices are

   * [Travis CI](https://travis-ci.org/)
   * [GitLab CI](https://about.gitlab.com/gitlab-ci/)
   * [Jenkins](https://jenkins-ci.org/)



