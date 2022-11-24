# ECE444-F2022-Lab6
Followed example from: https://github.com/mjhea0/flaskr-tdd

## Test cases added to group project
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-20-twenty/blob/e9d7e80f214a0cbf71f9c87820b2014e20f5ab73/Education_Pathways/tests/test_app.py#L99-L108

## What are the pros and cons of TDD?
Test Driven Development is a software development methodology that involes writing and running a set of tests before you write development code. The idea is that those tests will fail at first and then you write code to get all the tests to pass. Once all the tests pass, you can be confident in the quality of code and continue to the next phase of the project.

**Pros of TDD:**
- TDD helps you understand and internalise the key principles of good modular design by forcing your code to be more modular as a result of unit testing.
- TDD forces you to writing the tests first, which leads to various architectural problems to reveal themselves earlier. This teaches good architecture.
- TDD makes code easier to maintain and refactor because it provides clarity during implementation.
- TDD makes collaboration easier and more efficient because team members can edit each others code with confidence because the tests will inform them if the changes are bad.
- Unit tests can be used as a safety net when the code needs to be changed like when you want to add new features or fix bugs.
- Small and trivial mistakes can be caught very quickly thanks to unit testing and thus save QA time.

**Cons of TDD:**
- The test suite itself has to be maintained and tests may not always be completely deterministic.
- The tests can take up a lot of time to write and may be difficult to write especially beyond the unit testing level.
- TDD initially slows down development because you have to put in time to write robust tests before you start writing implementation and development code.
- TDD is hard to apply to existing legacy code if it was written using a different methodology.
- TDD relies heavily on everyone in the team to correctly and continuously maintain their tests otherwise the quality of the project development can quickly degrade.