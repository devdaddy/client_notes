# Notes on Pull Requests
## Unit Tests
* Unit test must be included for PR to be approved.
* Descriptions of the test's objectives are a must.
* Don't trust Unit Test results from Visual Studio.  Just because the test runner says they all passed does not mean they will pass on the CI server.

## Coding Methodologies
* Methods must use single responsibility principal.
* Comments for everything... the more the better.
* Don't concatenate strings.  Preference to object's properties / methods for adding values.
* Watch out for comments in your pull requests like not addressed, even though you addressed something, but it may not be to his standards.
* Inheritance, Inheritance, Inheritance
* Make sure to use constants when you are not re-assigning value
* Do not use static models.  Most of their models are dervied from JSON files.  So when you need to reference a field that is being used, it is probably in the following heirarchy:
  * .../Assets/.../*.json
* Write everything to be dynamic, but make sure you use inheritance.

## Coding Notes
* Codebase is complex. Take your time going through it and make sure you understand.
* If you have a question, ask it.  But be prepared you may get a full gamit of responses.
* 