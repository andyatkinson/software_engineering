## Pull Request Guidelines

The review process is a balancing act that attempts to provide constructive feedback that helps with knowledge sharing, lessening maintenance, improving self-documenting, discoverability, least surprising, reducing complexity, while also not blocking a team member accomplish the goal of releasing their code change.

This is somewhat of an art and science process.

Here are some guidelines I've found helpful over the years:

* Try to understand the primary purpose of the PR and not lose sight of that
* Look for evidence that the code works and ask the author to confirm they've manually tested it in at least one pre-release environment. This could be test coverage or a description of how something was tested manually.
* Look for potential accidental mistakes: mismatching method names, variable names, files, constants, etc.
* Make suggestions that might improve readability or maintainability improvements in the code itself, the PR title or description. Add a ticket number, related issue or PRs, external API documentation or other links that help tell the story. PRs are referred back to when investigating a bug or refactoring. PRs have "conversation" on them. The more information co-located on the PR the better.
* If there is test coverage, consider whether there are positive and negative tests. Consider avoiding test environment dependencies if possible (mocks, stubs, contract-based testing).
* Consider the potential for a performance issue that may not surface until there is a higher scale, when changing mature code.

A human is working on this:

* Be nice
* Have a bias towards an "approve" given functionality is confirmed as working. List comments as suggestions. A PR that has comments but no explicit approval or rejection is unclear.
* Look for (and ask for) patterns to encourage shared use.
* Be mindful that evidence, examples, other code etc. (a link, a blog post etc.) or a brief explanation on reasoning will be more easily consumable for the author and help them and others learn.

Create a Pull Request template for the project that lists important pre-flight checks.
