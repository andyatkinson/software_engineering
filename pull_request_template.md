### Pull Request Template

Here are some checkboxes to help evaluate my own changes before requesting a code review from others.

- This PR has Security and Privacy Concerns or Personally-identifying information I've addressed
- I have updated corresponding API documentation
- My changes do not generate new warnings (Rails: boot app with `$VERBOSE = true` somewhere, e.g. `config/application.rb`)
- I have added corresponding test code that demonstrates that my feature or fix works as intended
- I have added required environment variables to all environments
- I explained why this change is happening in the PR desc or associated ticket

### Development Flow

- Write some code on a feature branch
- Write positive and negative test cases for the code to confirm it's working as expected
- Plan for any backwards compatibility, add more code and tests
- When the CI suite passes, ship the code to a pre-production environment for further integration testing
- When integration testing is complete, ship to production. Integrate main branch changes into feature branch frequently.
- Repeat


