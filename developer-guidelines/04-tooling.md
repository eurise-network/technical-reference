# Tooling

In order to support an efficient development workflow and ensure a high degree of software quality
the use of appropriate tooling is strongly recommended.

This should include:

1. Using an appropriate code editor or IDE.

   While the individual person should be free to choose the solution that best fits his or her need, the
   editor/IDE should provide standard features such as syntax highlighting and code completion for all relevant languages.

   Use [EditorConfig](http://editorconfig.org/) to ensure consistency of code submitted by all developers.
   In case others can contribute to the software as well, it is recommended to add the respective `.editorconfig`
   to the software's repository.

1. Code linting within the editor, as pre-commit hooks and part of further automation should be used.

1. Unit testing to improve code quality and simplify future development.

1. Static code analysis to reduce common errors and improve overall quality by adhering to standards and best practices.

1. A Continuous Integration solution that runs on every code commit to verify the test suite, lint code, perform static analysis and more.

   Popular choices for CI are:

   * [Travis CI](https://travis-ci.org/)
   * [GitLab CI](https://about.gitlab.com/gitlab-ci/)
   * [Jenkins](https://jenkins-ci.org/)
